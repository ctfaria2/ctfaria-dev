---
title: "Thoughts: AI Augmented Development"
date: 2026-01-28
draft: false
description: "O brave new world"
tags: ["Thoughts", "Development", "AI"]
---

## O brave new world

Between my last post and now, the whole world has changed significantly. Back then we were using GitHub copilot as a glorified auto-complete and people were skeptical on whether it would have any legitimate impact. 

Today the conversation has shifted significantly. Agentic coding has taken the engineering world by storm, people are vibe coding–myself included–and the concept of not having to open an IDE has gone from fiction to a very real possibility.

I've had a lot of thoughts over the last year and a half. This post is an attempt to put them down, because between the 7-8 claude-code windows, watching the anthropomorphic agentic town experiment (read: GasTown) play out and keeping up with my 9-5, it's getting pretty full in here.

## Code is cheap

For years I've been managing my climbing session data and gym session tracking via a pretty comprehensive spreadsheet. I've always thought about how cool it would be to build an app for this, but I've never really had the motivation to dedicate the time to doing so. It's a simple problem, and a simple idea for something to automate but it's never been something I could justify doing.

Cue the agents. In ~3 hours. Claude reproduced my spreadsheet as a React Native App using Expo. It all started with a conversation about how we were going to work together. Then we talked a bit about different technology stacks. I showed Claude my spreadsheet. Claude showed me all their ideas. We had a bit of back and forth and then, once we got going, it was lightning quick.

Since then, I've expanded the app beyond the capabilities of my meager little spreadsheet. I also signed myself up as an apple developer so that I could publish preview builds to my phone for usage–a form of private distribution for now. I use this app daily and am not sure whether I will ever publish it publicly. Do I need to? The point is that code is cheap. Why would I ever spend hours tweaking a comprehensive spreadsheet again, when Claude can build me an app that is infinitely more usable?

This is the first of the significant pillars that have eroded over the last year. Code is cheaper. Code is more accessible than ever before. Agentic coding has made writing code as simple as talking in natural language. Anyone can write code, and anyone is.

## Not all code is good code

With code cheaper than ever before, we're seeing the rise of vibe-coding. The concept of detachment between the human and the code output. This great enabling of anyone and everyone to code means that we're starting to see wave after wave of new projects and ideas hit the net. The danger here is that vibe-coding often produces low-quality, risky, unmaintainable code. 

There's no thought to scalable architecture, clear design choices and proper verification. Maybe v1.0 works, but then a tweak is made for v2.0 and it breaks the v1.0 functionality, since the tests written don't actually validate the behavior, just the interfaces.

It's not to say that all vibe-coded code is bad. I believe there's a spectrum here. Some ideas/code is low-risk so the quality doesn't really matter. If it works, it works. Other changes are higher-risk and might need a little bit more rigor and quality assurance before being put out there. The term 'AI slop' is being thrown around a lot out there. I think there's going to be a few cases where we don't care about the code produced. If you're building a silly tool for private use, then does it really matter? Did we have to write tests for that spreadsheet we built? 

The same applies in a workplace setting. There's a spectrum. Not all agentic code is production-acceptable. In some cases though, who cares? Maybe the code is not the product, maybe the exploration or the solution is the product. A probe sent to reduce the time for a human to come and do it properly. 

## My preferred workflow

I like applying a Plan -> Review -> Execute -> Reflect -> Review workflow. 

First up, I engage Claude to discuss my idea. I'll tell Claude to ask me clarifying questions. If it's a new repository we'll go through setting this contract for how we work and enshrine it in a document. For example, for my app we established a `/plan-feature` command. It contained the contract for us to start working together. The output is a plan, following a checked-in template. I'd ask Claude to review the plan. I'd then review the plan. We'd agree and approve. 

A new Claude would then pick up the plan, it would check it over and start executing. Once done, it would check it over against the plan. Does it tick all the boxes? Claude would self-reflect. Anything that was missed would be added to our guidance, by Claude–maybe we need a new skill for working with x technology.

Finally, I would do a review of the pull request. For this project I'm not that strict about implementation details, so I'm checking the data structures, the tests and that the functionality matches my expectation. If I find anything that needs changing, Claude and I will figure out what we could do better next time.

I've settled on this flow because I still want rigor and validation to be part of what Claude and I produce. In my long list of experiments over the last year I've found that this cycle mirrors a healthy workflow and often leads to forward progress and accurate results. Sometimes we miss things, but those self-review steps help to catch that and we always learn from our mistakes.

## Scaling it up

At the height of my AI induced psychosis I've hit 7 or 8 parallel Claude instances firing on different projects with myself often doing something else and checking back in. I'm most excited about the tooling that is emerging to make this process smoother, specifically about the idea that my role in this process might even be replaced.

It feels like we're just scratching the surface of what's possible. Almost every day there's exciting literature being published from people pushing the front of this new wave. There's a plethora of new tooling emerging–not all of it good, but sometimes failure is important to progress–and, most importantly, there's new patterns being developed and shared. It's the most exciting time in a long time to be an engineer.

If you take one thing away from this ramble of thoughts it should be this: go out there and experiment. Code is cheap, every idea can be explored. Just be careful when it comes to security and your own or other people's data.

Onward.