---
title: Design quality assurance and the developer experience
subtitle: Building an Enterprise UI Component Library in Storybook.js
date: 2020-10-15 00:00:00
description: A design system for smoother collaboration amongst software teams and product scalability.
featured_image: quality-assurance-feature1.jpg
accent_color: '#222'
gallery_images:
  - quality-assurance-feature1.jpg
published: false
---

Upon joining my current organisation I was aware that I would be given a degree of autonomy to build a design process as I saw fit for the company.  I also knew I would be working on a large digital transformation under a certain number of constraints and a bit of ambiguity.  No a problem though, I'm happy to embrace this as a challenge.

As I was embarking on a journey to transform a multitude of products (new and old) I knew I needed to develop a way to effectively manage UX and UI of everything across the whole suite.  It was essential to avoid the rabbit hole that is rework and for the sanity of our development team.

#### Key Considerations
It was apparent that the organisation could benefit greatly from having a style guide, patterns and component library in place but I wanted to validate if there was real value in it.  This is what I discovered:

* There was no current design system but a plan to create one.
* We knew that as an organisation we could benefit from developing a reusable UI component set or ecosystem.
* The organisation were going threw a period of and needed to be able to design with a common language and consistent aesthetic.
* There was a plan to essentially white-label specific product sets.
* Current styles were inconsistent.  For example, different button styles.
* There was a lot of repetition across the whole product team.

#### Key Pain Points
* Design inconsistency.  As mentioned above, this was clearly apparent and needed to be nipped in the bud.
* No clarity on how to implement designs.  Developers were building the same design components over and over but with tiny differences each time.
* There was a demand to release changes and new features quickly.

#### Solution
Obviously a solution was needed.  Some sort of design framework, a simple set of design rules that could be easily interpreted and implemented.  There was a need to be able to constantly evolve our designs and keep them well maintained.  Enter Storybook js.

We reviewed a number of options and even considered building something custom.  Fortunately, there are plenty of great options off the shelf and some more suited than others.

Storybook is one of the most recognised.  It is an open source tool for developing UI components in isolation for React, Vue, Angular, and more. It makes building UIs organised and efficient.  I knew it was important to consider the developer experience so being able to design and develop UI components in isolation was a big plus. As great as this is for devs it is also a fantastic experience for the designers and any future members in our team.  It provided the long awaited framework and guidelines the product team needed to work with and can be kept updated and current.

#### Atomic Design
I wanted the development team to feature heavily in the process.  After all, one of the main goals was to make their lives signifcantly easier.  I leaned on them for much of the journey and extracted as much information out of them as I could.

I've always taken a modular approach to designing, delibrately creating components that are reusable across a sute of products.  A few years ago I stumbled across Brad Frost's Atomic design methodology.  As it turns out, it is rather similar to what I had already been practicing.

#### Summary
Two years ago, there was no way of assuring design consistency and frustration was high amongst the developement team.  Today, we have a constantly evolving design system which is beginning to mature. 
