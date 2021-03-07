---
layout: post
title: Good development practices from the outside (Part I)
comments_id: 3
---

[@pauldyson](https://twitter.com/pauldyson) asked an [interesting question](https://twitter.com/pauldyson/status/1364514478931517448) on Twitter a few weeks ago:

![paul's tweet]({{ site.baseurl }}/images/paul_dyson_tweet_good_dev_from_customer.png)

After a bit of discussion it seemed to come down to this: 

>As a non-technical person dealing with technologists, who I rely upon for the machinery of my business, how do I tell what they are doing will provide what I need to succeed ?
<!-- excerpt-end -->

This, of course, is tricky in early-stage projects because often the end-user is not fully identified or engaged, there are lots of uncertainties, and there are no immediate deliverables that can be put into a delivery backlog, but it doesn't necessarily become any easier the more established a project becomes.

The technology "literature" encourages leaping into writing code as soon as possible, and suggests the measure of good practice should be "frequent incremental features" guided by "rapid feedback from business and customers", but this doesn't address many of the concerns non-technical people have about technology-reliant organisations: are we making good technology choices? How much will this cost? Will it be sustainable ? Are we focussing on the right things ? What are the implications of the technical choices we are making ? How do these choices effect our future opportunities and financial requirements ? Are these activities producing the things we need now, next, and future ?

So the essence of the question is about assessing the risks emerging from work you don't understand. What you want to understand is how these risks are being mitigated, without having to be an expert.

Sadly, the "literature" suggest to technologists that this is all about building trust. By delivering "frequent incremental features" guided by "rapid feedback from business and customers" this develops trust with the business functions in the organisation. The mitigation of all these risks is "trust us, we know what we're doing". Whilst trust is always a component in understanding risk mitigation, the Russian proverb advises us to "trust, but verify" - trust alone is not sufficient. So how do you verify as a non-technical person ?

The answer from delivery teams is often "verify our practices" - see the cards; participate in the ceremonies; prioritise the backlogs; use the tools; look at the walls; come to the demos; you need to learn and understand; come, drink the Kool-Aid. This, however, is cargo-cult thinking. If we do these things, the right outcomes occur. Indeed, in demanding the non-technical people must learn, understand, and appreciate, it is almost cult thinking. Whilst these practices might mitigate delivery risks, and some help build cohesive tech teams, they do not address all the other risks which are of equivalent, if not greater, existential threat.

I think there may be a premise that needs to be rejected at the heart of the original question: Current development delivery practices and tools do not deliver the entirety of what you should expect, as a non-technical person, from your technology team. This is also a rejection of the message that the fundamental purpose of technology teams is to deliver customer-driven priorities.

We need to recognise there are two types of value, and two different groups benefiting from these separate values: 
- the customers of the business of the organisation; and,
- the organisation employing the technologists to develop the necessary capabilities to support the business of the organisation

These map to the value-streams of the business, and the value-chains of the business. Whilst the first is addressed by "customer-driven priorities" the technology teams also need to address the second, which is less delivery and more architecture, design, strategy, and planning - words and ideas which are much maligned these days but are nevertheless core skills of a good technology team, upon which the organisation relies.

Now I know using terms like value-streams, value-chains, capabilities, etc. is seen as meaningless by many, but I will endeavour in the next few posts to explain and be specific about what is meant by these things, and how it is important that they are seen as primary artefacts within the responsibilities of the technologists. 

Where I'm going with this is that for the non-technical person to verify the benefits of the practices, tools, and processes of technology teams, they need to be able to __verify their *shared* understanding of the artefacts that connect the business of the organisation to the activities of the technologists__

### What Needs To Be Verified

Examples of verification conversations a non-technical person should be able to have with the technology team would include:

 - What are the primary value-streams of the business ?
 - What are the value-chains that support the stages of the value-streams ?
 - Which capabilities are custom, product, or commodity ?
 - What are the non-functional concerns for the value-stream stages and capabilities ?
 - How will capabilities be matured over time to respond to the changes in functional and non-functional requirements ?
 - What options does the design enable or restrict ?
 - How do we make sure when we change the systems we don't break the value-streams ?
 - What are the risks of this design and approach ? Are we all OK with them ?
 - How are we creating effective teams for each of our capabilities ?

And verification conversations are two-way.

Lots of specific jargon in here. Next post will define most of them.