# 🌍 Angaza – Kenya’s 360° News Platform

**Angaza** is an innovative, behavior-based news platform that transforms how people discover, compare, and engage with stories. It provides a personalized and immersive news experience using a 360° comparison model, highlighting tone, bias, and facts from multiple sources.  

> _"Not just another headline—your full story."_

---

## 🚀 Project Goal

To create an inclusive, adaptive, and behavior-driven news platform that empowers Kenyans with diverse perspectives and encourages active civic engagement.

---

## 🎯 Objectives

- Deliver a **360° comparison** of national and global stories from multiple sources.
- Customize content based on **user behavior** (not demographics).
- Promote **generational and community-based dialogue** through topic-based commentary.
- Support **underrepresented voices** and local creators.
- Provide **interactive data visualizations** to make complex topics easier to understand.
- Ensure **accessibility** and **language inclusivity** (English & Swahili).
- Offer **monetization tools** for businesses and creators.
- Present **live actionable insights** to media, NGOs, and policymakers.

---

---

## 🔐 Accessibility Features

- High Contrast Mode
- Large Text Toggle
- Reduce Motion Option
- Screen Reader Compatibility
- Swahili ↔ English Language Toggle

---

## 🧩 Key Features

- 🌀 **360° Story View** – Side-by-side comparison from multiple sources
- 🧠 **Behavior-Based Feed** – Adapts to user interactions, not demographics
- 🎭 **Mood Lens** – Choose Quick Catch-Up, Deep Dive, or Balanced View
- 📈 **Data Visualizations** – Interactive charts and maps for complex topics
- 🗣 **Topic-Based Commentary by Age** – Dialogue by generation
- 📍 **Hidden Voices** – Spotlight on underrepresented communities
- 💬 **Community Hub** – Events, forums, and creator engagement
- 💼 **Sponsorships & Monetization** – Business integration & creator earnings
- 📊 **Insights-as-a-Service** – Data dashboards for policy and media partners

---

angaza-news-platform/
│
├── public/                         # Static files (favicon, manifest, robots.txt, index.html)
│   └── assets/                     # Images, icons, logos
│
├── src/
│   ├── components/                 # Reusable React components
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   ├── MoodLensSelector.jsx
│   │   ├── StoryCard.jsx
│   │   ├── LangToggle.jsx
│   │   └── AccessibilityToggle.jsx
│   │
│   ├── features/                   # Feature modules
│   │   ├── Feed/                   # Personalized news feed
│   │   │   └── FeedPage.jsx
│   │   ├── Story360/               # 360° Story Comparison
│   │   │   └── StoryCompare.jsx
│   │   ├── Community/              # Community Hub
│   │   │   └── CommunityHub.jsx
│   │   ├── Visuals/                # Data visualizations
│   │   │   └── VisualGallery.jsx
│   │   └── Saved/                  # Saved news
│   │       └── SavedStories.jsx
│   │
│   ├── ai/                         # AI logic and services
│   │   ├── summarizer.js          # Story summarization logic
│   │   ├── sentimentAnalyzer.js   # Tone/bias detection
│   │   ├── translator.js          # Swahili ↔ English toggle (NMT API)
│   │   └── recommender.js         # Behavior-based news feed logic
│   │
│   ├── context/                   # Global state/context providers
│   │   ├── AuthContext.jsx
│   │   ├── LangContext.jsx
│   │   └── ThemeContext.jsx
│   │
│   ├── hooks/                     # Custom React hooks
│   │   └── useUserBehavior.js
│   │
│   ├── pages/                     # Route pages
│   │   ├── Home.jsx
│   │   ├── Explore.jsx
│   │   ├── About.jsx
│   │   ├── Saved.jsx
│   │   └── Community.jsx
│   │
│   ├── styles/                    # Tailwind or CSS files
│   │   └── main.css
│   │
│   ├── App.jsx                    # Root component
│   └── main.jsx                   # React DOM render
│
├── .env                           # Environment variables (API keys, endpoints)
├── .gitignore
├── tailwind.config.js
├── vite.config.js                 # Vite config
├── package.json
└── README.md                      # Project documentation



Here’s a clean and scalable **project structure** for **Angaza**, based on your tech stack and AI-powered architecture.

---

## 🗂️ Project Structure: `angaza-news-platform/`

```bash
angaza-news-platform/
│
├── public/                         # Static files (favicon, manifest, robots.txt, index.html)
│   └── assets/                     # Images, icons, logos
│
├── src/
│   ├── components/                 # Reusable React components
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   ├── MoodLensSelector.jsx
│   │   ├── StoryCard.jsx
│   │   ├── LangToggle.jsx
│   │   └── AccessibilityToggle.jsx
│   │
│   ├── features/                   # Feature modules
│   │   ├── Feed/                   # Personalized news feed
│   │   │   └── FeedPage.jsx
│   │   ├── Story360/               # 360° Story Comparison
│   │   │   └── StoryCompare.jsx
│   │   ├── Community/              # Community Hub
│   │   │   └── CommunityHub.jsx
│   │   ├── Visuals/                # Data visualizations
│   │   │   └── VisualGallery.jsx
│   │   └── Saved/                  # Saved news
│   │       └── SavedStories.jsx
│   │
│   ├── ai/                         # AI logic and services
│   │   ├── summarizer.js          # Story summarization logic
│   │   ├── sentimentAnalyzer.js   # Tone/bias detection
│   │   ├── translator.js          # Swahili ↔ English toggle (NMT API)
│   │   └── recommender.js         # Behavior-based news feed logic
│   │
│   ├── context/                   # Global state/context providers
│   │   ├── AuthContext.jsx
│   │   ├── LangContext.jsx
│   │   └── ThemeContext.jsx
│   │
│   ├── hooks/                     # Custom React hooks
│   │   └── useUserBehavior.js
│   │
│   ├── pages/                     # Route pages
│   │   ├── Home.jsx
│   │   ├── Explore.jsx
│   │   ├── About.jsx
│   │   ├── Saved.jsx
│   │   └── Community.jsx
│   │
│   ├── styles/                    # Tailwind or CSS files
│   │   └── main.css
│   │
│   ├── App.jsx                    # Root component
│   └── main.jsx                   # React DOM render
│
├── .env                           # Environment variables (API keys, endpoints)
├── .gitignore
├── tailwind.config.js
├── vite.config.js                 # Vite config
├── package.json
└── README.md                      # Project documentation
```

---

## ⚙️ Tech Stack Reference

| Layer                  | Stack / Tool                     | Purpose                                              |
| ---------------------- | -------------------------------- | ---------------------------------------------------- |
| **Frontend**           | React.js + Vite + Tailwind CSS   | UI Framework, fast dev build, and styling            |
| **State Mgmt**         | React Context / Redux (optional) | Global state for themes, auth, language              |
| **AI Services**        | OpenAI / HuggingFace APIs        | Summarization, translation, tone/bias detection      |
| **Data Viz**           | Recharts / D3.js / Chart.js      | For interactive charts, election maps, story visuals |
| **Accessibility**      | WAI-ARIA, ScreenReader support   | High contrast, large text, reduced motion toggles    |
| **Translation**        | Google Translate API / MarianMT  | Swahili–English language toggle                      |
| **Backend (optional)** | Node.js + Express / Firebase     | For saved stories, events, and analytics             |
| **Auth**               | Firebase Auth / Clerk / Supabase | User login/session mgmt (if required)                |
| **Hosting**            | Vercel / Netlify                 | Frontend deployment                                  |

---






