### Hi, I'm Vasco

Senior .NET backend engineer in Lisbon. 12+ years building secure, high-performance systems for central and retail banks: payments, event-driven architectures, legacy modernisation and regulated fintech platforms.

This year I'm building open-source versions of the problems I know best, in public, with the design decisions written down.

#### Working on now

| Project | What it is | Status |
|---|---|---|
| [**payee-match**](https://github.com/softvasco/payee-match) | Verification of Payee name matching for .NET, following the EPC VOP scheme. Explainable match, close match and no match for SEPA instant payments. | name normaliser done, matchers next |
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
