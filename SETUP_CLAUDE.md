# How to create this project inside Claude

This guide shows exactly where to place each text and file when creating the assistant in Claude.

You are free to edit every part of this setup to match your style, niche, offers, or business model.

As of March 16, 2026, Anthropic's official help center says Claude Projects are available to all users, with free accounts able to create up to 5 projects.

## 1. Create a new project or custom assistant

Open Claude and create a new Project.

Important: according to Anthropic's official Projects documentation, Claude does not use the project name and description as behavior instructions. The real behavior should be placed in `Set project instructions` and in the uploaded knowledge files.

Use this name:

```text
AI Workers
```

## 2. Fill in the description

Paste this into the description field:

```text
👋 Get your CV optimized for global remote platforms.

This assistant helps you build a professional resume
formatted specifically for platforms like Mercor,
Micro1, and Turing — maximizing your visibility to
international hiring teams.

Just share your current CV and we'll do the rest.
Any field. Any level. Free.
```

## 3. Fill in the project instructions

In the project page, click `Set project instructions`.

Paste this into the instructions field:

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

## 4. Upload the knowledge files

On the right side of the project page, use the project knowledge area and upload:

- `cv_generator_prompt.md`
- `mercor_profile_guide.md`

These two files are the real operating brain of the assistant.

## 5. Do not upload the Mercor HTML snapshots

This repository intentionally avoids publishing Mercor HTML exports.

Instead, add a note in your project docs or README saying that users can:

1. Visit the official Mercor documentation pages
2. Save the pages locally as HTML if they want extra research material
3. Update `mercor_profile_guide.md` when the official docs change

Official reference URLs:

- https://talent.docs.mercor.com/how-to/setup-your-profile
- https://talent.docs.mercor.com/announcements-and-new-releases/application-fit
- https://talent.docs.mercor.com/new-releases/instant-offer

## 6. Recommended first-run test

After creating the project, send a message like:

```text
Hi, I need help optimizing my resume for Mercor. I already have a CV.
```

The assistant should first ask for the user's CV or background before doing anything else.

## 7. What each file does

- `cv_generator_prompt.md`: full assistant behavior, flow, resume logic, extraction logic, and document rules
- `mercor_profile_guide.md`: Mercor-specific rules, profile logic, keyword guidance, and platform references
- `README.md`: public landing page for GitHub visitors
- `SETUP_CLAUDE.md`: copy-paste setup guide for anyone who wants to recreate the assistant

## 8. What people are allowed to change

Anyone can edit:

- project name
- description
- donation links
- referral links
- prompt logic
- target platforms
- output language rules
- branding

This project is meant to be reused and adapted.

## 9. Recommended GitHub publishing flow

1. Keep only the markdown files and repo docs in version control.
2. Do not commit exported Mercor HTML pages or asset folders.
3. Publish the repository as public.
4. Add a short topic list on GitHub, such as:
   - `claude`
   - `prompt-engineering`
   - `resume-builder`
   - `mercor`
   - `career-tools`
5. Add a clear disclaimer that Mercor is a referenced platform, not the owner of this repository.
