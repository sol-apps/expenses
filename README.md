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

Built on the [solhann.net](https://create.solhann.net) platform. Static site — every push to `main`
auto-deploys via GitHub Actions → rsync → `/var/www/apps/expenses/`. The front matter above is what the
gallery reads to render this app's tile, so keep `title` / `description` / `emoji` up to date.
