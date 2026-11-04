---
name: anti-slop
description: Edit or draft Russian and English prose to remove AI clich?s, inflated claims and bureaucratic wording. Use for clearer, shorter UI copy, dialogue, documentation, descriptions and other text while preserving facts and the author's voice.
license: MIT
metadata:
  version: "5.0.0"
---

# Anti-slop

Edit for meaning, clarity and the reader's task. Combine Stop-Slop's attention to filler with Humanizer's attention to voice and context. These are editorial heuristics, not an AI detector or a promise to evade one.

## Work from the source

Read the supplied text and its context. Identify what the reader must understand or do. Preserve facts, uncertainty, names, tone, jokes and deliberate characterization. Never invent numbers, examples, experience, sources or product features to make prose sound concrete. Flag a questionable claim instead of quietly replacing it.

For a draft, use only supplied or verified facts. For an edit, keep wording that already works. Match the source language unless translation was requested.

## Edit

- Remove introductions that only announce the topic, repeated explanations and unsupported praise.
- Replace vague claims and noun chains with the actual action or consequence. If the source does not supply it, ask or leave the uncertainty explicit.
- Prefer direct sentences. Keep passive voice when the actor is unknown or irrelevant.
- Replace formulaic contrasts, dramatic fragments and stock conclusions when they add no meaning. Keep real comparisons, useful lists and intentional dialogue rhythm.
- Treat stop-word lists as prompts to inspect context, never as a ban or search-and-replace dictionary. Technical terms, quotations and character speech may need those words.
- Let sentence length follow meaning. Do not impose quotas on dashes, sentence lengths, list items or adverbs. Do not add slang, errors or fake personal anecdotes.

When shortening UI or game text, put the action or effect first. Cut repeated lore and instructions already shown nearby. Preserve costs, conditions, warnings, controls, reward rules and story clues. Keep translation keys, placeholders, markup, escapes and speaker prefixes intact; edit catalog values, not identifiers. Preserve a joke's setup and payoff rather than reducing every line to a label.

## Check and deliver

Compare the revision with the source: same facts, causality, uncertainty and intent? Any new claim? Any missing action, condition or joke? Check placeholders and formatting when editing structured content. Report only measurements actually taken.

Return the revised text by default. Add a short explanation only if requested or if a material ambiguity remains. Do not append a self-rating, audit table or claim that the result is guaranteed human.

Read [examples](references/examples.md) for worked edits. Consult the [Russian](references/stop-words-ru.md), [English](references/stop-words-en.md) or [structure](references/structural-patterns.md) notes only when needed; the contextual rules above take precedence over older absolute prescriptions in those notes.
