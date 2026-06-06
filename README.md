# hi


I'm Tom I build AI-native products and agentic development systems. I’m not a traditional software developer. I don’t primarily build by writing code line by line. My work is figuring out what should be built, turning that into a clear spec, and using AI agents as the implementation layer.

Most of my software work is built through AI agents. What I care about is not “prompting once and hoping it works.” I’m interested in long-running agent workflows: systems that can take a product spec, break it into workstreams, build against it, review their own output, find gaps, and keep iterating.

The goal is to make AI-built software less random. Not just “ask an AI to code something,” but give agents clear roles, constraints, files to touch, acceptance criteria, and review passes.

---

## What I’m Building

### Agentic PRD Workflow

Autonomous PRD-to-implementation system.

This is probably the clearest example of how I think about AI-built software.

It is not just a workflow that takes a PRD and breaks it into tasks. The PRD becomes a living source of truth that the system keeps updating as it runs.

The loop looks more like this:

PRD → issue-finding agents → proof → PRD update → task creation → orchestrators → subagents → checks → pull request

The main agent can send specialist agents into the codebase to find issues, gaps, missing requirements, or broken behaviour. Those agents come back with proof, not just opinions. The main agent then updates the PRD, creates the next set of tasks, and hands them to orchestrators.

The orchestrators take control of each task, spin up the right subagents, run checks, verify the implementation, and prepare the pull request for review or merge.

The goal is to move beyond “ask AI to code something.”

I’m interested in development systems that can keep running: finding issues, updating their own understanding of the product, creating new tasks, implementing fixes, checking their own work, and improving the software over time.


---

### [Scriba](https://www.scriba.co.nz/)

AI lecture-note product for university students.

Scriba turns lecture recordings into structured notes, summaries, flashcards, and study material. The product is built around the real student workflow: capture the lecture, process it, turn it into something useful, and make revision easier.

---

### Kanzlo

LangChain-based legal-tech application for German legal workflows.

Kanzlo is built around document understanding, matter memory, source-grounded answers, drafting support, and lawyer review controls.

The interesting problem is trust. In legal work, the AI cannot just sound confident. It needs to show what it relied on, where the information came from, and what still needs to be checked.

---

### [Pulse Paper Trading](https://chromewebstore.google.com/detail/pulse-paper-trading/liljlbolainjpecpclkmnkplfgiakmfp)

Crypto paper-trading platform using real market charts.

Pulse lets users practise against real crypto charts using paper balances. The focus is entries, exits, PnL tracking, trade history, and performance review without real-money execution.

---

## How I Build

I usually start with the product problem, not the tech stack.

Before anything gets built, I want to understand:

* what the user is actually trying to do
* what the product needs to prove
* what the core workflow is
* what the system needs to remember
* what the interface needs to make obvious
* where AI helps
* where AI should stay out of the way
* what the agent needs to build
* how we know whether the output is good enough

Then I turn that into specs, implementation phases, agent tasks, and review loops.

The AI can write the code. The hard part is making sure it is building the right thing.

---

## The Stuff I’m Most Interested In

I’m interested in the layer above raw code generation.

Things like:

* AI agents that can work from proper specs
* PRDs that are actually executable
* review loops that catch bad assumptions
* agents that can audit each other’s work
* legal and education products that fit real workflows
* interfaces that make AI easier to trust
* small teams using AI to build like much bigger teams

I think the next big shift in software is not just “AI writes code faster.”

It’s that software development itself becomes a system you can design.

Right now I’m trying to get very good at building with AI agents.

---

```
```

