# Edda

Edda is how I work with coding agents, written down one step at a time. Each chapter adds one idea to the ones before it. It rests on a real story from my own work. It ends with one thing you can try on your own repository the next morning.

## The promise

How far can you let coding agents go? I let mine go as far as my proof reaches. What could do damage that can't be undone, or carry big consequences, I read myself. The rest I check through the proof my agents bring. Edda tells how I got there, one real story at a time, starting from one agent and one request. My tools come in only at the step where my own hands stopped being enough.

## Who it's for

You use a coding agent every day (Claude Code, Cursor, Copilot, Codex), one session at a time, and you keep an eye on it while it works. At least once it told you "done" when it wasn't, and since then you don't let it go further than you can see. You don't need to know any of my tools.

## What I still decide

Working this way, I still understand my repositories, and they are still mine. I decide what holds them up, what "done" means and what an agent never does alone. I keep those decisions in files next to the code, with their reasons, where I and every agent can read them. I learned why that matters the day I found a concept in my own tool that I didn't remember introducing (step 9). The promise above sets what I read myself.

## How to read it

Start at the step where it hurts. Find your step by the symptom you have today and read that chapter. Try its one thing the next morning, then go on to the next step. Each chapter stands only on the steps before it and says which ones, so if you start at step 12, you know which earlier chapters to go back for.

Steps 0 to 4 are about proof, from one request to a measure. Steps 5 to 8 are about what holds while I'm not watching: what's written down, the wall, two locks and the two parts of a repository. Steps 9 to 13 are about letting go: questions, nights, many agents, the loop and the model. Steps 14 and 15 are about being honest with myself, and how far. Step 15 answers the question step 1 leaves open.

## The ladder

| Step | You're here if | The idea | Chapter | Episode |
|---|---|---|---|---|
| 0 | You write a request, take what comes back, and check it yourself by clicking through it or reading the result. | I have one agent and I ask it to do this and that for me. It does more than answer: it does the work on my computer. | [One agent and a request](chapters/00-one-agent-and-a-request.md) | [1](episodes/01-throw-out-the-junk.md) |
| 1 | The result is believable, and it isn't what you had in mind: "that's not what I meant." | Whatever I didn't say, the agent fills in on its own. So I spell out the part I mean until it stops guessing, or I make it stop and ask me. | [The agent fills the gaps](chapters/01-the-agent-fills-the-gaps.md) | [1](episodes/01-throw-out-the-junk.md) |
| 2 | You hear "done", "tested", "it works", and all you hold is that sentence. | When an agent tells me what it did, that's a claim. I ask for something I can see myself: a run, a screenshot, a film, the integration code. | "Done" is a claim (coming with its episode) | coming |
| 3 | Everything is green and something is still wrong, or nobody knows what the test compared against. | Green only means it matched what it was compared with. I ask with what, check the result where it lands, and in the end on the real system and with a real person. | Proof can lie (coming with its episode) | coming |
| 4 | The agent says "it already matches" and you can see it doesn't, or it chases a number that isn't the goal. | If I don't give the agent a target it can check, it chases whatever number it finds. A good measure matters more than a clever way to organise the work. | The measure (coming with its episode) | coming |
| 5 | In every new session you repeat the same rules, or you fix the same thing again in the next repository. | The agent doesn't remember between sessions, and after a day of changes neither do I. Only what's written in the repository counts: rules, decisions with their reasons, the state of the work. | Written down, not remembered (coming with its episode) | coming |
| 6 | The agent knows the rule and doesn't follow it, or it learns the minimum it takes to pass the check. | A rule I say in chat lasts one conversation. A rule in an instructions file is a request. A rule a machine checks stops every agent, every time. | A wall the agent can't argue with (coming with its episode) | coming |
| 7 | You have rules and the agents still break how the app behaves, or you have tests and the architecture drifts. | An agent works with confidence where it has two locks: one on structure (architecture and rules) and one on behaviour (end-to-end scenarios on the running app, with stand-ins checked against the real API). The load-bearing walls stay; the partition walls the agent builds as it likes, as long as they do their job. | Two locks (coming with its episode) | coming |
| 8 | The team sees a branch that changes its production code, when the task was only to add tooling. | A repository has two parts. The production code belongs to the team that answers for it and stays readable and simple. Next to it sits the part that lets agents work freely (harness, agent tests, stand-ins, container, rules, notes), and a developer can join it with one simple move. | The repository has two parts (coming with its episode) | coming |
| 9 | A wall of questions arrives in one message, or your project holds things you don't remember deciding. | The agent brings me one decision at a time, with the context, the options and its recommendation. If the agent wrote my options, it made my decision, so every line has an author and a reason. | One question at a time (coming with its episode) | coming |
| 10 | In the morning you find the work stood still for half the night. | Left alone, an agent fails by waiting: for a permission, a notification, my decision. Everything has to end on its own, and questions wait for the morning. | Nights without me (coming with its episode) | coming |
| 11 | Agents wait for each other, reports don't come back, the laptop roars and the backlog grows faster than it shrinks. | More agents talking to each other doesn't add up to more work. Each ends with one report, whoever searches doesn't fix, each works in its own copy of the repository, and my laptop and my tokens set how many run at once. | Many agents at once (coming with its episode) | coming |
| 12 | The approvals are there, and the agent that did the work gave them, or the plan is a straight line that breaks at every change. | Work goes through a list of issues, one worker per issue, and someone who didn't write it approves it. That promise holds only when a tool enforces it. | The loop and the fresh reviewer (coming with its episode) | coming |
| 13 | Every helper runs on the most expensive model because nobody named another, or the tokens run out mid-week. | I pick the model by what a mistake nobody notices would cost. The model is always named, the checker is never weaker than the worker, and I try a new model in practice. | Picking the model (coming with its episode) | coming |
| 14 | Every rule looks load-bearing, so none ever goes, or your tool is right and the agents do the same without it. | The rulebook only gets thicker, and the owner has to retire rules. My own tool also has to show it changes a decision: a true answer that changes no decision is worth nothing. | Rules and tools have to earn their place (coming with its episode) | coming |
| 15 | One day you say "you don't need me" and the next "I approve before you change anything", or an agent deletes something you can't get back. | Agents go as far as my proof reaches, inside lines I wrote down, and never through anything that can't be undone. What could do damage that can't be undone, or carry big consequences, I read myself. | This far (coming with its episode) | coming |

## When your own hands stop being enough

Steps 0, 2, 3, 5, 8, 10 and 13 need nothing of mine installed. At the other steps, doing it by hand stopped being enough for me, and one of my tools carries that step. Each tool comes in at its step and not before. They are open source, under the MIT licence.

| Step | Tool | What it does for me |
|---|---|---|
| 1 | [Urd](https://github.com/krzysztofdudek/UrdSkill) | Before the agent acts on something it could read two ways, it stops and looks up the source of truth or asks me: where it is, the options, and the one it would pick. |
| 4 | [Researcher](https://github.com/krzysztofdudek/ResearcherSkill) | Asks me what to optimise and how to measure it, then runs experiments on its own branch, keeping what works and reverting what fails. It can't tell me what is worth optimising. |
| 6 | [Yggdrasil](https://github.com/krzysztofdudek/Yggdrasil) | Say it once. Keeps my architecture rules next to the code, gives the agent the rules for the file it's about to edit, and checks every change in a pre-commit hook and in CI. |
| 6 | [Grain](https://github.com/krzysztofdudek/Grain) | Before I write a rule on an existing codebase, it reads the ones the code already keeps, from the code and its git history, with a count behind every claim. It never blocks. |
| 9 | [Ratatoskr](https://github.com/krzysztofdudek/RatatoskrSkill) | Keeps the agent talking to me in plain words: one sharp question when my ask is unclear, with the answer it would pick by default, and one clear yes before anything that can't be undone. |
| 11 | [Horde](https://github.com/krzysztofdudek/Horde) | For a mission too big for one head to plan up front: an architect plans it once onto the rules, a worker takes each ticket, and every change lands through a gate. How much it adds over the loop at step 12, I haven't measured. |
| 12 | [Jarl](https://github.com/krzysztofdudek/JarlSkill) | The loop. Every finding becomes an issue, each issue gets a worker in its own copy of the repository, and nothing closes without evidence. No code closes without a fresh reviewer's word. |

Some come back later, where they help again: Yggdrasil at steps 7 and 14, Researcher and Grain at step 14, Jarl at step 15.

## What this is, and what it isn't

Edda is one person's way of working with coding agents. Mine: I'm Chris Dudek, and I build with AI agents and prove their work. It shows what I do and what it gave me on my own projects, one step at a time. Each step comes with the story behind it. I'm still learning it. In my own words: "(…) it's not so one-shot that I knew everything from the beginning, no, no, I didn't know. (…) It aggregates, right? It will stay, it aggregates, this knowledge, this information."

It isn't a framework you install, and it isn't the one right way to work with agents. Chapters 0 and 1 need nothing beyond the agent you already use.

Built today: chapters 0 and 1 are written out, with [the page of episode 1](episodes/01-throw-out-the-junk.md) and its practice, [What you don't do alone](practices/what-you-dont-do-alone.md). Every other chapter comes out after its episode. Until then the ladder above shows its step.

The stories come from my own projects and from work with teams. A story from a team's work carries no names, no products and no numbers.

## How this is written

I write Edda with my agents, from my own record: session transcripts, notes and git history. A line in quotation marks that I call my own words is something I said, translated from Polish where I said it in Polish. Where a line of mine survives only in the notes an agent kept that day, the chapter says so. Everything else is narration.

## Where else it lives

Edda is the written side of one public system. The others are my YouTube series *How far can you let agents go?*, the READMEs of my tools, and [chrisdudek.com](https://chrisdudek.com). Each episode of the series tells the story behind a step, and [episode 1](episodes/01-throw-out-the-junk.md) is out. I'm building them on the same steps and the same words. A chapter comes here after its episode is out.

## Licence

The text is CC BY 4.0: reuse and adapt it freely, and credit Krzysztof Dudek with a link to [this repository](https://github.com/krzysztofdudek/Edda). The full terms are in [LICENSE](LICENSE).
