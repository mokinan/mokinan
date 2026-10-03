# Mohamed Kinan

**Principal Flutter Engineer** — I build production mobile apps, and the architecture,
standards and release pipelines that let a team keep shipping them.

7 years of Flutter, from first commit to store release and long-term maintenance.
I currently lead mobile engineering for the Rassd Cloud product line and Madark,
where I own architecture decisions, code standards and the release process.

## What I work on

- **Fintech** — financing and repayment flows, wallets, secure storage, biometric auth
- **ERP / SaaS** — billing, attendance, role-based access, multi-tenant setups
- **Offline-first apps** — local source of truth, sync queues, caching, safe retries
- **App security** — secure token handling, SSL pinning, hardening against common mobile findings
- **Engineering practice** — architecture decisions, code review, CI/CD, onboarding developers

## Production work

| Product | Domain | What it does | Stores |
|---|---|---|---|
| **[Madark](https://madark.sa)** | Fintech · education financing | Tuition financing for parents: applications, installment plans and repayments | [App Store](https://apps.apple.com/sa/app/id6768550546) · [Google Play](https://play.google.com/store/apps/details?id=com.madark.institution) |
| **[Rassd Cloud](https://rassd.sa) — Billing** | ERP / SaaS · invoicing | Cloud billing and invoicing for businesses | [App Store](https://apps.apple.com/sa/app/id6478158183) |
| **[Rassd Cloud](https://rassd.sa) — Attendance** | ERP / SaaS · workforce | Employee attendance tracking and reporting | [App Store](https://apps.apple.com/sa/app/id6456840349) · [Google Play](https://play.google.com/store/apps/details?id=com.worldofss.MotwagedRassdApp) |

Source code is proprietary; the public projects below use the same patterns.

## Selected projects

| Project | Highlights |
|---|---|
| [**flutter-fintech-wallet**](https://github.com/mokinan/flutter-fintech-wallet) | Offline-first multi-currency wallet · exact integer money math · idempotent outbox sync · single-flight token refresh · PIN & biometric lock · Arabic/RTL · 81 tests + E2E · ADRs |
| [**flutter-classifieds-marketplace**](https://github.com/mokinan/flutter-classifieds-marketplace) | Haraj-style marketplace · Riverpod 3 · monorepo (api / ui_kit / app) · cancellable debounced search · offline cache · optimistic UI · photo uploads · chat · deep links · Arabic/RTL |

## Open source

- [**gcc_validators**](https://github.com/mokinan/gcc_validators) — validation and normalization
  for GCC IBANs, Saudi national IDs/Iqamas, Emirates IDs, mobile and VAT numbers.
  Pure Dart, Arabic-digit aware.
- [**durable_sync_queue**](https://github.com/mokinan/durable_sync_queue) — persistent, ordered,
  retrying operation queue for offline-first apps: idempotency keys, per-group ordering,
  backoff with jitter, dead-lettering. Extracted from the wallet's sync engine.

## Toolbox

- **Core:** Flutter, Dart
- **State management:** Bloc / Cubit, Riverpod, Provider — chosen per problem
- **Architecture:** Clean Architecture, feature-first modules, monorepos (pub workspaces)
- **Data & backend:** REST, GraphQL, Firebase, WebSockets, Dio, Drift (SQLite)
- **Quality:** unit, widget & integration tests, strict static analysis
- **Delivery:** GitHub Actions, build flavors, Firebase Crashlytics

## Contact

[LinkedIn](https://www.linkedin.com/in/mohamed-kinan-7883851a8/) · [Email](mailto:mohamed.kinan3@gmail.com) · Open to remote roles
