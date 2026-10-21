# Hi, I'm Abdul Rehman 👋

**Android Developer | Kotlin • Java • Native Android**

I build native Android applications and reusable libraries, with a focus on maintainable architecture and practical functionality. Based in Islamabad, Pakistan, I work as an Android Developer at Cordstone, where I develop practical mobile software using Kotlin, Java, and the Android SDK.

<a href="https://kotlinlang.org" target="_blank">
  <img src="https://cdn.simpleicons.org/kotlin/7F52FF" width="22" height="22" alt="Kotlin" />
</a>
<a href="https://developer.android.com" target="_blank">
  <img src="https://cdn.simpleicons.org/android/3DDC84" width="22" height="22" alt="Android" />
</a>

## About me

- 📱 I develop native Android applications with Kotlin and Java, using the Android SDK, Android Studio, XML layouts, and Jetpack Compose.
- 🔐 I build and maintain open-source Android libraries focused on authentication and device security.
- 🏗️ I apply and learn modern Android architecture — MVVM, Clean Architecture, ViewModel, StateFlow, and Kotlin Coroutines.
- 🌐 I integrate REST APIs and Firebase, and I'm learning backend engineering and API design fundamentals.

I am a Junior Android Developer. My experience includes an Android Developer internship at Cordstone (September–November 2025) and a software development internship at Troon Technologies (July–September 2025). I do not claim expertise in every technology listed here.

## Tech stack

**Languages**  
Kotlin · Java

**Android**  
Android SDK · Android Studio · XML layouts · Jetpack Compose

**Architecture & asynchronous programming**  
MVVM · Clean Architecture · ViewModel · StateFlow · Kotlin Coroutines

**Networking & data**  
Retrofit · REST APIs · Room · Firebase

**Dependency injection**  
Hilt · Dagger · Koin

**Tools**  
Git · GitHub · Gradle · Postman

I use Kotlin, Java, the Android SDK, XML layouts, and Gradle regularly. Jetpack Compose, Clean Architecture, StateFlow, dependency injection, Room, and Firebase are areas I am actively applying and learning.

## Featured projects

### SecureAuthLib — Android Authentication Library
[abd476/authlibandroid](https://github.com/abd476/authlibandroid) · MIT License · Kotlin

A reusable Android authentication library that unifies fingerprint, face, PIN, pattern, and password login behind a single API.

**Genuine features**
- Unified `AuthManager` API for fingerprint, face, PIN, pattern, and password authentication
- Coroutine-based asynchronous handling with `AuthResult` outcomes (Success, Failure, Cancelled, NotAvailable)
- Secure token storage using AndroidX Security Crypto
- Intelligent method fallbacks and authentication-availability checks
- Customizable authentication prompts and a demo application

**My contribution:** Primary developer. Designed the `AuthManager` API, implemented the biometric and PIN/password helpers, secure token storage, the `AuthResult`/`AuthType` model, and unit plus instrumentation tests.

**Engineering highlight:** Documents a real `BiometricPrompt` limitation — face authentication may fall back to fingerprint on devices where both biometrics are enrolled ([FACE_AUTH_LIMITATION.md](https://github.com/abd476/authlibandroid/blob/master/FACE_AUTH_LIMITATION.md)).

**Technologies:** Kotlin · Android SDK · AndroidX Security Crypto · Kotlin Coroutines · Gradle

[View source](https://github.com/abd476/authlibandroid) · [Demo app](https://github.com/abd476/authlibandroid/tree/master/app)

---

### SecurityGuard — Android Security & Anti-Theft Library
[abd476/SecurityFeatures](https://github.com/abd476/SecurityFeatures) · MIT License · Kotlin

An Android library for on-device security monitoring with seven detection features — no backend required.

**Genuine features**
- Charger detection, battery monitor, WiFi monitor, clap detection (find my phone), motion detection, proximity detection, and handsfree detection
- `SecurityGuard` API with `SecurityGuardConfig` for sensitivity, alarm duration, and vibration
- Runtime permission handling and event callbacks via `SecurityGuardCallback`
- Configurable per feature, with a demo application

**My contribution:** Primary developer. Designed the `SecurityGuard` API and configuration, implemented the per-feature detection services, runtime permission handling, and event callbacks.

**Engineering highlight:** Sensor- and permission-driven background monitoring with configurable sensitivity, alarm duration, and vibration behavior. All processing happens on-device.

**Technologies:** Kotlin · Android SDK · AndroidX Core/AppCompat/Material · Gradle

[View source](https://github.com/abd476/SecurityFeatures) · [Quick start](https://github.com/abd476/SecurityFeatures/blob/main/QUICKSTART.md)

## Current focus

- Building maintainable native Android applications.
- Improving Android UI quality and application architecture.
- Developing reusable Android authentication and security utilities.
- Learning backend engineering and API design.

## GitHub activity

<a href="https://github.com/abd476" target="_blank">
  <img src="https://github-readme-stats.vercel.app/api?username=abd476&show_icons=true&hide=rank,prs,issues,contributions&theme=default" alt="abd476's GitHub stats" />
</a>

## Contact

- [GitHub](https://github.com/abd476)

Feel free to explore my repositories, collaborate on an Android library, or connect about native Android development.
