### Hi, I'm Vasco

Senior .NET backend engineer in Lisbon. 12+ years building APIs, event-driven services and high-performance integrations, and moving legacy applications onto current .NET. Most of it for central and retail banks, where correctness and uptime aren't optional.

This year I'm building open-source projects in public, with the design decisions written down as ADRs.

#### Working on now

| Project | What it is | Status |
|---|---|---|
| [**payee-match**](https://github.com/softvasco/payee-match) | Fuzzy name matching for .NET with explainable results: normalisation, legal forms, initials and word order. Built for the EU Verification of Payee check. | name normaliser done, matchers next |
| [**household-finance**](https://github.com/softvasco/household-finance) | Self-hosted household finance app: accounts, budgets, credits, net worth, car and pet costs. ASP.NET Core, EF Core, React, Docker. | in use, adding tests |
| [**ledger-core**](https://github.com/softvasco/ledger-core) | Event-sourced double-entry banking ledger in .NET 10: CQRS, outbox, PostgreSQL event store, .NET Aspire, OpenTelemetry. | domain model in progress |

#### Coming up

- **loan-flow**: consumer credit origination with an APR engine for the EU Consumer Credit Directive.
- **iso20022-rs**: a fast ISO 20022 parser in Rust with .NET and Python bindings.
- **finguard-analyzers**: Roslyn analyzers that catch money, time and data-access bugs.
- **legacy-to-blazor**: a strangler-fig migration from WebForms to .NET 10, with a playbook.

#### Stack

`C#` `.NET 10` `ASP.NET Core` `EF Core` `Blazor` `Azure` `Service Bus` `SQL Server` `PostgreSQL` `Docker` `.NET Aspire` `OpenTelemetry` `Rust` `Python`

#### Writing

Short notes on what I learn while building these, with real code: [softvasco.github.io](https://softvasco.github.io)

- [Normalising payee names: where NFKD stops](https://softvasco.github.io/2026/09/where-nfkd-stops/)
- [Why 0.05 × 0.5 is 0.02 in my ledger](https://softvasco.github.io/2026/09/rounding-in-a-ledger/)

[LinkedIn](https://www.linkedin.com/in/softvasco)
