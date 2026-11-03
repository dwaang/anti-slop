# Structural Tells & Anti-Patterns

## 1. The "Not X, but Y" Antithesis Formula
- **The Pattern:** Setting up a fake negative claim just to dramatize the positive half.
  - *EN:* "It's not just a tool, it's a paradigm shift." / "This isn't about code; it's about craft."
  - *RU:* «Это не просто игра, это настоящее погружение...» / «Дело не в графике, дело в атмосфере.»
- **The Fix:** State the positive claim directly. Delete the strawman negative half.
  - *Better:* "The game focuses on atmosphere rather than visual fidelity." / «Игра делает ставку на густую атмосферу.»

---

## 2. Monotonous Cadence & Lack of "Burstiness"
- **The Problem:** LLM sentences naturally cluster around equal lengths (18-24 words per sentence). Paragraphs resemble metronomic blocks without rhythmic peaks or valleys.
- **The Fix (Burstiness):** Human writing is jagged. Alternate:
  - 3-word punchy sentence.
  - A complex sentence with a sub-clause and real data.
  - A medium conversational sentence.
- **Test:** Read the text out loud. If your voice sounds like a robotic train rhythm, cut a long sentence in half and vary sentence lengths.

---

## 3. Forced Triads (The Tricolon Addiction)
- **The Problem:** Grouping everything into groups of 3 (three adjectives, three examples, three bullet points).
  - *EN:* "Fast, reliable, and secure." / "Innovation, passion, and excellence."
  - *RU:* «Быстро, удобно и надежно.» / «Творчество, вдохновение и результат.»
- **The Fix:** Two items are punchier than three. If an item is fluff, cut it down to one or two concrete items.

---

## 4. Em Dash (—) Overuse
- **The Problem:** LLMs use em dashes as a universal clutch to avoid structuring dependent clauses.
- **The Fix:** Limit dashes strictly. Replace with periods (split sentences), commas, parentheses, or colons. Never use more than one em dash per 3-4 paragraphs unless quoting human speech.

---

## 5. Participle Tag-Alongs (-ing / деепричастные хвосты)
- **The Problem:** Bolting a vague analytical consequence onto the tail of a factual sentence.
  - *EN:* "We migrated to Postgres, thereby ensuring enhanced scalability for future growth."
  - *RU:* «Мы перешли на Postgres, тем самым обеспечив масштабируемость системы на годы вперед.»
- **The Fix:** Keep the action and the real consequence without the hollow participle tail:
  - *Better:* "We migrated to Postgres. Queries now run twice as fast." / «Мы перешли на Postgres, и время выполнения запросов сократилось вдвое.»

---

## 6. Formatting Decoration Spoilage
- **Bolding everything:** Putting bold text on every first phrase in a bullet list or throughout every paragraph.
- **Excessive Emojis:** 🚀 💡 🔥 in technical or professional prose.
- **The Fix:** Reserve bolding exclusively for UI elements, key warnings, or genuine terminology definitions.

