# OzMetrics OS

AI-powered operating system for Ozon sellers, combining analytics, automation, content management, pricing intelligence, SEO optimization, advertising analytics, inventory control, and AI-driven business growth tools in a single platform.

---

## 🚀 Overview

OzMetrics OS is a comprehensive marketplace intelligence platform designed specifically for Ozon sellers.

The platform centralizes product analytics, advertising performance, profitability tracking, content optimization, competitor monitoring, inventory management, and AI-powered decision-making into one unified workspace.

Built to reduce operational complexity and help sellers scale faster through automation and actionable insights.

---

## ✨ Core Features

### 📈 Marketing Intelligence

- CTR AI Studio 2.0
- SEO Intelligence
- Competitor Intelligence
- Product Growth Center
- Card Optimizer
- Creative Generator
- AI Infographic Generator

### 📊 Analytics & Reporting

- Ozon Intelligence Dashboard
- Internal Analytics
- Advertising Performance Analytics
- Financial Performance Monitoring
- Inventory & Excess Stock Analysis
- Profitability Tracking
- Margin Protection System

### ⚙️ Automation

- Ozon API Synchronization
- Ozon Performance API Integration
- Auto Repricing Engine
- Review Response Automation
- Content Synchronization
- Data Collection & Processing Pipelines

### 🤖 Artificial Intelligence

- Google Gemini Integration
- OpenAI ChatGPT Integration
- CTR Optimization Analysis
- SEO Recommendations
- Product Card Auditing
- Content Generation
- Marketing Strategy Assistance

---

## 🏗 Architecture

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS

### Backend

- Next.js API Routes
- SQLite Database
- REST API Services

### Integrations

- Ozon Seller API
- Ozon Performance API
- OpenAI API
- Google Gemini API

---

## 🎯 Why OzMetrics

Most marketplace sellers rely on multiple disconnected services for:

- Analytics
- Pricing
- SEO
- Advertising
- Inventory Management
- Content Optimization

OzMetrics OS consolidates these workflows into a single AI-powered operating system focused on marketplace growth, profitability, and operational efficiency.

---

## 📸 Screenshots

### Dashboard

![Dashboard](docs/screenshots/dashboard.png)

### CTR AI Studio

![CTR Studio](docs/screenshots/ctr-studio.png)

### Content Manager

![Content Manager](docs/screenshots/content-manager.png)

### Advertising Analytics

![Advertising](docs/screenshots/advertising.png)

---

## 🛠 Installation

Clone repository:

```bash
git clone https://github.com/Bekmanov/ozmetrics.git
cd ozmetrics
```

Install dependencies:

```bash
npm install
```

Create environment file:

```bash
cp .env.example .env.local
```

Configure environment variables:

```env
# Ozon Seller API
OZON_CLIENT_ID=
OZON_API_KEY=

# Ozon Performance API
OZON_PERFORMANCE_CLIENT_ID=
OZON_PERFORMANCE_CLIENT_SECRET=

# AI Providers
OPENAI_API_KEY=
GEMINI_API_KEY=
```

Run development server:

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

## 🔑 Environment Variables

| Variable | Description |
|-----------|-------------|
| OZON_CLIENT_ID | Ozon Seller Client ID |
| OZON_API_KEY | Ozon Seller API Key |
| OZON_PERFORMANCE_CLIENT_ID | Performance API Client ID |
| OZON_PERFORMANCE_CLIENT_SECRET | Performance API Secret |
| OPENAI_API_KEY | OpenAI API Key |
| GEMINI_API_KEY | Google Gemini API Key |

---

## 🗺 Roadmap

### Completed

- ✅ Ozon Seller API Integration
- ✅ Ozon Performance API Integration
- ✅ CTR AI Studio
- ✅ SEO Intelligence
- ✅ Content Manager
- ✅ Product Analytics
- ✅ Gemini Integration
- ✅ OpenAI Integration

### In Progress

- 🚧 Full Product Content Synchronization
- 🚧 Advanced Competitor Intelligence
- 🚧 Multi-Currency Cost Management
- 🚧 Marketplace Automation Engine

### Planned

- 📌 Multi-Account Support
- 📌 AI Agent Workflows
- 📌 Wildberries Advanced Analytics
- 📌 Marketplace Expansion Toolkit
- 📌 Automated Growth Recommendations

---

## 🔒 Security

Never commit:

- `.env`
- `.env.local`
- API Keys
- Access Tokens
- SQLite Databases
- Backup Archives
- Credentials
- Personal Data

All sensitive information must be stored in environment variables.

Recommended `.gitignore`:

```gitignore
node_modules/
.next/
dist/

.env
.env.local
.env.production

*.db
*.sqlite
*.sqlite3

backups/
logs/
coverage/
```

---

## 🤝 Contributing

Contributions, feature requests, bug reports, and pull requests are welcome.

Please open an issue before submitting major changes.

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Ruslan Bekmanov

GitHub:
https://github.com/Bekmanov

---

## ⭐ Support

If you find this project useful, please consider giving it a star on GitHub.

It helps support ongoing development and future marketplace automation features.

---

**OzMetrics OS — AI-Powered Marketplace Intelligence Platform**
