# Timothy Bailey: instructions and AI prompting guide

[All guides](../README.md) · [Your design brief](../design/timothy-bailey.md) · [Work plan](../../WORK_PLAN.md)

**Role:** Member 1  
**Scope:** 8 topic pages. Distinguish the brand's personality from the visual movement used to express it. Explain why each example fits; do not present your interpretation of a brand as an official self-description without a source.

## Your topics and discovery questions

These are questions to develop your own ideas, not prescribed answers. Choose a topic you can explain or find a useful example for; Explorer is one possible starting point.

| Topic and file | Question to explore with your AI |
| --- | --- |
| [Explorer](../../brand-archetypes/explorer.md) | What kind of discovery or independence do you want visitors to feel, and what action would express it? |
| [Hero](../../brand-archetypes/hero.md) | What challenge is the audience trying to overcome, and how can the visitor remain the protagonist? |
| [Outlaw](../../brand-archetypes/outlaw.md) | Which convention would your brand challenge, and what constructive alternative does it offer? |
| [Sage](../../brand-archetypes/sage.md) | What does the audience want to understand, and how will the design make evidence easy to inspect? |
| [Bauhaus](../../design-movements/modernist/bauhaus.md) | Which researched design principle would shape function and composition in your example? |
| [Swiss Modernism](../../design-movements/modernist/swiss-modernism.md) | How would your grid, hierarchy, and typography help visitors find the most important information? |
| [Pop Art](../../design-movements/postmodernist/pop-art.md) | Which visual reference interests you, and how would you explain its connection to the movement with evidence? |
| [Memphis Design](../../design-movements/postmodernist/memphis-design.md) | How much visual play fits your audience, and what should remain calm and easy to read? |

## Detailed workflow

1. **Check the assignment.** Read the latest instructor brief, required format, due date, and AI-use rules. Put any uncertainty in your design brief. Team guidelines do not establish a grading rubric.
2. **Prepare your workspace.** Fork the group repository or use your existing fork in the same network. Follow CONTRIBUTING.md to fetch the group `main` and create a branch such as `tim-archetypes-design`. Your `origin` is your fork and your `upstream` is the group repository.
3. **Review existing content.** Open your linked files and preserve useful work. There is a pre-existing Explorer draft on `add-explorer-archetype` at root `explorer.md`. Coordinate with its author before using it; the assigned destination is `brand-archetypes/explorer.md`.
4. **Run the interview.** Copy the prompt below into your AI. Supply the actual documents if it cannot access links. Answer up to three questions at a time. Ask for an explanation or examples if a question is unclear.
5. **Confirm your intent.** Have the AI summarize your audience, message, example, desired response, constraints, and unresolved questions. Correct that summary and explicitly confirm it before drafting.
6. **Research one topic.** Identify the claims that need evidence, read sources, and record them in your [design brief](../design/timothy-bailey.md). Verify any brand classification or historical statement.
7. **Write and explain.** Create an outline, then complete the topic page. Include concrete design decisions and a rationale. Read it aloud or explain it back in your own words to catch gaps.
8. **Document and repeat.** Complete a short topic decision record in your brief. Repeat the interview for the next topic; do not reuse an answer merely because two topics appear similar.
9. **Check the contribution.** Preview Markdown, open links, credit any images, remove TODOs from completed pages, and check only your intended changes are included.
10. **Open a PR.** Use [the contribution instructions](../../CONTRIBUTING.md). Base: `ahmet360/archetype_design_persusion`, branch: `main`. Head: your own fork and topic branch. Explain the pages completed, sources checked, and remaining questions. Post the PR link in the group chat and address review comments on the same branch.

## What to send Ahmet

Send your PR URL, the topic pages completed, a short summary of your design direction, and any question that needs a decision. If you are blocked, name the blocker and what you already tried. You can open a clearly labeled draft PR for early feedback; that does not count as a finished submission.

## Copy this prompt into your AI

```text
Act as my research tutor and design partner for the IS117 group project.
I am Timothy Bailey, Member 1. My assigned topics are:
- Explorer: brand-archetypes/explorer.md
- Hero: brand-archetypes/hero.md
- Outlaw: brand-archetypes/outlaw.md
- Sage: brand-archetypes/sage.md
- Bauhaus: design-movements/modernist/bauhaus.md
- Swiss Modernism: design-movements/modernist/swiss-modernism.md
- Pop Art: design-movements/postmodernist/pop-art.md
- Memphis Design: design-movements/postmodernist/memphis-design.md

The group repository is https://github.com/ahmet360/archetype_design_persusion.
Read my personal guide, docs/DESIGN_DOCUMENTATION.md, my personal design
brief, WORK_PLAN.md, CONTRIBUTING.md, and my topic templates. I will provide
the actual instructor requirements and any AI-use policy. If you cannot
open a file or source, tell me and ask me to paste it. Never pretend you
have read something you cannot access.

Your first job is to understand my ideas and intent. Do not immediately
write all my pages, choose a brand for me, or generate a finished project.

Start with at most THREE short questions, then STOP and wait:
1. Which assigned topic should we work on first, and how do I understand it?
2. What audience and brand or website context do I want to explore, and
   what should a visitor think, feel, or do?
3. What instructor requirements, constraints, existing ideas, or examples
   should guide us?

After I answer, ask focused follow-up questions in small batches. Use the
topic-specific questions in my guide. Ask why I prefer an idea, what
alternative I considered, and how I would recognize a successful result.
If I am unsure, explain the concept simply and offer two or three
possibilities, clearly as options. Do not record an option as my decision
until I choose it.

For each topic, explore the definition, supporting sources, a concrete
example, message, layout, typography, color, imagery, usability, and
small-screen behavior only as relevant. My emphasis is:
Distinguish the brand's personality from the visual movement used to express it. Explain why each example fits; do not present your interpretation of a brand as an official self-description without a source.

Summarize my intent under: confirmed ideas, proposed ideas, open questions,
and constraints. Ask me to confirm or correct it, then STOP. Draft only
after I explicitly confirm the summary.

After confirmation:
- Propose a research plan and an outline for ONE selected topic.
- Distinguish sourced facts, my interpretation, and hypothetical examples.
- Use real sources that were actually read. Do not invent quotations,
  citations, access dates, results, testimonials, or statistics.
- If browsing is unavailable, identify the sources or evidence I need
  and wait for it instead of fabricating support.
- Help me complete the existing Markdown headings in my own voice.
- Explain how specific design decisions support my audience and intent.
- Record the confirmed decisions and remaining questions in my design
  brief; do not claim a planned check was performed.
- Ask me to explain the main idea back in my words. Help me correct any
  misunderstanding before we move to another topic.
- End with a concrete review checklist and a suggested PR description.

Do not edit other members' files, add collaborators, publish, push, merge,
or submit coursework without my specific instruction. I work in my own fork.
Any PR must target ahmet360/archetype_design_persusion -> main.
Follow the actual instructor policy for AI assistance and disclosure.

Begin with the three opening questions and wait for my answers.
```

## Useful follow-up prompts

- "Summarize what you understand about my idea, show any assumptions, and wait for my corrections."
- "Ask me the most important unanswered question for this topic; do not draft yet."
- "Which claims in this paragraph need a source, and which are my interpretation?"
- "Compare two ways to express my intent and explain their usability tradeoffs."
- "Quiz me on the topic using my chosen example, one question at a time."
- "Review only my assigned files against the guide and list concrete fixes without changing other work."
