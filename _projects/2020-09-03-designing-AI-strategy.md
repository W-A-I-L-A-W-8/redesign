---
title: Exploring AI
subtitle: Introducing our new friend, The Chatbot
date: 2020-09-03 00:00:00
description: This piece is about how we developed a strategy for implenting an AI/ML solution to align with the organisation's strategic priorities and to solve immediate problems.
featured_image: demo.jpg
accent_color: '#222'
# gallery_images:
#   - demo.jpg
#   - demo.jpg
#   - demo.jpg
---

Implementing the chatbot was the easy part.  Convincing the organisation they needed one was quite the opposite.

Meeting the needs of the consumer whilst aligning with the company's strategic priorities.

![](/images/demo.jpg)

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

For Product Designers a large part of the job is to design products that are great for the end user but we also need to design for the business too.  In this project I assummed the role as, not only the Product Designer but kind of an acting Product Manager/Owner too.

#### Pain Points

There were a number of ongoing problems within the organisation that needed addressing as follows: 

* Slow customer service response rates
* Missing pontential sales conversions
* Unsatisfactory customer experience
* Lack of content

#### Solution
chatbot off the shelf solution Amazon Lex.

#### Why
better engagement, bridging gap in content, increase revenue, reduce costs.Summary or outcome: KPIs achieved (see keynote doc).

#### Image carousels

Here's another gallery with only one column, which creates a carousel slide-show instead.

A nice little feature: the carousel only advances when it is in view, so your visitors won't scroll down to find it half way through your images.

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/demo.jpg,/images/demo.jpg,/images/demo.jpg
	"
%}