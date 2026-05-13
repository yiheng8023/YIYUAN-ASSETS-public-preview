# YIYUAN-ASSETS 公共预览

[English](README.md) | [简体中文](README.zh-CN.md)

YIYUAN-ASSETS 是 graph-first、domain-neutral 的数字能力基础设施 substrate，
面向受治理的开发者集成场景。

本仓库是 source-available 的公共预览面，不是私有核心仓库。它不包含受保护
核心内核、内部图权威实现、商业编排、安全控制细节或专有治理内核。

## 第一价值路径

YIYUAN-ASSETS 的第一价值路径是：外部业务模块通过受治理的 Assets API 接入，
获得身份、权限、审计、日志、导出、反馈和可选 AI/BYOK 边界，同时业务逻辑不
进入 core。

AI 可以增强系统，但不能成为系统事实来源。公共预览阶段仍保持图优先、尽量确定
性、AI 可选。

## API 预览入口

受限公共预览 API 入口见 [docs/API_PREVIEW.zh-CN.md](docs/API_PREVIEW.zh-CN.md)。

这是一份 contract 与评估入口，不是托管生产 API。它用于说明外部模块应如何
接近受治理的 Assets API，但不暴露受保护实现、内部图权威、商业编排、安全
内部细节或私有运维控制。

半开放仓库边界见 [docs/SEMI_OPEN_BOUNDARY.md](docs/SEMI_OPEN_BOUNDARY.md)。

## 公共预览范围

本仓库可以包含：

- 公开 README 与文档；
- 公共预览 API contract 和示例；
- 经批准公开的 SDK 或 adapter surface；
- 贡献、支持与安全边界；
- 非敏感治理证据和发布说明。

本仓库不包含：

- 受保护核心权威或图写入治理内部实现；
- 私有商业、计费、权益或反滥用实现；
- 密钥、租户数据、客户数据或 provider transcript；
- 私有安全发现或利用细节；
- 可能削弱产品边界的内部运维 runbook。

## 许可证

本仓库使用 YIYUAN-ASSETS Source-Available Public Preview License。它允许公开
查看、评估、提交 issue 和受限贡献评审，但不授予生产、商业、托管服务、再分发、
再授权或竞争性基础设施复刻权利。

详见 [LICENSE.md](LICENSE.md) 与 [NOTICE.md](NOTICE.md)。

## 当前成熟度

状态：公共预览面，不是生产发布。

项目正在为受治理的半开放预览做准备。API、边界、示例和公开材料在商业发布
或生产发布前仍可能调整。

## 社区入口

- [CONTRIBUTING.md](CONTRIBUTING.md) 说明安全贡献边界。
- [SECURITY.md](SECURITY.md) 说明私密安全报告边界。
- [SUPPORT.md](SUPPORT.md) 说明公共预览支持范围。
- [PUBLIC_PREVIEW.md](PUBLIC_PREVIEW.md) 说明预览成熟度和限制。
- [ROADMAP.md](ROADMAP.md) 说明阶段性公开方向。
