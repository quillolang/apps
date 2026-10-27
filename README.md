# Quillo apps

Whole applications written in [Quillo](https://github.com/quillolang/quillo), larger
than the [examples](https://github.com/quillolang/examples): what a real program in the
language looks like, and a test of it.

| App | What it is |
|---|---|
| [`crm/`](crm) | Relay, a multi-tenant CRM for merchants, bloggers and news outlets: contacts, deals, a shop with checkout, campaigns, a page designer, flows, and plugins whose rules run in the browser and on the server |

## Running one

With `quillo` installed (see [Getting started](https://github.com/quillolang/quillo#getting-started)):

```sh
quillo run crm/main.qwe --port 9000 --watch
```

Each app's README says more.

## Tests

`cargo test` loads each app in quillo's interpreter (the `quillo` crate, from
quillolang/quillo's `main`) and drives it as a browser would. `cargo update -p quillo`
moves the tests to quillo's latest commit.

## License

MIT
