---
name: yt-keyword-research
description: Generate a full YouTube keyword research report for a given video topic in the B2B marketing, lead generation, cold outreach, AI automation, and client acquisition niche. Use this skill when the user wants to (1) find primary and secondary keywords for a video, (2) identify long-tail keywords with lower competition, (3) build a keyword list for a video title/description/tags, (4) understand search intent behind a keyword, or (5) find related keyword clusters for a content series. Note: all keyword logic is based on training knowledge — no live search volume data.
---

# YouTube Keyword Research

Generate a structured keyword research report for a YouTube video topic using search intent logic, audience language patterns, and keyword clustering — without live volume data.

## Channel Context

**Niche:** B2B marketing, lead generation, AI automation for lead gen, cold outreach, client acquisition, offer creation

**Target Audience:**
- Cold outreach practitioners (beginners to intermediate)
- B2B agency owners (0–2 years)
- SaaS founders struggling with acquisition

## Keyword Research Framework

### Layer 1: Primary Keyword

The single most direct keyword a viewer would type to find this video.

Rules:
- 2–5 words
- Describes exactly what the video teaches
- Matches how the audience actually speaks (not industry jargon)
- Example: "cold email tutorial" not "asynchronous B2B prospecting methodology"

### Layer 2: Secondary Keywords

5–8 keywords that are closely related to the primary keyword.

Types:
- Synonym variations ("cold outreach" / "cold prospecting" / "cold email strategy")
- Problem-framing variations ("why cold emails don't get replies")
- Audience-specific variations ("cold email for agency owners")
- Tool-specific variations ("cold email with Instantly" / "cold email automation")

### Layer 3: Long-Tail Keywords

8–12 longer, more specific phrases (5+ words) with lower competition.

Logic: Long-tail keywords have lower competition but higher intent. Beginners searching for very specific answers are more likely to convert to subscribers.

Examples:
- "how to write cold emails that get replies 2024"
- "cold email sequence for B2B agency owners"
- "cold outreach system for getting first clients"

### Layer 4: LSI Keywords (Latent Semantic Index)

6–10 conceptually related terms that reinforce the topic's meaning for the algorithm.

Purpose: YouTube's algorithm reads your description and transcript. LSI keywords signal that your content is deeply relevant to the topic area — not just stuffed with one phrase.

Examples for "cold email":
- email deliverability, open rates, reply rates, personalization, subject lines, prospect list, lead list building, email warm-up, outreach sequences, follow-up emails

### Layer 5: Question-Based Keywords

5–7 questions people type directly into YouTube search.

Format: "how to", "why does", "what is", "best way to", "should I"

Examples:
- "how to write a cold email that gets a response"
- "why is my cold email open rate low"
- "what is the best cold email tool for beginners"
- "should I use cold email or LinkedIn for B2B outreach"

## Keyword Placement Guide

After generating keywords, map each to placement locations:

| Placement | What Goes Here |
|-----------|---------------|
| Video Title | Primary keyword + 1 secondary keyword (power combo) |
| First 2 Lines of Description | Primary keyword + 2–3 secondary keywords used naturally |
| Description Body | Long-tail keywords woven into natural sentences |
| Tags | All layers — primary, secondary, long-tail, LSI, questions |
| Chapters/Timestamps | Question-based keywords as chapter titles |
| Spoken in Video | Primary + secondary keywords mentioned naturally in first 60 seconds |

## Competition Difficulty Assessment

Without live data, assess competition difficulty using logic:

**Low Competition Signals:**
- Keyword is very specific (5+ words)
- Keyword targets a sub-niche (B2B agency, cold outreach for SaaS)
- Keyword includes a constraint (budget, time, tool-specific)

**Medium Competition Signals:**
- Keyword is 3–4 words
- Broad but niche-specific ("cold email tutorial")
- Tool-based without specifics ("n8n tutorial")

**High Competition Signals:**
- 1–2 word keywords ("lead generation", "cold email")
- Generic how-to with no specifics ("how to get clients")
- Keywords dominated by established channels (Hubspot, Neil Patel, Alex Hormozi)

**Strategy:** Target 1 medium competition primary keyword + primarily long-tail secondary keywords for new channels.

## Output Format

```
KEYWORD RESEARCH REPORT
Video Topic: [topic]
Primary Audience: [segment]

---

PRIMARY KEYWORD
[keyword]
Intent: [what the viewer wants when they type this]
Competition: [Low / Medium / High] — [1 line reason]

---

SECONDARY KEYWORDS (5–8)
1. [keyword] — [intent note]
2. [keyword] — [intent note]
3. [keyword] — [intent note]
4. [keyword] — [intent note]
5. [keyword] — [intent note]

---

LONG-TAIL KEYWORDS (8–12)
1. [keyword]
2. [keyword]
3. [keyword]
[etc.]

---

LSI KEYWORDS (6–10)
[comma-separated list]

---

QUESTION-BASED KEYWORDS (5–7)
1. [question]
2. [question]
[etc.]

---

PLACEMENT MAP
Title: [primary keyword] + [recommended secondary keyword]
Description opening: [2–3 keywords to use naturally in first 2 lines]
Tags list: [full list of all keywords ready to paste]
Chapter titles: [question-based keywords formatted as timestamps]

---

KEYWORD STRATEGY NOTE
[2–3 sentences on the competitive landscape for this topic and which keywords to prioritize for a new channel]
```

## Quality Rules

Before outputting:
- ✓ Primary keyword matches how the audience actually speaks
- ✓ Long-tail keywords are specific enough to have real search intent
- ✓ No keyword is repeated across layers
- ✓ Tags list is ready to paste directly into YouTube
- ✓ Competition assessment is honest — don't overestimate rankability
- ✓ Question-based keywords sound like real search queries, not formal questions
