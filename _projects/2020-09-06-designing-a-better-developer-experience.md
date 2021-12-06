---
title: Design quality assurance and the developer experience
subtitle: Building an enterprise UI Component Library in Storybook.js
date: 2020-09-10 00:00:00
description: A design system for smoother collaboration amongst software teams and product scalability.
featured_image: quality-assurance-feature1.jpg
accent_color: '#222'
gallery_images:
  - quality-assurance-feature1.jpg
published: true
---

#### The Situation
At this Fintech organisation they had developed a Forex platform as a white label that would be rebrandable.  I joined as the product was emerging onto the market and at this stage they had just three clients who were actively using the platform.

My role was to provide a strategy to effectively manage the experience of the interface but also a consistent way to customise and scale interfaces for the client's needs.

#### Key Considerations
It was apparent that the organisation could benefit greatly from having a set style guidelines, familiar UI patterns and a reusable component library in place but I wanted to validate if there was real value in it.  This is what I discovered:

* There was no current design system but a plan to create one.
* The organisation could benefit from developing a reusable UI component set or ecosystem.
* The organisation were going through a period of growth and needed to be able to design with a common language and consistent aesthetic.
* As the platform was built first, design elements were clearly inconsistent.
* There was a lot of repetition across the whole product team.

So, definitively, I think we were able to say that, a design system would be a great asset to the organisation.

#### Key Pain Points
We could now pinpoint the high level problems that existed.
* Design inconsistency.  As mentioned above, this was clearly apparent and needed to be nipped in the bud.
* No clarity on how to implement designs.  Developers were building the same design components over and over but with tiny differences each time.
* There was a demand to release changes and new features quickly.

#### Solution - The end goal.
A design framework, a simple set of design rules that could be easily interpreted and implemented.  There was a need to be able to constantly evolve designs and keep them well maintained.  Enter Storybook js.

We reviewed a number of options and even considered building something custom.  Fortunately, there are plenty of great options off the shelf and some more suited than others.

Storybook js is one of the most recognised.  It is an open source tool for developing UI components in isolation for React, Vue, Angular, and more. It helps to build UIs in an organised and efficient fashion.  I knew it was important to consider the developer experience too so being able to design and develop UI components in isolation was a big plus. Similarly for designers, it is also a fantastic experience.  It provided the long awaited framework and guidelines the product team needed to work with and could be kept updated and therefore current.

#### Atomic Design
Before developers could start delving into code, as a design practice we needed to develop the digital style guidelines and UI toolkit.

When it comes to design, I have always instinctively taken a modular approach to designing, delibrately creating components that are reusable across a suite of products.  A few years ago I stumbled across Brad Frost's Atomic design methodology.  As it turns out, it is rather similar to what I had already been practicing.  So it made perfect sense to continue in the same vein.

![Atomic Design by Brad Frost ](/images/projects/atomic-design-process.png "Atomic Design image from Brad Frost")
<figcaption>Image taken from Brad Frost's Atomic Design</figcaption>

Following the Atomic method, I began to design the foundational UI elements to serve as our base styles.  The colours, typography, buttons, form inputs etc. 

<!-- Next, the molecules.  Like a search input and button combined.

Organisms - nav

Templates - use a mobile wireframe as an example -->

## To be continued...
My apologies, I'll hopefully have this one finished for you soon.
<!-- #### Summary
Two years ago, there was no way of assuring design consistency and frustration was high amongst the developement team.  Today, we have a constantly evolving design system which is starting to mature.  It helps to relieve unnecessary stress and the product team can create and develop with confidence knowing they have the support of some great tools. -->
