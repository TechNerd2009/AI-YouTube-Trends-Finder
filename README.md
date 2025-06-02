# 🧠 AI YouTube Trends Finder 🎥

AI-powered automation workflow built with **n8n** to uncover the **latest content trends on YouTube** within any niche — powered by OpenAI's GPT-4.1 mini for blazing-fast and accurate insight generation.

## 🚀 What It Does

When a user inputs a niche (e.g., "iPhone camera reviews" or something more general like "tech"), this workflow:

1. **Scrapes YouTube** for **relevant videos from the past 2 days** using multiple dynamic search prompts.
2. **Feeds the video data** (titles, views, likes, comments, etc.) to a GPT-4.1 mini agent.
3. **Infers the niche** if the user’s input is vague or broad.
4. **Analyzes content performance trends** across the entire niche (not individual videos).
5. **Returns clear, actionable insights** about what’s trending, which content angles are performing well, and what creators are doing differently, along with specific video links.

## 🔍 Key Features

- Built in **n8n** for full visual control and easy modification
- **Agentic LLM behavior** with modular prompt logic
- **Multi-prompt YouTube scraping** for high relevance and coverage
- **Latency-optimized GPT-4.1 mini** for fast, real-time, and accurate results
- Focuses on **macro trends**, not micro stats

## 📁 File Structure

```
AI-YouTube-Trends-Finder/
├── Workflows/   # Visual screenshots of n8n workflows
├── Code/        # JSON exports of both workflows
├── Examples/    # Sample trend analyses (3 niches)
├── .gitignore
└── README.md
```

## 🧪 Try It Out

[AI YouTube Trends Finder Based on Niche](https://shopos-youtube-trends-finder.vercel.app)

## 🤖 Stack

- **n8n** – workflow automation
- **OpenAI GPT-4.1 mini** – fast and smart LLM
- **YouTube scraper (`YouTube Data API` from Google Cloud Console)** – fresh video data
- **Vercel** – frontend deployment (UI for user input)

## 📸 Previews

Check the [`Examples`](./Examples) folder to see what kind of insights you’ll get.

---

Built to help creators, marketers, and analysts stay **two steps ahead** of YouTube trends — all on autopilot.