---
title: Creative Coding Like an Artist
date: 2023-08-04T19:24:49.166Z
categories:
  - 30daychallenge
tags:
  - 30daychallenge
  - buildinpublic
  - web development
img_path: /assets/img/
image: flutterflow.png
slug: web-development
---

> My web development methodology and tech stack choice after building the same app three times using Python, JavaScript, and FlutterFlow

## What did I build?

I challenged myself to build and launch a SaaS product in 30 days this June. With little web development experience, I struggled, pivoted, and almost gave up during the process. But the reward at the end is also priceless. Not only did I gain confidence in building apps, but I also developed my methodology in app development which can help my future projects built in light speed.

I’m going to share with you the lessons I learned in these 30 days and my reflections on web development as an entrepreneur, so you can avoid the mistakes I’ve made and move faster. Check my [30-day challenge]({% post_url 2023-08-01-saas-challenge %}), if you’re interested in the journey.

### Python and [Streamlit](https://streamlit.io/)

I start with Streamlit because Python is what I know. The development experience of Streamlit is awesome! Great documentation, active community, and few-click integration and deployment. As said on its home page, Steamlit is perfect for building a website based on your existing data project and presenting it with beautiful graphs and basic interactions. But building a traditional static website or a modern web app is not what it’s designed for.

![Streamlit App](streamlit.png)
_[My Streamlit App](https://ignite-me.streamlit.app/)_

### JavaScript and [Svelte](https://svelte.dev/)

JavaScript is the gold standard in web development. You will have plenty of options from the classic big brothers like React, Vue, and Angular to the modern challengers like Svelte and Astro. Since JavaScript is the fundaments of web pages, you will have full control to tailor the website the way you want. However, it does come with a price of a steep and protracted learning curve. It’s perfect for people with a strong frontend background, who are looking for a job as a software development engineer, or who are interested in the pure coding part of web development.

![Svelte App](svelte.png)
_[My Svelte App](https://igniteme-7f641.web.app/)_

### Flutter and [FlutterFlow](https://flutterflow.io/)

Dart is not as popular a programming language as JavaScript, but it’s designed to be the unified programming language interface for all platforms, from iOS to Windows. Flutter is designed to be the all-in-one framework for app development which has adopted the design concepts of modern apps into simple building blocks. FlutterFlow, a low-code solution adds a visual layer over Flutter that encapsulates the technical complexity while keeping the flexibility. It’s great for all kinds of app development, especially if you may want to expand the app from one platform to more options. Use JavaScript if you’re building a static website such as a landing page or a blog.

![FlutterFlow App](flutterflow.png)
_[My FlutterFlow App](https://empowermentcircle.flutterflow.app/)_

## Web Development is Complicated as Hell

With the rise of ChatGPT and Github Copilot, lots of people see the possibility of building an application without having years of training in computer science. While these AI coding tools have the incredible ability to generate and debug codes, they are yet powerful enough to create a sophisticated and successful web application due to the complex nature of web development. Let me unfold the complexity in four dimensions.

### The Technology

Web development heavily relies on collaboration with all kinds of modules and services. To make the simplest website work, you have to work with a variety of infrastructures, third-party APIs, frameworks, and development tools. Below is an unfinished list of technology most front-end web developers need to deal with.

**The Incomplete List of Frontend Tech Stack**

- Web basics: HTML, CSS, and JavaScript
- JavaScript Frameworks: React, Vue, Svelte
- Meta Frameworks: Nextjs, Nuxtjs, SvelteKit, Astro
- CSS frameworks: Tailwind CSS, PostCSS, Sass
- UI Components: Material, Carbon, DaisyUI
- Compilers: Webpack, Vite
- Package Management: NPM, Yarn
- Toolings: TypeScript, ESLint, Prettier
- Version Management: Git
- CI/CD: Github Actions
- Hosting: Netlify, Vercel, Firebase hosting

While the above list is already overwhelming, the backend development and administration require a whole different tech stack and skill set. And the learning process is never-ending. Even the most experienced developers need to continuously learn as all the “wheels” they are using are changing every day. (e.g. the update of Nextjs 13 changes the entire project structure as well as the syntax for SSR/CSR rendering)

### The Management

The best way to get rid of the nitty gritty of coding is to let somebody do it. So, let’s say you managed to get some funding and decided to assemble a development team. A minimum team may include a product manager, a UI/UX designer, a front-end developer, and a back-end developer. Let's skip all the day-to-day management and only think about the deliverables.

It starts from the PRD (Product Requirement Documentation). A PRD is a written design of the product, usually, you will need a more detailed visual design which we call prototypes. Then your engineers will start to work on the technical design such as the data structure, APIs, and service architectures before they start writing the first line of code. Now we have four ways to model the same product idea: a written version from PRD, a visual version from prototypes, another written (sometimes visual) version of the technical design, and the final program in codes.

Everything looks fine until we want to make a change. If we want to add one more table in the database for some extra information, here’s what we need to do: change the schema in the database, change the API accordingly, change the API call from the frontend side, and change the component that consumes the newly added data. To be noticed, these are just the work on the coding version of the product. What about the technical design, the prototype design, or the PRD? The reality is that it’s nearly impossible to maintain consistency across all these documents.

### The Business

The product development of a web app is an engineering process. But the truth is nobody cares about how you build it. The business side of the product is more important than the product itself in many cases. You need to think about your marketing strategy, your copywriting on your ads, and your sources of finance. I won’t unfold this part, as basically, we are talking about the entire curriculum of an MBA program. However, the challenge doesn’t even stop here.

### The Art (& Luck)

Your unique opinion on how things should work which reflects the combination of features you put together is part of the reason why people use your app. People use your product because they agree with your opinion. But you don’t know their reaction until you create and present the product to your audience. The entrepreneur community has learned a lot from artists what they call “design thinking”, from the agile method to the lean startup approach, to smoothen the costfull process of trial and error.

That’s why I think web development is more like art. And just like any form of art, you need to master the skill of creating before expressing yourself freely. But the mainstream of web development makes things way too complicated for individual creators. Why can’t we focus on what matters the most in the business and spend less time on unnecessary coding and debugging?

## 3 Principles of Web Development

The complexity of web development troubled me years ago when I was in charge of a SaaS product rebuild. It’s now become my problem again as I decided to start my own SaaS business. So I spent a month dedicatedly exploring the most ideal method for web development that is practical for solopreneurs like me or small founding teams. (See my journey [here]({% post_url 2023-08-01-saas-challenge %})). And here is what I learned.

### Building Blocks

Basically, any web application can be broken down into four parts, the business logic that differentiates the app from other apps, the user interface people interact with directly, the data structure that represents the relationship of information, and the servers the application runs on.

Among the four, the first part is the soul of the app and where we should pour the most creativity. While the last three are more standard and are better to occupy less amount of effort. Thus I conclude with the following three principles:

1. **Design as code**
   Visual appearance is the ultimate expression of the frontend. Why should we do it once on the design tool and do it again in the codes?
2. **One schema rules all**
   Design the schema once and use it in databases, APIs, or custom functions. Why do we need to update the database, the backend API, the frontend API call, and the frontend component, for every single change in schema?
3. **No more wheels**
   Use existing infrastructure as much as possible. Why should we manage our own hosting, database backup, microservices, and crash reports when every website needs to do it in very similar ways?

### My FFF Kit Stack

The FFF Kit is a portmanteau of FlutterFlow and Firebase, with its name a tribute to [Jeff Delaney](https://twitter.com/Jeffdelaney23)'s [FKIT](https://youtu.be/rFP7rUYtOOg).

**Why do I choose FlutterFlow for Frontend**

- **All-in-one cross-platform language**
  Dart code can be compiled into mobile apps, web apps, and desktop apps with the same code base. Flutter framework provides templating, styling, and logic at the same time while we need to use HTML, CSS, and JavaScript together to do the same thing.
- **Build UI with the drag-and-drop visual builder**
  The design from FlutterFlow can be translated to high-quality Flutter codes as there is no need to worry about the countless evolving frameworks in the JavaScript ecosystem.

**Why do I choose Firebase for Backend**

- **Schemaless database**
  Traditional relational databases are backend oriented, the data structure is MECE. Document databases are more frontend oriented. GraphQL is an alternative if you are using relational databases but want to have a unified API interface.
- **Out-of-box backend services**
  Handle real-time data, authentication, and server-side functions out of the box. Build in A/B Testing, crash analytics, and extensions integrating Stripe, Agolia, and Google Cloud Platform services with few clicks

### FFF Stands For Flexibility, Functionality, and Freedom

My favorite thing about this tech stack is that it gives you the full range of coding freedom without the need to learn (much about) programming syntax, and you have the full power of a modern app without the hassle of building your own wheels.

## Your Creativity Matters, Not The Tools You Use

I’m always an enthusiast of technology and cannot stop myself from playing around with new tools, from Arch Linux, Termux terminal, Astro js, and all the possible packages and frameworks you can imagine. But the biggest lesson I learned from this 30-day challenge of building SaaS is quite the opposite, that all those tools don’t really matter.

Though I still have the impose to explore better coding tools, I learned to be less distracted by the tools and focus more on the product itself, the customers I’m building for, and the business model that makes the software valuable.

### Great Artists Don't Just Use Brushes

> _"The brush is nothing but an extension of the artist's mind." -- Pablo Picasso_

My choice of FlutterFlow and Firebase as my tech stack doesn’t mean that they are the best option on the market. They are just the most intuitive way for me to design, develop, and deploy my app. If you’ve plenty of experience in JavaScript, PHP, or other languages and have a library of your components or code snippets, then go with what best for you. As that being said, I think the FFF kit stack (FlutterFlow + Firebase) is a great beginner package for developers with little experience or interest in programming but still want to express themselves in the form of an application.

### Wait, What About Vendor Lock-in?

> _Freedom is an illusion._

The biggest critic of this tech stack is vendor lock-in. Yes, it is a real risk, but in my opinion, worth taking. Lots of people prefer open-source software and have a negative opinion of any paid services. But the reality is we don’t build things from scratch. Even the programming languages we are using are built and maintained by someone else. Instead of trying to own every piece of code, learning how to collaborate with others in a mutually beneficial way is more important. And many times, a paid service is a better business model to keep the software sustaining.

### What’s Next?

I wish my sharing has been of some help to you, and hopefully, inspires you to start on your own creation, just like other creators have done for me. I will keep posting my journey and thoughts on web development, entrepreneurship, and self-transformation.

_See you in the next post!_

---

<!-- prettier-ignore -->
> **I’d love to hear your thoughts! Let me know on Twitter [@ZhengyiShen](https://twitter.com/intent/tweet?text=@ZhengyiShen&url={{ page.url | absolute_url }})**
{: .prompt-tip }

{% include links.md %}

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">What would you do if you want to create an App but don&#39;t want to spend hours learning a programming language?<br><br>Here&#39;s what I learned after building the same app three times using <a href="https://twitter.com/streamlit?ref_src=twsrc%5Etfw">@streamlit</a> <a href="https://twitter.com/sveltejs?ref_src=twsrc%5Etfw">@sveltejs</a> <a href="https://twitter.com/flutterflow?ref_src=twsrc%5Etfw">@flutterflow</a> and <a href="https://twitter.com/Firebase?ref_src=twsrc%5Etfw">@Firebase</a> <a href="https://twitter.com/hashtag/buildinpublic?src=hash&amp;ref_src=twsrc%5Etfw">#buildinpublic</a><a href="https://t.co/lfN5bUzZvu">https://t.co/lfN5bUzZvu</a></p>&mdash; Zhengyi Shen (@ZhengyiShen) <a href="https://twitter.com/ZhengyiShen/status/1689637725769437184?ref_src=twsrc%5Etfw">August 10, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
