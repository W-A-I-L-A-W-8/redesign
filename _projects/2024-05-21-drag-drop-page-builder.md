---
title: Designing a brand portal people will love
subtitle: Reimagining an outdated HTML builder as a human centred drag and drop brand page creator.
date: 2021-06-30 00:00:00
description: A journey to transform a HTML builder into an intuitive drag and drop page builder that makes web page creation enjoyable and simple for all. Everyone can create stunning pages with ease.
featured_image: DnD_1.jpg
accent_color: "#A88CC8"
gallery_images:
- DnD_1.jpg
- DnD_2.jpg

---
_For confidentiality reasons some content may have been omitted or altered.  In some instances, the designs have been reinterpreted_

#### Background
Embarking on a journey to transform a dated HTML builder into something more suited to our user's needs. The mission? To make web page creation enjoyable and efficient, ensuring that everyone, regardless of their abilities, can craft stunning pages with ease.

#### Challenge
The starting point was an antiquated HTML builder. Both unfriendly and inaccessible. It was clearly aimed at the wrong audience and built by Engineers in a knee-jerk reaction to an urgent client request.

#### Approach
As with all good user research initiatives, I wanted to dive into the user experience and truly understand who we were building this for. By putting yourself in the shoes of users with consideration for different abilities, you can better understand their challenges and create solutions that address their needs.

###### The Proto Persona
It was interesting to learn that from previous research there were originally three personas. From further research and up to date information elicited from key stakeholders, as a collaborative effort, we were able to conclude that a single persona would satisfy all potential use cases.

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/projects/brandManager_protoPersona.jpg"
%}

###### What is a Proto Persona?
<div class="wrap">
		<blockquote>
				<p>"Proto personas capture a team's existing knowledge or assumptions about who their current users are."</p>
				 <cite>Nielson Norman Group</cite>
		</blockquote>
</div>

For greater empathy, I created a storyboard to trace the persona's journey. I shared this with the Project Team and Engineers so they were clear what we were all working towards.

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/projects/dndStoryboard.jpg"
%}

I must stress that this was used with caution.

###### Interviews
We spoke with brand managers across various industries, to understand their frustrations with the old builder. They described it as time-consuming and difficult to navigate. By observing users struggle with the old tool provided deep insights. Their candid feedback was crucial for our redesign strategy. It was apparent that our persona had limited coding knowledge.

#### Design Principles: Shaping User Friendly Experiences

###### Simplicity
Our goal was to design a decluttered interface, creating a straightforward design that anyone could use without a manual.

###### Consistency
Ensure consistent interactions throughout the builder to make it easy to learn and use, minimising the learning curve.

###### Flexibility
The tool had to accommodate different working styles, whether users preferred drag and drop, keyboard shortcuts, or voice commands.

###### Accessibility Features

* We had to ensure that full functionality via keyboard allowed users to navigate and interact without a mouse.
* Screen Reader Compatibility: By integrating ARIA roles and labels, we made the interface compatible with screen readers.
* Contrast and Font Size: High-contrast designs and scalable fonts improved readability for all users.
* Drag and drop alternatives: Dropdown menus and arrow keys provided alternatives to dragging, catering to users with motor impairments.

###### Inclusive Components: Empowering Creative Freedom

* Templates and Modules: We designed a library of accessible, customisable templates, allowing users to start with a professional look.
* Live Previews: Real-time previews provided immediate feedback, enhancing the creative process and reducing guesswork.

#### Ideation: Extracting actionable insights from research
I ran a design workshop to tease out ideas. At this stage, there were no limits. All ideas considered. It was a broad concepts, anything goes phase. Sketches and wireframes welcome. We generated heaps of ideas, from AI created pages to form based wizards. We were now able to visualise all potential use cases and begin thinking about the user stories.

#### Shaping Interactions
The primary component, a sidebar containing multiple core elements enabling users to simply, choose, drag and drop elements onto their page. Simple page interactions such as state and cursor changes provide great visual cues.

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/projects/widget_properties.jpg"
%}

#### Simulating Widget Movement
An early Figma prototype for testing how a widget might behave when being dragged onto the canvas.

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/projects/simulatingWidgetMovement.gif"
%}

#### Parting Thoughts
Designing a user-friendly, accessible drag and drop page builder was rewarding and fun. By focusing on the needs and experiences of our persona, I was able to design a tool that not only met but exceeded their expectations. This highlights the power of human centred design and the importance of accessibility in creating tools that resonate with users and drive business success.

###### MVP of the outcome

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/projects/brandyDemo.gif"
%}
