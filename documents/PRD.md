# 📘 InfoBoard - Product Requirements Document (PRD)

## 📌 Overview

**InfoBoard** is an intelligent information aggregation and summarization platform. Users set a **custom topic** (e.g., "LLM Agents in AI Customer Support"), and InfoBoard automatically pulls relevant content from diverse sources, organizes it into **Info Cards**, and helps users consume, filter, and transform the information into **Daily Reports** using AI-powered summarization and deep analysis.

---

## 🎯 Goals

- Help users **stay up-to-date** on niche or rapidly evolving topics.
- Provide **structured, personalized** information cards from diverse sources.
- Enable AI-powered **sorting, filtering, and deep summarization**.
- Generate **concise Daily Reports** based on user preferences or AI judgment.

---

## 👤 Target Users

- AI researchers & engineers
- Tech executives & product managers
- Students tracking niche domains
- Content curators & trend analysts

---

## 🔍 Use Cases

- A product manager wants a daily digest of “GenAI in e-commerce customer support.”
- A student is researching the evolution of “open-source LLM agents.”
- A founder wants to track “venture funding in autonomous AI agents.”

---

## 🧱 Core Features

### 1. **Topic Configuration**

- User can create/edit/delete a **custom topic**.
- Topics consist of:
    - Title (e.g., “AI Agents in Customer Support”)
    - Keywords / queries (optional)
    - Preferred sources (optional)

### 2. **Info Card Aggregation**

- Fetch relevant content from:
    - News sites
    - ArXiv/preprint archives
    - GitHub/commits
    - Hacker News, Reddit, X (Twitter)
- Each Info Card contains:
    - Title, Source, Snippet/Abstract
    - Link, Timestamp, Tags
    - Optional AI summary

### 3. **Info Sorting & Filtering**

- Sort cards by:
    - Recency
    - Relevance (AI-ranked)
    - Popularity (social engagement)
- Filter by:
    - Source type (news, papers, code, etc.)
    - Author
    - Confidence level (AI-detected)

### 4. **User Feedback Loop**

- User can:
    - Like / Save / Dismiss Cards
    - Comment or annotate
- AI uses feedback to improve:
    - Ranking
    - Card generation
    - Report focus

### 5. **Deep Research Engine**

- Selected or AI-picked cards undergo:
    - Entity extraction
    - Trend detection
    - Cross-source synthesis
- Outputs a **Daily Report**, including:
    - Executive summary
    - Key highlights
    - AI insights or predictions

### 6. **Delivery & Notifications**

- Reports can be delivered:
    - In-app
    - As email digest
    - As downloadable PDF
- User can set delivery frequency (daily/weekly)

---

## 🧠 AI Capabilities

- **Semantic Search**: Understanding topic intent & expanding search scope.
- **Summarization**: Abstractive and extractive summarization of long content.
- **Ranking**: Relevance prediction based on user history and community signal.
- **Synthesis**: Cross-document summarization and trend identification.

---

## 🛠 Tech Stack (Suggested)

- **Frontend**: React / Next.js + Tailwind
- **Backend**: Python (FastAPI)
- **AI Models**: GPT-4.5 / o4-mini for summarization & entity extraction
- **DB**: PostgreSQL + Redis (for real-time interaction)
- **Sources**: News API, Arxiv API, GitHub, Reddit API, X API, RSS feeds
- **Cloud**: AWS or Vercel (frontend), Supabase (optional)

---

## 📈 Metrics of Success

- Daily Active Users (DAU)
- Engagement per Topic (avg cards liked/saved)
- Daily Report Open Rate
- Avg. Time to Insight (how fast a user reaches a useful report)
- Model ranking accuracy (measured via user feedback)

---

## ⏱ MVP Scope

- Topic creation
- News + Arxiv integration
- Info Card UI
- Basic AI summarization
- Manual Daily Report generation
- Like/save feedback loop

---

## 🗺️ Future Features

- Multi-modal cards (video, podcast summaries)
- Team collaboration on reports
- Conversational interface for topic setup
- Custom “agent-style” reporters per topic
- Personal knowledge graph based on reading history