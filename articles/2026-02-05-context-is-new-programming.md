# Context Is the New Programming

**Published:** February 05, 2026
**Author:** Carlo Costantino

I spent six weeks building a personal context management system. I thought I was making a productivity tool. I was actually discovering something fundamental about how software works now.

## The Problem That Started This

AI assistants are stateless. Every conversation starts from zero. You explain your preferences, your projects, your constraints. Then you close the tab. Next time? Start over.

I got tired of re-explaining myself.

So I built a simple system: save things I want remembered, retrieve them automatically when relevant. Markdown files in a folder. No database. No proprietary format. Just text that any AI can read.

The first version took a weekend. Save mode captures knowledge. Enrich mode surfaces it. Two modes, one folder, done.

Then something interesting happened.

## The Evolution Nobody Predicted

**Week 1: Static storage.** I dumped things into files. Preferences. Decisions. Facts about projects. It worked. My AI conversations got better because I could point at context instead of typing it.

**Week 2: Retrieval.** I added search. Now the AI could find relevant context without me specifying which files. Ask about code reviews? My code review preferences surface automatically.

**Week 3: Structure.** I realized retrieval quality depends on how context is organized. Raw text isn't enough. I started adding titles, summaries, themes. Descriptions of when each piece of context should surface.

**Week 4: Portability.** I was using Claude, ChatGPT, Cursor. Each one starting from scratch. The fix was obvious: store everything in Google Drive, connect all my AI tools to it. Now they all have the same context. Same knowledge base, different interfaces.

I realized I wasn't building a storage system. I was building a shared brain for all my AI relationships.

## The Industry Confirms the Pattern

While I was building this, the AI industry was fighting the same battle at planetary scale.

Google announced "Personal Intelligence." Gemini now reads your Gmail, Photos, YouTube history, search queries. Sundar Pichai called it "uniquely tailored answers." Translation: they're building a context layer over your entire digital life.

Anthropic shipped Claude Co-work. The selling point? It can read your desktop files. Everything on your machine. The power comes from context access.

OpenAI launched ChatGPT Health. Their pitch: "health information is often scattered across portals, apps, wearables, PDFs." Their solution? Pull it all into one context layer that AI can reason over.

Apple has the most context of anyone. Your iMessages. Your photos. Your location history. AirPods that hear your conversations. They have more personal data than Google in some ways. And they're playing a different game. They're waiting for models to get small enough to run locally on device. Their bet: inference becomes a commodity, and whoever owns the context wins. They might already have this figured out.

The pattern is obvious; every major AI company is racing to capture, structure, and control personal context. Context is the product.

**Memory is the moat.**

## The Constitution Moment

Then I read Anthropic's Constitution.

Here's how Claude actually works: before you ever type a message, the Constitution is already there. It's the foundation. Everything you say builds on top of it.

The Constitution is a document. A long one, explaining values, priorities, how to handle conflicts, what kind of character Claude should have. It teaches Claude what to do and why. From the document itself:

> "Most AI prompts describe behaviors without explaining reasoning. This creates brittle systems that fail in novel situations. If an AI only knows what to do, it can't reason about what to do when instructions don't apply."

This is how Anthropic programs their AI. A document that gets injected into every conversation.

Then they gave it away.

Creative Commons license. Use it however you want. No credit required. No permission needed. One of the most valuable AI companies on Earth just showed the world exactly how they shape AI behavior and said "here, take it."

Forbes covered this as a transparency play. A trust-building exercise. They missed the point entirely.

Anthropic didn't release a marketing document. They released proof of concept. Proof that the information you feed into AI shapes its behavior at deep levels. And they're confident enough in that insight to give it away for free. That's not even their secret sauce. The mechanism is non-proprietary.

## The Thesis

Here's what I now believe:

**A new layer of software development is emerging: curating context that shapes how AI understands and acts.**

Code still matters. You still need engineers building systems, writing logic, handling infrastructure. That doesn't change.

But there's now a second layer. Call it context programming. Where traditional programming writes instructions for computers to execute, context programming curates understanding for AI to reason from.

The Constitution proves this works for character and ethics. My knowledge base proves it works at the personal level. And the same mechanism works for any domain: project context, user preferences, institutional knowledge, domain expertise.

When I tell Claude to "research this document before responding," I'm doing the same thing Anthropic does with the Constitution. Shaping behavior through context.

## What This Means for Building Things

If context is the new programming, then the valuable skill is curating context.

Three implications:

1. **Context has a lifecycle.** Information gets stale. Six months from now, your notes are outdated. Your decisions have changed. Treat context like a product that requires maintenance.

2. **Context creates leverage.** The same knowledge base can power every AI tool you use. Write it once, use it everywhere. Your context compounds over time.

3. **Context creates lock-in.** Once you have a year of well-organized context, switching costs become astronomical. This is why every AI company wants to own your context layer. And why you should own it yourself.

## The Business Version

The same approach works for organizations.

Imagine: every customer interaction, every product view, every support ticket, every transaction flows into one place. You add structure: customer intent, product preferences, price sensitivity, warning signs for churn.

AI agents query this with full context. "Show me everything relevant about Customer X." "Find all customers with this buying pattern." "What's this person's history and how should we prioritize them?"

The agents become useful because they have context. The context becomes valuable because agents can use it.

This is infrastructure. The foundation that makes everything else smarter.

## Where This Goes

The race for personal context will accelerate. Google, Anthropic, OpenAI, Apple, and others will keep building context layers. Most will be proprietary. Most will lock you in.

The alternative: own your context. Files on your machine. Git for version control. Markdown for portability. Any AI can read it. You control the substrate.

I'm calling this approach "personal context sovereignty." It sounds grandiose. It's actually practical. Your context, your files, your control.

Code will always matter. But there's now a second discipline: curating the understanding that shapes how AI operates.

That discipline is just getting started.
