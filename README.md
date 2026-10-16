👋 Hi, I'm Dwi Prasetyo

Android engineer with 4 years of production experience building offline-first field-worker software in Kotlin. I also build cross-platform apps with Kotlin Multiplatform (Android, iOS, Spring Boot backend).

**What I've done at work**
- Rebuilt an offline-first outbox sync layer: a 1,731-line monolith became a 56-line orchestrator (91% less code) using Strategy pattern, WorkManager and group-based error isolation, so one failed task no longer blocks the queue.
- Led modularization of a legacy 2017 app from 3 to 40 Gradle modules, with convention plugins for shared build config.
- Co-drove the Java → Kotlin migration (~16% → ~68% Kotlin) and introduced Jetpack Compose.
- The app serves about 1.4K daily active field workers.

**How I work**
I start with simple, explicit solutions (KISS / YAGNI), ship something that works, and let real problems earn their abstractions. Over-engineering on day one is just technical debt with better naming. I care about how an app behaves over time, not just how it looks on day one.

**What I'm interested in**
- Offline-first architecture (outbox-based sync, deferred execution)
- Predictable state management (MVVM / MVI / reducers)
- Moving business rules out of the UI layer
- Incremental refactoring of long-lived codebases

**Side Project**
- [Yuko-Gamify](https://play.google.com/store/apps/details?id=com.kakapo.yukoapp.beta&hl=id): KMP productivity app (Android, iOS, Spring Boot) with ~940 automated tests, including pipeline tests on a real SQLDelight stack and 61 "sabotage checks" to prove the tests can fail.

**Open source**
- [Oakane](https://github.com/Uwi0/Oakane): KMP personal finance app with a shared business layer, Compose and SwiftUI clients.

**Stack:** Kotlin · Jetpack Compose · Coroutines/Flow · Hilt · WorkManager · Room · Kotlin Multiplatform · SQLDelight · SwiftUI

📍 Indonesia (UTC+7) · Open to remote or relocation (Europe, East Asia, Australia, Southeast Asia)
📫 kakapoweb@gmail.com · [LinkedIn](https://linkedin.com/in/uwi0)
