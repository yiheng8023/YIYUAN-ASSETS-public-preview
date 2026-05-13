# API Preview Entry

[English](API_PREVIEW.md) | [简体中文](API_PREVIEW.zh-CN.md)

Status: bounded public-preview contract map, not a hosted production API.

This page describes the public-safe API entry for YIYUAN-ASSETS public preview.
It is intended for developers, integration reviewers, and early evaluators who
need to understand the first value path without receiving protected core
implementation details.

For repository-wide disclosure limits, see
[SEMI_OPEN_BOUNDARY.md](SEMI_OPEN_BOUNDARY.md).

## First Value Path

External business modules should integrate through a governed Assets API and
receive identity, permission, audit, logging, export, feedback, and optional
AI/BYOK boundaries without putting business logic inside the core.

## Boundary

This public-preview entry may describe:

- contract intent and route families;
- safe examples and evaluation scenarios;
- developer-key and BYOK separation;
- export, feedback, log, and audit expectations;
- non-production maturity limits.

This public-preview entry does not disclose:

- protected kernel implementation;
- internal graph authority or graph write governance internals;
- production entitlement, billing, or anti-abuse implementation;
- secrets, tenant data, customer data, or provider transcripts;
- private security findings or operational controls.

## Key Separation

Assets developer keys and BYOK provider keys have separate lifecycles.

An Assets developer key authorizes access to scoped Assets API surfaces through
auditable platform governance. A provider key remains user or tenant owned,
does not grant Assets platform authority, and must not be derived from or
substituted for an Assets developer key.

## Publication Rule

The complete OpenAPI preview contract should be published only through a
governed public bundle pipeline after private-core release gates, leakage
checks, and public-surface audits pass.

Until then, this page is the stable public entry for API preview expectations.

## Feedback

Use the integration request issue template for public-safe API preview feedback.
Do not include secrets, private customer data, exploit details, or protected
implementation assumptions in public issues.
