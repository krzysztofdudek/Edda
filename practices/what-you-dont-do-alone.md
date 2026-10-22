# What you don't do alone

A practice for step 1, [the agent fills the gaps](../chapters/01-the-agent-fills-the-gaps.md), and the exercise at the end of [episode 1](../episodes/01-throw-out-the-junk.md). Nothing to install.

## What it's for

Every request you give an agent has gaps, and the agent fills each one with its own guess. You see a guess only when you go and look at what the agent did. This practice turns one guess you found into one line your agent reads before its next session.

## What you need

- One session with your agent that already happened. Its record is what you read: the commands the agent ran and the files it touched, as your tool keeps them. In a repository, `git status` and `git diff` show the files. Anything the agent did outside the repository, only the session shows.
- Your agent's instructions file: `AGENTS.md`, `CLAUDE.md`, or the rules file your tool reads at the start of every session.

## The steps

1. **Find your request, word for word.** Open the session and copy what you asked for.
2. **List what the agent did.** Skip its final summary. The agent wrote it for you, and it only says what the agent did. Go through the record: every command it ran, and every file it created, changed, moved or deleted.
3. **Mark each item.** Next to each thing on the list, mark whether your request said it.
4. **Pick one.** From the things your request never said, take the one you'd least like to discover a week later.
5. **Write one line.** Put it into the instructions file, under one heading that collects these lines. Phrase it as something the agent doesn't do on its own, or does only after asking you.
6. **Next time, have it tell you back.** When you hand the agent something new, ask it to tell you what it understood before it starts. I ask it in my own words: "Tell me if you know what I mean. Tell me, and I'll confirm."

## The block to copy

```markdown
## What you don't do on your own

- If you notice something you didn't expect, stop and ask me before you act on it.
```

The first line comes from episode 1. After it deleted my model, the agent wrote itself a rule in my diary: "An anomaly in the review before deleting is a STOP signal, not a premise." The rule stayed in the diary and never reached the file my agents read before they start. Here it is as a line for that file. Add yours under it.

## How a line reads

- **One action**, named the way it happens on the machine, so the agent can tell when it's about to do it.
- **Taken from the record.** Each line names a gap the agent has already filled once.
- **What to do instead**: stop and ask, tell you back first, or bring you a list and wait for your answer.

A line in the file is for the next session. In the session you're in, you can say the part you mean straight away. When an agent brought me a list of what it would clean up on my disk, I answered with the one exception I meant: "Clean up, but leave the containers."

The file my agents read before every session has a few lines like this. Deleting files is one of them.

## Where it stops

The line is a request. The agent reads it, and nothing checks whether it keeps to it. An agent can also decide that this time is different. [Chapter 1](../chapters/01-the-agent-fills-the-gaps.md#where-it-stops) says where that leads.

## Where it comes from

- Step 1: [The agent fills the gaps](../chapters/01-the-agent-fills-the-gaps.md)
- Episode 1: [Throw out the junk](../episodes/01-throw-out-the-junk.md)
- [Back to the ladder](../README.md#the-ladder)
