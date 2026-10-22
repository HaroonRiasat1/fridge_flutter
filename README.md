# Fridge app: Flutter client

Flutter app for **Fridge**, which scans groceries to track expiry dates and suggests recipes. Built as a team project at Åbo Akademi University; it was a finalist at ICT Showroom 2025, winning Best UI from the jury plus first place for Best Technical Content and Best Presentation in the public vote.

The Django backend is in [fridge_backend](https://github.com/HaroonRiasat1/fridge_backend).

## Credits

Team project. This repository is a snapshot of [zaper1402/fridge_flutter](https://github.com/zaper1402/fridge_flutter); the original commit history is by Bulbul Rathore.

## Features

Splash screen, sign-up and login, home, grocery tracking, cuisine categories, favourites, notifications and profile.

## Run locally

```bash
flutter pub get
```

```bash
flutter run
```

Firebase is configured through `android/app/google-services.json` and `lib/firebase_options.dart`.
