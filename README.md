# anti-slop 🚫✍️

> **The Universal Anti-Slop & Prose Humanizer Agent Skill for English & Russian.**  
> Eliminates predictable AI clichés, robotic cadence, fake depth, and bureaucratic fluff. Restores punchy, authentic human voice.

---

## What is Anti-Slop?

Large Language Models (LLMs) default to statistically "safe", flattened prose:
- **Staging over substance:** *"It's not just a game, it's a testament to..."* / *«Это не просто выбор, это философия...»*
- **Throat-clearing openers:** *"Here's the thing:"*, *"At its core,"* / *«В современном динамично развивающемся мире...»*, *«Стоит отметить, что...»*
- **Monotonous rhythm (Lack of Burstiness):** Uniform sentences (18–24 words) marching in lockstep, lists forced into groups of three (tricolons), and em dashes (—) everywhere.
- **Hollow buzzwords:** *delve, tapestry, pivotal, robust, landscape, beacon / ключевой аспект, колоссальное значение, уникальный*.
- **Bureaucratic passive voice (Канцелярит):** *«было принято решение»*, *«осуществлять деятельность по обеспечению»*.

**`anti-slop`** is an agent skill that forces AI coding assistants and writers (Antigravity, OpenAI Codex, Claude Code, Cursor, Windsurf) to write with **genuine human burstiness, active voice, authentic density, and zero marketing syrup**.

---

## ⚡ The 5 Golden Rules

1. **Cut throat-clearing:** Start directly with the point. Never announce what you are about to say.
2. **Use active voice:** Real human subjects performing concrete actions.
3. **Kill empty adverbs & hedges:** Delete *really, just, virtually, essentially / безусловно, фактически*.
4. **Vary cadence (Burstiness):** Alternate ultra-short sentences with detailed, data-backed clauses. Two items beat three.
5. **State facts, don't perform depth:** If a sentence sounds like a motivational pull-quote or movie trailer, cut it or ground it in specific facts and metrics.

---

## 📂 Repository Structure

```text
anti-slop/
├── SKILL.md                          # Main skill instructions & YAML frontmatter
├── README.md                         # Documentation & installation guide
├── LICENSE                           # MIT License
└── references/
    ├── stop-words-en.md              # English AI buzzwords, fillers & business jargon
    ├── stop-words-ru.md              # Канцелярит, маркеры нейросетей и штампы на русском
    ├── structural-patterns.md        # Syntax tells: tricolons, antithesis, -ing riders, dash abuse
    └── examples.md                   # Real Before/After transformations (EN & RU)
```

---

## 🚀 Installation & Usage

### 1. Antigravity (Google / AGY)
Copy the folder to your global skills or project:
```bash
# Global installation (recommended)
cp -r anti-slop ~/.gemini/config/skills/anti-slop
```
Or add to `~/.gemini/config/skills.json`:
```json
{
  "entries": [
    { "path": "/path/to/anti-slop" }
  ]
}
```

### 2. OpenAI Codex / CLI
```bash
cp -r anti-slop ~/.codex/skills/anti-slop
```

### 3. Claude Code / Cursor / Windsurf
- For **Claude Code**: place in `.claude/skills/anti-slop/`
- For **Cursor / Windsurf**: place in `.agents/skills/anti-slop/` or reference `SKILL.md` in `.cursorrules`.

---

## 🧪 Before & After Quick Comparison

### English (Game Pitch)
> **AI Slop:**  
> *"Welcome to Memseum, an extraordinary rogue-lite expedition where history meets hilarity. In today's digital landscape, it's not just a game; it's a testament to the enduring power of internet humor. Delve into intricate grids with robust synergies. Let that sink in."*

> **Anti-Slop:**  
> *"In Memseum, you excavate forgotten internet relics across procedurally generated grid maps. Each dig costs bandwidth. Find legendary memes, pin them in your museum for passive yield, and combine synergistic tags like Cat, Tech, and Glitch."*

### Russian (Game Pitch / Техническое описание)
> **AI Slop:**  
> *«Погрузитесь в захватывающий мир Memseum — уникального проекта на стыке рогалика и археологии интернет-фольклора! В современном динамично развивающемся мире мемы играют колоссальную роль. Нами была осуществлена деятельность по переработке синергий, тем самым выводя геймплей на беспрецедентный уровень. Задумайтесь над этим.»*

> **Anti-Slop:**  
> *«Memseum — пошаговая игра про раскопки забытых мемов. Вы тратите трафик (BW) на расчистку клеток, находите реликвии вроде Древнего Баяна и выставляете их в собственном музее. У 73% артефактов 1 синергетический тег, у легендарных — 3. Каждая синергия дает понятный числовой бонус к доходу или силе инструментов.»*

---

## 📊 5-Dimension Scoring Matrix

Before delivering prose, evaluate against:
- **Directness (1–10):** Statements or throat-clearing announcements?
- **Rhythm / Burstiness (1–10):** Natural cadence with varied sentence length, or metronomic robot drone?
- **Trust (1–10):** Respects reader intelligence without over-explaining or hand-holding?
- **Authenticity (1–10):** Sounds like an experienced practitioner who actually built the thing?
- **Density (1–10):** Every sentence adds a new fact or consequence; zero fluff.

*(Revise if total score is below 40/50).*

---

## License

MIT © [dwaang](https://github.com/dwaang)
