<div align="center">

```
███████╗ ██████╗ ██╗   ██╗██╗██╗     ██╗██████╗ ██████╗  █████╗
██╔════╝██╔═══██╗██║   ██║██║██║     ██║██╔══██╗██╔══██╗██╔══██╗
█████╗  ██║   ██║██║   ██║██║██║     ██║██████╔╝██████╔╝███████║
██╔══╝  ██║▄▄ ██║██║   ██║██║██║     ██║██╔══██╗██╔══██╗██╔══██║
███████╗╚██████╔╝╚██████╔╝██║███████╗██║██████╔╝██║  ██║██║  ██║
╚══════╝ ╚══▀▀═╝  ╚═════╝ ╚═╝╚══════╝╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝
```

**Stabilizing the triangle of student life.**

[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Alpha-orange.svg)]()
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-blue.svg)](CONTRIBUTING.md)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red.svg)]()

[💬 Discord](https://discord.gg/equilibra) · [🐛 Report a Bug](https://github.com/equilibra-oss/equilibra/issues)

</div>

---

## 🔺 The Problem

Student life rests on a **fragile triangle**:

```
          🎓 Academic Performance
                    /\
                   /  \
                  /    \
                 /      \
                /________\
    💪 Physical          🧠 Mental
       Health              Balance
```

Neglect just one corner — and the whole triangle collapses.  
Most students navigate this alone, without tools to find balance.

**Equilibra changes that.**

---

## 🌟 Vision

> *"A thriving student isn't the one who sacrifices sleep for grades, nor the one who forgets their studies to take care of themselves. It's the one who holds all three corners at once."*

Equilibra is an open source platform built **by students, for students** — to monitor, understand, and improve the three pillars of student life in a truly holistic way.

---

## ✨ Features

### 🎓 Academic Performance
- Track grades, deadlines, and upcoming exams
- Manage study time allocation per subject
- Visualize semester-long academic progression
- Cognitive overload alerts before it's too late

### 💪 Physical Health
- Activity and sleep journal
- Active break reminders between study sessions
- Hydration and meal logging
- Wearable integrations (Fitbit, Apple Health, Google Fit)

### 🧠 Mental Balance
- Daily well-being journal (mood tracking)
- Stress management techniques (breathing exercises, mindfulness)
- Weekly global balance score
- Predictive burnout early-warning alerts

### 📊 Unified Dashboard
- Interactive triangular balance view
- Cross-pillar correlations and insights
- Personalized recommendations driven by your data
- Weekly and monthly report exports

---

## 🚀 Getting Started

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
git
```

### Installation

```bash
# Clone the repository
git clone https://github.com/equilibra-oss/equilibra.git
cd equilibra

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Start development server
npm run dev
```

The app will be available at `http://localhost:3000` 🎉

### With Docker

```bash
docker compose up --build
```

---

## 🏗️ Architecture

```
equilibra/
├── apps/
│   ├── web/              # Frontend (Next.js)
│   └── mobile/           # Mobile app (React Native)
├── packages/
│   ├── core/             # Shared business logic
│   ├── ui/               # Shared UI components
│   └── api/              # Typed API client
├── services/
│   ├── gateway/          # API Gateway (Express)
│   ├── academic/         # Academic microservice
│   ├── health/           # Physical health microservice
│   └── mental/           # Mental well-being microservice
├── infra/                # Docker & CI/CD configuration
└── docs/                 # Documentation
```

### Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | Next.js 14, TypeScript, Tailwind CSS, Recharts |
| **Mobile** | React Native, Expo |
| **Backend** | Node.js, Express, Prisma ORM |
| **Database** | PostgreSQL + Redis |
| **Auth** | NextAuth.js / OAuth2 |
| **CI/CD** | GitHub Actions |
| **Testing** | Vitest, Playwright |

---

## 🤝 Contributing

Equilibra lives through its community. All contributions are welcome!

### How to Contribute

1. **Fork** the repository
2. **Create** a branch (`git checkout -b feature/my-feature`)
3. **Commit** your changes (`git commit -m 'feat: add my feature'`)
4. **Push** the branch (`git push origin feature/my-feature`)
5. **Open** a Pull Request

### Commit Conventions

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
feat:     new feature
fix:      bug fix
docs:     documentation only
style:    formatting, no logic change
refactor: code refactoring
test:     adding or fixing tests
chore:    maintenance, configuration
```

### Areas Where You Can Help

- 🐛 **Report bugs** via [Issues](https://github.com/equilibra-oss/equilibra/issues)
- 💡 **Suggest ideas** via [Discussions](https://github.com/equilibra-oss/equilibra/discussions)
- 🌍 **Translations** (FR → EN → AR → ES → ...)
- 🎨 **UI/UX Design**
- 📖 **Documentation**
- 🧪 **Testing**

Read the [Contributing Guide](CONTRIBUTING.md) for more details.

---

## 🗺️ Roadmap

### v0.1 — MVP *(in progress)*
- [x] Base project architecture
- [x] Student authentication
- [ ] Interactive triangular dashboard
- [ ] Basic academic tracking module
- [ ] Well-being journal

### v0.2 — Health & Physical
- [ ] Sleep and activity tracking
- [ ] Wearable integrations
- [ ] Personalized recommendations

### v0.3 — Intelligence & Social
- [ ] Predictive burnout alerts
- [ ] Group mode / collaborative study
- [ ] Public API for third-party integrations

### v1.0 — Stable 🎯
- [ ] Mobile app (iOS & Android)
- [ ] University platform integrations (LMS, ENT)
- [ ] Offline mode

---

## 🌍 Internationalization

Equilibra is built to be global. Current language support:

| Language | Status |
|---|---|
| 🇫🇷 French | ✅ Available |
| 🇸🇦 Arabic |  ✅  Available |
| 🇬🇧 English | ✅ Available |
| 🇸🇦 Arabic | 🚧 In progress |
| 🇪🇸 Spanish | 🔜 Planned |
| 🇧🇷 Portuguese | 🔜 Planned |

Want to add your language? Check out the [i18n guide](docs/i18n.md).

---

## 📄 License

Distributed under the **MIT License**. See [LICENSE](LICENSE) for more information.

---

## 💬 Community

| Channel | Link |
|---|---|
| 💬 Discord | [Join the server](https://discord.gg/equilibra) |
| 📖 Documentation | []() |

---

## 🙏 Acknowledgements

Thank you to every student who shared their story and made this project possible.  
A project born in libraries, cafeterias, and university dorms around the world.

---

<div align="center">

**⭐ If Equilibra helps you, drop a star — it genuinely matters. ⭐**

*Made with 💚 by the Equilibra community*

</div>
