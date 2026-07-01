---
solhann_app: true
slug: expenses
title: Expenses
description: Drop in a receipt and get back a draft expense form with confirmation questions
emoji: 🧾
---

# 🧾 Expenses

Drop in a receipt and get back a draft expense form with confirmation questions

**Live:** https://expenses.solhann.net
**Gallery:** https://create.solhann.net

---

Built on the [solhann.net](https://create.solhann.net) platform. Every push to `main`
auto-deploys via GitHub Actions → rsync → `/var/www/apps/expenses/`. The front matter above is what the
gallery reads to render this app's tile, so keep `title` / `description` / `emoji` up to date.

Backed by its own PocketBase instance (`pocketbase@expenses`, same origin). The ledger syncs across
devices via an anonymous owner id (`pb-auth.js`) — persistence, not security. Schema lives on the
live instance only (edited via the platform's `pb-schema` helper), never in this repo.
