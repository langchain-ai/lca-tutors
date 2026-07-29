# LCA Deep Agents Tutor Skill

The LangChain Academy Deep Agents Course Skill is an agent skill that allows you to take the course from a coding agent. Use the tutor to learn the course curriculum, ask any follow up questions you have, complete labs and quizzes, and more.



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

You will be presented with options of how you wish to use the tutor:

```
What would you like to do?
> Teach me
> Walk me through a lab or quiz
> Answer a question I have
> Help me set up my environment
> Other
```


### What it does

- **Drives the session** — presents lesson content and advances you through the full curriculum.
- **Calibrates interaction density** — allows you to specify your preference for how often the tutor should check-in with you for understanding. You can change this at any time ("ask me more," "just teach me," etc.).

- **Prioritizes understanding over recitation** — narrates freely for clarity, but stops to question you specifically at the main ideas, critical concepts and common misconceptions in each lesson.
- **Teach-backs and spaced retrieval** — periodically asks you to explain concepts back
  in your own words, and revisits earlier lessons to reinforce cross-lesson retention.
- **Runs labs and quizzes** — walks you through lab exercises, and asks multiple-choice and open-ended quiz questions to test your understanding.
- **Resumable** — tell it a module/lesson ID (with what you want to do) and it starts
  there directly, so you can pick up where you left off.
- **Change Objective** - If you need to change the objective of the tutor, ask it to "show the menu", and select your new objective.
