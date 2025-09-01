# GitHub Project Management Guide

> Languages: [English](README.md) | [繁體中文](README-zh-TW.md) | [简体中文](README-zh-CN.md)


## Day 1: The starting point of an open-source project — Why open source? Setting goals and vision

I’m Wei Lin. I currently maintain several .NET-related utilities on GitHub, such as MiniExcel, MiniWord, OpenAiTx, Dapper-Guide, PocoClassGenerator, and HtmlTableHelper. Over time, they’ve accumulated over 4,000 stars, and package downloads have surpassed 8 million.

In these past few years, I’ve gone from being a developer who only wrote code to gradually learning how to be a project maintainer, a community responder, a documentation writer, and even a psychological shock absorber (lol). I’ve stepped on many landmines and gathered some lessons learned—shared here for reference. This is the first article in the series. I want to begin with the most fundamental questions: Why do you want to do open source? What are your goals?

### Why open source? Because “I think it’s cool.”

I built MiniExcel because when I was processing a large number of Excel files, I found that the existing .NET packages all required loading the entire file into memory, which often led to OutOfMemory. I wanted a streaming solution that could “read while processing.” I couldn’t find one that fit, so I wrote it myself.

So my first suggestion is: when you do open source, start with something you think is “cool, fun, and satisfying.” Don’t start by thinking about changing the world, getting adopted by big companies, or making the front page of Hacker News. That kind of motivation doesn’t last. What really sustains you is the inner drive that says, “Whoa, adding this feature makes me super happy.”

Don’t expect to make money. Most people are “powered by love.” 99.9% of open-source projects won’t bring direct income.

You might occasionally receive small GitHub Sponsors donations or someone might buy you a coffee, but that’s more a gesture than a business model. For my own projects, I’ve received about 328 USD so far. If you start open source for the money, you’ll likely be disappointed.

But that doesn’t mean it has no value. Open source has given me improved technical ability, accumulated influence, opportunities to connect with developers around the world, and even new possibilities at work. In the long run, these “intangible returns” might be more important than money.

### Personal advice: learn first, then build — “Find a project you like and study it deeply.”

Before you roll up your sleeves to build your own project, I strongly recommend “being a student” first. Pick an open-source project you admire. Spend time reading its source code, browsing its issue discussions, and understanding its design philosophy.

That’s exactly what I did. Back then, to understand ORM best practices in .NET, I spent a full 30 days reading through Stack Overflow’s Dapper project end to end. From SQL generation logic, to dynamic compilation, to performance optimization, to its testing strategy and processes—I took detailed notes.

I later organized those notes into a document, which became today’s Dapper-Guide. I didn’t expect it would help others curious about the same things—and it made me see more clearly what a “mature open-source project” looks like.

So, don’t rush to reinvent the wheel. First learn how others build wheels—you’ll avoid many detours.

### Community is important, but don’t let it consume you.

One of the most charming aspects of open source is collaborating with people around the world. But the flip side is: the community can take a lot without necessarily giving back.

You may receive baffling issues like “Why can’t you implement database features?” or “It’s been three days and you haven’t replied—are you not maintaining this seriously?” Some people talk like they’re giving orders, totally overlooking that you contribute for free.

At those times, my mindset is: learn to “not engage” and protect your energy.

Open source isn’t an obligation. You’re not responsible for responding to everyone. My current principle is: when I have inspiration, motivation, and time, I’ll update; if not, I’ll leave it. The project is my creation—not someone else’s chore.

Also remember: don’t let open source affect your family, job, or life. No matter how passionate you are, once it becomes pressure, it changes its nature.

### Technical tip: “Start small and build a clear differentiator.”

Many newcomers want to do open source and immediately aim to build an “all-in-one” tool with big, comprehensive features—only to abandon it halfway.

My advice: “Don’t chase big—chase clever.”

Take MiniExcel as an example. Its core value is just one thing: support streaming read/write for Excel without blowing up memory. Just that one small point—but it solves a real pain point for specific scenarios, and that gives it a reason to exist.

You don’t need to build another “Excel NPOI.” You only need to build something that’s “better than existing solutions in certain scenarios.”

Find that “differentiator,” then make it good enough, stable enough, and simple enough.

### Finally: Open source is a long-term dialogue with yourself.

Looking back over these years, I’ve gone from being an engineer who only wrote business logic to a developer who can independently design, release, and maintain multiple packages. This process—rather than “contributing to the community”—has been a training of myself: writing better code, producing clearer docs, communicating with more patience, and responding to criticism more rationally.

Open source ultimately isn’t for others—it’s to become the kind of developer you want to be.

So if you’re considering starting an open-source project, don’t overthink it. Ask yourself:

- Does this make me happy to work on?
- Does it solve a real problem?
- Can I accept that it might never get popular?

If the answers are yes, then go for it.

