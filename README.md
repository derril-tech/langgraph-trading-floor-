# 🚀 AI Trading Floor
**Powered by LangGraph + OpenAI**

🌐 **[View Live Application](https://langgraph-trading-floor.vercel.app)**

> **Transform market sector themes into structured, risk-aware trading idea sheets with AI-powered analysis—in seconds.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black.svg)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB.svg)](https://react.dev/)
[![LangGraph](https://img.shields.io/badge/LangGraph-AI_Agents-purple.svg)](https://langchain-ai.github.io/langgraph/)
[![Railway](https://img.shields.io/badge/Deploy-Railway-blueviolet.svg)](https://railway.app/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-black.svg)](https://vercel.com/)

---

## ✨ What It Does

AI Trading Floor is an intelligent trading idea exploration platform that uses a **multi-node LangGraph workflow** to:

1. **Fetch Sector Data** — Pull real-time market statistics from Finnhub and Alpha Vantage APIs
2. **Generate Trading Ideas** — Create structured, educational idea lists using GPT-4.1-mini
3. **Analyze Risk Scenarios** — Build comprehensive Base/Bear/Bull scenarios with probability assessments
4. **Generate Compliance Notes** — Produce context-aware compliance commentary and constraints

All in a beautiful, responsive interface with real-time progress tracking and no page reloads.

---

## 🎯 Core Features

### 🤖 **AI-Powered Analysis**
- **Real OpenAI Integration** — GPT-4.1-mini for intelligent, context-aware idea generation
- **Multi-Node Workflow** — LangGraph orchestrates 4 specialized nodes (Sector → Ideas → Risk → Compliance)
- **Live Market Data** — Finnhub and Alpha Vantage integration for real-time sector insights
- **Context-Aware Responses** — AI chat assistant understands your idea sheets and provides relevant answers

### 📊 **Rich Visualizations**
- **Real-time Progress Tracking** — Watch each LangGraph node execute with live status updates
- **Interactive Market Charts** — Recharts-powered visualizations of sector performance
- **Risk Scenario Analysis** — Base/Bear/Bull scenarios with probability bands and risk assessments
- **Idea Comparison View** — Side-by-side comparison of multiple idea sheets

### 🎨 **Modern UI/UX**
- **Single-Page Architecture** — Smooth state-driven transitions with React 19.2
- **Dark/Light Mode** — Beautiful theme system with system preference support
- **Mobile-First Design** — Responsive layout with 44px+ touch targets and safe area support
- **Micro-Animations** — Delightful interactions and smooth transitions throughout

### 📱 **Full Feature Set**

| Feature | Description |
|---------|-------------|
| 🎯 **Real-time Progress** | Live tracking of LangGraph pipeline execution |
| 💡 **AI Idea Generation** | Context-aware trading ideas based on sector data |
| ⚠️ **Risk Scenarios** | Base/Bear/Bull analysis with probabilities |
| ✅ **Compliance Notes** | Context-aware compliance commentary |
| 🔍 **Sector Suggestions** | AI-powered sector autocomplete |
| ✏️ **Interactive Editor** | Refine ideas with AI assistance |
| 💬 **AI Chat Assistant** | Context-aware Q&A about idea sheets |
| 📊 **Market Data Charts** | Real-time sector performance visualizations |
| 📥 **Export & Share** | JSON, PDF export, and shareable links |
| 🔎 **Advanced Search** | Filter by sector, risk band, and date range |
| 📋 **Comparison View** | Side-by-side idea sheet comparison |
| 🗄️ **Database Status** | Real-time connectivity monitoring |

---

## 🏗️ Tech Stack

### **Frontend** ⚛️
| Technology | Purpose |
|------------|---------|
| **Next.js 16** | React 19.2 with App Router and Server Components |
| **TypeScript** | Type-safe development with strict mode |
| **Tailwind CSS** | Utility-first styling with custom design system |
| **Radix UI** | Accessible, unstyled component primitives |
| **Recharts** | Interactive data visualizations |
| **next-themes** | Theme management with system preference |
| **react-markdown** | Markdown rendering for AI responses |

### **Backend** 🐍
| Technology | Purpose |
|------------|---------|
| **FastAPI** | High-performance async Python API |
| **LangGraph** | Multi-node AI orchestration workflow |
| **OpenAI GPT-4.1-mini** | Intelligent idea generation and analysis |
| **Pydantic v2** | Data validation and serialization |
| **Async/Await** | Non-blocking I/O for optimal performance |

### **Data & Cache** 💾
| Technology | Purpose |
|------------|---------|
| **Supabase** | PostgreSQL persistence with RPC functions |
| **Upstash Redis** | Job queue, caching, and rate limiting |

### **External APIs** 🔌
| API | Purpose |
|-----|---------|
| **Finnhub** | Real-time market sector data |
| **Alpha Vantage** | Historical market statistics |
| **OpenAI** | GPT-4.1-mini for AI features |

### **Deployment** 🚀
| Platform | Service |
|----------|---------|
| **Vercel** | Frontend hosting with edge functions |
| **Railway** | Backend API with auto-scaling |

---



---

## 📸 Key Pages

### 🏠 **Landing Page** (`/`)
*Elegant hero section with video background, clear value proposition, and seamless navigation*

### 🎮 **Playground** (`/playground`)
*Interactive workspace with real-time progress tracking, AI-powered features, and comprehensive idea sheet generation*

### 📊 **Dashboard** (`/dashboard`)
*Advanced filtering, search, comparison view, and database connectivity monitoring*

---

## 📖 User Guide

### Getting Started

1. **Enter Sector Theme** — Type a sector (e.g., "Renewable energy – EU grid storage")
2. **Adjust Settings** — Set risk tolerance and apply filters (ESG, investment grade, liquidity)
3. **Run Pipeline** — Click "Run LangGraph pipeline" and watch real-time progress
4. **Explore Results** — Review sector overview, ideas, risk scenarios, and compliance notes

### Understanding Your Results

| Section | What It Shows |
|---------|---------------|
| **Sector Overview** | Market data, performance indicators, and sector analysis |
| **Idea List** | 3-5 structured trading ideas with titles, descriptions, and risk levels |
| **Risk Scenarios** | Base/Bear/Bull scenarios with probabilities and risk band assessments |
| **Compliance Notes** | Context-aware compliance commentary and educational disclaimers |

### Pro Tips

- **Be specific** with sector themes for better analysis (e.g., "Utility-scale solar in MENA")
- **Use filters** to narrow down ideas (ESG-only, investment grade, public markets)
- **Adjust risk tolerance** to see how it affects scenario probabilities
- **Compare ideas** using the comparison view on the dashboard
- **Ask questions** using the AI chat assistant for deeper insights

---

## 🎨 Customization

### Theme Options
- ☀️ **Light Mode** — Clean, professional interface with stone grid palette
- 🌙 **Dark Mode** — Easy on the eyes with neon flow palette
- 🖥️ **System** — Follows OS preference (default: dark)

### Analysis Options
- **Sector Theme** — Any market sector or investment theme
- **Risk Tolerance** — Low, Medium, or High
- **Filters** — ESG-only, Investment grade, Public markets

---

## 📊 Performance

| Metric | Value |
|--------|-------|
| Pipeline Execution | ~15-25 seconds |
| Frontend Bundle | Optimized with Next.js 16 |
| Lighthouse Score | 90+ |
| Mobile Ready | ✅ Yes (95/100 mobile UX score) |
| API Response Time | < 1 second (cached) |

---

## 🛡️ Security

- ✅ **Schema Isolation** — Custom Supabase schema (`tradingfloor`) with RPC functions
- ✅ **API Rate Limiting** — Redis-based rate limiting (20 requests/minute)
- ✅ **CORS Protection** — Configured for production domains
- ✅ **Environment Variables** — All secrets stored securely
- ✅ **Input Sanitization** — Pydantic validation on all inputs
- ✅ **Educational Disclaimers** — Clear labeling throughout

---

## 🏗️ Architecture Highlights

### **State Management**
- React 19.2 hooks with optimized re-renders
- Real-time polling for job status updates
- Context-aware AI responses

### **Data Flow**
- Async/await throughout for optimal performance
- Redis caching for market data (60-300s TTL)
- Supabase RPC functions for secure database access

### **Error Handling**
- Graceful fallbacks if OpenAI fails
- Comprehensive error logging with traceback
- User-friendly error messages

### **Mobile Optimization**
- Safe area support for iPhone notches
- 44px+ touch targets throughout
- Responsive breakpoints (mobile-first)
- Touch feedback and animations

---

## 👨‍💻 Creator

**Derril Filemon**

This project demonstrates modern full-stack development with:

- 🤖 **AI/ML Integration** — LangGraph multi-node workflows, OpenAI GPT-4.1-mini
- ⚛️ **Modern React** — Next.js 16, React 19.2, Server Components, App Router
- 🐍 **Python Backend** — FastAPI, async/await, Pydantic v2
- 🎨 **UI/UX Design** — Responsive design, dark/light themes, mobile-first, accessibility
- ☁️ **Cloud Architecture** — Supabase, Upstash Redis, Railway, Vercel
- 🔧 **DevOps** — CI/CD, environment management, health monitoring
- 📊 **Data Visualization** — Recharts, real-time market data integration
- 🎯 **Production Ready** — Error handling, caching, rate limiting, security

---

## 🙏 Acknowledgments

- **[LangGraph](https://langchain-ai.github.io/langgraph/)** — Multi-node AI orchestration
- **[OpenAI](https://openai.com/)** — GPT-4.1-mini API
- **[Finnhub](https://finnhub.io/)** — Market data API
- **[Alpha Vantage](https://www.alphavantage.co/)** — Financial data API
- **[Supabase](https://supabase.com/)** — Database & RPC functions
- **[Upstash](https://upstash.com/)** — Redis caching
- **[Railway](https://railway.app/)** — Backend deployment
- **[Vercel](https://vercel.com/)** — Frontend hosting
- **[Radix UI](https://www.radix-ui.com/)** — Accessible components
- **[Recharts](https://recharts.org/)** — Data visualizations

---

## ⚠️ Important Disclaimer

**This tool is for educational and idea exploration purposes only. It does not constitute trading, investment, or financial advice. All ideas presented are hypothetical and should not be used for actual trading decisions. Users should consult with qualified financial advisors before making any investment decisions. No orders are executed through this platform.**

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

**⭐ Star this repo if you find it useful!**

[Live Demo](https://langgraph-trading-floor.vercel.app) 

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
