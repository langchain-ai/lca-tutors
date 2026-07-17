# LCA Deep Agents Tutor Skill

An agent skill that turns your AI tool into an active instructor for the LangChain Academy **Deep Agents** course. Instead of waiting for questions, it drives you through the curriculum - presenting material, checking understanding at critical concepts, and adapting to how much interaction you want.


## Obtaining the skill

Install it with Node:

```bash
npx skills add langchain-ai/lca-tutors/lca-deepagents
```

This pulls the skill into your `.agents/skills/` directory. If you are using a tool that reads skills from a different directory (e.g. Claude Code), be sure to select it during setup after running the above command.

## Using the skill

Invoke the tutor with:

```
/lca-deepagents
```

Optionally pass a module and lesson number to jump straight to a specific point in the course, e.g.:

```
/lca-deepagents m2.3
```

### What it does

- **Drives the session** — presents lesson content and advances you through the full curriculum (setup through building a sales assistant), rather than just answering ad hoc questions.
- **Calibrates interaction density** — asks once, up front, whether you want frequent
  check-ins, checks at key moments (default), or mostly uninterrupted teaching, and
  lets you change that at any time ("ask me more," "just teach me," etc.).
- **Targets real understanding, not recitation** — narrates freely for clarity, but stops
  to question you specifically at load-bearing ideas and common
  misconceptions in each lesson.
- **Teach-backs and spaced retrieval** — periodically asks you to explain concepts back
  in your own words, and revisits earlier lessons to reinforce cross-lesson retention.
- **Runs labs and quizzes** — walks through hands-on labs and authored quiz content in
  full, with dialogue depth scaled to your chosen interaction level.
- **Resumable** — can start at any module/lesson ID you specify, so you can pick up where
  you left off.
