# Hi, I'm Abdul Rehman 👋

I'm a Junior Android Developer based in Islamabad, Pakistan, currently working at Cordstone. I build native Android applications with Kotlin and Java, focusing on clean, maintainable architecture and practical software that solves real problems.

My primary focus is native Android development — the Android SDK, Kotlin, XML-based UI, and Jetpack Compose. I'm growing my experience with modern Android architecture (MVVM, Clean Architecture), dependency injection (Hilt, Dagger, Koin), and API integration with Retrofit and Firebase.

I enjoy building Android applications and open-source libraries that are easy to understand, test, and maintain.

## About me

- 📱 **Native Android development** — Kotlin and Java, Android SDK, Android Studio, XML layouts, Jetpack Compose
- 🏗️ **Architecture** — MVVM and Clean Architecture, ViewModel, StateFlow, Kotlin Coroutines
- 🌐 **API & data** — Retrofit, REST APIs, Room, Firebase
- 🔐 **Dependency injection & security** — Hilt, Dagger, Koin; Android authentication and secure token storage
- 🛠️ **Tools** — Git, GitHub, Gradle, Postman, IntelliJ IDEA

I currently work as an Android Developer at Cordstone. Previously, I completed an Android Developer internship at Cordstone and a software development internship at Troon Technologies.

Outside of client work, I maintain open-source Android libraries focused on authentication and device security.

## Currently focused on

- Building and improving native Android applications
- Applying MVVM, repositories, ViewModels, and reactive UI state with Kotlin Coroutines and StateFlow
- Learning and applying dependency injection with Hilt and Koin
- Improving Android UI quality, performance, and reliability
- Developing open-source Android authentication and security utilities
- Learning backend engineering and API design fundamentals

## Tech stack

**Languages**
Kotlin · Java

**Android development**
Android SDK · Android Studio · XML layouts · Jetpack Compose

**Architecture & asynchronous programming**
MVVM · Clean Architecture · ViewModel · StateFlow · Kotlin Coroutines

**Networking & data**
Retrofit · REST APIs · Room · Firebase

**Dependency injection**
Hilt · Dagger · Koin

**Tools & engineering**
Git · GitHub · Gradle · Postman · IntelliJ IDEA

I use Kotlin, Java, the Android SDK, XML layouts, and Gradle regularly. Jetpack Compose, Clean Architecture, StateFlow, dependency injection, Room, and Firebase are areas I am actively applying and learning. I do not claim production expertise in every technology listed.

## Featured projects

### SecureAuthLib — Android Authentication Library
[abd476/authlibandroid](https://github.com/abd476/authlibandroid) · MIT License · Kotlin

A reusable Android authentication library that unifies fingerprint, face, PIN, pattern, and password login behind a single API. Includes coroutine-based asynchronous handling, secure token storage (AndroidX Security Crypto), intelligent method fallbacks, configurable prompts, and a demo application.

**My contribution:** Primary developer. Designed the unified `AuthManager` API, implemented biometric and PIN/password authentication helpers, secure token storage, the `AuthResult`/`AuthType` model, and unit and instrumentation tests.

**Technologies:** Kotlin, Android SDK, AndroidX Security Crypto, Kotlin Coroutines, Gradle

**Engineering highlight:** Documents a real `BiometricPrompt` limitation — face authentication may fall back to fingerprint on devices where both biometrics are enrolled ([FACE_AUTH_LIMITATION.md](https://github.com/abd476/authlibandroid/blob/master/FACE_AUTH_LIMITATION.md)).

[View source](https://github.com/abd476/authlibandroid) · [Demo app](https://github.com/abd476/authlibandroid/tree/master/app)

### SecurityGuard — Android Security & Anti-Theft Library
[abd476/SecurityFeatures](https://github.com/abd476/SecurityFeatures) · MIT License · Kotlin

An Android library for device security monitoring with seven features: charger detection, battery monitor, WiFi monitor, clap detection (find my phone), motion detection, proximity detection, and handsfree detection. All processing happens on-device; no backend required.

**My contribution:** Primary developer. Designed the `SecurityGuard` API and configuration, implemented per-feature detection services, runtime permission handling, event callbacks, and a demo application.

**Technologies:** Kotlin, Android SDK, AndroidX Core/AppCompat/Material, Gradle

**Engineering highlight:** Sensor- and permission-driven background monitoring with configurable sensitivity, alarm duration, and vibration behavior.

[View source](https://github.com/abd476/SecurityFeatures) · [Quick start](https://github.com/abd476/SecurityFeatures/blob/main/QUICKSTART.md)

## Open source

I'm interested in Android utilities and libraries, authentication and mobile security, reusable components, and developer productivity. My public libraries are MIT licensed and include setup instructions, a demo application, and tests where applicable.

- [SecureAuthLib](https://github.com/abd476/authlibandroid) — Android authentication library
- [SecurityGuard](https://github.com/abd476/SecurityFeatures) — Android security & anti-theft library

I have not contributed to external open-source projects yet; my open-source work so far is my own libraries.

## Connect with me

- [GitHub](https://github.com/abd476)
- LinkedIn: [add your LinkedIn URL](https://www.linkedin.com/in/) *(placeholder — add your profile)*
- Email: [add your email address](mailto:) *(placeholder — add your address)*

Feel free to connect, collaborate on an Android library, or explore my repositories.

---

*Built with Kotlin and Android. This profile is a work in progress as I continue learning and shipping real code.*
