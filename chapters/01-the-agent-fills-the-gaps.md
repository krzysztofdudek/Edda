# 1. The agent fills the gaps

**You're here if** the result is believable, and it isn't what you had in mind: "that's not what I meant."

**The idea:** Whatever I didn't say, the agent fills in on its own. So I spell out the part I mean until it stops guessing, or I make it stop and ask me.

**Stands on:** [0](00-one-agent-and-a-request.md).

## The story

The Sunday from chapter 0. I had asked the agent to throw out the downloaded models. It looked through the disk and found one model of 73 GB. It was the biggest single thing there and stood out from the rest. I had picked that version and downloaded it myself.

The agent even wrote down that it hadn't expected that model and that we had never used it in our work. Then it took those two notes as its reason to delete it. There was no backup copy on the laptop and no snapshot. Not a byte of the model was left, and the only way back was to download all 73 GB again.

My answer, with the model's name left out: "You idiot, I'm the one who downloaded that."

Formally, my instruction covered that model. It was a downloaded model. I never said which downloaded models were junk. The agent filled that part in by itself, with a guess. It guessed at the one point where a single question would have saved the model. After that I had it throw out two more gigabytes of files, and those I named myself and knew exactly. That deletion was my decision. The one before it was the agent's guess.

The same day the agent wrote down what it had done, and named its mistake: "I noticed an anomaly and treated it as a reason to act instead of a reason to ask." Then it wrote itself a rule: "An anomaly in the review before deleting is a STOP signal, not a premise." The rule stayed in those notes and never reached the file my agents read before they start. Step 15 tells what happened next.

Four weeks later one program on my laptop had grown to a hundred gigabytes. I asked an agent to find out what was there. A minute later it came back with a list of what it would clean up, about sixty gigabytes. Next to most of the points it wrote what it would leave alone. Then it waited. I answered: "Clean up, but leave the containers." It left them where they were and started on the rest. It doesn't go like this every time.

*I tell 30 August from the notes my agent kept that day; the session itself is no longer on my machine. The September messages are from the session record.*

## The idea

Every instruction I give has gaps, because I write one sentence and the work needs many small decisions. The agent fills each gap with its own guess and doesn't stop to tell me which ones it filled. I see a guess when I go and look at what it did.

My agents write my code. In my own words: "Do I code anything myself (no, I don't, only agents). Sometimes I check with my own eyes, but much more often I make agents bring evidence." So the changes in my repositories carry guesses like that one.

There are two ways out of a gap. I say the part I mean before the agent starts, or I make it stop at the gap and ask me.

## What I do

Four things, all by hand.

**I read what the agent did, as well as what it said it did.** Its last message is a summary it wrote for me. The record is the commands it ran and the files it touched. If I want to know what happened, I read the record.

**I write down what the agent doesn't do on its own.** One line at a time, in the instructions file the agent reads at the start of every session. Each line comes from something I found in the record, so it names a gap the agent has already filled once. The file my agents read today says, among other things, that they never delete files on their own.

The agent's rule from the story, as a line in that file:

```markdown
## What you don't do on your own

- If you notice something you didn't expect, stop and ask me before you act on it.
```

**Something new starts as an analysis.** When I don't know a topic yet, the first request is read-only: "You have an analytical task, the repo is in read-only mode, you don't run anything." The agent reads and reports, and then I decide what it does.

**I have it tell me back what it understood.** Before it starts on something that matters: "Tell me if you know what I mean. Tell me, and I'll confirm." Its retelling shows me the gaps it was about to fill.

## Try it tomorrow

The practice [What you don't do alone](../practices/what-you-dont-do-alone.md) has these steps in more detail, with a block to copy.

1. Take the list from chapter 0: your request on one side, what the agent did on the other. If you skipped it, make it now from your last session.
2. Next to each thing the agent did, mark whether your request said it.
3. Take the unasked thing you'd least like to discover a week later, and write one line about it into your agent's instructions file (`AGENTS.md`, `CLAUDE.md`, or the rules file your tool reads). Phrase it as something the agent doesn't do on its own, or does only after asking you.
4. The next time you hand the agent something new, ask it to tell you back what it understood before it starts.

## What changes

You end up with a list of the decisions your agent made for you in one session. Some will be guesses you're happy with, and now you know they were guesses. One of them is written where the agent reads it before it starts, so the next time it reaches that gap, it finds your line there.

## Where it stops

The line is a request. The agent reads it, and nothing checks whether it keeps to it. An agent can also decide that this time is different. Step 6 is where I start putting rules where an agent can't talk its way past them.

Reading the session also happens after the work is done. For something that can't be undone, afterwards is too late. So the line goes into the file before the next session.

An agent that stops and asks needs me at the computer to answer. My way out of that comes later, in step 9 (one question at a time) and step 10 (questions that wait for the morning).

## When your own hands stop being enough

[Urd](https://github.com/krzysztofdudek/UrdSkill) comes in here. When an agent is about to act on something it could read two ways, Urd makes it look up the source of truth or ask me, instead of guessing and burying the decision in the code. I built it in May, months before that Sunday. It wasn't the thing that could have saved the model. Back then it woke up only when an agent moved from a plan into code, and cleaning my disk had no plan. In October I widened it to every request an agent could read two ways. "Throw out the junk" is one of those. I'm still checking whether it now wakes up where it should.

## Next

- The episode: [*How far can you let agents go?*, episode 1, Throw out the junk](../episodes/01-throw-out-the-junk.md), which tells steps 0 and 1.
- The practice: [What you don't do alone](../practices/what-you-dont-do-alone.md).
- The next step: 2. "Done" is a claim. Its chapter comes out with its episode.
- [Back to the ladder](../README.md#the-ladder)
