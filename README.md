# someflydev

I build systems that help coding assistants do better work with less waste.

My recent focus is a prompt-first, context-aware workflow for creating high-quality repos with stronger docs, testing, structure, and long-running agent discipline.

## What I’m building

I started with a simple pattern:

- create a `.prompts/` directory
- write ordered `PROMPT_XX.txt` files
- run pre-flight checks on the prompt collection
- commit the prompt set
- run one megaprompt per fresh coding-assistant session

That approach kept sessions fast, focused, and high-signal while producing better code, docs, tests, and repo structure.

From there, the real challenge became obvious:

**context management matters just as much as prompt quality**.

Longer-running unattended sessions need better ways to decide:

- what context to load
- what constraints to follow
- what good output looks like
- how to validate work before trusting it
- how to hand work off cleanly between sessions and agents

## Current direction

That led to a broader system for context engineering and agent-guided repo creation:

- codified `.prompts/` planning for derived repos
- context-first repo generation
- doctrine / manifest / stack / router separation
- reusable skills
- memory and handoff patterns
- spec and validation oriented workflows
- better performance through smaller, more relevant context
- better artifacts through clearer operating rules

The goal is simple:

**help coding assistants produce more reliable work, more efficiently, with fewer tokens and less drift.**

## What these repos explore

This work also supports a growing set of canonical, tested examples across many languages and deployment styles, especially around:

- backend APIs in multiple languages
- choosing a strong web framework per language
- HTMX + Tailwind + Plotly driven interfaces
- Playwright UI/UX verification
- separate `docker` / `docker-test` stacks
- varied datastores, queues, streams, and event systems
- prompt-driven repo bootstrapping with stronger validation

## Repo family

The public foundation is `agent-context-base`.

From that, I planned and began building three private cloud-focused spinoff repos in parallel for:

- serverless / function-oriented systems
- simpler container-based systems
- fuller Kubernetes-oriented systems

Together, they are meant to explore how the same core discipline can scale across different operational environments.

## Why this exists

This work is meant to do a few things at once:

- create a serious foundation for an eventual community/platform
- support selective consulting and hands-on implementation work
- demonstrate unusual leverage as an engineer and technical strategist
- show how AI-assisted development can be made more disciplined, repeatable, and impressive

## Important context

This `someflydev` account is the newer, AI-centered umbrella for this body of work.

It is intentionally separate from my older GitHub identity, which contains more traditional human-built shell, Python, and related open source projects.

If you’re interested in:
- agent-context engineering
- prompt-first repo creation
- long-running coding assistant workflows
- multi-language canonical examples
- validation-driven AI-assisted development

you’re looking at the right place.
