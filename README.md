# Velichie Custom GPT Knowledge Bundle

This folder contains the public handoff bundle for a Custom GPT focused on archived 2026 meeting transcripts related to party "Величие".

## Files

- `instructions.md`: the GPT instructions/system prompt drafted for the agent
- `index.md`: corpus index of included meetings
- `knowledge_01.md` to `knowledge_09.md`: transcript knowledge files for upload
- `setup_guide_bg.md`: detailed Bulgarian setup guide for creating and configuring the GPT from a new official account

## Intended Usage

In the ChatGPT GPT Builder for the official account:

1. Create or open the target custom GPT.
2. Paste the contents of `instructions.md` into the Instructions field.
3. Upload `index.md` and all `knowledge_*.md` files as knowledge files.

## Recommended Conversation Starters

Use these as the visible starter prompts in the GPT:

- `Какви проблеми виждат в България и с какви примери от срещи ги обясняват?`
- `Защо казват, че са влезли в политиката и как го обясняват в срещите?`
- `Какви решения предлагат и има ли конкретни идеи от срещите?`
- `Как говорят за българите в чужбина и какво точно казват в срещите?`

## How To Configure It In Custom GPT

These starter prompts are configured in the GPT editor, not inside the uploaded files.

In ChatGPT on the web:

1. Open `Explore GPTs` and create or edit the target GPT.
2. Go to the `Configure` tab.
3. Fill in the user-facing fields:
   - `Name`
   - `Description`
   - `Conversation starters`
4. Paste the four starter prompts above into the `Conversation starters` section.
5. Paste `instructions.md` into `Instructions`.
6. Upload `index.md` and all `knowledge_*.md` files into `Knowledge`.
7. Save or publish the GPT.

General rule:

- `Instructions` control behavior
- `Knowledge` provides source material
- `Conversation starters` are only example opening questions shown to the user

## Source Scope

- Corpus source: YouTube meeting transcripts from the `@SvobodenGlas` channel
- Time scope: meetings since January 2026 that were processed in the local pipeline
- Known gap: one London meeting from February 28, 2026 had no Bulgarian subtitles available and is not included in the transcript bundle
