---
name: yt-topic-ideation
description: Generate high-potential YouTube video topic ideas for B2B marketing, lead generation, cold outreach, AI automation, and client acquisition channels. Use this skill when the user wants to (1) brainstorm video ideas from scratch, (2) validate a rough topic idea, (3) find content angles that target beginners and struggling agency owners, (4) identify content gaps in a niche, or (5) build a batch of topic ideas for a content calendar.
---

# YouTube Topic Ideation

Generate validated YouTube video topic ideas optimized for B2B marketing, lead generation, AI automation, cold outreach, and client acquisition niches — using search intent logic and audience psychology, not live data.

## Channel Context

**Niche:** B2B marketing, lead generation, AI automation for lead gen, cold outreach, client acquisition systems, offer creation

**Primary Audience:**
- People actively doing cold outreach (beginners to intermediate)
- B2B marketing agency owners (0–2 years in business)
- SaaS founders struggling with client/customer acquisition

**Audience Pain Points:**
- Not getting replies to cold emails or LinkedIn DMs
- Don't know how to position their offer
- Confused about which tools to use
- Getting clients feels random, not systematic
- Watching too many gurus, not getting real results
- Can't afford expensive sales tools
- Don't know how to use AI practically for lead gen

## Content Type Classification

Every topic generated must be tagged as one of two types:

### Type 1: Actionable Content
Practical, functional, step-by-step, immediately applicable. The viewer can watch this video and do something today.

Characteristics:
- Has a clear process or system
- Viewer gets a concrete output (a sequence, a template, a workflow, a list)
- Search intent is "how to" or "show me exactly"
- Works as a tutorial, walkthrough, or framework breakdown

Examples:
- "How to build a cold email sequence in Instantly — step by step"
- "The 5-step system I use to qualify B2B leads before reaching out"
- "How to set up n8n to automate LinkedIn outreach in 30 minutes"

### Type 2: Mindset / Thinking Content
Still practical and grounded in real experience — but not immediately executable. The viewer gets a shift in how they think about a problem, which changes how they operate over time.

Characteristics:
- Challenges a belief or assumption the audience holds
- No step-by-step process — the output is a new mental model or perspective
- Search intent is "why" or "am I thinking about this wrong"
- Works as opinion pieces, contrarian takes, or reframes

Important: Mindset content on this channel is NOT motivational fluff. It must be grounded in real B2B experience and tied to a specific operational consequence. "You need to believe in yourself" is rejected. "Why treating cold outreach as a numbers game is destroying your reply rates" is accepted.

Examples:
- "Why more leads is not the answer to your agency's growth problem"
- "The real reason you're not closing clients (it's not your pitch)"
- "Stop optimizing your cold email — fix this first"

**Tag every topic output with: [ACTIONABLE] or [MINDSET]**

---

## Topic Ideation Framework

### Step 0: YouTube SERP Research (Run First)

Before generating or validating any topic, use web search to find what is currently ranking on YouTube for that topic or keyword.

**How to do this:**
Search Google using this format:
`site:youtube.com "[topic keyword]"`

Examples:
- `site:youtube.com "cold email tutorial"`
- `site:youtube.com "how to get B2B clients"`
- `site:youtube.com "n8n lead generation"`

**What to extract from SERP results:**
- Which video titles are appearing (exact wording)
- What angles are being used (how-to, listicle, case study, contrarian)
- What the top videos are NOT covering (content gap)
- Whether the topic is oversaturated or has room for a new angle

**Why this matters:**
Web search returns Google's index of YouTube videos. The titles and thumbnails that appear are the ones YouTube's algorithm is already surfacing for that keyword. This tells you what's working — and what angle is missing.

**Output from this step:**
Before the topic batch, include a brief SERP snapshot:

```
SERP SNAPSHOT: [keyword searched]
Top results found:
- [Title 1] — [angle used]
- [Title 2] — [angle used]
- [Title 3] — [angle used]
Content gap identified: [what none of them cover]
Recommended differentiation: [how the generated topics exploit this gap]
```

If the user gives a topic that's already heavily covered with no differentiable angle, flag it before generating titles.

### Step 1: Identify the Input Type

When user provides a topic idea:
- Extract the core problem it solves
- Identify which audience segment it targets
- Assess search intent: educational, how-to, tool-based, or results-based

When user asks for ideas from scratch:
- Generate across all 5 content pillars (see below)
- Prioritize pillars with highest beginner search intent

### Step 2: Apply the 5 Content Pillars

**Pillar 1: Cold Outreach Tactics**
Topics around cold email, LinkedIn DMs, follow-up sequences, reply rates, personalization

Example angles:
- Why your cold emails get ignored (and what fixes it)
- Cold email vs LinkedIn DM — which works better for [specific niche]
- The exact cold email sequence that books 3 meetings/week
- How to write a cold email opening line that doesn't sound like everyone else

**Pillar 2: Client Acquisition Systems**
Topics around building repeatable, scalable systems for getting clients

Example angles:
- How to get your first 3 B2B clients without a big budget
- Build a client acquisition machine using only free tools
- Why most agency owners can't scale past 5 clients
- The exact system I use to sign 2 clients per month consistently

**Pillar 3: AI Automation for Lead Gen**
Topics around using AI tools (n8n, Clay, Apollo, Claude, etc.) to automate prospecting and outreach

Example angles:
- How to build an AI lead gen system in n8n (step by step)
- Automate your entire LinkedIn outreach with AI — no manual work
- Use Claude to write 100 personalized cold emails in 10 minutes
- AI tools that actually work for B2B lead generation in [year]

**Pillar 4: Offer and Positioning**
Topics around crafting an offer that sells, niching down, and standing out

Example angles:
- Why your B2B offer isn't converting (and how to fix it)
- How to niche down without being afraid of losing clients
- The offer framework that books calls without a sales page
- What your prospect actually wants to hear in a cold pitch

**Pillar 5: Tools and Tech Stack**
Topics around specific tools, comparisons, tutorials, and workflows

Example angles:
- Best free tools for B2B lead generation in [year]
- Apollo vs Instantly — which is better for cold outreach beginners
- How to set up a full cold outreach stack for under $50/month
- n8n workflow tutorial: automated lead enrichment for B2B agencies

### Step 3: Apply the PVCA Filter

Before finalizing any topic, validate against 4 criteria:

**P — Pain:** Does this address a specific, felt pain the audience experiences regularly?
**V — Value:** Does the viewer walk away with something actionable?
**C — Clarity:** Is the topic specific enough that a viewer knows exactly what the video covers?
**A — Audience Match:** Does this fit beginner-to-intermediate agency owners or cold outreach practitioners?

Reject any topic that fails P or C. Flag topics that are weak on V or A.

### Step 4: Generate Title Variations

For each validated topic, produce 3 title variations:

**Format 1 — Problem/Solution:**
"Why [common mistake] — and what actually works"

**Format 2 — How-To Specific:**
"How to [specific outcome] in [timeframe or constraint]"

**Format 3 — Result-Led:**
"I [achieved result] using [method] — here's exactly how"

## Output Format

Always output in this structure:

```
TOPIC BATCH: [number] ideas for [pillar or theme]

---

TOPIC 1: [Core Topic Name] — [ACTIONABLE] or [MINDSET]

Target Audience Segment: [which sub-audience]
Content Type Rationale: [1 sentence on why this is actionable or mindset]
Pain It Solves: [specific pain in plain language]
Search Intent: [educational / how-to / tool-based / results-based / contrarian]
PVCA Score: P✓ V✓ C✓ A✓ (or flag weaknesses)

Title Variations:
1. [Problem/Solution format]
2. [How-To Specific format]
3. [Result-Led format]

Recommended Angle: [1 sentence on which angle will perform best and why]

---

TOPIC 2: [repeat structure]
```

## Batch Size

- Default: Generate 5 topics per request
- If user asks for a content calendar: Generate 10–15 topics grouped by pillar
- If user gives a single rough idea: Validate it + generate 3 alternative angles

## Quality Rules

Before outputting any topic:
- ✓ Topic solves one specific problem (not a broad theme)
- ✓ Title is specific enough to set clear viewer expectations
- ✓ Audience segment is identified
- ✓ Content type is tagged [ACTIONABLE] or [MINDSET] with rationale
- ✓ At least 2 of 3 title variations match the content type (how-to for actionable, contrarian/why for mindset)
- ✓ Mindset topics are grounded in real operational consequences — no motivational fluff
- ✓ No topics that require live data to execute (trend-based, viral-dependent)
- ✓ SERP snapshot completed before generating titles

## Common Mistakes to Avoid in Topic Selection

- Too broad: "How to grow your agency" → Too vague, no clear search intent
- Too niche too fast: "n8n webhook setup for Smartlead API v2" → Wrong for beginner audience
- Guru bait: "How I made $10K in 30 days" → Avoid unless paired with a real system breakdown
- Tool-dependent without context: "Use Clay for lead gen" → Must explain what problem Clay solves first
- Mindset without stakes: "Why mindset matters for your agency" → Rejected. Must name a specific operational consequence: "Why your mindset about volume is killing your reply rates" → Accepted
