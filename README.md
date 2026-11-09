# Ken C. Demanawa

**Senior Software Engineer · Software Architect · Backend & Platform Engineering**

Ruby and Rails · PostgreSQL · Distributed Systems · Rust · AWS

I build dependable backend systems and open-source tools for data movement, developer infrastructure, and AI integrations. My work spans long-lived Rails products, PostgreSQL change-data capture, cloud platforms, and Rust/Linux software. I’m based in the Philippines, have worked remotely since 2007, and am open to remote senior roles in software engineering, software architecture, backend engineering, and platform engineering.

[LinkedIn](https://linkedin.com/in/ken-c-demanawa) · [Email](mailto:kenneth.c.demanawa@gmail.com) · [RubyGems](https://rubygems.org/profiles/kanuto) · [Rust crates](https://crates.io/users/kanutocd) · [GHCR packages](https://github.com/kanutocd?tab=packages)

[![XERJ Corpus Hub contributor](https://hub.xerj.org/contributors/kanutocd/badge.svg)](https://hub.xerj.org/contributors/kanutocd)

## Featured work

### Data infrastructure · Ruby and PostgreSQL

### Ruby concurrency

- **[Ratomic](https://github.com/mperham/ratomic)** — Co-author and current maintainer of a Ruby library providing Ractor-safe mutable data structures, including shared concurrent primitives and ownership-aware pools.

- **[Mammoth](https://github.com/kanutocd/mammoth)** — The open-source data plane of a broader private Mammoth platform project. It relays PostgreSQL logical-replication events for reliable downstream delivery, with durable checkpoints, retry and dead-letter recovery, and operational visibility.
- **[CDC Ecosystem](https://github.com/kanutocd/cdc-core)** — Composable Ruby libraries for PostgreSQL replication transport, protocol parsing, decoding, normalized events, concurrent runtimes, and job-queue integrations. Start with [`cdc-core`](https://github.com/kanutocd/cdc-core), [`cdc-sidekiq`](https://github.com/kanutocd/cdc-sidekiq), or [`cdc-solid-queue`](https://github.com/kanutocd/cdc-solid-queue).

### AI and developer infrastructure

- **[Prescient](https://github.com/kanutocd/prescient)** — Ruby gateway for hosted and local AI providers, available as a gem, CLI, REST API, and container image. The gem has passed **25,000 downloads**. [RubyGems](https://rubygems.org/gems/prescient) · [GHCR](https://github.com/kanutocd/prescient/pkgs/container/prescient)
- **Sandbox Loom** *(private project; public documentation)* — A coding-agent execution platform I actively dogfood, with scoped capabilities, policy checks, approval gates, verification, and retained run evidence. Its workflow is demonstrated in the public [USB Camera Taytay reference application](https://github.com/kanutocd/usb-camera-taytay). [Read the public documentation](https://sandbox-loom-documentation.dogfooding.shop/).

### Rust, edge systems, and cloud platforms

- **Taytay (`lunsaran-taytay`)** — Publicly published Rust crate and Linux edge bridge within the broader private Lunsaran platform, supporting durable, resumable uploads. The public [USB Camera Taytay](https://github.com/kanutocd/usb-camera-taytay) application is a reference app for both Taytay and Sandbox Loom. [Crate](https://crates.io/crates/lunsaran-taytay) · [JavaScript SDK](https://www.npmjs.com/package/@lunsaran/entregar) · [Other published Rust crates](https://crates.io/users/kanutocd)
- **[Spherical Mammoth](https://github.com/kanutocd/spherical-mammoth)** — Cloud-native reference SaaS for deploying and operating Mammoth across local Kubernetes and managed cloud environments.
- **[poorman-aws](https://github.com/kanutocd/poorman-aws)** — Reusable, cost-conscious AWS infrastructure and release workflows built with OpenTofu, Packer, and GitHub Actions.

## Selected upstream contributions

Small contributions across established Ruby projects:

- [`ruby/time`](https://github.com/ruby/time) — [commit 1](https://github.com/ruby/time/commit/ada62114ab3077994b8eb4856a6cffe56ea0f88a), [commit 2](https://github.com/ruby/time/commit/2b43839fc28ad6cdaa56c9a1a0a6e28986b3cf06), [commit 3](https://github.com/ruby/time/commit/8be241ed7cd4954f01f60e58d940e08b5da61899)
- [`ruby/ruby`](https://github.com/ruby/ruby) — [commit](https://github.com/ruby/ruby/commit/8ff8963995e6df14c0ec589a526a268dde4b9cc5)
- [`rubycdp/ferrum`](https://github.com/rubycdp/ferrum) — [commit 1](https://github.com/rubycdp/ferrum/commit/f9fea5748303ae7ec7d585406841d3ba1cc62a05), [commit 2](https://github.com/rubycdp/ferrum/commit/dd292cfbcebd5a1bb9bdf528d34efebd051a7089), [commit 3](https://github.com/rubycdp/ferrum/commit/5370021038bfe307e5e2520b9c93678d49d22d61)

## Upstream design discussions

- Followed a proposal from [`kino #4`](https://github.com/yaroslav/kino/pull/4) into [`rb-sys #748`](https://github.com/oxidize-rb/rb-sys/pull/748), then discussed it with Ruby core maintainers in [`ruby/ruby #17975`](https://github.com/ruby/ruby/pull/17975). The rb-sys PR was closed after those discussions.

## Open-source distribution

I publish and maintain software across the ecosystems I build for:

- Ruby gems: [RubyGems profile](https://rubygems.org/profiles/kanuto)
- Rust crates: [crates.io profile](https://crates.io/users/kanutocd)
- Container images: [GitHub Container Registry packages](https://github.com/kanutocd?tab=packages)

My work is represented in **10 XERJ Corpus Hub corpora** spanning Ruby audit tooling, supply-chain security, PostgreSQL CDC and concurrency, and Rust edge systems. These licensed, attributed corpora let coding agents retrieve real implementation examples. [Browse the corpora and selected work](https://hub.xerj.org/contributors/kanutocd).

## For contributors

I welcome focused bug reports, reproducible examples, documentation improvements, and thoughtful design discussions. For larger changes, please open an issue first so we can align on behavior and API shape. Each project’s contribution guide and issue tracker are linked from its repository.

---

*Building software that makes data movement, deployment, and day-to-day engineering easier to reason about.*
