# Master Experience Bank — Md. Habib Ullah Yeasin

> **Purpose:** Single source of truth. Nothing here is filtered for length or trimmed for a specific job. Pull from this bank when tailoring a resume, a LinkedIn profile, or interview prep.
>
> **Sources merged:** `Habib_Ullah_Yeasin_Resume.pdf` + project detail notes (Apps 1–5).
> **Consolidated:** 11 August 2026
>
> **Rule applied:** No facts, metrics, or numbers were invented. Where the source documents disagree with each other, both versions are preserved and the conflict is flagged in *§ Accuracy Guardrails*.

---

## Contact & Identity

| Field | Value |
|---|---|
| **Name** | Md. Habib Ullah Yeasin |
| **Target Title** | Flutter Developer / Cross-Platform Mobile Engineer |
| **Location** | Zam Zam Tower, Mohakhali, Banani, Dhaka, Bangladesh |
| **Email** | habibullahyeasin@outlook.com |
| **Phone** | +880 1303 219937 |
| **LinkedIn** | *(linked on resume — insert full URL)* |
| **GitHub** | github.com/H-Yeasin |

---

# Professional Summary

Three interchangeable variants. All state "1+ years of practical experience" per the source resume — do not inflate.

### Variant A — Mobile-Focused (closest to current resume)
Results-driven Flutter Developer with 1+ years of practical experience building high-performance, cross-platform mobile applications. Proficient in Dart, the Flutter framework, and modern mobile architecture. Expert in REST API integration, JSON handling, and complex state management across Bloc/Cubit, Riverpod, and Provider. Passionate about collaborating with designers to deliver pixel-perfect UI/UX, and thrives in fast-paced production environments.

### Variant B — Full-Stack / Product-Ownership Angle
Cross-platform mobile engineer with 1+ years of practical experience and four applications shipped to Google Play and the Apple App Store. Owns products end-to-end across all three tiers — Flutter clients, Node.js/TypeScript and Firebase Cloud Functions backends, and React admin dashboards — sharing unified authentication, real-time, and push-notification infrastructure. Deep hands-on experience with real-time systems (Socket.IO, Agora RTC/VoIP), payment and subscription infrastructure (Stripe, PayPal, RevenueCat), and application security (JWT rotation, custom 2FA, client-side encryption, Firestore security rules).

### Variant C — Security & Real-Time Specialist Angle
Flutter developer specializing in real-time and security-critical mobile systems. Built and shipped VoIP calling with native CallKit/PushKit integration, client-side RSA/AES message encryption with secure key exchange, custom OTP-based two-factor authentication on serverless infrastructure, and Firestore security rules that prevent client-side privilege escalation on billing fields. Comfortable across the full stack — Flutter/Dart, Node.js/TypeScript/Express, MongoDB, Redis, and the Firebase suite.

---

# Master Skills

Exhaustive, categorized inventory of every tool, language, framework, service, and methodology named across both source documents.

### Languages
Dart · TypeScript · JavaScript (ES modules) · C++ (via CS Fundamentals coursework) · SQL (HackerRank certified) · HTML/CSS · Swift *(iOS build configuration & Podfile/SPM troubleshooting only — not application code)*

### Mobile Development
Flutter · Dart · Android (native integration) · iOS (basic + native call-stack integration) · Google Play release & compliance · Apple App Store release · Android manifest permission auditing · Play Integrity · App Attest · flutter_screenutil (responsive UI) · Light/dark theming · Shimmer loading states · CustomPainter · Glassmorphism components · Custom design systems (AppTheme / AppColors / AppTypography)

### State Management
flutter_bloc (Bloc + Cubit pattern, 20+ modules at scale) · Riverpod (including code-generated providers and notifier-based patterns) · Provider / ChangeNotifier · GetX · Async programming (Futures / Streams) · Singleton service pattern for cross-cutting concerns · Global navigator key routing

### Architecture & Design Patterns
Clean Architecture (`core/` + `features/<name>/{data,domain,presentation}`) · MVC · MVVM · Domain-Driven / modular backend architecture · Dependency Injection (`get_it`, single composition root) · Repository pattern · Model ↔ Entity boundary mapping · DTO layering · Layered domain/infrastructure separation · Feature-based project structure · Functional error handling (`dartz` `Either<Failure, T>`, explicit `Failure` types) · Backwards-compatible API response parsing (v1 flat / v2 nested) · Offline-first data design · Code generation (freezed, json_serializable, Hive adapters, Riverpod generator) · Custom module scaffolding generator (`makeModule.ts`)

### Routing & Navigation
go_router (declarative routing, ~50 routes) · `ShellRoute` nested tab navigation · Route guards · Deep linking · Android App Links · iOS Universal Links (`.well-known` endpoints) · Push-notification-to-screen deep-link routing

### Backend & Runtime
Node.js · TypeScript · Express.js · Socket.io (server) · Firebase Cloud Functions (Node 22, ES modules) · Serverless architecture · REST API design · Swagger / OpenAPI (auto-generated live docs) · Callable functions · Scheduled/cron functions

### Databases & Data Layer
MongoDB / Mongoose · Cloud Firestore · Redis (caching + rate limiting) · SQLite (`sqflite`) · Hive (on-device NoSQL, code-generated adapters) · `flutter_secure_storage` · Firestore Security Rules · Geospatial data & geohashing · EC key model for encryption key exchange

### Real-Time & Communications
Socket.IO (client + server) · Custom singleton Socket.IO client service (auto-reconnect, 20+ typed event listeners) · JWT-authenticated socket middleware · Presence & typing indicators · Chat moderation events (report/like) · Agora RTC Engine (1:1 and group audio/video) · VoIP calling · `flutter_callkit_incoming` (native call UI) · iOS PushKit VoIP tokens · Group-call participant state tracking · Call signaling · Channel management, mute, camera switch, speaker toggle

### Authentication & Security
JWT (access/refresh token rotation) · bcrypt password hashing · OTP email verification · Custom OTP-based 2FA (salted SHA-256, expiry windows, rate limiting) · Google OAuth / Google Sign-In · Sign in with Apple · Role-Based Access Control (admin / user / partner) · Account status gating · Firebase App Check · Firestore Security Rules (per-user isolation, billing-field privilege-escalation prevention) · Biometric authentication (`local_auth`) · PIN lock · Session-timeout auto-lock · Client-side RSA/AES E2E-style encryption (`encrypt`, `pointycastle`) · Secure key storage · Screenshot/recording protection (`screen_protector`) · Firebase Secrets Manager · CORS allow-listing · API rate limiting · Automatic session invalidation on 401 · GDPR-compliant cascading account deletion

### Validation
Zod · `class-validator` / `class-transformer` · Joi

### Payments, Subscriptions & Monetization
Stripe (PaymentIntents, SetupIntents, saved payment methods, webhooks) · `flutter_stripe` · PayPal (order create/capture, webhooks) · RevenueCat (entitlements, paywalls, webhook + client dual-sync, regression guards, restore purchases, trial expiration jobs) · `in_app_purchase` · Google Mobile Ads (banner, interstitial, rewarded, native, app-open) · Webhook reconciliation · Subscription-gated feature access · Forced-update version gating

### Cloud, Storage & Serverless
AWS S3 (direct upload via `multer-s3`, external image re-hosting) · Cloudinary · Firebase Storage · Firebase Cloud Functions · Firebase Secrets Manager · Firebase Admin SDK · Vercel (backend deployment) · Static hosting · AWS cloud fundamentals (AWS Academy)

### Push Notifications & Messaging
Firebase Cloud Messaging (Android, iOS, Web + service worker) · Apple Push Notification service (APNs, dedicated service) · PushKit · Foreground / background / terminated state handling · Multi-device delivery · Notification deduplication · Call-vs-message payload routing · High-importance Android notification channels · Full-screen intents (call screen over lock screen) · Deep-link routing on notification tap · Nodemailer / SMTP · Mailgun · Handlebars email templates

### Maps, Location & Geospatial
Google Maps · `flutter_map` + OpenStreetMap · Custom cached tile provider · Custom marker factory · Geolocation · Geocoding · Haversine distance calculation · Geohashing for proximity queries · Geo-fenced "local missions" · Nearby / proximity search · Leaflet (web admin map of geo-tagged reports)

### Networking
Dio (interceptor-based auth-token injection, request/response logging, centralized 401 handling) · Custom `ApiClient` layer (JWT bearer auth, automatic token refresh, retry/backoff, multipart file upload) · REST API integration · JSON parsing & serialization · Multipart uploads

### Web / Admin Frontend
React 18 · Vite · Tailwind CSS v4 · Recharts (analytics dashboards) · Leaflet (live maps) · Reusable component systems (DataTable, CRUDModal, FilterBar) · Socket-driven live UI updates · Hand-rolled i18n context · Web service workers (push)

### Third-Party & Domain Integrations
Shopify Admin API (product/collection sync) · Agora · Pathao courier API (OAuth-style client/secret) · RedX courier API · Steadfast courier API · AI order-parsing service integration

### Media, Documents & Files
PDF generation (`pdf`) · Printing (`printing`) · In-app PDF viewing (`flutter_pdfview`) · Image capture & compression pipeline · File CRUD (upload / download / share) · Media storage pipelines (S3, Cloudinary, Firebase Storage)

### Internationalization
Flutter ARB files (4 languages) · Custom FR/EN localization · Riverpod notifier-based i18n · React context-based i18n · `intl` (date formatting)

### Testing & QA
`flutter_test` · `bloc_test` · `mocktail` · `firebase-functions-test` · Postman (Certified — API Fundamentals Student Expert) · Standalone HTML test harnesses against live APIs · Live credential "Test Connection" validation

### DevOps, Tooling & Ops
Git · GitHub · GitHub Actions (CI/CD) · VS Code · Android Studio · Figma · Firebase CLI · Vercel · `flutter_dotenv` (environment-based config) · `node-schedule` cron jobs · Firebase scheduled functions · `log4js` structured logging with daily rotation · Swagger live docs · Swift Package Manager conflict resolution (duplicate-symbol, Podfile pin) · Play Store / App Store submission & review compliance

### Methodologies & Practices
Clean Architecture · Domain-Driven Design (modular) · Dependency Injection · Repository & Singleton patterns · Code generation-first development · Functional error handling · Offline-first design · Security-by-design · GDPR compliance · Separation of concerns · Testable, decoupled composition roots · Instructional design & EdTech principles (academic background)

---

# Work History

> **Status note:** No formal employment entries (company, title, dates) appear in either source document. This section holds the scaffold plus the verifiable shipping record. Fill in employer names, titles, and date ranges — do not fabricate them.

### Employment Scaffold — *To Be Completed*

| Field | Value |
|---|---|
| Company | *(to fill)* |
| Job Title | *(to fill)* |
| Dates | *(to fill)* |
| Location / Arrangement | *(to fill)* |
| Attached projects | Map App 1–5 below to the correct employer, client, or "personal/freelance" |

### Verified Shipping Record

| # | Product | Platform(s) | Package / Bundle ID | Public Source |
|---|---|---|---|---|
| 1 | 212 Messenger | Google Play | `com.freshcodes.twoonetwomessenger` | Play Store listing |
| 2 | FFP Vault — Financial Freedom Power | Google Play | `com.ffpvault.app` | Play Store listing + `github.com/H-Yeasin/assetmanagement` |
| 3 | Hesteka | Google Play + Apple App Store | `com.emmafve.app` / App Store ID `6777662331` | Both store listings + `github.com/H-Yeasin/findanimalApp` |
| 4 | DocMobi | Google Play + Apple App Store | `com.docmobi.app` / App Store ID `6760239548` | Both store listings + `github.com/H-Yeasin/AroggyaPath` |
| 5 | SnapShip | Repository only (no store link provided) | — | `github.com/H-Yeasin/snapship` |
| 6 | Language Learning App | *(not specified)* | — | Listed on resume |

**Aggregate claim you can safely make:** *4 applications shipped to production app stores; 2 of them published on both Google Play and the Apple App Store.*

---

# Full Project Repository

Every project, every detail. XYZ-formatted bullets are resume-ready; the technical inventory beneath each is for interview prep and targeted tailoring.

---

## Project 1 — 212 Messenger
**Real-Time Messaging & VoIP Platform** · Flutter + Node.js/TypeScript · **Live on Google Play**

- **Live link:** `play.google.com/store/apps/details?id=com.freshcodes.twoonetwomessenger`
- **Repositories:** `flutter_mrauxins` (mobile) · `backend_mrauxins` (backend)
- **Scope:** End-to-end ownership of both client and server

### XYZ Bullets

- **Delivered a production real-time messaging platform to Google Play**, as measured by end-to-end ownership of both the Flutter client and the Node.js/TypeScript server, by architecting chat plus 1:1 and group voice/video calling on a Socket.io + MongoDB stack.
- **Enabled native-grade incoming-call UX on iOS**, as measured by full-screen call handling that works in background and terminated app states, by integrating Agora RTC with `flutter_callkit_incoming` and iOS PushKit VoIP tokens.
- **Protected message contents on-device and in transit**, as measured by a client-side RSA/AES end-to-end-style encryption scheme backed by an EC key-exchange model, by implementing cryptography with `encrypt`/`pointycastle` and persisting keys in `flutter_secure_storage`.
- **Unified notification delivery across Android and iOS**, as measured by a single FCM/APNs pipeline covering foreground, background, and terminated states with deduplication logic and multi-device fan-out, by routing call-type versus message-type payloads into CallKit or the chat stack respectively.
- **Scaled client-side state management**, as measured by 20+ Bloc/Cubit modules under automated test coverage, by standardizing on the `flutter_bloc` pattern and testing with `bloc_test` and `mocktail`.
- **Stabilized real-time connectivity**, as measured by a custom singleton Socket.IO client service with auto-reconnect and 20+ typed event listeners layered alongside a REST layer, by building the socket service in-house and pairing it with `dio` for request/response traffic.
- **Opened two parallel revenue streams in a single release**, as measured by a Stripe-backed premium tier alongside five Google Mobile Ads formats (banner, interstitial, rewarded, native, app-open), by integrating `in_app_purchase` and `google_mobile_ads` with AWS S3-backed media uploads.
- **Cleared Google Play review**, as measured by a successful production listing, by auditing and stripping unjustified Android manifest permissions and adding screenshot/recording protection (`screen_protector`) plus app-links deep linking for invites.
- **Made the app usable across four markets**, as measured by full internationalization into 4 languages via ARB files, by building a responsive UI with `flutter_screenutil`, light/dark theming, and shimmer loading states.
- **Guaranteed message availability without connectivity**, as measured by an offline-first local `sqflite` database persisting message history, by designing local persistence alongside the real-time sync layer.
- **Separated backend concerns for maintainability**, as measured by a clean split between domain (models, DTOs, services, controllers) and infrastructure (Express + Socket.io bootstrap), by enforcing schema validation with `class-validator`/`class-transformer` and Joi and publishing live auto-generated Swagger documentation.
- **Secured account access server-side**, as measured by a JWT + bcrypt authentication flow with OTP email verification, by templating verification mail with Handlebars and delivering through Mailgun/Nodemailer.
- **Automated privacy-driven data cleanup**, as measured by a `node-schedule` cron job that auto-deletes disappearing messages on schedule, by building the job into the backend service layer.
- **Instrumented production observability and mobile ops support**, as measured by structured `log4js` logging with daily rotation, forced-update version gating, and `.well-known` universal-links endpoints, by wiring these into the Express bootstrap.

### Technical Inventory

**Mobile (Flutter) — `flutter_mrauxins`**
`flutter_bloc`/Cubit (20+ Cubits) · `bloc_test` · `mocktail` · Custom Socket.IO singleton client (auto-reconnect, 20+ typed listeners) · `dio` REST layer · Agora RTC (1:1 + group) · `flutter_callkit_incoming` · iOS PushKit VoIP tokens · Firebase Cloud Messaging (all app states, dedup, call-type routing) · `encrypt` + `pointycastle` (RSA/AES) · `flutter_secure_storage` · `sqflite` offline DB · Google Mobile Ads (5 formats) · `in_app_purchase` · `screen_protector` · App links / deep linking · ARB i18n (4 languages) · `flutter_screenutil` · Light/dark theming · Shimmer states · Manifest permission auditing

**Backend — `backend_mrauxins` (Node.js/TypeScript)**
Express + Socket.io bootstrap · Layered domain/infrastructure architecture · Socket.io handlers for chat, calls (with group-call participant state tracking), typing, presence · JWT + bcrypt + OTP email verification (Handlebars templates) · AWS S3 (`multer-s3` direct upload + external image re-hosting) · Firebase Admin (FCM) · Dedicated APNs service · Stripe · Mailgun / Nodemailer · `node-schedule` cron (disappearing-message auto-deletion) · Swagger auto-generated live docs · `class-validator` / `class-transformer` / Joi · Mongoose/MongoDB with EC key model for encryption key exchange · `log4js` daily-rotation logging · Forced-update version gating · `.well-known` universal-links endpoints

---

## Project 2 — FFP Vault (Financial Freedom Power)
**Personal Finance & Secure Document Vault** · Flutter + Firebase Serverless · **Live on Google Play**

- **Live link:** `play.google.com/store/apps/details?id=com.ffpvault.app`
- **Repository:** `github.com/H-Yeasin/assetmanagement`
- **Package:** `ffp_vault` · **Version:** v6.0.0+8 (mature, iteratively shipped product)
- **Codebase:** ~104 Dart files in a feature-based structure (Auth, Dashboard, Profile, Vault, Housing, Insurance, Loans, Onboarding, `services/`, `providers/`)

### XYZ Bullets

- **Shipped and iterated a mature production finance app**, as measured by release version 6.0.0+8 spanning 100+ screens and ~104 Dart files, by building a feature-based Flutter/Riverpod codebase on go_router with `ShellRoute` nested tab navigation across ~50 routes.
- **Removed the need for a custom API server entirely**, as measured by a fully serverless backend built on Firebase (Auth, Firestore, Cloud Storage, Cloud Functions, FCM, App Check) with no custom REST or GraphQL layer, by implementing backend logic as Node 22 ES-module Cloud Functions.
- **Built a custom OTP-based two-factor authentication and password-reset system**, as measured by salted SHA-256 hashing, expiry windows, and rate limiting protecting registration verification, password reset, and 2FA, by implementing Cloud Functions backed by Firebase Secrets Manager with Nodemailer/SMTP delivery.
- **Kept subscription entitlement state consistent under race conditions**, as measured by a webhook + client dual-sync architecture with a regression guard that prevents stale data from clobbering active subscriptions, by integrating RevenueCat with entitlement polling that absorbs backend propagation delay plus restore-purchases support.
- **Hardened on-device access to sensitive financial data**, as measured by biometric unlock, PIN lock, and session-timeout auto-lock over encrypted storage, by combining `local_auth`, `flutter_secure_storage`, and Hive with code-generated adapters.
- **Prevented client-side privilege escalation**, as measured by Firestore Security Rules enforcing per-user data isolation and locking down billing fields against client writes, by authoring custom ownership-based access control rules.
- **Delivered GDPR-grade data erasure**, as measured by a single callable function cascading deletion across Firestore, Cloud Storage, OTP records, and the Firebase Auth user itself, by building the cascade as one atomic user-facing action.
- **Automated recurring engagement and billing hygiene**, as measured by a 15-minute cron job for reminder push notifications and a daily trial-expiration job, by scheduling serverless Cloud Functions.
- **Unblocked a stalled iOS release**, as measured by resolution of a Swift Package Manager duplicate-symbol conflict, by diagnosing the dependency clash and documenting a permanent Podfile pin.
- **Monetized premium storage**, as measured by subscription-gated file CRUD with upload, download, and share inside a secure document Vault, by tying feature access to RevenueCat entitlement state.
- **Modeled domain-specific financial logic in-app**, as measured by loan amortization calculations, multi-frequency payment normalization, and housing/insurance cost tracking, by implementing the calculation layer against the app's finance data model.
- **Reduced authentication friction while raising app integrity**, as measured by Google Sign-In and Sign in with Apple OAuth paths validated by Firebase App Check (Play Integrity on Android, App Attest on iOS), by wiring both providers into the Firebase Auth flow.

### Technical Inventory
Flutter/Dart · Riverpod · go_router (`ShellRoute`, ~50 routes) · Firebase suite (Firestore, Auth, Cloud Functions, Cloud Storage, App Check, FCM, Secrets Manager) · Node.js Cloud Functions (Node 22, ES modules) + scheduled cron · RevenueCat (subscriptions, paywalls, webhooks) · Stripe (`flutter_stripe`) · Hive (code-generated adapters) · `flutter_secure_storage` + `local_auth` · Nodemailer/SMTP · Google Sign-In · Sign in with Apple · Firestore Security Rules · Swift Package Manager / Podfile build engineering

### Known Gaps *(interview-only — do not put on the resume)*
- No automated test suite, despite `flutter_test` and `firebase-functions-test` being declared dependencies.
- No CI/CD pipeline — deployment is manual via Firebase CLI.

---

## Project 3 — Hesteka (`emmafve`)
**Full-Stack Rewards, Missions & Community Platform** · Flutter + Node.js/Express/MongoDB + React Admin · **Live on Google Play and the Apple App Store**

- **Google Play:** `play.google.com/store/apps/details?id=com.emmafve.app`
- **App Store:** `apps.apple.com/fr/app/hesteka/id6777662331`
- **Repository:** `github.com/H-Yeasin/findanimalApp`
- **Headline signal:** All three tiers built and connected — mobile app ↔ API ↔ admin dashboard — sharing one auth, real-time, and notification infrastructure. Most candidates show one tier.

### XYZ Bullets

- **Owned all three tiers of a live consumer product**, as measured by a Flutter app published on both Google Play and the App Store, a Node.js/Express/MongoDB API, and a React admin dashboard sharing a single auth, real-time, and notification layer, by designing shared infrastructure once and consuming it identically across every tier.
- **Standardized and accelerated backend delivery**, as measured by 20 feature modules each following identical controller/service/route/model/validation layering, by writing a custom code generator (`makeModule.ts`) to scaffold new modules and enforcing Zod schema validation on every endpoint.
- **De-risked payment collection**, as measured by dual gateway support — Stripe (PaymentIntents, SetupIntents, saved payment methods) and PayPal (order create/capture) — each with full webhook handling and reconciliation, by building both integrations and validating them through standalone HTML test harnesses hitting the live API.
- **Secured multi-provider authentication at scale**, as measured by JWT access/refresh token rotation, Google OAuth, Sign in with Apple, and OTP email verification operating under role-based access control across admin, user, and partner roles, by layering bcrypt hashing, account-status gating, Redis-backed rate limiting, and CORS allow-listing.
- **Delivered moderated real-time chat**, as measured by community and private 1:1 channels supporting message report and like moderation actions, by implementing Socket.IO with custom JWT-authenticated socket middleware.
- **Drove user retention through a points economy**, as measured by an automated cron-based balance-reset job paired with a photo-based donation-proof verification workflow tied to a rewards ledger, by building the validation pipeline and scheduled reset into the API layer.
- **Enabled proximity-based "local missions"**, as measured by geohashed proximity queries powering geo-fenced mission discovery, by integrating Google Maps with geolocation and geocoding on the mobile client.
- **Built the operator control plane**, as measured by 18 CRUD admin pages, Recharts analytics dashboards, and a live Leaflet map of geo-tagged reports, by composing reusable DataTable/CRUDModal/FilterBar components in React 18 + Vite + Tailwind v4 with socket-driven live updates.
- **Mirrored an external commerce catalogue in-product**, as measured by Shopify Admin API product and collection browsing surfaced in both the mobile app and the admin panel, by building a sync integration against the Shopify Admin API.
- **Shipped bilingual UX twice in two independent paradigms**, as measured by separate FR/EN internationalization systems — a React context implementation on web and a Riverpod notifier implementation on mobile — by hand-rolling localization for each platform rather than relying on a shared package.
- **Kept push notifications consistent across every surface**, as measured by Firebase Cloud Messaging wired identically into the backend, the admin web app (with a service worker), and the mobile client, by centralizing notification dispatch in the API layer.
- **Structured the mobile client for scale**, as measured by clean architecture folders (`core/`, `features/<name>/{data,domain,presentation}`) with route-guarded navigation, by using code-generated Riverpod providers, go_router guards, `freezed` + `json_serializable` codegen, a Dio networking layer, and `flutter_secure_storage`.

### Technical Inventory

**Backend (Node.js/TypeScript):** Express.js · TypeScript · MongoDB/Mongoose · Redis (caching + rate limiting) · 20 modular domain-driven feature modules · `makeModule.ts` custom scaffolding generator · Zod validation on every endpoint
**Auth & Security:** JWT access/refresh rotation · Google OAuth · Sign in with Apple · OTP email verification · RBAC (admin/user/partner) · Account status gating · bcrypt · Rate limiting · CORS allow-listing
**Payments:** Stripe (PaymentIntents, SetupIntents, saved payment methods, webhooks) · PayPal (order create/capture, webhooks) · Standalone HTML test harnesses against the live API
**Real-Time & Notifications:** Socket.IO with custom JWT socket middleware · Community chat · Private 1:1 chat · Chat moderation/reporting · FCM across backend, admin web (service worker), and mobile
**Integrations:** Shopify Admin API · Cloudinary · Nodemailer/SMTP · Geohashing / geo-fenced missions
**Mobile (Flutter):** Riverpod (code-generated providers) · go_router with route guards · Clean architecture · `freezed` + `json_serializable` · Dio · `flutter_secure_storage` · Google Maps · Geolocation/geocoding · Deep linking · Custom FR/EN localization
**Admin (React):** React 18 · Vite · Tailwind v4 · 18 CRUD pages · Reusable DataTable / CRUDModal / FilterBar · Recharts · Leaflet · Socket-driven live updates · Hand-rolled i18n context

### Known Gaps *(interview-only — do not put on the resume)*
- No CI/CD pipeline and no containerization (Docker) anywhere in the stack. Deployment is Vercel for the backend and static hosting for the admin panel.
- **Highest-leverage fix identified:** adding a GitHub Actions workflow and a backend Dockerfile would close the one real gap versus a "production-grade" story, at a cost of a few hours.

---

## Project 4 — DocMobi
**Telehealth / Telemedicine Platform** · Flutter + Custom REST Backend · **Live on Google Play and the Apple App Store**

- **Google Play:** `play.google.com/store/apps/details?id=com.docmobi.app`
- **App Store:** `apps.apple.com/fr/app/docmobi/id6760239548`
- **Repository:** `github.com/H-Yeasin/AroggyaPath`

### XYZ Bullets

- **Launched a role-based telehealth product on both major app stores**, as measured by fully separate patient and doctor experiences delivered from a single Flutter codebase, by implementing role-driven UI, routing, and theming across the app.
- **Enabled live doctor–patient consultations**, as measured by Agora RTC audio/video sessions supporting channel management, mute, camera switch, and speaker toggle, by layering Agora media streams over Socket.IO signaling and presence.
- **Delivered lock-screen-grade incoming-call UX on Android**, as measured by custom high-importance notification channels with full-screen intents that render the call screen over the lock screen, by wiring FCM through foreground, background, and terminated app states with deep-link routing into specific screens on tap.
- **Hardened and centralized the networking layer**, as measured by a hand-built `ApiClient` providing JWT bearer auth, automatic token refresh with 401 handling, retry/backoff logic, and multipart file upload across 7 domain API service modules (auth, appointments, chat, doctors, users, dependents, uploads), by replacing scattered ad-hoc HTTP calls with one shared client.
- **Built doctor discovery on a non-default mapping stack**, as measured by `flutter_map`/OpenStreetMap integration with a custom cached tile provider and a custom marker factory, by adding geocoding and Haversine distance calculation to rank nearby doctors by proximity.
- **Delivered an end-to-end medical document pipeline**, as measured by image capture and compression on upload paired with PDF generation, in-app viewing, and printing on retrieval, by integrating `pdf`, `printing`, and `flutter_pdfview` across Android and iOS.
- **Organized application state for a multi-role domain**, as measured by 6 domain providers (auth, user, doctor, appointment, medical records, dependents) plus singleton services for sockets, calls, location, and notifications, by using the Provider/ChangeNotifier pattern with a global navigator key so push notifications can route into the app from outside the widget tree.
- **Supported a realistic clinical workflow end-to-end**, as measured by appointment booking and scheduling, medical record management, dependent/family-member booking, doctor reviews, and emergency contacts, by modeling each as a first-class domain feature.

### Technical Inventory
Flutter/Dart · Agora RTC Engine · Socket.IO (chat, presence, call signaling) · Firebase Cloud Messaging (all app states, deep linking on tap) · Custom high-importance Android channels + full-screen intents · Custom `ApiClient` (JWT, token refresh, retry/backoff, multipart) · 7 API service modules · `flutter_map` + OpenStreetMap · Custom cached tile provider · Custom marker factory · Geocoding · Haversine distance · `pdf` · `printing` · `flutter_pdfview` · Image capture/compression · Provider/ChangeNotifier (6 domain providers) · Singleton service pattern · Global navigator key · Role-based UI/theming

### Do Not Overclaim on This Project *(critical)*
- **Firestore and Firebase Auth are in `pubspec.yaml` but never used in code.** Auth and data are 100% the custom REST backend. **Do not list "Firebase Firestore" for this project.**
- **Riverpod and GetX are declared dependencies but unused here.** Actual state management is plain `provider`.
- **No payment gateway is integrated**, despite payment API endpoints existing in the backend config. Do not claim payment integration on this project.
- **No `.arb`/l10n setup exists** — `intl` is used only for date formatting. Do not claim localization here.
- **No automated tests and no CI/CD.** Be upfront if asked rather than implying test coverage.

---

## Project 5 — SnapShip
**AI-Assisted E-Commerce Logistics & Multi-Courier Dispatch Hub** · Flutter · **Repository only (no store link provided)**

- **Repository:** `github.com/H-Yeasin/snapship`

### XYZ Bullets

- **Architected a merchant logistics app for maintainability**, as measured by Clean Architecture applied across 5 feature modules (auth, dashboard, profile, ship_hub, snap_engine) each split into `data`/`domain`/`presentation` layers, by applying `flutter_bloc` consistently and wiring dependencies through a single `get_it` composition root registering singletons and factories.
- **Unified three competing courier APIs behind one interface**, as measured by normalized integration of Pathao (OAuth-style client/secret), RedX, and Steadfast (API keys) despite incompatible credential schemas, by abstracting all three behind a single domain interface for dispatch.
- **Turned unstructured customer messages into dispatch-ready orders**, as measured by an AI parsing pipeline ("SnapEngine") that extracts name, phone, address, COD amount, and weight from free-text "Banglish" (mixed Bangla/English) input and returns an `OrderConfidence` score covering overall score, address-match score, match method, and phone validity, by surfacing human-readable warnings to the merchant before dispatch.
- **Enabled informed courier selection before commitment**, as measured by a live `/couriers/compare-rates` engine showing per-courier price estimates side by side, by adding a dedicated tracking BLoC and repository that pulls consignment status per order after dispatch.
- **Prevented invalid courier credentials from ever being persisted**, as measured by an in-app "Test Connection" check validated against the real courier auth endpoint before storage, by storing merchant API keys in `flutter_secure_storage` and exposing per-courier webhook URL configuration for delivery status callbacks.
- **Eliminated unchecked exceptions across async network flows**, as measured by end-to-end use of `dartz` `Either<Failure, T>` with explicit `Failure` types from repository through to UI, by replacing throw/catch propagation with functional error handling at every layer boundary.
- **Future-proofed API consumption against breaking changes**, as measured by `OrderModel` parsers that handle both v1 flat and v2 nested API response shapes, by enforcing an explicit Model → Entity mapping discipline at the repository boundary.
- **Secured merchant sessions**, as measured by JWT persistence in `flutter_secure_storage`, auto-attached via a Dio interceptor, with automatic session invalidation on 401, by centralizing auth-token injection, request/response logging, and 401 handling in one Dio client.
- **Established a distinctive branded design system**, as measured by a dedicated `AppTheme`/`AppColors`/`AppTypography` layer with dark-mode-first design, `CustomPainter` dashed "tactical" borders, glassmorphism `GlassCard` components, and shimmer loading states, by building the theme layer as shared infrastructure rather than per-screen styling.
- **Kept secrets out of source control**, as measured by environment-based configuration of API base URLs and secrets, by adopting `flutter_dotenv` for runtime config.

### Technical Inventory
Flutter/Dart · Clean Architecture (5 feature modules) · `flutter_bloc` (full Blocs for dispatch/tracking/shipments + narrow Cubits: `ThemeCubit`, `CourierSetupCubit`) · `get_it` DI (`injection_container.dart`) · `dartz` `Either<Failure, T>` · Dio (interceptors: auth injection, logging, centralized 401) · `flutter_secure_storage` · `flutter_dotenv` · Pathao / RedX / Steadfast courier APIs · AI parsing endpoint integration · Confidence scoring system · Webhook configuration · `AppTheme`/`AppColors`/`AppTypography` · `CustomPainter` · Glassmorphism · Shimmer

---

## Project 6 — Language Learning App
**EdTech / LMS-Style Vocabulary & Grammar Platform** · Flutter *(from source resume)*

### XYZ Bullets

- **Built an interactive vocabulary and grammar learning app**, as measured by quiz flows, progress tracking, and daily learning streaks comparable to modern LMS platforms, by developing the educational logic layer around exercise and assessment mechanics.
- **Managed learner state efficiently**, as measured by persistent user sessions, quiz scores, and daily streak tracking, by using Riverpod as the single state management layer.
- **Supported pronunciation practice**, as measured by integrated audio playback within a responsive, student-friendly interface, by designing the UI/UX around learner accessibility.

### Technical Inventory
Flutter · Dart · Riverpod · Audio playback · Responsive UI · Quiz & progress-tracking logic

---

## Project 6b — AroggyaPath *(as described on the original resume)*
**Healthcare / Telemedicine Application**

> ⚠️ **Conflict flag:** This shares the `AroggyaPath` repository with **Project 4 (DocMobi)**, but the two source documents describe the stack differently. Both versions are preserved verbatim below. **Verify against the codebase before using either.** See *§ Accuracy Guardrails*.

**Original resume bullets (unverified against code):**
- Structured the codebase using Clean Architecture to ensure scalability and testability.
- Implemented Hive for local data caching, allowing users to view appointments without internet.
- Integrated REST APIs to fetch real-time health data and utilized JSON serialization.
- Tech stack claimed: Flutter, Provider, Firebase Firestore, FCM (Push Notifications).

**XYZ-formatted (if verified):**
- **Enabled offline appointment access**, as measured by users being able to view appointments without an internet connection, by implementing Hive for local data caching.
- **Structured the codebase for scalability and testability**, as measured by a Clean Architecture layer separation, by organizing domain, data, and presentation concerns independently.
- **Surfaced real-time health data in-app**, as measured by live REST-driven appointment and record data, by integrating REST APIs with JSON serialization.

---

# Education

**University of Frontier Technology, Bangladesh**
*B.Sc. in Educational Technology and Engineering (EdTEE)* · Jan 2020 – Jan 2025
**CGPA: 3.28 / 4.00**

A multidisciplinary program integrating software development, instructional design, networking, and engineering principles.

**Relevant coursework:** Mobile Application Development · Data Structures & Algorithms · Object-Oriented Programming · Database Management Systems · Networking · Software Engineering · Database Systems · Cloud Computing · Testing & QA

---

# Certifications

| Certification | Issuer | Year | Note |
|---|---|---|---|
| SQL (Basics) Certified | HackerRank | — | Validates relational database knowledge |
| Postman API Fundamentals Student Expert | Postman | 2025 | — |
| AWS Academy Graduate: Introduction to Cloud | AWS Academy | 2025 | — |
| CS Fundamentals With Phitron | Phitron | 2025 | Focus on C++ and Data Structures |
| 21st Century Core Employability Skills Development Program | Wadhwani Foundation | 2023 | **Achieved 90% score** in "Competencies of Job Ready Modules" under Wadhwani Opportunity's global workforce readiness initiative |

---

# Accuracy Guardrails

Everything in this section is preserved from your own project notes. Read it before every resume submission.

### Conflicts Between the Two Source Documents — Resolve Before Claiming

| Claim | Resume says | Project notes say | Action |
|---|---|---|---|
| **Firebase Firestore on AroggyaPath/DocMobi** | Listed in the tech stack | In `pubspec.yaml` but **never used in code**; auth and data are 100% custom REST | Verify in code. Default to **removing** the Firestore claim for this project. |
| **Hive on AroggyaPath** | "Implemented Hive for local data caching" for offline appointments | Not mentioned anywhere in the DocMobi/AroggyaPath breakdown | Verify. Hive **is** confirmed on FFP Vault (Project 2) — safe to claim there. |
| **Clean Architecture on AroggyaPath** | Claimed | Notes describe Provider/ChangeNotifier + singleton services, not Clean Architecture | Verify. Clean Architecture **is** confirmed on Projects 3 and 5 — safe to claim there. |
| **GetX (Advanced)** | Listed as an advanced skill | On DocMobi, GetX is a declared but **unused** dependency; no other project uses it | Only claim GetX if you have genuine experience outside these five apps. |
| **Riverpod on DocMobi** | Implied by the general skills list | Declared but unused on that project | Riverpod **is** confirmed on Projects 2, 3, and 6 — claim it there. |
| **GitHub Actions (CI/CD)** | Listed in Tools & DevOps | **No CI/CD found** in Projects 2, 3, or 4 | Only claim if used elsewhere. Otherwise this is the single highest-value gap to close. |

### Portfolio-Wide Gaps *(honest answers for interviews — never on the resume)*
- **No automated test suite** on Projects 2, 3, 4, or 5. Test coverage **is** genuine on Project 1 (20+ Bloc/Cubit modules tested with `bloc_test`/`mocktail`) — that is your one real testing story, so lead with it.
- **No CI/CD pipeline** on Projects 2, 3, or 4. Deployment is manual: Firebase CLI (Project 2), Vercel + static hosting (Project 3).
- **No containerization (Docker)** anywhere in the portfolio.
- **No payment gateway on DocMobi**, despite backend payment endpoints existing.
- **No real l10n setup on DocMobi** — `intl` is date formatting only.

### Highest-Leverage Improvements Identified
1. Add a **GitHub Actions workflow** and a **backend Dockerfile** to Project 3 — a few hours of work that closes the one real gap versus a "production-grade" story and legitimizes the CI/CD line already on your resume.
2. Add a minimal test suite to Project 2 or 5, where the testing dependencies are already declared.

---

# Quick-Pull Bullet Bank

The highest-signal bullets, grouped by the theme a job description is likely to emphasize. Pull 4–6 per application.

### If the role emphasizes **Real-Time / Communications**
- Enabled native-grade incoming-call UX on iOS, as measured by full-screen call handling in background and terminated app states, by integrating Agora RTC with `flutter_callkit_incoming` and PushKit VoIP tokens. *(P1)*
- Stabilized real-time connectivity, as measured by a custom singleton Socket.IO service with auto-reconnect and 20+ typed event listeners, by building the socket layer in-house alongside a Dio REST client. *(P1)*
- Delivered moderated real-time chat, as measured by community and private 1:1 channels with report/like moderation, by implementing Socket.IO with custom JWT-authenticated socket middleware. *(P3)*
- Enabled live doctor–patient consultations, as measured by Agora RTC sessions with channel management, mute, camera switch, and speaker toggle, by layering Agora media over Socket.IO signaling and presence. *(P4)*

### If the role emphasizes **Security**
- Protected message contents on-device and in transit, as measured by client-side RSA/AES encryption backed by an EC key-exchange model, by implementing `encrypt`/`pointycastle` with keys in `flutter_secure_storage`. *(P1)*
- Built a custom OTP-based 2FA and password-reset system, as measured by salted SHA-256 hashing, expiry windows, and rate limiting, by implementing Cloud Functions backed by Firebase Secrets Manager and Nodemailer. *(P2)*
- Prevented client-side privilege escalation, as measured by Firestore Security Rules enforcing per-user isolation and protecting billing fields, by authoring ownership-based access control rules. *(P2)*
- Delivered GDPR-grade data erasure, as measured by one callable function cascading deletion across Firestore, Storage, OTP records, and the Auth user, by building the cascade as a single atomic action. *(P2)*
- Secured multi-provider authentication, as measured by JWT access/refresh rotation, Google OAuth, Sign in with Apple, and OTP verification under RBAC across three roles, by adding bcrypt, account gating, Redis rate limiting, and CORS allow-listing. *(P3)*

### If the role emphasizes **Architecture / Code Quality**
- Scaled client-side state management, as measured by 20+ Bloc/Cubit modules under automated test coverage, by standardizing on `flutter_bloc` with `bloc_test` and `mocktail`. *(P1)*
- Standardized backend delivery, as measured by 20 feature modules with identical controller/service/route/model/validation layering, by writing a `makeModule.ts` code generator and enforcing Zod validation on every endpoint. *(P3)*
- Eliminated unchecked exceptions across async network flows, as measured by end-to-end `dartz` `Either<Failure, T>` usage from repository to UI, by replacing throw/catch with explicit `Failure` types. *(P5)*
- Future-proofed API consumption, as measured by parsers handling both v1 flat and v2 nested response shapes, by enforcing Model → Entity mapping at the repository boundary. *(P5)*
- Hardened and centralized the networking layer, as measured by a hand-built `ApiClient` with JWT auth, token refresh, retry/backoff, and multipart upload across 7 domain services, by replacing scattered HTTP calls with one shared client. *(P4)*

### If the role emphasizes **Full-Stack / Ownership**
- Owned all three tiers of a live consumer product, as measured by a Flutter app on both stores, a Node.js/Express/MongoDB API, and a React admin dashboard sharing one auth, real-time, and notification layer, by designing shared infrastructure once and reusing it across every tier. *(P3)*
- Delivered a production real-time messaging platform to Google Play, as measured by end-to-end ownership of both the Flutter client and the Node.js/TypeScript server, by architecting chat plus 1:1 and group calling on Socket.io + MongoDB. *(P1)*
- Removed the need for a custom API server entirely, as measured by a fully serverless Firebase backend with no custom REST or GraphQL layer, by implementing backend logic as Node 22 ES-module Cloud Functions. *(P2)*

### If the role emphasizes **Payments / Monetization**
- Kept subscription entitlement state consistent under race conditions, as measured by a webhook + client dual-sync architecture with a regression guard against stale-data clobbering, by integrating RevenueCat with propagation-delay-tolerant entitlement polling. *(P2)*
- De-risked payment collection, as measured by dual gateway support (Stripe and PayPal) with full webhook reconciliation on both, by building and validating both integrations against the live API. *(P3)*
- Opened two parallel revenue streams in a single release, as measured by a Stripe-backed premium tier alongside five Google Mobile Ads formats, by integrating `in_app_purchase` and `google_mobile_ads`. *(P1)*

### If the role emphasizes **Shipping / Product Delivery**
- Shipped and iterated a mature production finance app, as measured by release version 6.0.0+8 across 100+ screens and ~104 Dart files, by building a feature-based Riverpod + go_router codebase across ~50 routes. *(P2)*
- Cleared Google Play review, as measured by a successful production listing, by auditing and stripping unjustified manifest permissions and adding screenshot/recording protection. *(P1)*
- Unblocked a stalled iOS release, as measured by resolution of a Swift Package Manager duplicate-symbol conflict, by diagnosing the clash and documenting a permanent Podfile pin. *(P2)*
- Launched a role-based telehealth product on both major app stores, as measured by separate patient and doctor experiences from one codebase, by implementing role-driven UI, routing, and theming. *(P4)*

---

*End of Master Experience Bank.*
