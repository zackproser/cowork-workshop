# Claude Cowork GTM Workshop

![Claude Cowork GTM Workshop at WorkOS SF](https://zackproser.b-cdn.net/images/claude-cowork-gtm-luma-header.webp)

**Build a complete go-to-market pipeline in one Claude Cowork session.**

Hands-on workshop materials from the live session at WorkOS San Francisco (February 26, 2026). 800 people registered — 150 got in. Followed by a Q&A with Lydia from Anthropic's Claude Code team.

📝 **[Full workshop recap and video →](https://zackproser.com/blog/claude-cowork-workshop-anthropic)**

## What We Built

In one hour, in a single Cowork chat session, we built a complete GTM pipeline from scratch:

| Module | What It Does | Time |
|--------|-------------|------|
| **ICP Identification** | Scraped 33 speakers from AI Engineer Europe, enriched with company data, industry, and key contacts | ~8 min |
| **Competitive Intelligence** | Gathered real user complaints from G2, Capterra, Reddit, and dev forums into a structured battlecard | ~7 min |
| **Positioning Analysis** | Read the WorkOS website and mapped product strengths against competitor vulnerabilities | ~5 min |
| **Personalized Cold Emails** | Generated individualized outreach for each prospect using accumulated context | ~5 min |
| **Blog Content** | Drafted SEO-aware content targeting ICP pain points using the marketing plugin | ~8 min |
| **Content Calendar** | Produced a 4-week publishing plan based on all gathered intelligence | ~3 min |
| **Scheduled Tasks** | Set up automated content production — Cowork writes the next blog post every Monday at 9 AM | ~2 min |

**Key insight:** Keeping everything in one session means each step builds on the context from all previous steps. The cold emails are good because Cowork already has the competitive intel, the positioning, and the prospect data.

## What's in This Repo

- `cowork-workshop-slides.pptx` — Full slide deck from the live presentation

## The Slides

The slides were built with Claude's help and [Nano Banana](https://ai.google.dev/) (Gemini's image generation API) for custom visuals. The same AI tools we demoed in the workshop were used to create the workshop itself.

## Tools Used

- **[Claude Cowork](https://claude.ai)** — Agentic AI for multi-step workflows. Built on the same Agent SDK as Claude Code.
- **[WisprFlow](https://wisprflow.com)** — Voice dictation at 179 WPM. Every prompt in the workshop was spoken, not typed.
- **[Granola](https://granola.ai)** — AI meeting notes without a bot. Used in the call summary plugin demo.

## Running It Yourself

1. Open [Claude Cowork](https://claude.ai) (requires Claude Pro or Team)
2. Create a new chat and a working directory for the outputs
3. Follow the modules above in order — each one builds on the previous context
4. Install the **marketing plugin** from the Cowork plugin marketplace before Module 5

The prompts are conversational. Describe what you want in plain English. The magic is in keeping everything in one session so context accumulates.

## About

Created and delivered by [Zack Proser](https://zackproser.com) (Applied AI, WorkOS). Q&A with Lydia Hallie (Claude Code team, Anthropic).

![Workshop Q&A with Lydia from Anthropic](https://zackproser.b-cdn.net/images/workshop-qa-lydia-zack-v2.webp)
