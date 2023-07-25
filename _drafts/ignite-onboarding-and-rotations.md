---
layout: post
title: Running New Relic's Ignite Program, Part 2 - Onboarding and Rotations
---

This is part 2 of a series on running New Relic's Ignite program. First, I'll go over the onboarding process for new hires. Then, I'll describe how we ran the various team rotations and activities that comprised the bulk of an engineer's time in the program. If you haven't read [Part 1, about hiring](https://djspinmonkey.github.io/2023/07/10/ignite-hiring/), you may want to start there. This article will be somewhat less broadly applicable than the post on hiring, but some of this material could still be applied generally.

## Onboarding Phase

Once a new group of Ignite engineers started, they were officially Associate Software Engineers (or ASEs). First on the agenda for new ASEs was a two week onboarding period, during which they learned the basics of interacting with New Relic's systems and teams. We covered things like Git, JIRA, standups, code reviews, retros, and so on. This is also when the new cohort went through our engineering-wide onboarding process.

### Kickoff

On their first day, I held a kickoff meeting with the new group. In this meeting, the new cohort met each other for the first time, and I laid out the overall structure of the Ignite program. This was also a chance to start building a rapport with the new engineers and establish an environment of psychological safety.

### Working Agreements

After the kickoff, we held a session with all Ignite engineers (both the new group and anybody still in the program from the previous group) to establish our working agreements. There was one nonnegotiable agreement, which was "We will be respectful and considerate of one another." We also established agreements around hours, group working styles, meeting conventions, and so on. This was a very collaborative process! There were prompts for specific areas that needed to be agreed on, but folks were also encouraged to bring their own suggestions to cover anything that was important for them personally to create a productive and welcoming work environment.

We went through this process from scratch every time new engineers joined the team, and I generally advise doing something similar on any team when somebody joins. Having worked both with functional programming languages and as a manager, one of my favorite sayings is "teams are immutable data structures." That is to say, any time you add somebody to a team, you now have a totally new team. (It's very funny if you happen to have that specific overlap of backgrounds! Well, I think so, anyway.)

### Sample Project

The rest of the onboarding time was spent working on the sample project, which was a simplified version of a query builder for our proprietary internal database. We would build a few different versions of the project that each interacted with New Relic's internal systems and tools in different ways. For instance, one version would be a pure JavaScript application using the frontend platform built into the product, another would be a full Rails or Java service with an integrated frontend and backend, and so on. One goal of this was to gain some basic familiarity with our hosting infrastructure, build and deploy pipelines, and internal APIs. We also wanted our new engineers to learn some of the basics of interacting with code as a software engineer, such as how to scope pull requests, how to do effective code review, trying out different collaboration styles, and just generally seeing what it's like to work on a team day-to-day.

As folks got started on the project, we had experts from relevant teams come introduce our internal systems, and they would also follow up later with a Q&A session after folks had been working on the project for a while. This was partially to teach the new folks about the systems, of course, but it was also a way to start forming social connections and meeting friendly faces the ASEs could reach out to for help later. Those kinds of social bonds and a general sense of community make cross-team collaboration run much more smoothly, so fostering connections like this was a major theme of the Ignite program. Also, people are just happier if they feel a sense of belonging with the folks they work with. Like many things in Ignite, you can view this through the lens of successful business practices that increase productivity, or as a way of making people's lives better -- it serves both goals.

### Assigning Generalist Mentors

During the onboarding period, we also found mentors for all of our Ignite engineers. Part of the purpose of Ignite was for new developers to try a lot of different kinds of software engineering before selecting a long term team, so we didn't try to focus on any particular technology with these initial mentors. Instead, the purpose was to match them with somebody who could provide another perspective on how to succeed as an early career software engineer at New Relic. They could often answer questions about the particular challenges faced in that role or act as a sounding board.

Given that, early to mid career engineers were ideal. If the mentee was a member of an underrepresented group, somebody with a similar background could also be helpful. Both of these considerations were to make it more likely that the mentor might be familiar with some of the specific challenges and circumstances the mentee would face.  Previous Ignite engineers made great generalist mentors!

To find potential generalist mentors, I kept a running list of everybody who had mentioned being interested in mentoring. After the program had been running a few years, folks would often approach me about this! If you don't have such a list, broadcasting in your company's Slack channels (or equivalent) asking for folks who are interested in being mentors might be a good way to seed one.

Once I had identified a possible match, I would contact the potential mentor's manager before doing anything else. This was to make sure that they agreed it would be a good idea, and would fit into that person's schedule and current workload. The expected time commitment was about half an hour a week, or an hour every other week.

I would then reach out to the potential mentor. I would explain the generalist mentor role and the rough expectations, and see if they were interested. If they were, I then set up an introduction with the mentee so the two could meet and see if it might be a good fit. My standard email template introduced the potential mentor and mentee to each other and laid out some guidelines and advice for a successful mentoring relationship. If, after meeting, the Ignite engineer and potential mentor decided not to move forward with the mentorship for any reason, that was totally fine, and I was happy to find an alternate mentor. This happened a few times, and it was no problem.

As a side note, after running Ignite for a few years, existing employees started regularly asking for help finding mentors, too. So, we expanded this aspect of Ignite into a broader "Mentorship Matchups" program that was available to everybody.

## Team Rotation Phase

After onboarding, engineers entered the team rotation phase, which comprised the bulk of an ASE's time in the program. During this phase, the cohort worked with a variety of teams throughout the company in two week engagements, learning about the systems they owned and making social connections with engineers and managers. They also had specialized presentations and learning opportunities for technologies in common use at the company, as well as more advanced software engineering topics.

### Rotations

The main thing we did during the Team Rotation Phase, of course, was rotations with teams. During a typical rotation, the full Ignite cohort worked with another team to accomplish some goal. I found that two weeks was about the right amount of time for a rotation. One week usually wasn't enough time to get up to speed and finish anything, which became frustrating for the engineers. Three weeks could be a lot to ask of the hosting team, and meant we couldn't rotate with as many teams.

Our goal was to be net positive for the hosting team's velocity, on average. Hosting a rotation took some time away from the team to work with the Ignite folks, of course, but we were also doing real work that the team actually needed. Usually, they came out a little ahead. That said, there was a fair amount of variance from team to team -- sometimes we would blow through a huge amount of work, other times we might spend days stuck in dev setup or blocked by some unforeseen obstacle. Aside from keeping an eye on our average overall impact, though, productivity wasn't the main focus during rotations. We wanted to pull our weight in the short term, but the main focus of Ignite was the long term engineering strength of the company, which we contributed to by placing brilliant, well prepared engineers on teams they were excited to join.

There were a few specific styles of engagement with Ignite that I found worked well.

  * **Full engagement**: Whatever the team was doing, the Ignite engineers jumped in and did it with them. This needed the least amount of up-front planning, but required the most time and energy from the hosting team during the engagement, and was the style most likely to reduce the team's velocity during that time. This was especially well suited to teams that did party programming or heavy pairing, but was not well suited to teams under significant time pressure. If the circumstances allowed, this is the style I found most useful to see whether a team was a good fit for any Ignite engineers, and I tried to make sure we did a good number of this style of rotation.
  * **Ticket based**: Rather than having the Ignite engineers participate in everything the team was working on, some teams opted to have them work on a pre-selected batch of tickets as a separate work stream. Before the engagement started, I would sit down with somebody from the hosting team (such as a manager, technical lead, or PM) and go through their backlog looking for tickets that would be suitable for Ignite engineers -- that is, relatively self contained items that didn't require too much specialized knowledge of the codebase overall. We aimed for at least two tickets per ASE, plus one to use as an example, and one or two stretch tickets. During the engagement, we designated an "Ignite hero" from the hosting team who was available to answer questions and pair with ASEs. The hero could also be different people on different days, if there were a lot of folks interested.  Similarly, we designated one ASE as the "shadow" each day, who worked with somebody on the hosting team instead of working on Ignite tickets.  They might follow along with the team's on-call, pair with team members on whatever they were working on, join design discussions, etc. This approach required a medium amount of up-front prep and time investment from the hosting team, and was a good middle-of-the-road option in terms of cost/benefit.  It was well suited to teams with a lot of high-value tickets in their backlog, or a lot of tickets that didn't require too much special knowledge to work on. It could be made to work for almost any team, though.
  * **Project based**: Another alternative was to complete a small project together. Before the engagement started, I would sit down with somebody from the hosting team and spec out a project for the Ignite engineers to work on. This needed to be fairly limited in scope, since there were only two weeks to work on it. It might involve spinning up a simple service, converting something old to match newer standards, upgrading a technology, or anything else suitable in scope. Once we had the specs, we would break the project down into tickets (this could also be done on the first day of the rotation, to demonstrate the process). We tried to make sure that the tickets were parallelizable, so more than one person or pair could be moving forward at the same time. Ideally, we tried to have an MVP requirement that was very simple and could almost certainly be completed, and then a number of improvements and stretch goals to go further. That way, we could definitely get to an end point and say "We did the thing!", and we'd also be sure to have enough to work on to fill the entire two weeks. Occasionally, we would do a project that wasn't for a specific team.  For example, we built a clone of the popular Donut Slack app (ours was named Danish) which ended up being used quite broadly across the company and adopted by one of our internal tooling teams. This style of rotation creates a great sense of accomplishment and allows ASEs to see the full development cycle from start to finish, so I made to sure to include at least one or two of these for every group.
  * **Solo rotation**: Once an engineer had been in the program for two months, they were eligible for solo rotations. Around this time, ASEs were generally forming ideas of the teams and technologies they were particularly interested in. So, if there was a team they really wanted to work with, but we weren't able to fit that team into the main rotation schedule, or maybe the team didn't feel up to taking on the whole group of ASEs, we could schedule them for a solo rotation with that team. They would then split off from the main group for one rotation slot and join the hosting team on their own. This was usually in "Full Engagement" style, but with only one person, we could be even more lightweight with the prep, and it was usually easier for the hosting team to fit them into their existing workflow. Solo rotations were strictly optional -- they were a tool we could use when it was useful, but plenty of folks never did solo rotations, and that was also fine.

Occasionally, managers or engineers would have an idea for a different approach they wanted to try for a rotation. I liked to be as flexible as possible in trying experimental new formats. They didn't always work out, of course -- that's the nature of experiments. I always learned from them, though, and sometimes they became valuable options for the future. That's how we came up with solo rotations, for example. Not all experiments were feasible or advisable, but even if we didn't do exactly what was proposed, we could often come up with some other option that addressed the same hopes or concerns.

Regardless of the particular style used for a given rotation, it was important that the Ignite engineers got a chance to put their hands on keyboards and do some of the team's actual day-to-day work themselves. It was tempting sometimes for a team to include ASEs in group programming or pairing sessions where they mostly just ended up "along for the ride." While it was possible to get some value from these sorts of sessions, it was generally much less useful than actually doing the work.

Teams' schedules and priorities often change, so we tried to avoid planning rotations too far in advance. At New Relic, I found that planning about 1-2 months out worked well. I would use the following criteria to choose teams for rotations.

  * Teams that work in different technical areas (front end, services, high throughput data, operations, internal tooling, etc).
  * Teams with different working styles (campfire/party programming, mostly solo, pairing, mixed, etc).
  * Teams that wanted different styles of engagements (full engagement, ticket based, project based).
  * Teams that somebody in the Ignite program had expressed a specific interest in.
  * Teams that had expressed a specific interest in working with Ignite.
  * Teams that engineering leadership had called out as good candidates to recieve an Ignite headcount.
  * Teams that owned particularly interesting products or systems.
  * Teams that owned fundamental central tooling or infrastructure that engineers were likely to interact with.
  * **Especially**, teams that would provide a supportive environment for early career engineers. Not all teams are well set up for this, perhaps due to the existing balance of experience levels, general temperament, or interest.
  * **Avoid** teams under tight deadlines. They will generally be less available to engage with ASEs, and we don't want to distract them (or even have any appearance of distracting them) from the urgent work they're doing.

### Social Events

Since we couldn't do full rotations with every team (there were many dozens by the time I left!), we also had informal social meetings with teams we weren't rotating with. Generally, I would choose these teams based on similar criteria as for rotations, though some were less relevant if we weren't actually going to be working with the team.

Once we transitioned the program to being fully remote during covid, we switched to doing online social events with our hosting team. Since we weren't able to just go out to lunch or have similar informal social gatherings, it was important to intentionally create those opportunities for non-work-related conversations and socializing.

For teams other than the hosting teams, I found it worked well to schedule these 1-2 weeks in advance, and do one every week or two. First, I would contact the manager to make sure they were open to the idea, and to find out if there were particular times or days to avoid (eg, maybe lots of folks were on PTO one week, or the team had a regular WFH day). Once I had the go-ahead from the manager, I'd create a calendar event and invite everybody on both teams.

For in-person events, just going for a walk to a nearby coffee shop was a great option. I would let the team choose the destination, and Ignite picked up the tab. I say coffee, but they could also choose to go for ice cream, hot chocolate, or any other delightful destination within walking distance. For remote events, I would offer a choice of options ahead of time, which ranged from very low key, like letting folks expense some coffee and having a Zoom chat, or they could be much more involved, such as virtual escape rooms, cooking classes, online games, and others.

During the event, I might seed some conversation about the team and their part of the company. For example, I would open with questions like "What do you spend most of your days doing?", "What's the next big thing your team is working on?", "Do you have an on-call rotation? How does that usually go?", etc. Once conversations had starting up and were going on their own, though, I didn't try to force any particular topic. It was fine for folks to chat about non-work related things.

#### Ignite Alumni Social Hour

Every time we hired a new group of folks, we would also hold a large social event and invite everybody who had ever come through the program. This was a chance for the new folks to ask questions, get advice, and see examples of all the other engineers who had been through a similar experience and landed on a long-term team. It also started forming that vital network of social connections throughout the company.

While large in-person gatherings are fine, this group quickly became too big to just drop everybody in one giant zoom call. Once the program went remote, we would generally start with a round of introductions and then split into breakout rooms. Each new ASE would be in a different room, and a group of alumni would join them. Halfway through, there was a notification to optionally shuffle rooms. This worked well for us, though eventually we were getting to the point where even the breakout rooms were large, so we might have needed to come up with a different arrangement before too much longer.

### Presentations

Like most companies, we used a variety of technologies, and had local experts on each of them. And of course, there are a wide range of core skills that are foundational to software engineering, regardless of the specific technologies being used. Experts on these topics are an invaluable resource to a program like Ignite, and in my experience, many folks are excited and eager to share their knowledge with others.

I kept a running list of topics I thought would be valuable for new engineers to learn about, and local experts on those topics who were interested in teaching. I tried to front-load some foundational presentations early on, such as reliability or how to work with our critical infrastructure. I also tried to schedule presentations around the time that those skills would be put into practice. For example, the week before a team rotation involving a lot of Kafka work was a great time for a Kafka presentation. I found that about one presentation per week was a good pace. The list of upcoming presentations and topics was shared with the Ignite engineers, and I periodically asked them if there were any other topics they'd like to see added. Some of our best recurring presentations were suggestions from folks in the program!

## Administrative Tasks and Scheduling

Here's the list of tasks I used to keep everything on track. For me, it worked well to make these repeating tasks in my todo app. We were working with different teams week to week, and wanted to cause as little disruption as possible, so we generally conformed to the existing team schedules. That meant many repeating Ignite-specific events needed to be scheduled manually each week, rather than being repeating calendar items, in order to avoid schedule conflicts.

### Every Day

  * Have a joint standup with the hosting team.
  * Make sure all Ignite engineers are clear on what they should be doing that day.
  * I also set up a daily "Office Hours" zoom call for folks to optionally drop in for pairing, code review, answering questions, dev coaching, etc. This is where having a manager with recent technical skills is important, and this was called out by some participants as one of the most valuable aspects of the program.

### Every Week

  * Hold a 1:1 with each ASE.
  * Hold an Ignite team retro for the week.
  * Verify there's a presentation scheduled for each of the next two weeks (and arrange one if needed).
  * Verify there's a social event scheduled for the following week (and arrange one if needed).

### Every Rotation

  * First thing on the first day, have a joint kickoff meeting with the Ignite engineers and the hosting team.  In this meeting, have the hosting team explain the systems they own, and then go over the plan for the rotation.
  * At the end of the rotation, have a joint demo / celebration / retro. Go over what was accomplished and discuss things to keep doing, stop doing, or adjust going forward. Sometimes we would join existing demos if the timing worked out.
  * Ensure the next two to four rotations are scheduled.
  * Have a rotation planning meeting with the manager of the next rotation.
  * Schedule all the next rotation's meetings (kickoff, retro, standups, etc) and make sure all the Ignite folks are invited to everything they should be invited to for that rotation, like Slack channels and regular team meetings.
  * Check in with the manager of the previous hosting team to get feedback on the rotation and see what they thought about any Ignite engineers potentially joining the team.

### Every Cohort

  * Schedule an onboarding period with related activities and presentations.
  * Schedule an Ignite Alumni Social Hour.
  * Check in with engineering leadership for a list of teams to either avoid or try to include in the upcoming rotation schedule.

### Continuously
  * Keep tabs on the ASEs' career goals and thoughts on various teams, and coordinate transfers and promotions as good matches come up.
  * Hiring for the next cohort. In addition to all the usual hiring manager duties, like reviewing applications and conducting screens, I also handled most of the code evaluations, trained and coordinated the interviewers, and so on.  Part 1 of this series has more details on everything involved with hiring.

## What's Next?

In the next and final post in this series, I'll discuss how we handled team placements, the process of transitioning from Ignite onto a long term team, and the followup steps that came afterward.
