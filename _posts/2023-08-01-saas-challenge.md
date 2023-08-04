---
title: What I learned after building & launching a SaaS in 30 Days
date: 2023-08-01T17:49:49.790Z
categories:
  - 30daychallenge
tags:
  - buildinpublic
  - indiehackers
  - saas
  - web development
  - entrepreneurship
  - lean startup
  - 30daychallenge
slug: saas-challenge
img_path: /assets/img/posts/2023-08-01/
image: twitter_1.png
---

## A journey of building an online community for achievers

I decided to take on a [#buildinpublic](https://buildinpublic.com/) challenge this June. Motivated by the entrepreneurs and creators who had previously accomplished it, and who had shown me that such an ambitious goal was achievable, I challenged myself to learn, build, and launch a SaaS product in 30 days.

## A Little Background

Starting my own SaaS business has always been my dream. That's why I moved from being a data scientist to a product manager and why I got my MBA from the best entrepreneurial business school. It sounded promising, but what was missing? I had never done it before, real coding and real business.

I knew that I would encounter some setbacks and that I would be 100% likely to give up in the middle. But I just wanted to see if things would be different if I could push through the pain and reach the finish line. That is why I set a 30-day deadline for myself.

And here I am, reflecting on my journey and sharing the lessons I learned along the way. I want to be upfront and say that this article will be very opinionated. But I am not married to these opinions and I know that they will change over time. But I still think it is worth sharing. So, if you are still interested, here is my story.

## Dreaming: The Big Idea (Day 1)

_Everyone has a big idea, and so do I._

This idea is motivated by Barbara Sher and her Success Team (check out her TED talk [here](https://youtu.be/H2rG4Dg6xyI)). The work Barbara Sher has done is incredibly heart-warming and inspiring. I want to replicate her magic and build an online community where we support each other with strong care.

{% include embed/youtube.html id='H2rG4Dg6xyI' %}

_Why it matters?_

Loneliness and isolation have become huge problems in the US. As one city mayor put it, “It’s staggering how many people have no one to call in the face of a crisis.” And the situation got even worse during the COVID.

“Many companies have launched products aimed at relationship-building, but few have been successful. "IRL" reached unicorn status before imploding in June. Sam Altman's "Loopt" was unable to retain its users. Danny Trinh's "Free" didn't last long after its announcement. Google's "Who's Down" also disappeared with little impact. The list of failures goes on.”

While all of these solutions focused on forming interest groups, I think it’s better to foster human connections by encouraging others to contribute to the most precious aspects of people's lives: their dreams! And so, the IginiteMe app was born.

## Design Phase: Copy Creatively (Day 2 - Day 4)

_Good artists copy, great artists steal. — Picasso_

I’m no artist, and I don’t know much about web design, but at least I can learn and copy.

**I learned …**

- How to structure a landing page
- How to craft the message using StoryBrand
- How to do SEO
- How to setup the design system (color, fonts, etc)

**I copied …**

- Names and copywriting from ChatGPT
- UI Designs (of web apps) from Airbnb, Github, WeChat, and more.
- Data structure from to-do list apps
- Tech stack choice from [Fireship.io](https://fireship.io) (my favorite YouTube channel on web development)

**What I got:**

![Landing page on Framer](/assets/img/posts/2023-08-01/framer.png)
![Prototype on Figma](/assets/img/posts/2023-08-01/figma.png)

I was satisfied with the high productivity and excited about the progress on Day 4. But little did I know, it’s just the beginning.

## Development Phase I: Coding with Streamlit (Day 5 - Day 12)

_The best tool is the one you are familiar with._

Due to my background in data science, Python is always my go-to programming language. It’s not an ideal choice for web development but thanks to the framework of Streamlit, I decided to give it a shot.

I’ve to say, the overall learning and development experience with Streamlit was pretty awesome. It only took me a few hours to learn the framework and explore components in the community. Since you don’t need to (and you can’t only with Python) style the components, the coding process is just like stacking LEGO bricks one above another. The integration with 3rd party API and the cloud deployment is seamless. I managed to set up a basic web app with OpenAI’s API integrated and deploy the app on Streamlit Cloud on my first coding day.

_Everything seemed going all right until it broke._

Streamlit is perfect for building data apps, but my app is just a traditional forum-like app. The limited component library and less optimized UI functions were no longer a neglectable issue. This was the time I thought about migrating the project to JavaScript. However, I certainly underestimated the [complexity of the world of JavaScript][complexity of the world of JavaScript]. After I spent three days working with Svelte but only found myself debugging ESLint errors and package incompatibility, I realized JavaScript wasn’t the right tool for me in this challenge.

This was just two weeks into the challenge and I had already stuck in my development with only a crapy app barely working ([Check the Streamlit app here](https://ignite-me.streamlit.app/)). What should I do next?

![IgniteMe.app on Streamlit](/assets/img/posts/2023-08-01/streamlit.png)

## Development Phase II: Build with FlutterFlow (Day 22 - Day 30)

_The best code is no code at all. — Jeff Atwood_

I’ve been interested in the low-code/no-code trend since 2019, but the process from design to code was never satisfying due to the nature of JavaScript (See the complexity in JavaScript, link).

But luckily, I learned about FlutterFlow, again, after I tried it 3 years ago. I was surprised by how FlutterFlow, together with Firebase, perfectly aligns with my [philosophy about web development]().

I decided to go all-in with FlutterFlow when I was only a week from the deadline. I worked as crazy, learning and building. And surprisingly, I managed to finish the app with a much better user interface and more comprehensive functionality, in 7 days! (check out the app [here](https://empowermentcircle.flutterflow.app/))

![twitter_1](/assets/img/posts/2023-08-01/twitter_1.png)
![twitter_2](/assets/img/posts/2023-08-01/twitter_2.png)
![twitter_3](/assets/img/posts/2023-08-01/twitter_3.png)
![twitter_4](/assets/img/posts/2023-08-01/twitter_4.png)

But before we wrap up the story and cheer for the success, let me share two interludes.

## Mistake #1 Not Knowing Your Customer (Day 10 - Day 14)

_The more I learn, the more I realize how much I don't know. ― Albert Einstein_

Product development is only half of the equation for SaaS success. The other half, and the more important one, is “Customer Development”, a term coined by Steve Blank in "The Four Steps To Epiphany", the book that launches the “Lean Startup” revolution.

While Steve pointed out the essence to be minimum and lean, it will be reflective to also read the “$100M Offer” authored by [Alex Hormozi](https://twitter.com/AlexHormozi), a book emphasizing the value of premium pricing and over-delivery. Though they seemed talking about two opposite opinions, I found their theories complement each other very well and I highly recommend both. (See my notes [here]())

After conducting interviews with friends, I realized the community platform may not align with their needs. Little time did I have at that moment, I could only stick with what I had. But I was aware of the mistakes I made and I shall be more thoughtful on my next app.

## Mistake #2: Forgetting I Have a Life First (Day 15 - Day 21)

_A balanced life is the cornerstone for long-term success_

I got chest pain on day 15. A friend warned me it might be myocarditis, but I didn’t pay too much attention until the symptom got worse. After spending a few days trying to figure out the healthcare system, the insurance networks, and the options for medical services (I’m still new to this country). I ended up seeing a doctor at an urgent care center who found no problems with my heart and suggested that I might be suffering from anxiety. Though a false alarm, it was a good warning that I shouldn’t be too obsessed with coding and neglect my real life.

## Beyond The Challenge

The journey of this 30-day challenge building in public is so much fun and rewarding. I didn't believe I could do it when I started the challenge. I've been through the ups (when I quickly built the Streamlit app in the first week) and the downs (when I got stuck with JavaScript), and I would definitely gave up the development if I wasn't doing this challenge. But I didn't, and I made it till the end! The rewards are priceless for me. Not only did I gain the confidence to build a SaaS product from scratch, develop my own [3 principles of web development][3 principles of web development], but I also witnessed the transformation happened on me because of this 30-day challenge.

While the SaaS challenge has ended, the story of my self-transformation and new venture creation has just begun. The blog you're reading right now is a part of my another 30-day challenge of blogging. I will continue to share my journey and the lessons I learned along the way.

See you in the next post!

## Reference

1. [Isolation is the dream-killer, not your attitude](https://youtu.be/H2rG4Dg6xyI), Barbara Sher
2. "The Four Steps To Epiphany", Steve Blank
3. “$100M Offer”, Alex Hormozi
4. [Fireship.io](https://Fireship.io), Jeff Delaney

> **Please leave a comment on [Twitter](https://twitter.com/intent/tweet?text=@ZhengyiShen&url={{ page.url | absolute_url }}) if you have any questions or suggestions. I'd love to hear from you!**

{% include links.md %}
