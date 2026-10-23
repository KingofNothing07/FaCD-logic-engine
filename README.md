# FaCD — Factored Context and Discernment

**An algebraic test of semantics.**

FaCD turns claims, plans, options, testimony, and staged goals into checkable equations. You write the problem as `Left = Right`, factor both sides in public, apply only the operations that do work, tag the result, and leave a transparent page that a later reader can rerun.

It is not a memory or logging system. It is a discernment method that makes reasoning visible and testable. It works fully standalone and is also a natural companion to [Semantic Shorthand](https://github.com/KingofNothing07/Semantic-Shorthand): they share the same Language Core notation, so a finished FaCD pass is already valid shorthand and a `=` inside a shorthand log is already a FaCD-testable claim.

---

## Purpose

Natural language hides its factors. A claim can look finished while its words are still closed. A strategy can look like one goal while it is actually two. Two people can appear to disagree about the world when they are only disagreeing about the meaning of a word.

FaCD exists to surface that hidden structure:

- Write the demand as the Right side of an equation.
- Factor both sides so the definitions become explicit.
- Name the bridges or links that must hold.
- Tag whether the sides meet (True), fail (False), remain incomplete (Unsolved), or are still unclear (Unknown).
- Produce a Clarity sentence that states the outcome without hiding a second job.

The goal is a page anyone can re-run: raw set, equation, factors, bridges, working comments (if any), tag, and Clarity.

---

## Core Abilities

| Ability | What it does |
|---------|--------------|
| **Semantic equations** | Express a claim, plan, or option as `Left = Right` (or show `!=`). One Right per equation. |
| **Public factoring** | Open both sides into their constituent factors so definitions are visible rather than assumed. |
| **Gated working** | Only the operations that actually do work are applied. Shotgun (surface-level check) is used only when level-0 already shows the sides meet. |
| **Tagging** | Clear Phase III result: True, False, Unsolved, or Unknown. |
| **Clarity** | Leads with the solution, then what it is, then why — so the outcome is immediately readable. |
| **Synthesis** | When a pass misses, keep the same Right and build a new Left from supporting factors (including misses), then rerun. |
| **Bridging** | Declare when two or more factors become the definition of a new term or an emergent relation. |
| **Rerunnability** | The finished page is self-contained enough that a later reader (or different model) can follow and verify the reasoning. |
| **Standalone or companion** | Teaches the Language Core completely enough to run alone; shares notation cleanly with Semantic Shorthand when both are loaded. |

---

## Why Use FaCD

- **Checkable reasoning** — Replace “it feels right” or opaque summaries with a tagged, factorable equation.
- **Expose hidden assumptions** — Factoring forces definitions into the open.
- **Handle stacked options** — Test multiple Lefts against one Right and use misses as material for Synthesis.
- **Testimony vs. record** — Structured way to compare claims against evidence or constraints.
- **Staged goals and missing transforms** — Useful when a plan has intermediate steps or a lambda that has not yet been specified.
- **Transparent hand-off** — The page itself is the artifact; no private chain of thought is required to understand the result.
- **Honest uncertainty** — Probability tags are only used when verifiable or explicitly marked as guesses.

FaCD is especially valuable whenever a decision, claim, or plan must remain defensible and reconstructible by someone who was not in the original conversation.

---

## How to Install and Use with AI

### Quick Install
1. Copy the **entire** contents of [`01.01_FaCD-Factored_Context_and_Discernment-Skill_Package.md`](01.01_FaCD-Factored_Context_and_Discernment-Skill_Package.md).
2. Paste it into your AI as a system prompt, custom instructions, project knowledge, or skill upload.

The package includes a complete teaching of the Language Core, so nothing else is required to run FaCD.

### Activation Notes
- Loading the package does not force every response into FaCD form.
- Explicit requests (“use FaCD,” “run a pass,” “balance this claim,” or the skill name) activate it.
- On explicit invocation the AI will typically ask two short things if they are not already clear: what the demand (Right) is, and whether you want a quick pass or full rigor.
- Ambient or brainstorming work does not automatically trigger a formal pass. The AI can think in FaCD form without ceremony when the structure would help.
- After a pass, if the tag is Unsolved or False and Synthesis or an Inverse would change the work, the AI will name the gate and ask whether to run it.

### Practical Tips
- Wrap real FaCD passes in fenced code blocks. Several symbols are meaningful Markdown outside fences.
- Disable autocorrect. Straight quotes, arrows, and operators can be silently altered.
- Verify that copied or handed-off passes still contain literal operators before treating them as clean.
- One Right per equation. Split when two demands cannot share one tag.
- When in doubt, prefer the smaller pass that can carry an honest tag.

### Companion Use with Semantic Shorthand
If you also load Semantic Shorthand, the two skills share notation with no translation step. They keep independent Read Gates and Activation Discipline — satisfying one does not satisfy the other. FaCD does not automatically log its results; when you want a pass to survive as an inheritance artifact, ask Semantic Shorthand to carry it.

---

## Files — Detailed Descriptions

| File | What it contains | Best for |
|------|------------------|----------|
| [`01.01_FaCD-Factored_Context_and_Discernment-Skill_Package.md`](01.01_FaCD-Factored_Context_and_Discernment-Skill_Package.md) | Full FaCD skill package: skill prompt, philosophy and axioms, complete Language Core teaching, phases, gates, Working, Synthesis, Clarity, and practice guidance. Fully standalone. | Running FaCD passes and learning the system end-to-end. This is the file most users should install. |
| [`Semantic_Shorthand_Language_and_Grammar.md`](Semantic_Shorthand_Language_and_Grammar.md) | Language Core reference only: notation, symbols, syntax, Hard/Soft Rules, Special Sets, Math Mode, Absolute/Invariant, compression, and glossary. Shared with Semantic Shorthand. | Quick lookup of shared notation when you already know FaCD or want a lighter reference. |
| [`FaCD_Solutions_Library.md`](FaCD_Solutions_Library.md) | Curated collection of real problems worked with FaCD. Currently empty; structured for community contributions via pull request. Each entry shows problem, domain, outcome tag + Clarity, key factors/bridges, and contributor. | Seeing worked examples and adding your own after review. |

---

## How a Pass Typically Flows

1. Identify the single demand (the Right).
2. Write the equation.
3. Factor both sides in public.
4. Apply only useful gates / working.
5. Produce the tagged Phase III line.
6. Lead Clarity with the solution.
7. If the tag is Unsolved or False and further work would help, consider Synthesis (new Left, same Right) and rerun.

The finished page should let a later reader follow the same path and reach the same tag.

---

## License

MIT — free to use, modify, and share. See [`LICENSE`](LICENSE).

---

Contributions to the Solutions Library and improvements to the skill or documentation are welcome via pull request or issues.