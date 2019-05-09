# Redline Projects

The redline projects are projects where you can show off your acquired skills. While making them you will also have some focus on working in a team, making tradeoffs and simulate some 'reallife' experience.

## Mode of operation

Each project is inspired by real situations and needs, but will not be given to a real customer. 


### kickoff: identify projects

### Phase 1 (guerilla style) : a one-pager in 8 hours.

**Learning objectives**

* Learn how to quickly create a website, based on existing templates. Guerilla style. 

* Understand by the absurd the interest of understanding a request well before coding.

**To be delivered**

You receive a project. Produces, in a few hours, an onepager (a **github page**) that proposes a better version of this project, using either a [CSS framework](http://cssframeworks.org/) or a template (for example: [html5up.net](https://html5up.net/)). Make sure that this page gets a **maximum score on the lighthouse test**.

During this phase, meeting the deadline is **Required and non negotiable**.

______________


### Phase 1 : (managed style) : study of the request

#### Learning objectives

- Find the questions to be clarified in order to be able to produce a digital project on a good basis and that is a relevant answer to a given problem.
- Explore Google Analytics

#### Procedure

The group identifies the client's needs and writes a detailed briefing to each other, asking all the questions that they think are relevant to the client.

The previous phase responded to emergency scenarios. Now, let's enter a diagram of a classic project where you have the time you need to work methodically. During this phase, the client answers all the questions asked by the solution team. Who is the customer? What is its activity? Who are its competitors? What is the problem to be solved? Who are the target audiences? Etc, etc.... This information is collected and formatted in a "specification" (or "briefing"), on the project repository (either in the repository itself or in the accompanying wiki).

#### Pedagogical sequences

- Group distribution (ideally: 3 max per group)
- The group agrees on the project, choosing the one that achieves consensus among the 3 one-pagers of the previous phase.
- group brainstorming: which questions to ask?
- Research in the style of a "web design questionnaire" and bring back as many interesting questions as possible to ask the client. Debrief as a group.
- Contact with the "[client](./your-client.md)": the group meets the "client" in a single interview of a maximum of 10 minutes during which the group asks all its questions to the client.
- Creating a rest (name starts with `redline-`).
- Drafting of a briefing / specifications in this rest period.
- Delivery of the rest to the team who will take over.

#### To be delivered

The rest containing the project management tools and information gleaned during the study.

- repository, with readme.md in markdown as the starting point for project documentation. ("the client", "the problem/opportunity", "objectives", "target audience"),
- the documents (rest wiki or sub-folder with markdown), 
- the issues,
- the kanban of project management ("github project"),
- the names of the team members under a subtitle "Customer Contact",
- define the KPIs (Key Performance Indicators) of the project (key performance indicators) and plan to track them in Google Analytics.

#### Time allowed

2 days, in groups.
______________


### Phase 2: Design of the "one-pager v2" solution

**Learning objectives**

* UX study of a responsive onepager, which announces the upcoming arrival of the solution. This page must include a newsletter registration form, functional, in a db) ---> UX prototyping via balsamiq and invision
* HTML/CSS integration of this onepager
* A client transaction -> server -> client -> client
* This site contains a MySQL table to receive emails from people subscribing to the newsletter
* Deployment on a traditional hosting provider, for example [hebergratuit.com](http://www.hebergratuit.com) or [https://www.hostinger.fr/](https://www.hostinger.fr/). Another free option: [heroku](http://heroku.com/) for the php, [freemysqlhosting.net](https://www.freemysqlhosting.net) for the MySQL database.

**To be delivered**

In the rest, add a link to the low-def prototype + high-def prototype of the onepager on invision, as well as the files of the onepager v2.

* Low-def prototype (balsamiq + invision.com)
* High-def prototype (figma.com)
* The one-pager in HTML/CSS/JS 
* The page must get the best possible score on the lighthouse test
* Implement Google Analytics and provide access to the customer's contacts (the team that wrote the specifications)

**Badges**

Possibility to obtain semantic HTML + CSS + Lighthouse badges

**Time allowed**: 5 days, in groups.

**Steps**
- Consult the follow-up table to know the project to be worked on for this phase.
- Fork the repository of the group in charge of the previous step.
- Activate the "Issues" of the repo (see "Settings")
- The team identifies the tasks and allocates them according to each member's learning objectives for this phase.
- Each task becomes an Issue assigned to the member of the group that obtained it
- Use the "Projects board" of the repo for task management / Issues (columns: todo / doing / Done)
- Readme: add the names of the team members for this phase.
- include the link to the online demo in the readme file.
- On the day of delivery, send the link to the readme on Ryver.

Use the same procedure for each relay between phases.
______________

### **Phase 3 : Creating a "multipage website "**

**Learning objectives**

* Client/server interaction
* "Mobile first" design method
* Use of CSS frameworks
* MVC architecture if ruby/php/python or react/angular/vue.js -> SPA (Single Page Application) framework

**To be delivered**

* An interactive prototype (in html/css/js) of a multi-page site, designed according to the "mobile first" approach and using a css framework of your choice.
* The content is static ( = does not come from a database) and contains at least 3 pages + 1 page with a form (e. g. a contact form)
* If MVC, realization of this static site using HTML, CSS, JS + PHP include() and MVC architecture (without the M).
* If SPA, think about semantics (read about[Fragments](https://blog.jmes.tech/react-fragment-and-semantic-html/)), separate the components (1 component = 1 molecule in Atomic Design ([read this] (http://bradfrost.com/blog/post/atomic-web-design/)))
* Each page of the site must obtain the best possible score on the lighthouse test (if React, read [this](https://medium.com/a-man-with-no-server/create-a-progressive-web-app-with-react-792ed8c69bc7) and for accessibility, read [this] (https://reactjs.org/docs/accessibility.html))
* The application must be recognized as a PWA on Android/Chrome, and therefore invite to install devices running on Android/Chrome on the homescreen.

**Badges**

Possibility to obtain semantic HTML + CSS, UX Prototyping, PHP basics badges

**Time allowed**: 7 days, in groups.

**Steps**
- Consult the follow-up table to know the project to be worked on for this phase.
- Fork the repository of the group in charge of the previous step.
- Activate the "Issues" of the repo (see "Settings")
- The team identifies the tasks and allocates them according to each member's learning objectives for this phase.
- Each task becomes an Issue assigned to the member of the group that obtained it
- Use the "Projects board" of the repo for task management / Issues (columns: todo / doing / Done)
- Readme: add the names of the team members for this phase.
- Include the link to the online demo in the readme file.
- On the day of delivery, send the link to the readme on Ryver.

Use the same procedure at each phase.
______________


### **Phase 4: development of a Backoffice (CMS)**

**Learning objectives**

* Dreate a basic CMS via MVC framework (minimum: CRUD and authentication)
* Database
* Ajax

**To be delivered**

- Allow the customer to update his site himself by adding a custom CMS, developed to measure.
  - be able to connect and disconnect
  - be able to add, modify and delete content from the "public" site
- Prototype (low-fi) of the CMS administration interface
- HTML/CSS/JS interface of the CMS administration, if possible using ajax to streamline the experience
- The CMS can be coded via an MVC framework

**Badges**

Possibility to obtain badges: MVC dev / OOP / CRUD.

**Time limit**: 30 days, in groups.

______________

### **Phase 5 : Mobile application**

**Learning objectives**

* Develop a first mobile application via cordova/ionic

**To be delivered**

Conversion of the multipage or frontend of the CMS into a native mobile app or Progressive Web App (optional) via a framework such as Cordova / ionic.

**Badges**

Possibility to obtain badges: Progressive Web App Builder / Mobile Native Builder.

**Estimated time available if cordova/ionic**: 3 days, in groups.


![Giphy](https://media0.giphy.com/media/3o751XEshooVby9y7e/giphy.gif?cid=348844935a58c2f9325a41615952d0b5)