---
layout: post
title: Running New Relic's Ignite Program, Part 3 - Placement and Followup
---

This is the third and final post in a series on running New Relic's Ignite program. In this article, I'll be covering the final steps of an engineer's journey through the program and discussing some of the organizational aspects of a program like this. If you aren't already familiar with Ignite, you may want to start with [Part 1, about hiring](https://djspinmonkey.github.io/2023/07/10/ignite-hiring/) or [Part 2, about onboarding and rotations](https://djspinmonkey.github.io/2023/07/25/ignite-onboarding-and-rotations/).

## Placement

One of the last steps of Ignite for an engineer is team placement, but it's one of the first things to figure out as you're designing a hiring program. The main things to consider are how you'll be handling the budgeting, and what the cadence of hiring and placement will be. These are closely related topics, and you'll need to work closely with engineering leadership and other areas of your company as you consider them.

### Budgeting

This process is probably going to be very specific to each company, and may be somewhat dependent on how headcount is handled by Finance or other departments, so I won't try to provide a one-size-fits-all answer here. Some possibilities include:

  * No special budgeting or consideration. You will just need to find open positions for your engineers when the time comes. I do not recommend this approach. In fact, I mention it only so that I can specifically not recommend it.
  * Schedule cohorts to wrap up at the same time that a lot of appropriately leveled positions come open. This might be an option if your company has a predictable schedule for such things.
  * Assign teams headcount that is specifically earmarked for folks who have come through your program.
  * Keep a separate headcount budget for engineers coming through your program, and transfer some of that budget to an engineer's new team as they're placed.

The last option takes the most special handling, but has a lot of advantages if you're able to arrange it. By deferring the choice of which teams to place the engineers on, you allow the company to react to changing needs and circumstances, and you also allow the new engineers to explore different possibilities and discover what they're most excited to work on. In order to maintain some control of headcount allocation, it can be helpful to coordinate your rotation schedule with leadership, so that you're working with the teams they'd most like to see receiving new engineers, but there's a big upside to letting a little bit of that control go. The more flexibility you're able to maintain for placements, the higher the likelihood of finding a great team fit, which ultimately leads to stronger, more motivated teams and engineers doing work they love.

Another great feature of the "separate headcount" approach is the way it changes the dynamic between the engineers and their new managers. If you're just hoping to find open positions, that will often mean a manager has to decide between hiring a mid (or even senior) level engineer versus accepting an entry level engineer from your program. Some folks will be willing to do that, especially after the caliber of the engineers coming through becomes clear, but it can be a big ask before you've established a proven track record. On the other hand, even though at a high level the budgeting works out the same, offering an Ignite engineer as "extra" feels very different for a manager. Now you're bringing them a much needed resource, and they are thrilled their team was fortunate enough to receive this wonderful new engineer! Good feelings abound, and everybody is happy about how things have worked out.

However you decide to coordinate your budgets, make sure you have all the details worked out with Engineering leadership, Finance, and HR in the design phase of your program, well before anything is actually up and running. It's important that everybody is on board with the plan for budgeting before you're actually hiring people.

### Cadence

There are many options for how the timing of hires and placement could work, and to some extent it will depend on how you handle the budgeting. This was one of the major areas of experimentation over the years for Ignite, and while any of these can be made to work, some make it easier than others.

#### Fixed Cohorts

At first, Ignite had fixed duration cohorts. Everybody in a cohort was hired on the same day, and then at the end, they were all placed on teams on the same day. This was... ok. People generally ended up on teams that they were relatively happy with, but it was a stressful experience for everybody involved as the big day approached. Engineers were worried about what would happen if they didn't find a team in time, and it was a lot of frantic running around and trying to line things up on my part. We missed out on some great placements just because the timing didn't match up.

We also found that there wasn't any single "right" amount of time for an engineer to be in the program. We tried ranges from two to six months. At the short end, there were people who felt rushed and ended up settling for a "good enough" team. At the long end, sometimes folks _would_ find that perfect team, but then had to wait months before they could actually join, which also felt bad.

That said, there were advantages. By knowing when a given group would be wrapped up, we could be very intentional about scheduling time to retrospect and iterate on the program. We could also keep the hiring phase and the rotation phase separate, which was helpful early on. With more experience, it wasn't a problem to do both at once, but it would have been a challenge initially.

#### Flexible Cohorts

I didn't try this approach, personally, but you could keep the hiring and rotation phases separate while avoiding the stressful fire drill at the end of a fixed cohort by introducing some flexibility into placement dates. In this model, you might decide to hire a group every four months, and allow ASEs to stay in the program anywhere from two to three months. That would give you one month guaranteed between cohorts, which is about how long it takes to run a full hiring cycle. It would also give you a fixed time to reflect and iterate on the program's structure and processes.

This might be a good tactic to use at first, to help ease an organization into a new early career hiring program. Eventually, though, I would still recommend moving to a hiring pool if your volume supports it.

#### Hiring Pool

Ultimately, Ignite moved to a continuous "pool" model. We had a regular quarterly hiring cadence, where we would hire three to five engineers at a time. Engineers could stay in the program anywhere from two to six months, which meant cohorts would usually overlap fluidly. There were outliers at either end, but most folks opted to join a team around the three month mark. Consequently, the number of people in the program at any given time varied, but was usually similar to the size of the quarterly hiring group. There were almost always engineers available for placement with this model, and the more experienced members could help the new folks.

In combination with the flexible budgeting mentioned earlier, this gave us the best possible results for finding perfect team fits. It did make some aspects less predictable, but that didn't end up causing any problems in practice. For early career engineering hiring, this is the approach I would recommend.

One concern I could imagine being raised about this model is expense. Engineers cost a lot of money, and you wouldn't want to potentially hire and pay somebody for six months before they started contributing. That's part of why Ignite always worked on real tickets and projects, doing actual work that teams were generally very excited to see getting done. That also happens to be the best way to learn engineering and see what it would be like to work on a team! So, while you could look at this period as an investment in the company's future engineering bench strength, Ignite engineers were also contributing real value as soon as they were through the initial onboarding, just like any other engineer.

As a side note, the trade-offs work out a bit differently for more senior levels. When we applied the Ignite model of hiring to those roles, we found that those engineers didn't get the same benefits from going through more teams. They usually already know what kind of engineering they want to do, and have seen different team processes and workflows. We still did a few rotations, since it was valuable to meet prospective team mates and get a bit of hands-on experience with related systems, but it was fixed at three rotations.

## Assigning Technical Specialist Mentors

Once an Ignite engineer was matched with their new team, we found them a technical specialist mentor. A technical specialist mentor is somebody who specializes in the specific stack the ASE will be using. For example, an ASE joining a team related to data ingest might need a mentor skilled in Java, Kafka, concurrency, and high throughput environments. An ASE joining a frontend team might need a mentor with React, CSS, and GraphQL experience. To find a mentor, I consulted my list of potential mentors, and found somebody on a team working in a similar area, or that I knew had those skills. Then, I went through the same steps as for assigning a generalist mentor (check with the potential mentor's manager, then the mentor themself, then make the introduction).

## Team Onboarding

The final phase of the Ignite program for an engineer was the Team Onboarding phase. During this phase, ASEs focused on the specific skills they would need to hit the ground running on their new team, and started learning the processes and systems of the team in more detail. Importantly, they were not officially on the team yet, and were not expected to pick up tickets or be productive at this point! This was a period for learning.

### Team Onboarding Kickoff Meeting

First, I scheduled a kickoff meeting with the ASE, the manager of their target team, their technical specialist mentor, and optionally a tech lead or senior engineer from the target team. I would let everybody know that we'd be collecting areas of study and specific study resources (books, conference talks, papers, blog posts, etc) for the ASE, so they could start thinking about these or collecting them ahead of time. At the kickoff, the goal was to create a personalized study plan for the ASE.

We started by creating a large list of all the topics, technologies, and areas of knowledge that would be valuable to know on that team, as well as resources to help learn about those topics. It was important to emphasize that there was no expectation that the ASE would master all of this in two weeks! Usually, these were comprehensive enough that by the time somebody was well versed in every single topic on the list, they would probably be a lead engineer. The purpose of this list was to outline the shape of what the team worked on and establish the topics that the new engineer should be particularly keeping an eye out for. Then, from the long list, we pulled out a small number of specific things to look into for the next two weeks. These might be things that were especially foundational to the team, or areas that the team knew they'd be working on soon. It also depended on what the ASE was already familiar with. For example, an engineer joining a team that did high throughput streaming data processing might have a short list with just Java concurrency and the Flink framework -- that's plenty to learn in two weeks!

The other thing to work out in this meeting was the working agreements for the onboarding period. I started with a few suggested agreements, but they could be modified or replaced wholesale if the team or engineer preferred. I found that about a 50/50 split between study time and working with the team was effective, and pairing with team members was a particularly valuable exercise during this period. Other good onboarding activities included meeting with the team's stakeholders, joining all ongoing meetings and team rituals, and reviewing (or writing) documentation for the team's systems.

### Other Team Onboarding Considerations

When we were working in person, I tried to arrange for each ASE to go ahead and start sitting with their target team, though of course that wasn't a consideration once we went remote. The basic principle that we wanted to start integrating the ASE into the team's daily schedules and social fabric as much as possible still applied, though.

Halfway through the onboarding period, I would check in with the manager and the engineer to see how things are going, and ask whether they thought there should be any adjustments for the second half. This was very informal, just a quick ping on Slack, and usually they just responded with "Yep, going great!" Occasionally, though, there would be something to adjust or something they realized they hadn't gotten to and should schedule for the second week.

## After Placement

At the end of the onboarding phase, we officially placed the Associate Software Engineer on their new long term team! They were now ready to continue with their career in the company, but our work in the program was not done yet.

### Handoff

There were a few things to do as the engineer transferred to their new team. In Ignite, this was always accompanied by a promotion to Software Engineer 1 in recognition of their new skills and knowledge of the company. We also supplied a packet of resources to the manager to help them with the specific needs of managing an early career engineer.

### Check-ins

A little while after an engineer had been placed, we would check in with them and see how things are going. This was an opportunity for informal feedback on the Ignite process, and was a good time to provide any additional support that the new engineer or their manager could use, such as help finding a new mentor if their existing ones didn't work out, or finding opportunities for additional training if there were particular areas where their skills could use some additional sharpening. Initially, I liked to check in at two weeks, a month, and two months. Once we had the program flow dialed in a bit more, though, we found that a single checkin was generally sufficient.

### Followup Surveys

In addition to the informal feedback from the check-ins, we collected more formalized feedback in the form of surveys sent to the participants of the program and their new managers. These were sent a month after the final placement, so that folks had had a chance to settle in a bit and get a feel for the new team and how things were going, but the experience of joining was still fresh. In addition to the usual sorts of questions ("Would you recommend this program to a friend?", etc), we also asked about areas where additional training or ramp-up would have been helpful, or things they wished they'd known before joining the team. We then took this feedback and use it to iterate on the program design for the next cohort.

In the early days of the program, this feedback was indispensable, and it led to some valuable improvements. Over time, it generally became much more uniformly positive and there were fewer suggestions or issues to address.

### Reviews

Depending on when in the review cycle the engineer transferred to their new team, there were a few different ways to handle this. If they joined near the end of a cycle, then we just had the Ignite manager conduct the review for their time in Ignite, and the new team manager would have them for a full review cycle and conduct the next one. If they joined more toward the middle of the cycle, we might conduct a joint review with both managers. If they spent most of the cycle with their new manager, of course, that manager handled the review as normal.

## Reflection and Iteration

From time to time, it was important to review feedback, consult all the notes I'd been taking, and revise and iterate on the program. It would never be perfect, and even if it were, as circumstances and people changed over time, there would still be changes to be made. I liked to do this on a roughly quarterly basis, and would think about questions like these:

  * What went poorly? Why?
  * Of course, how can you improve those situations next time?
  * Do they hint at any other pitfalls you haven't run into yet?
  * What went well? Why?
  * Are there lessons from those things that could be applied elsewhere?
  * What underlying principles or systems have been suggested by all this?
  * What experiments are worth trying going forward?

This article is about how we ran the Ignite program, of course, but this process of ongoing reflection and iteration is broadly applicable to most human endeavors.

## Conclusion

Of all the things I've worked on over the course of my career, both as an engineer and as an engineering leader, Ignite was easily the most rewarding. But it wasn't just about personal fulfillment. This program also bolstered the bench strength of New Relic's engineering organization with a caliber of talent that's impossible to consistently hire at other levels. Ignite was about creating pathways into tech for underrepresented groups, yes, and also addressing the inequities of the tech industry. But it was also about building engineering teams at New Relic for the future, looking down the road and seeing the incredible value that these engineers would bring for years to come. It was one of the rare cases where doing the best thing for society lined up with doing the best thing for the success of the company. Choose whatever reasons are compelling for you. Personally, there's nothing I'd rather be doing with my life.
