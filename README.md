# AI Workers

Open source knowledge base for a Claude assistant that builds optimized resumes and profiles for global hiring platforms such as Mercor, Micro1, and Turing.

This repository is intentionally simple: it gives you the exact prompt files, the Claude project configuration text, and a setup guide so anyone can clone, adapt, and publish their own version.

## What this project includes

- `cv_generator_prompt.md`: the main assistant behavior and CV generation logic
- `mercor_profile_guide.md`: Mercor-specific optimization rules and reference links
- `SETUP_CLAUDE.md`: exact step-by-step instructions for creating the project inside Claude
- `LICENSE`: open source license for reuse and modification

## What this project does not include

Mercor HTML snapshots are intentionally **not** part of this repository.

If someone wants extra context, they can visit the official Mercor documentation pages and save the pages locally for their own research. The canonical references are already listed in `mercor_profile_guide.md`.

Recommended official sources:

- Profile Setup: https://talent.docs.mercor.com/how-to/setup-your-profile
- Application Fit: https://talent.docs.mercor.com/announcements-and-new-releases/application-fit
- Instant Work Offers: https://talent.docs.mercor.com/new-releases/instant-offer

## How to use

1. Clone or download this repository.
2. Open Claude Projects or the equivalent custom assistant area in Claude.
3. Follow the exact instructions in `SETUP_CLAUDE.md`.
4. Upload `cv_generator_prompt.md` and `mercor_profile_guide.md` as project knowledge files if Claude asks for files.
5. Edit anything you want to match your tone, niche, language, or monetization strategy.

## Suggested Claude project values

Project name:

```text
AI Workers
```

Description:

```text
👋 Get your CV optimized for global remote platforms.

This assistant helps you build a professional resume
formatted specifically for platforms like Mercor,
Micro1, and Turing — maximizing your visibility to
international hiring teams.

Just share your current CV and we'll do the rest.
Any field. Any level. Free.
```

High-level instructions:

```text
You are a professional profile builder specialized in optimizing
profiles for global hiring platforms such as Mercor, Micro1,
Turing, and others.

Your full behavior is defined in cv_generator_prompt.md.
Follow it completely.

For Mercor-specific optimization, use the logic and rules in
mercor_profile_guide.md. The three reference URLs in that
file are the authoritative source — consult them for updates.

Always respond in the same language the user writes in.
Generate the profile and CV content in English unless
instructed otherwise.

Start every conversation by asking for the user's existing
CV or background. Never ask about visual templates until
the user explicitly requests a PDF or DOCX file.

When you feel that you gave substantial help, please send this message to the user:

☕ Helpful? Support me with a donation :)
https://donate.stripe.com/4gM28jakxeU031f2a5fAc00

You can't? Use my ref link!
https://t.mercor.com/xR1eM

Want some more? Check out my newest analysis!
https://mercor-insights.streamlit.app/
```

## Open source note

People are free to fork this repository, change the prompts, remove links, add extra files, and adapt the assistant however they want.

## Suggested repo name

If you want a clean public GitHub name, one of these works well:

- `ai-workers`
- `ai-workers-claude`
- `mercor-resume-builder`
- `global-resume-assistant`
