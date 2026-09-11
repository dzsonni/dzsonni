# Robert-Berti Kato

Independent software engineer. Fifteen years in mobile, rooted in native Android. Today I build Flutter apps, modernize backends, and improve the tooling teams use to ship.

**https://kaladev.com** · robert.kato@kaladev.com · [LinkedIn](https://www.linkedin.com/in/robertbertikato/)

## About this profile

Most of my work lives in private client and product repositories, so the contribution graph is real but the code behind it mostly isn't public. What is:

- **[flutter-pre-commit](https://github.com/dzsonni/flutter-pre-commit)** — deterministic checks wired in front of every commit. The small version of how I fence AI-assisted changes: linters and scripts decide what gets through, not the model.
- **[hms-flutter-plugin](https://github.com/dzsonni/hms-flutter-plugin)** — maintained fork of Huawei's HMS Flutter plugins after upstream went quiet: AGP namespace fix, Fresco 3.5.0 for Android's 16 KB page-size requirement, module updates. The kind of platform upkeep production apps need and nobody budgets for.
- **[retrofit.dart](https://github.com/trevorwang/retrofit.dart)** — contributor.
- **Quicks** — peer-to-peer rental marketplace I co-founded. Flutter on iOS and Android, Supabase backend, Stripe payments, Next.js admin, Astro site. I own the technical stack and delivery. [App Store](https://apps.apple.com/us/app/quicks-app/id6762560232) · [Google Play](https://play.google.com/store/apps/details?id=com.quicks.app.quicks) · [quicks-app.com](https://quicks-app.com)

## How I work with AI tooling

Built for client teams; the code stays with them, the approach doesn't.

- Deterministic tooling (linters, static analysis, scripts) sits in the generation loop, locally and in CI, and fences where the AI is allowed to operate.
- AI opens issues and pull requests only through filtered wrappers, never the open API.
- PR checklists are scripts that verify the steps actually ran — with a tamper guard, added after models tried to forge the evidence.
- Review tooling onboards the human first (purpose, root cause, blast radius, intent vs. what landed) before surfacing findings. Human review stays in the process.

## Background

Skobbler (acquired by Telenav) → AROBS → CloudLink/Rivo → Accenture → MEJIX → 3Pillar Global → independent since 2021. Cluj-Napoca, Romania. Remote, EU hours.
