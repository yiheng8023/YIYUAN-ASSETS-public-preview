# 半开放边界

[English](SEMI_OPEN_BOUNDARY.md) | [简体中文](SEMI_OPEN_BOUNDARY.zh-CN.md)

公共预览仓库是受控公开表面，不是对完整 YIYUAN-ASSETS core 的披露。

## 公开表面

- 公开文档；
- 公共预览 contract；
- 经选择的示例；
- 安全 issue template；
- 贡献与支持边界；
- 非敏感治理证据。

## 受保护表面

- core graph authority 实现；
- graph write governance 内部机制；
- 商业权益、计费和反滥用逻辑；
- 私有安全报告和利用细节；
- 内部运维 runbook；
- 密钥、租户数据、客户数据和 provider transcript。

## 同步原则

公开材料只能通过明确的审查边界，从私有核心生成、复制或整理。公共仓库不得
继承私有 Git 历史。

公共反馈进入私有核心时只能作为候选信号；它不能直接修改 canonical graph
truth、受保护权威、release gate 或商业承诺。
