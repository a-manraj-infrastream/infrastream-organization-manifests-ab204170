# Island Venues — organization manifests

Infrastructure for **Island Venues**, the open-source reference app of the DevFest 2026
talk "The Era of Agentic Developer Platforms": book event venues across Mauritius.

Every change to this repository is a pull request. Infrastream plans it on the pull
request and applies it when it is merged.

| Repository | What it is |
|---|---|
| [island-venues-api](https://github.com/a-manraj-infrastream/island-venues-api) | Go API: venue catalog, bookings, staff actions, payment webhook |
| [island-venues-notifier](https://github.com/a-manraj-infrastream/island-venues-notifier) | Go service: booking confirmation e-mails from Pub/Sub |
| [island-venues-web](https://github.com/a-manraj-infrastream/island-venues-web) | React customer app |
| [island-venues-admin](https://github.com/a-manraj-infrastream/island-venues-admin) | React staff console behind Identity-Aware Proxy |

## Layout

- `organization/island-venues/` — the organization, its users and groups, registries and the GitHub connection with the four repositories and their build definitions.
- `organizational-unit/island-venues/` — environments `development` and `production`, the `island-venues` project in each, and the `main` release track.
