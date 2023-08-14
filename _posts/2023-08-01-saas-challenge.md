---
title: What I Learned After Building & Launching a SaaS in 30 Days
date: 2023-08-01T17:49:49.790Z
categories:
  - 30daychallenge
tags:
  - web development
  - 30daychallenge
img_path: /assets/img/
image: twitter_1.png
---

> A journey of building an online community for achievers

I decided to take on a [#buildinpublic](https://buildinpublic.com/) challenge this June. Motivated by the entrepreneurs and creators who had previously accomplished it, and who had shown me that such an ambitious goal was achievable, I challenged myself to learn, build, and launch a SaaS product in 30 days.

## A Little Background

Starting my own SaaS business has always been my dream. That's why I moved from being a data scientist to a product manager and why I got my MBA from the best business school in entrepreneurship. It sounded promising, but what was missing? I never started, the real building and real business.

I knew that the process would not be smooth and the output might not be desirable, but I just wanted to see if things would be different if I could push through the pain and reach the finish line. That is why I set a 30-day deadline for myself.

And here I am, reflecting on my journey and sharing the lessons I learned along the way. I want to be upfront and say that this article will be very opinionated. But I am not married to these opinions and I know that they will change over time. But I still think it is worth sharing. So, if you are still interested, here is my story.

## Dreaming: The Big Idea (Day 1)

> _Everyone has a big idea, and so do I._

My idea was motivated by [Barbara Sher](https://twitter.com/BarbaraSher) and her [Success Teams](http://shersuccessteams.com/). The work Barbara Sher has done is so heart-warming and empowering that inspired me to replicate her magic and build an online community where we support each other to become better selves.

{% include embed/youtube.html id='H2rG4Dg6xyI' %}

> _Why it matters?_

Loneliness and isolation have become a growing problem, especially after COVID. As one city mayor in the US put it, “It’s staggering how many people have no one to call in the face of a crisis.”

Many companies have launched products aimed at relationship-building, but few have been successful. "[IRL](https://www.irl.com/)" reached unicorn status before imploding in June. Sam Altman's "[Loopt](https://en.wikipedia.org/wiki/Loopt)" was unable to retain its users. Danny Trinh's "[Free](https://medium.com/@dtrinh/introducing-free-4f709474e6eb)" didn't last long after its announcement. Google's "[Who's Down](https://techcrunch.com/2015/10/30/google-asks-if-you-are-down/)" also disappeared with little impact. The list of failures goes on.

Despite all the failures that happened before, I still want to give my idea a shot. I believe it’s better to foster human connections by encouraging others to contribute to the most precious aspects of people's lives: their dreams! And so, the Iginite app (now [Empowerment Circle](https://empowermentcircle.flutterflow.app/)) was born.

## Design Phase: Copy Creatively (Day 2 - Day 4)

> _Good artists copy, great artists steal. — Picasso_

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

![Landing page on Framer](framer.png)
_Landing page on Framer_

![Prototype on Figma](figma.png)
_Prototype on Figma_

I was satisfied with the high productivity and excited about the progress on Day 4. But little did I know, it’s just the beginning.

## Development Phase I: Coding with Streamlit (Day 5 - Day 12)

> _The best tool is the one you know._

Due to my background in data science, Python is always my go-to programming language. It’s not an ideal choice for web development but thanks to the framework of Streamlit, I decided to give it a shot.

I’ve to say, the overall learning and development experience with Streamlit was pretty awesome. It only took me a few hours to learn the framework and explore components in the community. Since you don’t need to (and you can’t only with Python) style the components, the coding process is just like stacking LEGO bricks one above another. The integration with 3rd party API and the cloud deployment is seamless. I managed to set up a basic web app with OpenAI’s API integrated and deploy the app on Streamlit Cloud on my first coding day.

> _Anything that can go wrong will go wrong. — Murphy's law_

Streamlit is perfect for building data apps, but my app is just a traditional forum-like app. The component library and UI functions in Streamlit were no longer enough. This was the time I thought about migrating the project to JavaScript. However, I certainly underestimated the [complexity of JavaScript ecosystem][complexity of JavaScript ecosystem]. After I spent three days working with Svelte but only found myself debugging ESLint errors and package incompatibility, I realized JavaScript wasn’t the right tool for me in this challenge.

This was just two weeks into the challenge and I had already stuck in my development with only a bare-bone app. What should I do next?

![IgniteMe.app on Streamlit](streamlit.png)
_[IgniteMe.app](https://ignite-me.streamlit.app/) on Streamlit_

## Development Phase II: Build with FlutterFlow (Day 22 - Day 30)

> _The best code is no code at all. — Jeff Atwood_

I’ve been interested in the low-code/no-code trend since 2019, but the process from design to code was never satisfying due to the nature of JavaScript. But this time, I found FlutterFlow, again, after I tried it first time 3 years ago. I was surprised by how FlutterFlow, together with Firebase, perfectly aligns with my [principles of web development][3 principles of web development].

When I decided to go all-in with FlutterFlow, I was only a week from the deadline. I had to work like crazy, learning, building, and debugging. And surprisingly, I managed to finish the app with a much better user interface and more comprehensive functionality, in 7 days!

![Empowerment Circle on FlutterFlow](flutterflow.png)
_[Empowerment Circle](https://empowermentcircle.flutterflow.app/) on FlutterFlow_

But before we wrap up the story and cheer for the success, let me share two interludes.

## Mistake #1 Not Knowing Your Customer (Day 10 - Day 14)

> _The more I learn, the more I realize how much I don't know. ― Albert Einstein_

Product development is only half of the equation for SaaS success. The other half, and the more important one, is “Customer Development”, a term coined by [Steve Blank](https://twitter.com/sgblank) in "[The Four Steps To Epiphany](https://a.co/d/9qVwCTM)", the book that launches the “Lean Startup” revolution.

While Steve pointed out the essence to be minimum and lean, it will be reflective to also read the “[$100M Offers](https://a.co/d/gFoNaGz)” authored by [Alex Hormozi](https://twitter.com/AlexHormozi), a book emphasizing the value of premium pricing and over-delivery. Though they seemed talking about two opposite opinions, I found their theories complement each other very well and I highly recommend both. (my notes coming)

After conducting interviews with friends, I realized the community platform may not fully align with their needs. Little time did I have at that moment, I could only stick to my guns. But I was aware of the mistakes I made and I shall be more thoughtful on my next app.

## Mistake #2: Forgetting I Have a Life First (Day 15 - Day 21)

_A balanced life is the cornerstone for long-term success_

I got chest pain on day 15. A friend warned me it might be myocarditis, but I didn’t pay too much attention until the symptom got worse. After spending a few days trying to figure out the healthcare system, the insurance networks, and the options for medical services (I’m still new to this country). I ended up seeing a physician at an urgent care center. Luckily, my heart was working all right, she suggested that I might be suffering from anxiety. Though a false alarm, it was a good warning that I shouldn’t be too obsessed with coding and neglect my real life.

## Beyond The Challenge

The journey of this 30-day challenge building in public is so much fun and rewarding. I didn't believe I could do it when I started the challenge. I've been through the ups (when I quickly built the Streamlit app in the first week) and the downs (when I got stuck with JavaScript), and I would probably give up the development if I wasn't doing this challenge. But I didn't, and I made it to the end! The rewards are priceless to me. Not only did I gain the confidence to build a SaaS product from scratch, but I also witnessed the transformation that happened to me because of this 30-day challenge.

While the SaaS challenge has ended, the story of my self-transformation and new venture creation has just begun. The blog you're reading right now is a part of my next 30-day challenge of blogging. I will continue to share my journey and the lessons I learned along the way.

_See you in the next post!_

## Reference

1. [Isolation is the dream-killer, not your attitude](https://youtu.be/H2rG4Dg6xyI), [Barbara Sher](https://twitter.com/BarbaraSher)
2. [The Four Steps To Epiphany](https://a.co/d/9qVwCTM), [Steve Blank](https://twitter.com/sgblank)
3. [$100M Offers](https://a.co/d/gFoNaGz), [Alex Hormozi](https://twitter.com/AlexHormozi)
4. [Fireship.io](https://Fireship.io), [Jeff Delaney](https://twitter.com/Jeffdelaney23)

---

<!-- prettier-ignore -->
> **I’d love to hear your thoughts! Let me know on Twitter [@ZhengyiShen](https://twitter.com/intent/tweet?text=@ZhengyiShen&url={{ page.url | absolute_url }})**
{: .prompt-tip }

{% include links.md %}

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">The recap of my 30-day journey building &amp; launching a SaaS<br><br>Huge thanks to <a href="https://twitter.com/Fer_MOMENTO?ref_src=twsrc%5Etfw">@Fer_MOMENTO</a> and Justin Hartung who motivated me with their achievements.<a href="https://twitter.com/hashtag/buildinpublic?src=hash&amp;ref_src=twsrc%5Etfw">#buildinpublic</a> <a href="https://twitter.com/hashtag/indiehackers?src=hash&amp;ref_src=twsrc%5Etfw">#indiehackers</a> <a href="https://twitter.com/hashtag/30daychallenge?src=hash&amp;ref_src=twsrc%5Etfw">#30daychallenge</a><br> <a href="https://t.co/IiUGGwOKcj">https://t.co/IiUGGwOKcj</a></p>&mdash; Zhengyi Shen (@ZhengyiShen) <a href="https://twitter.com/ZhengyiShen/status/1689353458028015617?ref_src=twsrc%5Etfw">August 9, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
