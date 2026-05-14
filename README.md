# YIYUAN-ASSETS Public Preview

[English](README.md) | [简体中文](README.zh-CN.md)

中文用户可以先阅读 [README.zh-CN.md](README.zh-CN.md)。本仓库是
YIYUAN-ASSETS 的 source-available 公共预览面，不是私有核心仓库；它用于
公开评估、边界说明、API 预览、贡献入口和社区协作。

YIYUAN-ASSETS is a graph-first, domain-neutral digital capability infrastructure
substrate for governed developer integrations.

This public repository is the source-available public-preview surface. It is not
the private core repository and it does not contain the protected kernel,
internal graph authority implementation, commercial orchestration, security
controls, or proprietary governance internals.

## First Value Path

YIYUAN-ASSETS is designed so external business modules can integrate through a
governed Assets API and receive identity, permission, audit, logging, export,
feedback, and optional AI/BYOK boundaries without putting business logic inside
the core.

AI can enhance the system, but AI is not the system truth source. The public
preview posture remains graph-first, deterministic where possible, and
AI-optional.

## API Preview Entry

The bounded public-preview API entry is documented in
[docs/API_PREVIEW.md](docs/API_PREVIEW.md).

This is a contract and evaluation surface, not a hosted production API. It
shows how external modules should approach the governed Assets API without
exposing protected implementation, internal graph authority, commercial
orchestration, security internals, or private operational controls.

The semi-open repository boundary is documented in
[docs/SEMI_OPEN_BOUNDARY.md](docs/SEMI_OPEN_BOUNDARY.md), with a Chinese version
available at [docs/SEMI_OPEN_BOUNDARY.zh-CN.md](docs/SEMI_OPEN_BOUNDARY.zh-CN.md).

## Public Preview Scope

This repository may include:

- public README and documentation;
- public-preview API contracts and examples;
- SDK or adapter surfaces approved for public use;
- contribution, support, and security boundaries;
- non-sensitive governance evidence and release notes.

This repository does not include:

- protected core authority or graph write governance internals;
- private commercial, billing, entitlement, or anti-abuse implementation;
- secrets, tenant data, customer data, or provider transcripts;
- private security findings or exploit details;
- internal operational runbooks that could weaken the product boundary.

## License

This repository uses the YIYUAN-ASSETS Source-Available Public Preview License.
It allows public viewing, evaluation, issue reporting, and bounded contribution
review, but it does not grant production, commercial, hosted-service,
redistribution, sublicensing, or competing-infrastructure rights.

See [LICENSE.md](LICENSE.md) and [NOTICE.md](NOTICE.md).

## Current Maturity

Status: public-preview surface, not production release.

The project is being prepared for a governed semi-open preview. APIs,
boundaries, examples, and public-facing materials may change before a commercial
or production release.

Public preview readiness, commercial baseline evidence, hardening-cycle
evidence, and a healthy finding register do not grant commercial release
clearance. Commercial use, production deployment, hosted-service operation, and
commercial licensing require separate written authorization.

## Community Entry

- [CONTRIBUTING.md](CONTRIBUTING.md) describes safe contribution boundaries.
- [SECURITY.md](SECURITY.md) describes private security reporting boundaries.
- [SUPPORT.md](SUPPORT.md) describes public-preview support scope.
- [PUBLIC_PREVIEW.md](PUBLIC_PREVIEW.md) describes preview maturity and limits.
- [ROADMAP.md](ROADMAP.md) describes staged public direction.
