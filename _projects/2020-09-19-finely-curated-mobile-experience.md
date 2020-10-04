---
title: Finely Curated Mobile Experience
subtitle: Enterprise model for delivering a booking experience on mobile devices.
date: 2020-09-03 00:00:00
description: Creating a great booking experience on mobile and doing it globally across all products within the organisation.
featured_image: 'khoa-nguyen-b839k0lK3Dk-unsplash.jpg'
gallery_images:
  - khoa-nguyen-b839k0lK3Dk-unsplash.jpg
accent_color: '#222'
published: false	
---

#### From cluttered desktop to tidy small devices
So, how do you transform this tired, cluttered desktop UI into a finely crafted mobile experience keeping all the features and functionality?  Curation is key.

{% include post-components/gallery.html
	columns = 2
	full_width = true
	images = "/images/projects/rr-hotel-details.png,"
%}

This is a B2B platform for booking and managing hotel reservations.  It is not consumer facing, the persona is the travel agent.

![](/images/projects/khoa-nguyen-b839k0lK3Dk-unsplash.jpg)

You can create lists:

* Simple bulleted lists
* Like this one
* Are cool

And:

1. Numbered lists
2. Like this other one
3. Are great too

You can also add blockquotes, which are shown at a larger width to help break up the layout and draw attention to key parts of your content:

> “Simple can be harder than complex: You have to work hard to get your thinking clean to make it simple. But it’s worth it in the end because once you get there, you can move mountains.”

The theme also supports markdown tables:

| Item                 | Author        | Supports tables? | Price |
|----------------------|---------------|------------------|-------|
| Duet Jekyll Theme    | Jekyll Themes | Yes              | $49   |
| Index Jekyll Theme   | Jekyll Themes | Yes              | $49   |
| Journal Jekyll Theme | Jekyll Themes | Yes              | $49   |

And footnotes[^1], which link to explanations[^2] at the bottom of the page[^3].

[^1]: Beautiful modern, minimal theme design.
[^2]: Powerful features to show off your work.
[^3]: Maintained and supported by the theme developer.

You can throw in some horizontal rules too:

---

#### My Role

The was prodominently a UX piece.

{% raw %}
```liquid
{% include post-components/gallery.html
	columns = 2
	full_width = true
	images = "/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,
	"
%}
```
{% endraw %}

*See what we did there? Code and syntax highlighting is built-in too!*

Change the number inside the 'columns' setting to create different types of gallery for all kinds of purposes. You can even click on each image to seamlessly enlarge it on the page.

After a UX Audit.

#### Pain Points
The primary problem here was not the lack of content but how do we go about squeezing it all onto the small screen.  we ran some research and we discovered that cognitively, it presented a problem to many users.  On reviewing the platform, experience wise, we were surprised to discover was not too bad at all and there were some well thought out features.

The stakeholder also wanted this to work across multiple screen resolutions so the approach had to be responsive so we could forget about doing a native application.  It meant we would have to define some useful breakpoints.  However, we knew if we were ever asked to do a native application we could borrow many of the design features from the mobile device resolution.

#### Why?
chatbot off the shelf solution Amazon Lex.Why: better engagement, bridging gap in content, increase revenue, reduce costs.Summary or outcome: KPIs achieved (see keynote doc).

#### Image carousels

Here's another gallery with only one column, which creates a carousel slide-show instead.

A nice little feature: the carousel only advances when it is in view, so your visitors won't scroll down to find it half way through your images.

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/demo.jpg,/images/demo.jpg,/images/demo.jpg
	"
%}