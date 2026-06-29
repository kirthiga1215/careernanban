# 🚀 Career Nanban

**Guiding you today, empowering you tomorrow.**

Career Nanban is an AI-powered career guidance platform built with React + TypeScript. It helps students and professionals navigate their career journey through personalized roadmaps, gamified learning levels, mock interviews, and real placement preparation — all in one platform.

## ✨ Features

### 🎯 AI-Powered Career Platform
- **AI Roadmap Creator** — Tell us your goal and experience. Get a complete learning path in seconds.
- **Gamified Levels** — Learn through structured levels. Earn XP and credits on every completion.
- **Daily Tasks** — Wake up to a focused daily task list. Never wonder what to study next.

### 🛠️ Core Tools
- **AI Chatbot** — Ask anything career-related. Get instant answers, resources, and guidance.
- **Mock Interview** — Practice real interview questions with AI feedback. Be ready before day one.
- **Leaderboard** — Compete with peers, climb rankings, stay motivated.
- **Achievements** — Unlock badges and milestones as you progress.

### 👤 User Experience
- **Splash Animation** — Engaging animated intro screen
- **Onboarding Flow** — Guided setup for new users
- **Login / Signup** — Authentication with local storage persistence
- **Dashboard** — Personalized progress overview
- **Responsive Design** — Works seamlessly on desktop and mobile

## 🖥️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **React 18** | UI framework |
| **TypeScript** | Type safety & developer experience |
| **Vite 6** | Fast build tool & dev server |
| **Tailwind CSS 4** | Utility-first styling |
| **shadcn/ui** | Reusable component library (Radix UI primitives) |
| **MUI** | Material UI components & icons |
| **Motion** | Framer Motion animations |
| **React Router** | Client-side routing |
| **Recharts** | Data visualization & charts |
| **Lucide React** | Icon library |

## 📁 Project Structure

```
src/
├── app/
│   ├── App.tsx                    # Root app component
│   ├── routes.tsx                 # Route definitions
│   ├── components/
│   │   ├── Splash.tsx             # Animated intro screen
│   │   ├── Landing.tsx            # Marketing landing page
│   │   ├── MarketingLayout.tsx    # Public layout with nav/footer
│   │   ├── AppLayout.tsx          # Authenticated app layout
│   │   ├── Dashboard.tsx          # User dashboard
│   │   ├── Roadmap.tsx            # Career roadmap
│   │   ├── Level.tsx              # Learning levels
│   │   ├── Interview.tsx          # Mock interview
│   │   ├── Chatbot.tsx            # AI chatbot
│   │   ├── Leaderboard.tsx        # Leaderboard
│   │   ├── Achievements.tsx       # Badges & achievements
│   │   ├── Onboarding.tsx         # User onboarding
│   │   ├── Login.tsx              # Login page
│   │   └── ui/                    # shadcn/ui components
│   └── utils/
│       ├── AuthContext.tsx         # Authentication context
│       └── ProtectedRoute.tsx     # Route guard
├── styles/
│   ├── index.css                  # Main styles entry
│   ├── tailwind.css               # Tailwind imports
│   ├── theme.css                  # Design tokens
│   └── fonts.css                  # Google Fonts
├── imports/
│   └── pasted_text/               # Project documentation
└── main.tsx                       # Entry point
```

## 🚀 Getting Started

### Prerequisites
- **Node.js** >= 18
- **npm** or **pnpm**

### Installation

```bash
# Clone the repository
git clone https://github.com/kirthiga1215/careernanban.git
cd careernanban

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will be available at **https://ai-learning-platform-amber-beta.vercel.app**.

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.

## 🌐 Live Demo

Visit the live site at: **https://ai-learning-platform-amber-beta.vercel.app**

## 🎨 Design

The platform features a dark theme with:
- **Primary colors:** Deep navy (`#0A0F2C`), Gold (`#F5A623`), Cyan (`#00A8CC`)
- **Typography:** Poppins (headings), Inter (body), Space Grotesk (accents)
- **Animations:** Spring transitions, scroll-based reveals, floating elements

## 📸 Screenshots

> *Coming soon*

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is for educational purposes.

## 🙏 Acknowledgments

- Built with ❤️ for students and career seekers
- Inspired by the need for accessible career guidance
- Powered by modern web technologies

---

**Career Nanban** — *Guiding you today, empowering you tomorrow.*
