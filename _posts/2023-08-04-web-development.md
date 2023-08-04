---
title: Unleash Your Creativity in Coding like an Artist
date: 2023-08-04T19:24:49.166Z
categories:
  - 30daychallenge
tags:
  - buildinpublic
  - indiehackers
  - saas
  - web development
  - 30daychallenge
  - NoCode/LowCode
pin: true
slug: web-development
img_path: /assets/img/posts/2023-08-04/
preview: /img/posts/2023-08-04/flutterflow.png
---

{% include links.md %}

## My web development principles and tech stack choice after building the same app three times using Python, JavaScript, and FlutterFlow

## What did I build?

I challenged myself to build and launch a SaaS product in 30 days this June. With little web development experience, I struggled, pivoted, and almost gave up during the process. But the reward at the end is also priceless. Not only did I gain confidence in building apps, but I also developed my methodology in app development which can help my future projects built in light speed.

I’m going to share with you the lessons I learned in these 30 days and my reflections on web development as a product manager, so you can avoid the mistakes I’ve made. If you’re interested in how I did my 30-day challenge, you can see the full journey [here]({% post_url 2023-08-01-saas-challenge %}).

### Python and [Streamlit](https://streamlit.io/)

I start with Streamlit because Python is what I know. The development experience of Streamlit is awesome! Great documentation, active community, and few-click integration and deployment. As said on its home page, Steamlit is perfect for building a website based on your existing data project and presenting it with beautiful graphs and basic interactions. Building a traditional static website or a modern web app is not what it’s designed for.

![Streamlit App](streamlit.png)
_Streamlit App [App URL](https://ignite-me.streamlit.app/)_

### JavaScript and [Svelte](https://svelte.dev/)

JavaScript is the gold standard in web development. You will have plenty of options from the classic big brothers like React, Vue, and Angular to the modern challengers like Svelte and Astro. Since JavaScript is the fundaments of web pages, you will the full control to tailor the website the way you want. However, it does come with a cost of a steep and protracted learning curve, which is dealing with all the nitty gritty in the JavaScript world. It’s perfect for people with a strong frontend background, who are looking for a job as a software development engineer, or who are interested in the pure coding part of web development.

![Svelte App](svelte.png)
_Svelte App [App URL](https://igniteme-7f641.web.app/)_

### Flutter and [FlutterFlow](https://flutterflow.io/)

Dart is not as popular a programming language as JavaScript, but it’s designed to be the unified programming language interface for all platforms, from iOS to Windows. The framework Flutter has adopted the design concepts of modern apps and made them into simple building blocks. Flutter is comparable to a combination of React, Nextjs, Tailwind, and DaisyUI in the JS world. It’s designed to be the all-in-one programming language for app development and is perfect for low-code/no-code solutions. Using FlutterFlow helps to encapsulate the unnecessary technical complexity while still having all flexibility in app design and development. It’s great for all kinds of app development, especially if you may want to expand the app from one platform to more options. Use JS or other low-code platforms if you’re building a static website such as a landing page or blog.

![FlutterFlow App](flutterflow.png)
_FlutterFlow App [App URL](https://empowermentcircle.flutterflow.app/)_

## Web Development is Complicated as Hell!

With the rise of ChatGPT and Github Copilot, lots of people see the possibility of building an application without learning how to code. While these AI coding tools show their incredible ability to generate and debug codes, they are yet powerful enough to create a sophisticated and successful web application because the complexity of web development is more than you could imagine. Let me unfold the complexity in four dimensions.

### The Technology

Web development heavily relies on collaboration with all kinds of packages and services. To make the simplest website work, you have to work with a variety of infrastructures, third-party APIs, frameworks, and development tools. Below is an unfinished list of “stakeholders” most front-end web developers need to deal with.

**The Incomplete List of Frontend Tech Stack**

- Web basics: HTML, CSS, and JavaScript
- JavaScript Frameworks: React, Vue, Svelte
- Meta Frameworks: Nextjs, Nuxtjs, SvelteKit, Astro
- CSS frameworks: Tailwind CSS, PostCSS, Sass
- UI Components: Material, Carbon, DaisyUI
- Compilers: Webpack, Vite
- Package Management: NPM, Yarn
- Toolings: TypeScript, ESLint, Prettier
- Version management: Git
- CI/CD: Github Actions
- Hosting: Netlify, Vercel, Firebase hosting

While the above list is already overwhelming, the backend development and administration require a whole different tech stack and skill set. And the learning is never-ending. Even the most experienced developers need to continuously learn as all the “wheels” they are using are changing every day. (e.g. the update of Nextjs 13 changes the entire project structure as well as the syntax for SSR/CSR rendering)

### The Management

The best way to get rid of the nitty gritty of coding is to let somebody do it. So, let’s say you managed to get some funding and decided to assemble a development team. A minimum team may include a product manager, a UI/UX designer, a front-end developer, and a back-end developer. Assume the best scenario, the hiring process and the team dynamics are going smoothly and you have the PRD (product requirement document) for the next release already. So can we expect the app development to come naturally? Unfortunately, No.

A PRD is a written design of the product, usually, you will need a more detailed visual design which we call prototypes. Then your engineers will start to work on the technical design such as the data structure, APIs, and service architectures before they start writing the first line of code. Now we have four ways to model the same product idea: a written version from PRD, a visual version from prototypes, another written (sometimes visual) version of the technical design, and the final program in codes.

Everything looks fine until we want to make a change. If we want to add one more table in the database for some extra information, here’s what we need to do: change the schema in the database, change the API accordingly, change the API call from the frontend side, and change the component that consumes the newly added data. To be noticed, these are just the work on the coding version of the product. What about the technical design, the prototype design, or the PRD? The reality is that it’s nearly impossible to maintain consistency across all these documents.

### The Business

The product development of a web app is an engineering process. But the truth is nobody cares about how you build it. The business side of the product has the same importance as (if not more than) the product itself. You need to think about your marketing strategy, your copywriting on your ads, and your sources of finance. I won’t unfold this part, as basically, we are talking about the entire curriculum of an MBA program. However, the challenge doesn’t even stop here.

### The Art (& Luck)

The unique combination of features you put together which reflects your unique opinions (or taste) on how things should work and appear plays a big role in the final result. People use your product because they believe or love your opinion. But you don’t know their reaction until you create and present the product to your audience. The business world has learned a lot from artists what they call “design thinking”, from the agile method to the lean startup approach.

That’s why I think web development is more like art. And just like any form of art, you need to master the skill of creating before expressing yourself freely. But the mainstream way of web development makes things way too complicated for creators. Why can’t we focus on what matters the most in the business and spend less time on unnecessary coding and debugging?

## 3 Principles of Web Development

The complexity of web development troubled me two years ago when I was in charge of a SaaS product rebuild. It’s now become my problem again as I decided to be a solopreneur to start my own SaaS business. So I decided to spend a month dedicatedly exploring the most ideal method for web development that is practical for solopreneurs like me or small founding teams. (See the journey [here]({% post_url 2023-08-01-saas-challenge %})). And here is what I learned.

### Building Blocks

A web application can be broken down into four parts, the business logic that differentiates the app from other apps, the user interface people interact with directly, the data structure that represents the relationship of information, and the servers the application runs on.

The first part is the soul of any app and where we should pour the most creativity. The last three parts are more standard, so it's better to put the least amount of effort into them. Thus I conclude with the following three principles:

1. **Design as code**
   Visual appearance is the ultimate expression of the front-end. Why should we do it once on the design tool and do it again in the codes?
2. **One schema rules all**
   Design schema once and use it in databases, APIs, or custom functions. Why do we need to update the database, the backend API, the frontend API call, and the frontend component, for every single change in schema?
3. **No more wheels**
   Use existing infrastructure as much as possible. Why should we manage our own hosting, database backup, microservices, and crash reports when every website needs to do it in very similar ways?

### My FFF Kit Stack

The FFF Kit is a portmanteau of FlutterFlow and Firebase, and its name is a tribute to [Jeff Delaney](https://twitter.com/Jeffdelaney23), the creator of [Fireship](fireship.io).

**Why do I choose FlutterFlow for Frontend**

- **All-in-one cross-platform language**
  Dart code can be compiled into mobile apps, web apps, and desktop apps with the same code base. Flutter framework provides templating, styling, and logic at the same time while we need to use HTML, CSS, and JavaScript together to do the same thing.
- **Build UI with the drag-and-drop visual builder**
  The design from FlutterFlow can be translated to high-quality Flutter codes as there is no need to worry about the countless evolving frameworks in the JavaScript world.

**Why do I choose Firebase for Backend**

- **Schemaless database**
  Traditional relational databases are backend oriented, the data structure is MECE. Document databases are more frontend oriented. GraphQL is an alternative if you are using relational databases but want to have a unified API interface.
- **Out-of-box backend services**
  Handle real-time data, authentication, and server-side functions out of the box. Build in A/B Testing, crash analytics, and extensions integrating Stripe, Agolia, and Google Cloud Platform services with few clicks

### FFF as Flexibility, Functionality, and Freedom

My favorite thing about this tech stack is that it gives you the full range of coding freedom without the need to learn programming syntax, and you have the full power of a modern app without the hassle of building your own wheels.

## Your Creativity Matters, Not The Tools You Use

I’m always an enthusiast of technology and cannot stop myself from learning and playing around with new tools, from Arch Linux, Termux terminal, Astro js, and all the possible packages and frameworks you can imagine. But the biggest lesson I learned from my 30-day challenge of building SaaS is quite the opposite, that all those tools don’t really matter.

Though I still have the impose to explore better coding tools, I learned to focus more on the product itself, the customers I’m building for, and the business model that make the software valuable.

### Great artists don't just use brushes

_"The brush is nothing but an extension of the artist's mind." -- Pablo Picasso_

My choice of FlutterFlow and Firebase as my tech stack doesn’t mean that they are the best option. They are just the most intuitive way for me to design, develop, and deploy my app. If you’ve plenty of experience in JavaScript, PHP, or other languages and have accumulated a library of your components or code snippets, then they are the best option for you. As that being said, I think my FFF kit (FlutterFlow + Firebase) is a great beginner package for developers with little experience or interest in programming but still want to express themselves in the form of an application.

### Wait, what about vendor lock-in?

_Freedom is an illusion._

The biggest critic of this tech stack is vendor lock-in. Yes, it is a real risk, but in my opinion, worth taking. Lots of people prefer open-source software and have a negative opinion of any paid services. But the reality is we don’t build things from scratch. Even the programming languages we are using are built and maintained by someone else. Instead of trying to own every piece of code, learning how to collaborate with others in a mutually beneficial way is more important. I believe that’s the spirit of open source. It just turns out that sometimes a paid service is a better business model to keep the software sustaining.

### What’s Next?

I hope my sharing has been of some help to you, and hopefully, inspire you to start on your own creation, just like other creators have done for me. I will keep posting my journey and thoughts on web development, entrepreneurship, and self-development. See you in the next post!
