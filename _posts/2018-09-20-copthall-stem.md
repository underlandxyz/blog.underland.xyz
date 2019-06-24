---
layout: post
title:  Working with Copthall School to bring their STEM Programme to life.
date:   2018-09-20 00:00:00 +0000
author: Kevin Lewis
---

Back in February, we had a meeting with one of my old teachers about a project they were working on at their current school and if we’d be able to help. [Copthall School](https://twitter.com/copthall_school) is a girl’s secondary school and sixth form (11–18) in London, where Poonam is heading up a new STEM Scholars initiative starting in October.

The aim of the programme is to give students the skills to enrich their STEM careers. This means they’ll learn how to give good talks, run workshops, and write code. With this project aiming to address the fact that only 25% of tech sector jobs being filled by women, and equipping girls as young as 11 with critical digital skills, we were super keen to get involved.

![Stats around women in tech](/assets/posts/wit-stats.jpg)

At our first meeting, the requirements were as loose as ‘a platform to help us run the programme and take some of the heavy lifting off of us’. We had lots of ideas, but ultimately inspired by one of the past formats for [Joe Nash’s](https://twitter.com/jna_sh) GitHub Campus Experts programme, we decided on the following approach:

- Each year, students get a choice of assignments to choose from — some are mandatory, some are optional (with a minimum number of optional badges required).
- Students can complete these assignments, motivated by badges which will be visible on their profile once complete.
- Moderators can review work, and then go on to approve it or request changes, ultimately awarding a badge.

![Screenshot of the Copthall STEM platform](/assets/posts/copthall-stem.png)

## Why badges?

One thing I noticed from the Campus Experts programme back when it had this format was that many students didn’t just stop at the bare minimum. Motivated not only by additional skills, but also badges on their profile, they often went above and beyond to complete more modules.

We’ve also been following Mozilla Open Badges for a while, and did some research into the their function while designing this project. They gamify learning and motivate students to participate, collaborate and be recognised for their achievements. For this platform, implementing Open Badges was a little out of scope, but hopefully the functions of our platform mimic closely that of OB.

![Copthall students in a science lesson](/assets/posts/copthall-science.png)

## For the nerds

This was also an interesting project for [Wilson](https://twitter.com/stdlibdoh) and I to work on from a technical standpoint. In the past, we’ve built quite large applications with Flask/Django and Sinatra/Rails.

With the affordance of time, we tried to change things up a bit and go from building monolithic applications to two separate applications for the API and client.

Wilson built the API with Flask and learnt lots about CORS (and by learnt I mean he routinely shouted at his code to just work), and I built my first client work using Vue.js (which has some interesting nuances but overall was very fun to write). Working in this way led to much less dependence on each other to get things done, and it has helped establish our working pattern for future projects.

## Training matters

We seem to have built a platform which is quite easily used (based on the fact that within a couple of days of handover, Poonam was already filling it up with badges), however we had to design our training materials for the lowest common denominator.

While we initially planned on going in to deliver some face-to-face training, we would rather provide materials which can be rolled out continuously without there being a need for our time (or budget to pay for it). We landed on a series of short screencasts in a documentation packet which we’ll host online indefinitely. We’ll report back on how these are received!

## Start small and prove worth

There were so many ways we could have further built on this project, but we decided to start with a fairly small, limited scope to test our hypotheses about the platform’s purpose and usefulness. The first year should hopefully show us what works well, and what needs work (not just at a high-level, but also how we can automate more granular admin).