[![Python](https://img.shields.io/badge/Python-3.10+-3776AB)]
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6)]
[![StartHack](https://img.shields.io/badge/StartHack-2026-FF6F00)]
[![License](https://img.shields.io/badge/License-MIT-yellow)]

# Deviate — StartHack 2026 (Studyond Challenge)

**AI-powered thesis-matching platform** built in 48 hours at StartHack 2026 for the Studyond AG challenge — connecting students with professors by analysing research interests, publication history, and thesis topics through conversational AI.

## The Problem

Finding a thesis supervisor is broken:
- Students spend weeks emailing professors blindly
- Professors are buried in generic requests that don't match their research
- No structured way to match student interests with available topics
- Current platforms are static directories, not recommendation engines

## Our Solution

Deviate replaces the directory with a **conversational matching engine**:

```
Student → AI chat (explores interests, skills, career goals)
              ↓
    Profile enrichment (extracts NLP keywords, research vectors)
              ↓
    Professor matching (publication similarity + topic availability)
              ↓
    Warm introduction (generates personalised outreach draft)
```

## What we built

| Feature | Status | Tech |
|---------|--------|------|
| Conversational interest profiler | ✅ | GPT-4o + LangChain |
| Professor publication crawler | ✅ | Semantic Scholar API |
| Research vector similarity | ✅ | Sentence-BERT embeddings |
| Thesis topic recommender | ✅ | Hybrid CF + content-based |
| Personalised email drafter | ✅ | Few-shot GPT |
| Matching dashboard | ✅ | React + Tailwind |

## Stack

| Layer | Tech |
|-------|------|
| Frontend | React 19 + TypeScript + Vite + Tailwind CSS |
| Backend | Python 3.10+ (FastAPI) |
| AI | GPT-4o, LangChain, Sentence-BERT |
| Data | Semantic Scholar API, PostgreSQL |
| Deployment | Docker + Cloudflare Pages (frontend) |

## Team

Built by **Team Deviate** at [StartHack 2026](https://starthack.ch) — 48 hours from idea to working demo.

## License

MIT — built for hackathon judging. Feel free to fork and evolve.
