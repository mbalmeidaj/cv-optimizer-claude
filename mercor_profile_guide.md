# Mercor Profile & CV Optimization Guide

> **Reference Documentation (always check these for updates):**
> - Profile Setup: https://talent.docs.mercor.com/how-to/setup-your-profile
> - Application Fit: https://talent.docs.mercor.com/announcements-and-new-releases/application-fit
> - Instant Work Offers: https://talent.docs.mercor.com/new-releases/instant-offer

---

## How Mercor's Matching System Works

Mercor uses an automated matching engine that cross-references a candidate's profile against active listings. Understanding this engine is the single most impactful thing you can do to increase visibility.

**What the system reads:**
1. **Profile keywords** — pulled from Summary, Skills & Tools, job titles, and project descriptions
2. **Verified interview and assessment performance** — stored scores that persist across applications
3. **Availability signals** — weekly hours, start date, and time zone
4. **Profile completeness** — incomplete profiles are ranked lower by default

**Instant Offer logic:** When a candidate's verified performance, skills, and availability closely match a listing's criteria, the hiring team may extend an offer without requiring an application. This means a well-built profile can generate inbound opportunities passively.

---

## Universal CV Construction Logic for Mercor

These principles apply to **any professional field** — engineering, medicine, humanities, design, research, law, education, etc.

---

### 1. Professional Summary

**In the Mercor profile field:** maximum ~150–200 words of plain prose.

**Structure (field-agnostic):**
```
[Degree/credentials] + [years of experience + domain] + [what you do / current focus]
+ [tools, methods, or frameworks you use] + [2–3 quantified outcomes]
+ [role targets] + [location, availability, languages]
```

**Universal rules:**
- Lead with your identity in the **first sentence**: who you are + what you do.
- Include **explicit keywords** tied to your domain — the NLP parser reads prose, not just the Skills section.
- Add **2–3 concrete outcomes** with metrics whenever possible. Every field has measurable results:
  - Engineering: "reduced processing time by 40%"
  - Medicine/Health: "supported care for 200+ patients/month", "reduced diagnostic turnaround by 2 days"
  - Education: "improved student pass rates by 15%"
  - Legal: "managed a caseload of 50+ clients"
  - Design/Creative: "delivered 30+ brand identities for SMBs"
  - Humanities/Research: "published 3 peer-reviewed papers on X"
- Close with: **target roles + location/TZ + weekly availability + languages**.
- Write in **English** even if your primary market is non-English — Mercor is a global platform.

**Anti-patterns to avoid:**
- Generic openers: "I am a passionate professional…" — no signal for the parser.
- Listing tools without context: "Python, R, SQL" alone does nothing; embed them in sentences.
- Missing availability: profiles without availability set are deprioritized for Instant Offers.

---

### 2. Skills & Tools Section

This is the most parser-sensitive section. Mercor reads it left-to-right and captures the **first 5 skills** it finds on its internal whitelist.

**Format rule (non-negotiable):**
```
Skill1 | Skill2 | Skill3 | Skill4 | Skill5 | Skill6 | ...
```
Plain text, pipe-separated, centered, italic. **Never a table or bullet list.**

**Section heading must be exactly:** `Skills & Tools`
(Not "Technical Skills", not "Core Competencies", not "Expertise".)

**Ordering strategy:**
- Slots 1–5: your most strategic skills **from the platform whitelist** for your target roles.
- Slots 6+: supporting tools, secondary methods, adjacent skills.
- **Deduplication rule:** if a term already appears in your tagline or headline, it's already captured — don't waste one of the first 5 slots repeating it.

**Field-specific whitelist guidance:**

| Field | High-signal terms (confirmed or likely on Mercor) |
|---|---|
| Data / ML / AI | `Machine Learning`, `Statistical Analysis`, `Python`, `SQL`, `Data Science`, `Predictive Modeling`, `Data Visualization`, `Causal Inference` |
| Marketing Analytics | `Marketing Mix Modeling`, `Marketing Analytics`, `Attribution Models`, `Customer Segmentation`, `Budget Optimization`, `A/B Testing` |
| AI Evaluation / RLHF | `AI Evaluation`, `STEM Expert`, `Prompt Engineering`, `Data Labeling` |
| Software Engineering | `Software Development`, `Backend Development`, `Frontend Development`, `API Development`, `Cloud Infrastructure` |
| Research / STEM | `Research`, `STEM Expert`, `Bayesian Inference`, `Statistical Modeling`, `Data Analysis` |
| Healthcare / Clinical | `Clinical Research`, `Healthcare Analytics`, `Patient Data`, `Medical Writing`, `EHR Systems` |
| Design / UX | `UX Design`, `Product Design`, `Figma`, `User Research`, `Prototyping` |
| Finance / Quant | `Financial Modeling`, `Risk Analysis`, `Quantitative Research`, `Valuation`, `Excel` |
| Legal / Compliance | `Contract Review`, `Legal Research`, `Compliance`, `Regulatory Affairs` |
| Education / Training | `Curriculum Development`, `Instructional Design`, `E-Learning`, `Training Delivery` |

> **Note:** This table is a working reference. Always verify against the live documentation and update this file as new confirmations arrive.

**Terms to avoid in first 5 slots:**
- Overly generic: `Communication`, `Teamwork`, `Leadership` — no whitelist signal.
- Too narrow/non-standard: acronyms and niche jargon that the parser may not recognize.
- Compound forms only work as written: `STEM Expert` (two words) works; `STEM` alone does not on Mercor.

---

### 3. Work Experience

**Header format:**
```
Company Name  —  Job Title
Month/Year – Month/Year  |  City, Country
```

**Bullet rules:**
- 4–6 bullets per role (3 minimum for older roles).
- Always start with an **action verb in simple past**: Built, Led, Designed, Developed, Reduced, Improved, Launched, Managed, Delivered, Analyzed, Created, Established.
- One idea per bullet. Max 2 lines.
- **Metric formula:** Action + What + Result + Scale.
  - "Reduced customer churn by 18% by implementing a propensity-to-cancel model across 500K accounts."
  - "Delivered 12 end-to-end UX projects for healthcare clients, improving task completion rates by 22%."
  - "Managed a caseload of 60+ immigration cases with a 94% approval rate."

**For any field, look for metrics in:**
- Volume: number of clients, patients, students, cases, transactions, units.
- Time: reduced from X to Y days/hours.
- Money: cost savings, revenue generated, budget managed.
- Quality: accuracy, error rates, satisfaction scores, approval rates.
- Scale: team size managed, geographic reach, platform users.

---

### 4. Projects

Projects are especially important for candidates who want to show skills beyond their formal work history — freelancers, researchers, career changers, and early-career professionals.

**Header format (period FIRST — parser rule):**
```
Project Title
2023 – 2024  |  Context (Freelance / Academic / Personal / Company)
```

**Content rules:**
- 2–3 bullets per project, outcome-focused.
- Include the problem, your approach, and the result.
- For AI evaluation or data labeling platforms (Mercor, Scale AI, etc.): **never include internal project names**. Use descriptive generic titles:
  - ✅ "STEM Content Quality Evaluation", "Prompt Adjudication", "Medical Reasoning QA"
  - ❌ Internal codenames or client names

---

### 5. Education

**Format:**
```
Degree (e.g., M.Sc., B.Sc., MBA, M.D., J.D., B.A.)
Field of Study — Institution Name
Start Year – End Year
GPA: X.X / 4.0  (include only if ≥ 3.5 or equivalent strong result)
```

Include relevant coursework, thesis title, or honors only if directly relevant to target roles.

---

### 6. Profile Completeness Checklist

Mercor's matching algorithm deprioritizes incomplete profiles. Before publishing:

- [ ] Full name, city, country, time zone set
- [ ] Resume uploaded (PDF recommended)
- [ ] LinkedIn URL added
- [ ] GitHub / Portfolio added (if applicable to field)
- [ ] Availability set (start date + weekly hours)
- [ ] At least one completed assessment or AI interview
- [ ] Skills & Tools section populated with pipe format
- [ ] Summary written (150–200 words, outcome-focused)
- [ ] Notifications enabled (email/app) — required to receive Instant Offers in time

---

### 7. Availability & Instant Offers

From the Instant Offers documentation:
- Availability must be **accurate and current** — stale availability suppresses matching.
- The system can surface a candidate to hiring teams **without an application** if the match score is high enough.
- Declining an Instant Offer does **not** affect future matching.
- Offers have an expiry deadline — respond before it expires.

**Implication for CV building:** always ask the user to confirm their available hours/week and update it in their Mercor profile after uploading the CV.

---

### 8. Tagline / Headline

**Format:**
```
[Area 1] & [Area 2]  |  [Key Differentiator]  |  [X+ Years Experience]
```

**Universal examples:**
- `Clinical Research & Healthcare Analytics  |  Evidence-Based Decision Making  |  8+ Years Experience`
- `UX Design & Product Strategy  |  Human-Centered Systems  |  5+ Years Experience`
- `Software Engineering & Cloud Infrastructure  |  Scalable Backend Systems  |  7+ Years Experience`
- `Legal Research & Contract Management  |  Regulatory Compliance Specialist  |  10+ Years Experience`
- `Education Technology & Curriculum Design  |  E-Learning & Training Delivery  |  6+ Years Experience`

Keep it in English. The tagline feeds directly into the parser's keyword extraction.

---

### 9. Languages & Hobbies

**Languages:** list each with a standard proficiency level:
- Native / Fluent / Professional Working Proficiency / Conversational / Basic

**Hobbies:** Mercor's matching system includes interest data. Include genuine hobbies — they can improve profile-to-role affinity on platforms that factor cultural fit. Keep it to 4–6 items, one line.

---

## Summary: The 5 Highest-Impact Actions on Mercor

1. **Write a keyword-rich, outcome-driven Summary** — this feeds the NLP matching engine directly.
2. **Order your Skills & Tools strategically** — first 5 slots on the whitelist determine discoverability.
3. **Keep availability current** — the Instant Offer system will not surface you if availability is blank or stale.
4. **Complete at least one assessment or AI interview** — verified performance unlocks the pre-qualified tier.
5. **Quantify everything possible** — metrics are the clearest signal of impact across all fields and seniority levels.