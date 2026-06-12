# Hoàng Xuân Việt

Backend engineer based in Ho Chi Minh City. I design and run systems where correctness and throughput actually matter — ERP backbones, trading engines, event-driven platforms.

Currently focused on **AI-assisted developer tooling** and **quantitative trading infrastructure**.

## What I'm building

**[Vardionix](https://github.com/vietgs03/Vardionix)** — AI-powered DevSecOps platform. Detects, fixes, and validates security issues inside the developer workflow instead of bolting scanning on at the end of CI. The interesting problems here are not the scanning itself, but trust: how do you make an automated fix something an engineer will actually merge?

**[Kairos-v2](https://github.com/vietgs03/Kairos-v2)** — Fully automated quantitative trading engine. AI/ML signal generation layered on a statistical risk framework. The hard part isn't the model — it's the execution path: idempotent order handling, reconciliation under partial failure, and removing every place a human emotion could leak into the loop.

**[diagram-toolkit](https://github.com/vietgs03/diagram-toolkit)** — Opinionated Mermaid pipeline powering [blog.viethx.com](https://blog.viethx.com). Component taxonomy, icon inlining, semantic motion, and a rule validator — because architecture diagrams deserve a linter too.

## How I think about systems

- **Boring at the core, sharp at the edges.** Postgres, Go, and a message queue solve most problems. Novelty budget goes where it earns its keep.
- **Design for the failure path first.** Retries, idempotency keys, and reconciliation jobs are the architecture — the happy path is just a special case.
- **Performance is a feature with a budget.** I've cut p99 latencies and query times not by guessing, but by measuring: indexes, batch boundaries, and knowing when a cache hides a design flaw versus fixes one.
- **Code is a liability; behavior is the asset.** The best PR is often a deletion.

## Background

Several years shipping business-critical backends: warehouse management and accounting ERP for manufacturers (Việt Tiến, Khánh Hòa Nutrition), a QR-based prize redemption platform for Glico Vietnam handling 50k+ scans/day with real-money payouts, and eCommerce microservices on RabbitMQ/Redis.

**Daily drivers:** Go, TypeScript/Node.js, PostgreSQL, Redis, Kafka, Docker. PHP when the legacy calls.

## Elsewhere

Writing at [blog.viethx.com](https://blog.viethx.com) · [LinkedIn](https://linkedin.com/in/viet-hoang-286277178) · [viet.gs03@gmail.com](mailto:viet.gs03@gmail.com)

<details>
<summary>GitHub stats</summary>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vietgs03&show_icons=true&count_private=true&theme=graywhite&hide_border=true" alt="GitHub Stats" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vietgs03&layout=compact&theme=graywhite&hide_border=true" alt="Top Languages" height="160" />
</p>
</details>
