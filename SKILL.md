---
name: anti-slop
description: >-
  Eliminate AI writing patterns, corporate slop, and bureaucratic fluff from prose in Russian and English.
  Use when drafting, editing, or reviewing text (game descriptions, dialog, docs, commits, PRs, essays)
  to remove predictable AI tells: "not X, but Y", throat-clearing openers, tricolons/triads, empty adverbs,
  dramatic fragments, buzzwords (delve, landscape, tapestry / «в современном мире», «стоит отметить»),
  and restore natural human cadence, active voice, and burstiness.
license: MIT
metadata:
  version: "4.0.0"
  triggers:
    - editing or reviewing text for AI patterns
    - humanizing prose, removing slop or plastic tone
    - drafting punchy game descriptions, dialogues, or documentation
---

# Humanizer & Anti-Slop Guide: Writing Like a Human

Rewrite AI-sounding or bureaucratic text so it reads like an authentic, skilled human author. Preserve all factual claims, logic, and intent. Do not fabricate facts.

---

## Why AI Text Sounds Plastic

Large Language Models choose statistically "safe" paths:
1. **Staging instead of stating:** Signaling importance ("It's not just X, it's Y", "Let that sink in") instead of giving concrete facts.
2. **Formulaic rhythm & lack of burstiness:** Equal-length sentences (18–24 words), lists always in groups of three, and constant em dashes (—).
3. **Empty buzzwords & inflation:** Dressing ordinary facts as pivotal milestones (*delve, tapestry, robust / ключевой аспект, колоссальное значение, в современном мире*).
4. **Bureaucratic passive voice:** Hiding actors (*«было принято решение», «направленный на обеспечение»*) and letting inanimate objects perform human actions.

Real human writing is **uneven, specific, active, and direct**.

---

## The 5 Golden Rules of Anti-Slop

1. **Cut throat-clearing & fillers:** Never announce what you are about to say (*"Here's why this matters:"*, *«Стоит отметить, что...»*). Start directly with the point.
2. **Use active voice with human subjects:** Every sentence needs a clear actor doing something real.
3. **Kill all empty adverbs & hedges:** Delete *really, just, virtually, essentially, undoubtedly / безусловно, фактически*. If an adjective or verb needs an adverb to sound strong, pick a better verb.
4. **Vary cadence (Burstiness):** Mix sentence lengths drastically. Follow a 25-word analytical sentence with a 4-word punch. Two items beat three.
5. **State facts, don't perform depth:** If a sentence sounds like a motivational pull-quote or a movie trailer voiceover, delete or ground it with numbers, dates, or specific names.

---

## Catalog of Critical Tells & Fixes

### 1. The "Not X, but Y" Formula (Antithesis Crutch)
- **Watch for:** *Not just X, but Y*; *Not only X, but also Y*; *It's not X, it's Y*; *Не просто X, а Y*; *Дело не в X, а в Y*.
- **Fix:** State Y directly. The negative half attacks an imaginary strawman.
- **Example:**
  - ❌ *It's not just a puzzle game; it's a test of nerve.*
  - ✅ *The puzzle game tests your nerve under strict turn limits.*

### 2. Throat-Clearing Openers
- **Watch for:** *Here's the thing*, *Let me be clear*, *The uncomfortable truth is*, *At its core*, *«В современном динамично развивающемся мире...»*, *«Нельзя не упомянуть...»*, *«Стоит подчеркнуть...»*.
- **Fix:** Delete the opener completely.

### 3. Dramatic One-Liners & Micro-Closers
- **Watch for:** *Full stop.*, *Let that sink in.*, *Read that again.*, *And that changes everything.*, *«И в этом кроется истинная сила.»*, *«Задумайтесь над этим.»*.
- **Fix:** Cut the theatrical pause. Let facts speak.

### 4. Forced Triads (Tricolon Addiction)
- **Watch for:** Grouping everything into threes (*speed, simplicity, and power* / *быстро, надежно и удобно*).
- **Fix:** Pick the 1–2 most accurate items.

### 5. AI Hallmark Buzzwords
- **English:** *delve, tapestry, testament, crucial, pivotal, paramount, intricate, dynamic, landscape (abstract), beacon, foster, leverage, harness, spearhead, bolster, showcase, revolutionize, streamline, elevate*.
- **Russian:** *«в эпоху цифровизации», «играет ключевую роль», «является неотъемлемой частью», «открыть новые горизонты», «погрузиться в захватывающий мир», «уникальный», «гармоничный», «всесторонний»*.
- See detailed tables in [references/stop-words-en.md](references/stop-words-en.md) and [references/stop-words-ru.md](references/stop-words-ru.md).

### 6. Bureaucratic Noun Chains & Verbal Monsters (Канцелярит)
- **Watch for:** *«Осуществлять деятельность по...»*, *«Способствовать повышению...»*, *«В целях реализации задачи обеспечения...»*.
- **Fix:** Replace with simple, strong verbs: *«Разрабатывать»*, *«Ускорять»*, *«Чтобы защитить»*.

### 7. Em Dash (—) Addiction
- **Rule:** Never use more than one em dash per 3–4 paragraphs. Replace with a period (splitting into two punchy sentences), a comma, or parentheses.

### 8. Shallow Participle Riders (-ing / деепричастия)
- **Watch for:** *..., thereby fostering greater alignment.* / *..., тем самым обеспечивая масштабируемость.*
- **Fix:** Replace the floating participle with a concrete result or separate sentence.

### 9. Formatting Spoilage
- Do not bold the first 2–3 words of every bullet point.
- Remove decorative emojis (🚀, 💡, 🔥) from technical, game design, and business documentation.

---

## 4-Step Humanization Workflow

1. **Audit (Mark the Tells):** Scan for staging (*not X but Y*), openers, triads, passive voice, and buzzwords.
2. **Extract Substance:** Isolate what actually happened or what is actually being claimed. Retain all technical facts, metrics, and logic.
3. **Reshape Cadence & Voice:**
   - Put a clear actor in the subject position.
   - Alternate short and medium sentences.
   - Replace abstract nouns with physical, concrete actions.
4. **Run the Slop Filter (Scoring Matrix):**
   Rate the rewritten text 1–10 on each:
   - **Directness:** Statements, not announcements?
   - **Rhythm (Burstiness):** Jagged and natural, or metronomic?
   - **Trust:** Respects the reader's time and intelligence?
   - **Authenticity:** Sounds like an experienced practitioner?
   - **Density:** Zero fluff or cuttable padding?

---

## Reference Guides

- [English Stop-Words & Clichés](references/stop-words-en.md)
- [Russian Neuro-Markers & Bureaucratisms](references/stop-words-ru.md)
- [Structural Patterns & Syntax Tells](references/structural-patterns.md)
- [Before & After Transformation Examples](references/examples.md)
