# Guitar App 🎸

A Flutter application that helps you find and learn guitar chords for specific songs.  
The app provides chord diagrams, sound playback for each chord, and quick access to external resources.

---

## 📁 Project Structure

- `/assets/images/` — Chord diagrams, app icons, UI assets.
- `/assets/sound/` — MP3 files for chord sounds.
- `/lib/` — Main application source code (pages, models, services).
- `pubspec.yaml` — Dependency and asset management.
- `.gitattributes` — Git settings for line ending normalization (LF).
- `.gitignore` — Files and folders ignored by Git.

---

## 🔥 Key Features

- 🎵 **Chord Visualization**: Multiple positions (1, 2, 3) for each chord.
- 🔊 **Sound Playback**: Play corresponding chord sounds to aid practice.
- 🧠 **AI Assistance**: Auto-generate chord sheets from song names using AI prompts.
- 🎯 **Favorite Chords**: Mark favorite chord sheets and manage them easily.
- 🌍 **External Links**: Launch external websites (e.g., Instagram, Email) directly from the app using `url_launcher`.
- 🎨 **Theming**: Light/Dark mode support with customizable UI.
- 🌐 **Language Toggle**: Supports English and Traditional Chinese user interface.

---

## 🛠️ Tech Stack

- **Flutter** — Core framework.
- **Provider** — State management (theme, volume, language, chat).
- **Audioplayers** — Playing local audio (chord sounds).
- **URL Launcher** — Open external URLs and email apps.
- **HTTP** — Networking support for future features.

---

## 🧩 Main Packages Used

| Package | Purpose |
|:--------|:--------|
| `provider` | App-wide state management |
| `audioplayers` | Play chord MP3s |
| `url_launcher` | Launch email and web URLs |
| `http` | API requests (planned/future) |
| `flutter_lints` | Code quality and best practices |

---


