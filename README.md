# The Technical Fundamentals Project

A lot of people have been impacted by a difficult hiring market in the tech industry in 2022 and beyond.

Whether you're a new graduate from a college, university, or code school, or even self-taught, the inspiration of this project was to help each individual practice a core set of fundamental skills by building a single project.

## Leveling of the Skills

Primarily, this is meant to be a list of ENTRY-LEVEL skills, since I do a lot of career coaching with new graduates, and NOT meant to be an exhaustive list of things that a senior-level applicant "should" know to get a job later in their career.

However, I also use these skill lists whenever I want to learn a new technology. If I'm a middleware developer and want to switch from Rails to Django, I have a list of things I can follow to learn to implement. If I'm a front-end developer switching from React to Vue, I also have a list of core skills to implement. And so on.

For those coming out of college/university, you might not have some of these skills. Coming out of a bootcamp/program, you might have worked on a small part of a large team project and don't feel confident that you could individually build some of these things. And if you're self-taught, my hope is that this will be a guiding point of things to build and practice.

## Table of Contents:
- [The Technical Fundamentals Project](#the-technical-fundamentals-project)
  - [Leveling of the Skills](#leveling-of-the-skills)
  - [Table of Contents:](#table-of-contents)
  - [What this project is about:](#what-this-project-is-about)
  - [What this is NOT:](#what-this-is-not)
  - [Pull requests welcome](#pull-requests-welcome)
- [GOALS](#goals)
- [The Fundamentals](#the-fundamentals)
  - [A not about Full-Stack Development](#full-stack-development)
  - [Front-end Development](#front-end-development)
  - [Middleware Development](#middleware-development)
  - [Back-end API Development](#back-end-api-development)
  - [QA Engineering](#qa-engineering)
  - [DevOps](#devops)
- [Community and Accountability](#community-and-accountability)
  - [Public accountability](#public-accountability)
- [Sponsorship \& Community Involvement](#sponsorship--community-involvement)


---

## What this project is about:

The heart of this project is merely the implementation of a set of core skills that demonstrate your individual ability to build something with these fundamentals in mind.

It is a checklist of ideas for you to build into a project, which you can maintain over time. **It is tech stack agnostic** -- aside from some front-end skills like JavaScript and HTML, the list of skills should not include specific programming languages, frameworks, databases, etc. no matter their popularity. You can choose to implement these skills in whatever tech stack you want, and you can choose to implement them in whatever order you want.

I want this to be a community-driven effort to support one another. Encourage each other to keep going when you are feeling discouraged or stuck. Help each other get past any hurdles that are blocking your progress.

## What this is NOT:

1. This is not a group project, nor a group effort. YOU need to know these skills, so YOU can talk about these skills in your interviews, therefore YOU need to build these in an individual, solo project. If someone needs help, you should GUIDE them to the answer, not GIVE them the answer, nor write the code for them. You won't be there in their interview...

2. I don't want this to become a gate-keeping list that we see so often, saying "you must know these 50 things or you are not a competent developer/devops/qa." In fact, I want to avoid the word "should": you "should" know this, you "should" be able to demonstrate this, you "should" be able to talk about this. Every company will have different skills for which they are interviewing. They will need some of these skills found in this project, and not need others. They may need skills not included in this project, but you can always add those things later. If you want to take a "generalist" career path, you'll want to take a little bit from all of these disciplines.

3. This is NOT a project that I expect you'll put on a resume. You can certainly extend the project and use it as a launching point to start new projects if you choose. But if implemented as-is, it probably will not look too fancy, and may feel unfinished. That's okay. The goal is to demonstrate your knowledge of these skills, not to build a fancy production-ready project.

## Pull requests welcome

I am very open to communication about things that the community would like to see on these lists, and alternate prioritization ideas. I just don't want the lists to become huge. Let's work to keep them simple, aimed at new graduates.

# GOALS

**I want to help people get jobs.** Our tech industry is one where demonstration of your skill is a necessary portion of the interview process, as well as technical communication. By building this project, you will be better prepared to execute ideas in technical challenges and take-home assignments, and speak to the purpose of each of these skills as a web developer.

**Practice Makes Better.** Building this project will allow you to practice these fundamental skills in a single environment, instead of having a larger number of projects (or smaller personal involvement in larger projects) trying to showcase each of these skills.

**Self-paced, no deadlines.** Building this application quickly won't guarantee you a job any more than working at it methodically and carefully. However, you will prioritize working on this project in a way that represents your urgency of finding a new job.

---

# The Fundamentals

(last updated June 2023)

These fundamental skills are broken down first by job role, and then by "core skills" and "nice to have" skills. They are prioritized by the community and ideally added to your application in this order. Ultimately, this is YOUR project to implement, so build it however you feel makes sense to you or to highlight the kinds of skills YOU want to present to a hiring company.


## Full-Stack Development

I've removed the "full stack" development list, as "full stack" means a lot of things to a lot of people. Instead, draw on the core fundamental skills that multiple disciplines know and use, and you can choose for yourself which pieces of information you want to focus on knowing.


## Front-end Development

A front-end developer deals with user interactions, user interface controls, and the overall "experience" of the application. This list contains the only "specific" technologies in the project, being JS, HTML and CSS).

#### Core Skills:

- JavaScript
- HTML/CSS and data presentation
- understanding of Framework / components / routing
- event handling
- user input (building forms, setting up browser-side validation)
- async data fetching
- parsing complex data payloads
- global state management

#### Nice-to-have Skills:
- accessibility standards
- authentication (workflow of login, starting the OAuth flow, etc)
- Web security topics (OWASP Top Ten) which are applicable to front-end, such as protecting against click-jacking or cross-site scripting vulnerabilities.
- Behavior-driven or Test-driven development


## Middleware Development

Middleware is the "glue logic" that helps tie together a front-end application with back-end APIs. It probably includes some database work and maybe a little HTML, but isn't what I would consider "full-stack".

#### Core Skills:
- MVC design pattern in your framework of choice
- form processing (CRUD)
- ORM for storing/retrieving data from a database
- handling authentication requests (finishing the OAuth workflow)
- determining authorization access (what are they allowed to do)
- consume third-party APIs
- parsing and building complex data payloads

#### Nice-to-have Skills:
- Web security topics (OWASP Top Ten) especially around data handling, and user access controls
- Test-driven Development, maybe some behavior-driven development


## Back-end API Development

Back-end development is more "behind the scenes" work, and processing of data, with less direct user interaction. A typical back-end developer will be storing and retrieving data in some sort of database, or getting and transforming data to or from a third-party API service.

#### Core Skills:
- building API endpoints to industry standards
- ORM for storing/retrieving data from a database
- handling authentication requests (managing API keys, etc)
- determining authorization access (what are they allowed to do)
- parsing and building complex data payloads

#### Nice-to-have Skills:
- Web security topics (OWASP API Top Ten) especially around data handling, and user access controls
- OAuth (do something on behalf of the user)
- Test-driven development


## QA Engineering

The idea of QA Engineering is testing system compatibilities, determining the root cause of problems, and automating these tasks.

#### Core Skills:
- reading and writing software tests
- building test strategies across many systems
- service-oriented architecture and system communication (APIs, data payloads, etc)
- automated test environments and CI/CD pipelines
- strong code revision skills to 'cherry pick' specific branches for testing
- building automation through scripting/programming
- some use of bug tracking and reporting systems
  
#### Nice-to-have Skills:
- defect tracking and reporting tools
- some amount of programming skills in the languages used to generate the software you're testing


## DevOps

DevOps means a lot of things to companies and encompasses many areas of automation, some amount of system-level scripting, and setting up systems for deployment.

#### Core Skills:
- operating system fundamentals (Linux, Windows, etc) for your system of choice
- shell scripting (Bash, PowerShell, etc) or other scripting languages (Python, Ruby)
- basic use of monitoring systems, logging, and alerting
- basics of containerization and orchestration
- scripting and knowledge of automating repetitive tasks
- cloud infrastructure basics
- basic use of CI/CD pipelines 

#### Nice-to-have Skills:
- some use of infrastructure-as-code
- some use of system installation and setup/configuration automation

---

# Community and Accountability

I have two goals in mind for community, and must conform to an agreed-upon set of community behavior guidelines for conduct. What I DON'T want is for a hundred Discord communities to start popping up with their own rules or exclusions. Nor do I want to be in charge of setting up a "central" place to communicate. But I *do* feel it is best if the community finds a way to have regular conversation about their progress.

1. **A regular check-in of some kind: with each other, and with mentors.**
    - For the "with each other" check-in, it doesn't have to be a daily stand-up, but the community needs a place where people feel comfortable talking and sharing their progress or where they're stuck. Hold each other accountable, form smaller accountability teams where you'll notice if someone is NOT there or not making progress. Talk about where you're stuck, ask for helpe.
    - For meeting with mentors, ideally a weekly 1-hour or 2-hour public "office hours" session where mentors can facilitate help at a high level. (not all mentors will necessarily have experience with the tech stack you choose) Mentors have some amount of professional development experience in the workplace. (at least 2 years, ideally 4+ years)
    - Regular "be proud of your work" demo time. Perhaps this is part of the mentor office hours where the call begins with demonstrating some portion of your project. It is important that this doesn't become a showcase of how quickly someone can code, or how brilliantly someone designed an interface, or this will discourage others from making progress. There's a difference between being proud of your work, and showing off.

2. **Group Communication, but Solo Execution.** While it's imperative to have community help when you get stuck, it's important that YOU are the one writing the code, not just copying/pasting snippets of code from sources you find online.
    - Pair programming is helpful and encouraged, as long as someone else is not contributing code directly to your project.
    - Individuals openly share their code, and their progress, publically. Posting on social media is a great way to start, and community members can help support those posts with likes, comments, etc..

## Public accountability

People who write about their progress on a regular basis may find networking with other professionals a little easier. If you can get community members to re-share your post, or even just to like it, comment on it, etc, it will promote your post to other peoples' timelines, increasing the exposure of your work.

**Important: Do NOT write your progress as a series of "how-to" articles.** These kinds of posts quickly go out of date, and you will get more negative responses about how that wasn't the "correct" way to do something.

Instead, post TWICE PER WEEK on your platform of choice which includes a brief summary of your progress.

The very first post will contain the following:
- that you're working on a new project
- please link to this repo :) as your inspiration to get started
- mention the frequency/cadence of how often you'll post about your progress
- ask for encouragement and to like/reshare your content -- be SHAMELESS about this, people are less likely to do it if you don't ask for it

> I am starting to work on a new project which showcases my knowledge of web development fundamentals. I'm following a guide found at https://tig.fyi/project and will be posting notes about my progress every Monday and Thursday until I finish, or until I find a new job, whichever comes first. I would love any encouragement from my network. Please add a like to this post to help others in your network see that I'm looking for a new job.

After that, your regular posts should cover the following 4 points, but you can rearrange them however you like so it doesn't look/sound repetitive. Each point should be one to three sentences:
- here's some progress I've made recently on my project that I'm proud to talk about
- here's an area where I got stuck
- here's a helpful resource related to all of this content, or how I got unstuck
- I'm looking for a job, please introduce me to people in your network

Here are some examples that you can expand upon (I'm only doing one sentence per point above):

> Over the last few days, I implemented ORM functionality into my ongoing project to save/retrieve data from a MySQL database. I had trouble getting MySQL installed, but I found a great guide at http://blahblahblah.com that helped. Next, I'll be adding some user roles to implement authentication and authorization! Please add a comment below about what you think of my progress! If you want to see my commit history, check out my repo at ...
 
> I'm working on a project that showcases my fundamental knowledge of web development including things like API consumption, HTML layouts and testing; here's a link to the repo if you want to follow along. This week I've been putting in most of my effort into the testing aspect, but I was getting stuck on some automation processes for CI/CD pipelines. Here's a link to a resource that got me unstuck, hopefully it'll help others. By the way, I'm looking for full-time work, and I would appreciate any engagement with this post, and introductions to any recruiters at your company.

> I'm currently looking for full-time work as a full-stack developer, so any introductions to a recruiter at your company would be welcomed. As part of my journey, I wanted to explore how to do some complex data storage for a project I'm working on (insert github repo link), and I found a post by (insert author) about (summarize the title). Turns out they're going to be speaking at virtual event/meetup/whatever (insert link) so I'm excited to continue my learning. Throw a comment on this post if you know any other similar resources that could help me out!


---

# Sponsorship & Community Involvement

This project was brainstormed and kicked off by [Ian Douglas](https://linkedin.com/in/iandouglas736), a long-time tech industry professional programmer and educator. Ian [live-streams on Twitch](https://tig.fyi/live) about career advancement and interview preparation, and has a lot of [free content online](https://techinterview.guide) and on [YouTube](https://youtube.com/iandouglas). Ian first started working on this project outline idea as part of his job coaching in late 2021.

Efforts to launch this project idea began with staff and students from [The Turing School of Software & Design](https://turing.edu) in January and February 2023.

Ultimately, the goal of this project is to reach beyond Turing and serve a wider community where we can rally around one another for support and encouragement.
