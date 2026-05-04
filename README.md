<h1 align="center">Hi, I'm Fayziddin 👋</h1>
<p align="center">
  <strong>Flutter developer</strong> from Qarshi, Uzbekistan · shipping production apps since 2023
</p>

<p align="center">
  <a href="https://t.me/Fayziddin_B"><img src="https://img.shields.io/badge/Telegram-@Fayziddin__B-26A5E4?logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://www.linkedin.com/in/fayziddin2000"><img src="https://img.shields.io/badge/LinkedIn-fayziddin2000-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:ruslanmedia.uz@gmail.com"><img src="https://img.shields.io/badge/Email-ruslanmedia.uz%40gmail.com-EA4335?logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open_to-Office_(Qarshi)_/_Remote-2EA44F" alt="Open to work" />
</p>

---

### What I do

I build Flutter apps that ship to real users — restaurants, food delivery, fintech, kiosks. My focus is the boring-but-important parts: clean architecture that scales past 50 features, network layers that don't leak `DioException` into the UI, offline caches that survive flaky 3G, and CI pipelines that auto-publish to TestFlight and Play Internal.

Most of my production work is private, so I built three open-source skeletons that distill the patterns:

| Repo | What it shows |
|------|---------------|
| 🟢 [**flux_simple**](https://github.com/Fayziddin2000/flux_simple) | The smallest Clean Architecture Flutter app — 3 layers, 1 feature, no codegen, no DI container. Read this first. |
| 🔵 [**flux_starter**](https://github.com/Fayziddin2000/flux_starter) | Production-ready template: BLoC + GetIt + Retrofit + Dio + `safeApiCall` pattern. The skeleton I fork for new projects. |
| 🟣 [**flux_advanced**](https://github.com/Fayziddin2000/flux_advanced) | Full-feature sample: phone/OTP auth, offline cache (sqflite), cart, search with debounce, theme switching, 3-language i18n. |

---

### Stack I work with

**Flutter & Dart** (daily)
`flutter_bloc` · `get_it` · `dio` · `retrofit` · `auto_route` · `equatable` · `json_serializable` · `build_runner`

**Storage & data**
`flutter_secure_storage` · `sqflite` · `shared_preferences` · `connectivity_plus`

**Firebase**
Core · Crashlytics · Analytics · Cloud Messaging · Remote Config

**Native integrations**
OneSignal push · Yandex MapKit · WebView · Geolocator · QR / barcode scanning · `package_info_plus` · `app_tracking_transparency`

**Release & CI**
Fastlane (Match, App Distribution, TestFlight, Play Internal/Production) · GitLab CI · GitHub Actions · App Store Connect API

**Testing**
`flutter_test` · `mocktail` · `bloc_test` · golden tests

**i18n**
`intl_utils` (English, O'zbek, Russian, Turkish)

---

### Patterns I'm opinionated about

- **Clean Architecture** with three layers (`domain` / `data` / `presentation`) and one-way dependencies
- **`DataState<T>`** sealed class instead of `Either<Failure, T>` — Dart 3 pattern matching is enough
- **`safeApiCall`** helper — kills 80% of repository boilerplate
- **Session-expired stream** instead of in-interceptor refresh — no race conditions, no shared lock
- **Offline-first** repositories: connectivity check → fall back to sqflite cache → fire-and-forget cache write on success
- **Memory hygiene** in stateful widgets (always dispose controllers, cancel subscriptions, close BLoCs that are not GetIt singletons)

---

### Currently

- 📍 Based in **Qarshi, Uzbekistan**
- 💼 **Open to opportunities** — full-time office in Qarshi or remote
- 🔧 Refining the `flux_*` skeletons; happy to take feedback
- 📚 Recent reading: production migration patterns, BLoC concurrency, cross-platform release automation

---

### Get in touch

<a href="https://t.me/Fayziddin_B">Telegram</a> ·
<a href="https://www.linkedin.com/in/fayziddin2000">LinkedIn</a> ·
<a href="mailto:ruslanmedia.uz@gmail.com">Email</a>

<p align="center"><sub>If a repo here is useful to you, ⭐ it — that's the only signal that tells me to write more.</sub></p>
