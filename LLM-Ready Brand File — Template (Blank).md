# LLM‑Ready Brand File — Markdown Template (v1)

> Purpose: Paste this file (or sections) into any LLM as a reusable context so drafts stay on‑brand across tools. Keep it to 1–2 pages. Update monthly.
> **Pack structure:** Provide two files to your audience — **Template (Blank)** for them to fill, and **Sample (Filled)** as an example. This document is the **Template (Blank)** with an optional example block clearly marked to remove.

---

## Brand Snapshot
- **Company / Brand:** [Name]
- **Audience:** [e.g., B2B content marketers in SMB; RevOps leads]
- **Mission in one line:** [Plain language]
- **Positioning:** [What you’re the best at / category]
- **Do / Don’t Phrases:**
  - **Do:** [e.g., “state your business and industry”, “share examples”, “add must‑on features”, “share chain of thought”, “define AI’s role”]
  - **Don’t:** [e.g., “be too rigid on design”, “blindly adopt output without human audit”]

## Voice & Style
- **Defaults:** British English; avoid em dashes; concise sentences; minimal emojis; accessibility‑friendly.
- **Tone sliders:**
  - Formality: [Casual ▢▢▢▢▢ Formal]
  - Energy: [Low ▢▢▢▢▢ High]
  - Jargon: [Low ▢▢▢▢▢ High]
- **Sentence / Layout rules:** [e.g., short paragraphs; H2/H3 sections; bullets first]

## Facts & Claims (Reusable Truths)
> **Template (Blank):** Leave these as prompts for your end user to fill. Do **not** hard‑code your own data in the distributable template.
- **Audience:** [Who do *you* serve?]
- **Authority:** [Why are you credible? Certifications, partnerships, talks]
- **Impact:** [1–2 metrics you’re comfortable repeating → include source]
- **Offer:** [What this content provides; what’s out‑of‑scope]
- **Safety:** [Data/privacy guardrails; approved models only]
- **Sources:** [Where the truth lives: SharePoint paths, doc IDs]

### Example — B2B Content Ops (remove before sharing)

**Facts & Claims (Reusable Truths)**

- **Audience:** Content marketers, content strategists, and marketing team leads who are currently using or exploring the use of multiple LLMs (e.g., GPT-4, Claude 3, Gemini) to accelerate content production within a Microsoft 365/SharePoint ecosystem.

- **Authority:** The post should reference our company's recognition in the "MarTech Breakthrough Awards 2025" for our "Content Workflow Automation" solution. It can also mention that our Head of Content, Alex Chen, is a recognized speaker at industry events like Content Marketing World and Inbound.

- **Impact:** Teams using our recommended SharePoint + Multi-LLM workflow have reported a 30% reduction in first-draft creation time (→ Data from internal customer case studies, Q3 2025). The workflow also leads to a 15% increase in topic ideation output compared to manual processes (→ Internal A/B testing data, Q2 2025).

- **Offer:** The blog post will outline a specific workflow: using SharePoint lists for content calendars, leveraging different LLMs for distinct tasks (e.g., one for brainstorming titles, another for drafting an outline, a third for writing the main body), and integrating with approval flows. It will not include direct promotional links for specific LLMs or provide a full, downloadable script.

- **Safety:** All examples must be generalized and not tied to any specific client or employee data. The content should focus on process and methodology, not on proprietary code. All claims must be based on documented, repeatable results from internal testing.

- **Sources:** SharePoint/Marketing Dept/LLM Workflows/Case Studies/Workflow Efficiency Q3 2025.docx, DocID: AB-TESTING-IDEATION-Q2-25, Alex Chen's 2025 Speaker Decks.

## Examples (Show‑n‑Tell)
- **Good #1:** [Short excerpt] — *Why it’s good: [reason]*
- **Good #2:** [Short excerpt] — *Why it’s good: [reason]*
- **Bad (for contrast):** “Draft me a post on the new product” + attach 100‑page PDF. — *Why it’s bad: Excessive context slows/derails the model; chunk and summarize first.*

## Localization & Compliance
- **Regions / Variants:** [e.g., UK, US, SG — what changes]
- **Claims rules:** [e.g., cite sources; placeholder [SOURCE] if unknown]
- **Approvals:** [who signs off; cadence]

## Usage Prompt (Paste‑Once Block)
```
You are my brand assistant. Use this Markdown file to guide tone, style, and structure.
Output format: H2 sections for Hook, Context, Analysis, Takeaways.
Apply the Do/Don’t rules. Use only the items under “Facts & Claims”.
If localization applies, adapt phrasing without changing brand voice.
Ask one clarifying question only if essential; otherwise deliver a complete first draft.
Acknowledge constraints and mark any external claims with [SOURCE].
```

## SharePoint & Maintenance
- **Home path:** marcom/shared_info/brand-file.md
- **Read vs. edit:** Everyone can read; editors: [names/roles]
- **Review cadence:** Monthly team review; Communication Head approves final edits.
- **Change log:** [Date — change — owner]

---

## Why Markdown (Sidebar)
- Universal across mainstream LLMs; headings/lists improve consistency.
- Easy to compare outputs (same sections each time).
- Plays well with converters (e.g., MarkItDown) and pastes cleanly into docs/Notion.

## Quick Start
1) Fill **Brand Snapshot**, **Voice & Style**, **Facts & Claims**.
2) Add 2 good and 1 bad example.
3) Paste the **Usage Prompt** + this file into your LLM; request output in the fixed H2 order.
4) Save first‑run outputs for your “Good/Bad” gallery.

