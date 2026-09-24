<a href="https://vedavid.dev"><img src="./hero.png" alt="vedavid — Observability for 2026. Built in the open." width="100%"></a>

**vedavid** puts your Prometheus dashboards on your phone. Everything that touches your cluster — the connector, the dashboard compiler, the dashboards themselves — is open source under Apache-2.0. Read it before you run it.

[vedavid.dev](https://vedavid.dev) · [Docs](https://docs.vedavid.dev) · [Get the iOS app](https://testflight.apple.com/join/CTSQrsnb)

<br>

<img src="./flow.png" alt="How the repositories fit: dashboards (YAML) → dashboard-dsl compiles → connector serves beside Prometheus → dials out to the relay → the app reads" width="100%">

A dashboard starts as YAML in your repo and ends on a phone. Your metrics never leave the cluster — the only connection is the one the connector opens.

<br>

> **Nothing we run ever opens a connection to you.**

Issues and pull requests are welcome — especially dashboards. If you run it, someone else does too.
