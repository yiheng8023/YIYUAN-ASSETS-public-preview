# API 预览入口

状态：受限公共预览 contract map，不是托管生产 API。

本文说明 YIYUAN-ASSETS 公共预览阶段的公开安全 API 入口。它面向开发者、集成
评审者和早期评估者，用于理解第一价值路径，但不提供受保护核心实现细节。

## 第一价值路径

外部业务模块应通过受治理的 Assets API 接入，获得身份、权限、审计、日志、
导出、反馈和可选 AI/BYOK 边界，同时业务逻辑不进入 core。

## 边界

本公共预览入口可以说明：

- contract 意图和 route family；
- 安全示例和评估场景；
- developer key 与 BYOK 的生命周期隔离；
- 导出、反馈、日志和审计预期；
- 非生产成熟度限制。

本公共预览入口不披露：

- 受保护内核实现；
- 内部图权威或图写入治理内部机制；
- 生产权益、计费或反滥用实现；
- 密钥、租户数据、客户数据或 provider transcript；
- 私有安全发现或运维控制。

## Key 隔离

Assets developer key 与 BYOK provider key 拥有独立生命周期。

Assets developer key 通过可审计的平台治理授权访问有作用域的 Assets API
surface。Provider key 仍归用户或租户所有，不授予 Assets 平台权限，也不能
从 Assets developer key 派生或替代 Assets developer key。

## 发布规则

完整 OpenAPI 预览 contract 只应在私有核心 release gate、泄漏检查和公开表面
审计通过后，通过受治理的 public bundle pipeline 发布。

在此之前，本文作为 API 预览预期的稳定公开入口。

## 反馈

请通过 integration request issue template 提交公开安全的 API 预览反馈。不要
在公开 issue 中包含密钥、私有客户数据、利用细节或受保护实现假设。
