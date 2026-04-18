# RealTalk

RealTalk is a production-grade, high-performance real-time messaging platform designed for cross-platform communication. Built with a robust Go backend and featuring dedicated Web and Flutter clients, it prioritizes performance, scalability, and exceptional user experience.

---

## 🚀 Features

- **Real-Time Synchronicity**: Lightning-fast message delivery powered by optimized WebSockets.
- **Cross-Platform Access**: Seamless communication across native Mobile (Flutter) and Web (HTML5/Vanilla JS) environments.
- **Live Typing Indicators**: Real-time "user is typing" UI synced instantly across both mobile and web clients.
- **Secure Authentication**: Robust user registration and login flows powered entirely by Supabase GoTrue.
- **Dynamic Room Management**: Create rooms, join via unique IDs, view live online user counts, and seamlessly manage your personal room list.
- **Message Persistence & Control**: Full message history synchronization with "Delete for Me" and "Delete for Everyone" functionality.
- **Premium Aesthetics**: Modern, responsive UI featuring glassmorphism elements, vibrant gradients, and smooth micro-animations.

## 🏗️ Technology Stack

- **Backend**: Go (Gin Gonic, Gorilla WebSockets)
- **Web Frontend**: Vanilla JavaScript, Semantic HTML5, CSS3 Custom Properties
- **Mobile App**: Flutter / Dart
- **Database/Auth**: Supabase (PostgreSQL & GoTrue)
- **Configuration**: Environment-driven via native platform secret management.

## 🛠️ Getting Started

### Prerequisites

- [Go](https://go.dev/) 1.25+
- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- A Supabase Project

### Running Locally

**Backend:**
```bash
cd server
go run main.go
```

**Mobile:**
```bash
cd app
flutter run
```

**Web:**
Simply serve the `web/` directory using any static file server or open `index.html`.

---
