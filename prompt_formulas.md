# Prompt Formulas (Copy/Paste)
ROLE: [who the model is] +
GOAL: [what outcome] +
CONSTRAINTS: [rules/limits] +
STYLE: [tone, voice, format] +
EXAMPLES: [few-shot samples] +
STEPS: [ordered tasks]

## Text (Article)
SYSTEM: You are a {role}. Follow AP style. Cite sources inline.
USER: Write a {word_count}-word article on {topic} for {audience}.
Constraints: {constraints}
Outline: {outline}
Deliver in Markdown with H2/H3.

## Image (MidJourney)
/imagine prompt: {subject}, style of {style_ref}, lighting {lighting}, --ar {ratio} --v 6 --seed {seed}

## Video (Shorts/Reels)
Hook (0–2s): {hook}
Payoff (3–12s): {big_idea}
CTA (last 2s): {cta}
Overlay captions: {keywords}

## Code Task
SYSTEM: You are a senior engineer. Output only code fenced blocks.
USER: Build a {feature} in {language}. Requirements: {reqs}. Include tests.
