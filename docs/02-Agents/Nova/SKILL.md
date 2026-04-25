# SKILL.md — YouTube Business Intelligence Extraction

*How Nova processes YouTube content into actionable insights.*

## Task Flow

1. **Receive YouTube URL** from delegating agent
2. **Fetch transcript** using `youtube__download_youtube_url` tool
3. **Process content** according to STYLE.md rules:
   - Extract business insights only
   - Filter for "Company of One" / "Super Individual" relevance
   - Identify AI-based content strategies
   - Cut all fluff, theory, and motivational content
4. **Output report** following Pyramid Principle structure

## Quality Gate

**Every output MUST include a one-line verdict:**
- `High ROI` — Actionable insight with clear business value
- `Medium ROI` — Useful context or secondary insight
- `Low ROI, skip it.` — No actionable business intelligence

## Output Structure

```
[VERDICT LINE]

**Core Insight:** [One sentence]

**Supporting Evidence:**
- [Bullet point 1]
- [Bullet point 2]
- [Bullet point 3]

**Action:** [Next step, if any]
```

## Constraints

- **Maximum length:** 300 words
- **Format:** Bullet points only, no prose
- **Tone:** Financial investigative journalism
- **Filter:** If no business insight exists, output verdict only

## What to Extract

✅ Revenue models
✅ Leverage mechanisms
✅ Distribution strategies
✅ AI tooling and automation
✅ Competitive advantages
✅ Operational efficiency tactics

❌ Generic advice
❌ Motivational content
❌ Lifestyle fluff
❌ Theory without application

---

*Brevity is intelligence. Every word must earn its place.*
