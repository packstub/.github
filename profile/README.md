# Packstub

Plugins for [Filament](https://filamentphp.com) panels and the Laravel packages behind them, by [XLITE](https://xlite.dev). Most of it is open source under MIT. The paid plugins are sold on [packstub.dev](https://packstub.dev) the Composer-native way: buy once, get a personal token, `composer require`, and keep getting updates with your licence.

Every plugin has its docs on packstub.dev, and the open-source ones are on Packagist. The repos marked beta are usable today and tagged as pre-releases until 1.0.

## Open source

| Plugin | What it does | Links |
| --- | --- | --- |
| [Filament Agents](https://github.com/packstub/filament-agents) | An in-panel AI assistant and an MCP server from one tool list, with the panel's own authorization, approve-in-chat writes and live tables and charts in answers. Built on `laravel/ai` and `laravel/mcp`. | [Docs](https://packstub.dev/docs/filament-agents) · [Directory](https://filamentphp.com/plugins/packstub-agents) · [Packagist](https://packagist.org/packages/packstub/filament-agents) |
| [Filament Account Switcher](https://github.com/packstub/filament-account-switcher) | Switch between accounts without signing out: impersonation, linked sub-accounts with password-confirmed escalation, developer logins and an audit log. | [Docs](https://packstub.dev/docs/filament-account-switcher) · [Directory](https://filamentphp.com/plugins/packstub-account-switcher) · [Packagist](https://packagist.org/packages/packstub/filament-account-switcher) |
| [Filament Flow](https://github.com/packstub/filament-flow) | Visual workflow automation: triggers, conditions and actions drawn on a canvas and run by your queue. | [Docs](https://packstub.dev/docs/filament-flow) · [Directory](https://filamentphp.com/plugins/packstub-flow) · [Packagist](https://packagist.org/packages/packstub/filament-flow) |
| [Filament Form Builder](https://github.com/packstub/filament-form-builder) | Build forms in the admin, render them with Blade, Livewire or JSON, collect and export submissions. | [Docs](https://packstub.dev/docs/filament-form-builder) · [Directory](https://filamentphp.com/plugins/packstub-form-builder) · [Packagist](https://packagist.org/packages/packstub/filament-form-builder) |
| [Filament Kanban](https://github.com/packstub/filament-kanban) | A fast Kanban board: optimistic drag and drop, per-user columns and drop rules, focus mode. | [Docs](https://packstub.dev/docs/filament-kanban) · [Packagist](https://packagist.org/packages/packstub/filament-kanban) |
| [Filament Rating](https://github.com/packstub/filament-rating) | Star ratings as a form field, table column, infolist entry and summarizer. Half stars, keyboard and screen-reader support. | [Docs](https://packstub.dev/docs/filament-rating) · [Packagist](https://packagist.org/packages/packstub/filament-rating) |
| [Filament Session Replay](https://github.com/packstub/filament-session-replay) (beta) | Session replay inside a panel: a Sessions resource, a player with errors, rage clicks and web vitals on the timeline, replays next to each user, masking declared on the form field. | [Docs](https://packstub.dev/docs/filament-session-replay) · [Packagist](https://packagist.org/packages/packstub/filament-session-replay) |
| [Nitpick](https://github.com/packstub/filament-nitpick) (beta) | Designed themes for Filament panels, an open theme registry, a default per panel and a per-user choice from the profile. | [Docs](https://packstub.dev/docs/filament-nitpick) · [Packagist](https://packagist.org/packages/packstub/filament-nitpick) |

### Laravel packages

The engines behind the Filament plugins. Each one runs in a plain Laravel app on its own.

| Package | What it does | Links |
| --- | --- | --- |
| [Agents for Laravel](https://github.com/packstub/agents) | An agent engine and an MCP server sharing one tool list: tools, turns, budgets and limits. Filament Agents builds on it. | [Docs](https://packstub.dev/docs/agents) · [Packagist](https://packagist.org/packages/packstub/agents) |
| [Session Replay for Laravel](https://github.com/packstub/session-replay) (beta) | An rrweb recorder with privacy defaults, token-signed ingest, recordings on your own disk and database, and a player behind a gate you define. | [Docs](https://packstub.dev/docs/session-replay) · [Packagist](https://packagist.org/packages/packstub/session-replay) · [Demo app](https://github.com/packstub/session-replay-demo) |
| [Account Switcher for Laravel](https://github.com/packstub/account-switcher) | The session core behind Filament Account Switcher: impersonation, linked sub-accounts, developer logins, audit log, routes and Blade components. | [GitHub](https://github.com/packstub/account-switcher) |
| [Partisan](https://github.com/packstub/partisan) | Artisan for Laravel packages: `make:` generators that write into `src/` with your package namespace. Built on Orchestra Testbench. | [Docs](https://packstub.dev/docs/partisan) · [Packagist](https://packagist.org/packages/packstub/partisan) |

## Paid plugins

Sold on packstub.dev with licensed updates, VAT invoices and a customer portal that shows you exactly how to install. Together they are the [Filament SaaS Stack](https://packstub.dev/bundles/filament-saas-stack).

| Plugin | What it does | Links |
| --- | --- | --- |
| Filament Tenancy | Database-per-tenant workspaces for Filament v5 panels: one database per tenant, any number of database servers. Powered by [stancl/tenancy](https://github.com/stancl/tenancy). | [Store](https://packstub.dev/plugins/filament-tenancy) · [Docs](https://packstub.dev/docs/filament-tenancy) · [Directory](https://filamentphp.com/plugins/packstub-tenancy) · [Demo app](https://github.com/packstub/filament-tenancy-demo) |
| Filament Teams | Teams, email invitations, seat limits, a Members page, ownership rules and tenant-scoped roles that plug into Filament Shield or Spatie Permission when present. | [Store](https://packstub.dev/plugins/filament-teams) · [Docs](https://packstub.dev/docs/filament-teams) |
| Filament Features | Plans, limits and feature flags per tenant: per-tenant overrides, kill switches, usage checks, and gating for pages, actions, routes and Blade. | [Store](https://packstub.dev/plugins/filament-features) · [Docs](https://packstub.dev/docs/filament-features) |

## About the public mirrors in this org

The `*-mirror` repositories are provenance mirrors of the open-source packages the paid plugins build on. The `mirror/*` tags are the exact trees served through our Composer channels, so customers can audit precisely what they install. They are not development forks: all development happens upstream, and we are grateful to the maintainers of those projects.

## Links

- Store and docs: [packstub.dev](https://packstub.dev)
- Download and star history for every package: [stats.packstub.dev](https://stats.packstub.dev)
- Built by [XLITE](https://xlite.dev); open-source work at [@xlitedev](https://github.com/xlitedev)
- Support: support@packstub.dev
