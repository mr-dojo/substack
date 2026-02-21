# It's Just Folders of Text Files

*Carlo Costantino | February 21, 2026*

I spent five articles describing a system I was building. Context as programming. Exporting for other AIs. Repos as personal context containers. Each piece pointed at something bigger without showing the whole thing.

I finished building it this week and here's what it actually is.

A few folders, a bunch of text files, and an AI that reads them before it talks to me.

That's it.

## What I Built

A repository on my machine. The repo has this structure:

```
/soul
/context
/drafts
AGENTS.md
README.md
INDEX.md
```

I used GitHub because I wanted version tracking. You don't need GitHub. A Google Drive folder works. So does Dropbox, OneDrive, iCloud, or a local directory. Anything a connected AI can read.

README.md is for humans, it describes what this is. Any AI that lands here cold reads it first and has orientation immediately. AGENTS.md is the behavioral contract: what to read at session start, what the agent can and can't do, how to name files it creates (if it can). It can be a .txt file, a Google Doc, a Word doc, a PDF. Doesn't matter. Just a file an AI can open that tells it how to behave.

Every major AI that connects to external folders reads something like AGENTS.md natively. Claude, ChatGPT, Gemini. Point any of them at this folder structure and they know what to do.

The agent reads /soul at the start of every session. Always present, not just retrieved when relevant. Then it reads the index, finds what's active in /context and /drafts, pulls in what matters for the conversation.

I talk to mine through Telegram via OpenClaw running in Docker. But that's my setup. The same structure works with ChatGPT connected to Google Drive, Claude connected to a local folder, or any AI that can read files you control.

Most companies already collect and use my data, why wouldn't I?

## The Rename That Changed How I Think

I called the main folder /knowledge for months. Then I changed it to /context and something clicked.

Knowledge implies a library. Passive. Shelves of things I've learned. Context implies something oriented toward use. Ready. Pointing at the next task.

The rename didn't change any files. It changed how I think about curation. I'm not building an archive. I'm building context. There's a difference in what I keep, what I cut, and how I structure what stays.

## The Soul Folder

This is the part I didn't expect to matter as much as it does.

/soul holds who I am underneath the work. My writing principles. My values. The doctrine I've built through experience. My artistic lineage. The Costantino family approach to craft that goes back five generations.

Nothing lands in /soul by accident. I ask one question before placing anything there: did this inform me, or did it form me? Information goes to /context. Formation goes to /soul.

The agent reads soul every session because it's not context. It's character. A Notion database doesn't have a soul. Mine does. An agent that reads it before answering is working in my service rather than just responding to my queries.

AGENTS.md makes this happen. One line in the behavioral contract: read /soul before every session. The whole system depends on that instruction existing somewhere the agent actually reads.

## How I Actually Use It

A conversation produces something worth keeping. I ask the agent to capture it. It creates a new file in /context with a date prefix, fills in a short summary block, writes what was learned or decided.

I review the file. I commit it. It's part of my context base.

Next conversation on the same topic, the agent reads the index, finds the entry, pulls it in. I don't re-explain. I continue from where I left off.

I've been doing this for 6 weeks. My context folder has 47 files. I've deleted 12. The ones I deleted were stale, superseded, or just wrong. Stale context is worse than no context. I prune deliberately.

The soul folder has 6 files. It hasn't lost any.

## The Compounding Effect

Week 1, my context folder had 12 files. Useful, but not dramatically different from a cold start.

Month 2, it has 47 files with 12 pruned. The agent surfaces connections I forgot I made. A decision from 5 weeks ago is relevant to something I'm working on today. I didn't have to remember it. The index found it.

I expect month 6 to be qualitatively different. Not because the folder is bigger. Because what remains is dense and accurate. The pruning is doing as much work as the adding.

## What This Actually Is

Most people will read this and think: smarter chatbot. Better answers because the AI knows me. That's real, but it's the small version.

The bigger version is what happens when the agent has agency. Not just answering. Acting.

Tools like OpenClaw can connect to your calendar, your files, your email, external APIs. When an agent with agency reads your soul folder before it does anything, something changes. It's not executing a generic task. It's executing your task, filtered through your values, in your voice, consistent with decisions you've already made and documented.

I ask mine to draft something. It doesn't write generic content and wait for edits. It reads my writing principles from /soul, checks /context for related decisions I've already made, looks at /drafts for the threads I'm actively developing. Then it drafts. The output lands close enough that I'm editing, not rewriting.

People are already running agents that act without being asked. One developer's OpenClaw negotiated $4,200 off a car purchase by scraping dealer inventories and playing them against each other over email while he slept. Another's agent read a rejected insurance claim, drafted a rebuttal citing policy language, and sent it unprompted. Lemonade reopened the case.

Both of those agents were acting. The difference between an agent that acts well and one that acts wrong is context. Specifically: does it know enough about you to make decisions you'd actually make?

That's what the folder structure is for. Not memory. Ground truth.

Without it, an agent with agency is a liability. It acts confidently in the wrong direction. With a soul folder that defines character and a context folder that carries history, it acts in your service.

That's what I'm building. Not a productivity tool. An AI that knows me well enough to act for me.

I'll keep writing about what happens when it does.

## What to Build First

Create a folder. Anywhere. Google Drive, your desktop, a GitHub repo.

Inside it: a soul folder, a context folder, a drafts folder. A README that describes who you are. An AGENTS file that tells any AI how to behave in this folder: read soul first, create files in context, don't delete anything.

Connect any AI that supports external folders. ChatGPT with Google Drive. Claude with a shared folder. Whatever you already use.

Send it your first message. Ask it to read the folder and introduce itself back to you.

Watch it orient.

That's the whole system. Everything else is iteration.

It's just folders of text files.

---

*This structure is CC0. Use it, change it, build on it.*

*Co-authored with Claude Sonnet 4.6*
