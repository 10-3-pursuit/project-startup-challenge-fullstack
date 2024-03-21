# Project Startup Challenge 3 - FULLSTACK

<img src="lightbulb.png" width="500" height="500">

## Overview

You originally participated in a basic Startup Challenge in Module 2 using user research, user stories and pitches to present ideas. Then, in Module 3, you created a 'pseudo' fullstack Startup Challenge Poject using ReactJS and json-server.

Now it's time to build an actual fullstack application that persists data using ReactJS, ExpressJS & PostgreSQL and pg-promise.

You and your team now have the technical and intellectual capability to build out an MVP that solves an actual problem. Don't forget all of the tricks and code you've used in other projects.

**Programmers reuse code whenever they can!**

You are ultimately going to give a presentation that exhibits the problem you are trying to solve, the user (persona), for whom, you are trying to solve this problem, as well as present the actual functioning MVP application representing the first iteration of the solution.

This project has four parts:

1. The Pitch
1. Non-Coding Deliverables
1. The Application
1. The Presentation

## Part One: The Pitch

**You should have already completed this part and can skip to Part Two**

[Startup Challenge Pitch Instructions](https://github.com/10-3-pursuit/project-startup-challenge-pitch)

## Part Two: Non-Coding Deliverables

For Final Presentation, you will create 5 slides using Google Slides or any other power point type application.

**Slide Requirements:**

1. Team Name

1. The problem you are trying to solve

1. The solution to the problem

1. A persona representing a user of the application

1. Name of the app

Please refer to the [Slide Preparation](slide-prep.md) section to understand the details of this task.

### Planning Deliverables

In the readme.md of your Frontend Github Repo, you will create:

- A visual ERD of your table(s) for your database
- At least 5 User Stories
- 2 User Personas showcasing users with similar but different needs

#### Post these deliverables in your team Slack channel:

1. Your front and backend Github repos

1. Your Group Norms Doc Link . Refer to this [Group Norms Repo Link](https://github.com/10-3-pursuit/unit-react/tree/main/group-norms-and-teamwork) to review how to establish Group Norms.

1. You will set up a trello board (or another tracking systemd) where you invite your team members as well as the instructors. The trello board must have 3 minimum cards: `To Do`, `Doing`, and `Done`. You will post the link to your Trello Board to your Team Channel.

#### You will also create:

1. A snapshot of wireframes for each view of the application.

1. Diagram your component architecture. Clearly define how components will interact, including how state and props will flow. This visual representation will help your team better understand the structure of your application.

<img src="purple-matrix.png" width="400" height="250">

<sub>Shoutout Purple Cobras CodeRhythm</sub>

### Github requirements

1. Your team should be working on branches.
1. Teams should commit and push several times daily (we will monitor the repo commits).
1. Use the clone and branch method as a team on Github.
1. No hot fixes on the main branch without consulting a coach!

## Part Three: The Application

You will create and deploy an application that uses Vite, ReactJS, React Router 6.2.1, ExpressJS, PostgreSQL, pg-promise, CSS, and vanilla JavaScript. The application must have full CRUD functionality for one part of the application (e.g. comments, shopping cart, favorites, etc, your choice).

> **Note**: Your contributions to this group project must be equitable.
> Please also note that team members should work _across_ the stack. One team member should not be solely responsible for the CSS or non-coding deliverables, for example.

### Frontend Requirements:

1. One teammate should `fork` the [react-basic-starter](https://github.com/10-3-pursuit/react-basic-starter) and all other teammates should clone that teammates repo.

1. Your frontend repository should have a readme.md file with:

   - User Stories
   - Wireframe images
   - Setup instructions for your application
   - A Link to your deployed application
   - A Link to your local backend application

1. Your frontend repository should be built collaboratively. There should be commits from you and other developers on your team.

1. The application should have a coherent design and appear clean and easy to understand.

1. Responsive CSS is required with at least one breakpoint.

1. The frontend application should be successfully deployed to the web using netlify.com. To enable page refreshing, you will need to add an extra file called \_redirects. Please take a look at the [Netlify Deployment Resources](https://github.com/10-3-pursuit/10-3-resources/blob/main/netlify-deployment.md) for the solution, explanation and resources.

#### View Requirements

To complete the application, you will need to build a React application that implements the following features.

1. The application includes _at least_ five separate views:

   - Landing Page - [Landing Page Examples & Suggestions](https://www.wix.com/blog/best-landing-page-examples?utm_source=google&)
   - Header/Nav
   - About - You may transfer your about page from your former project or create one that aligns with the style of your new project
   - Main View
   - Detailed View
   - One Other View - this will be based on the architecture of your application

1. The application must fetch to your database to `create`, `read`, `update` and `delete` and persist the data.

1. For the `read` of CRUD the team must include both an `Index` view and a `Show` view.

#### Differentiation goals

This section of the project measures your ability to go above and beyond. To score points in this section, you should incorporate two features, technologies, or skills not explicitly required by the instructions.

_Make sure to include a description of any differentiating features you implemented inside your readme.md._ You may choose from the list below or come up with features or tasks that are more relevant to your specific implementation of the project.

**Ideas:**

- CSS Framework such as Bootstrap or Tailwind
- Favorites Feature
- Filtering and showing results by subject e.g. genres, tags, favorites, items in cart
- Comments on a resource that persist in the JSON server
- Sorting some data
- Searching for data
- Light Mode/Dark Mode
- Error Components
- Designed CSS 404 Page
- Programmatically upload and store images on Cloudinary and in your JSON as a string.
- Integrate an external React package such as [React DnD](https://react-dnd.github.io/react-dnd/about) or [Styled Components](https://styled-components.com/) or some other package. (research carefully)
- Use CSS Animations for your landing page and/or other views.
- Use Chart.js or another package that will enhance the application.
- Optionally, fetch and incorporate third party api data.

#### Routing

Use of React Router v6.2.1 is required. it is already included in the `package.json` of the React starter repo that you forked and cloned.

You must have a minimum of 4 Routes.

### Backend Requirements:

1. One teammate should fork and clone the [express-server-starter](https://github.com/10-3-pursuit/express-server-starter) and the other team members should clone it.

1. Setup routes, queries and controllers for each resource.

1. POST and PUT routes should have some type of validation either using middleware and vanillaJS or using [Express-Validator](https://express-validator.github.io/docs/)

1. Create a database schema with a minumum of 1 table and a maximum of 3

1. Seed data into your database in order to have data that can load on to a view at start.

### Optional User Login and Authentication Starter Usage

If your team feels they are capable of adding User Login to the application, you may **only** do this using the already prepared `User Auth login front and backend starters`.

#### Starter Github Repo Front and Backend Links

- [Backend](https://github.com/10-3-pursuit/auth-express-login)
- [Frontend](https://github.com/10-3-pursuit/auth-react-login)

#### Auth Starter Video Demos Front and Backend

- [Backend Part One](https://us06web.zoom.us/rec/share/zcUpuUEOD-u6rzCCDxVnsblnyZU2PKP5SpO3L9mEgvTC-KUc0yizYznlMBVeEv9V.DwBcjda5SJCZycvi?startTime=1710861741000)

- [Backend Part Two](https://us06web.zoom.us/rec/share/zcUpuUEOD-u6rzCCDxVnsblnyZU2PKP5SpO3L9mEgvTC-KUc0yizYznlMBVeEv9V.DwBcjda5SJCZycvi?startTime=1710864108000)

- [Frontend](https://us06web.zoom.us/rec/share/zcUpuUEOD-u6rzCCDxVnsblnyZU2PKP5SpO3L9mEgvTC-KUc0yizYznlMBVeEv9V.DwBcjda5SJCZycvi?startTime=1710865581000)

## Part Four: The Presentation

Your team will all participate in a presentation that lasts no more than 15 minutes.

### Your presentation will consist of the following:

1. 30 second introduction on who each of you are and how you decided to be a programmer. **Do not start with your name.** You may use the speeches that you already practiced in class.

   _Resources:_

   - [Snapshots of Our Journeys to Tech](https://github.com/10-3-pursuit/snapshots-of-our-journey-solo-intros) - instructions on how to create your intro.
   - [Self Introduction Presentation](https://us06web.zoom.us/rec/share/ItuyO7ddqIAnUP77YqHYM5KmfdrT6LD1QKGuQcu4vEt8YpRolQDgIlsyZF3Ta6M.58fyd3xaDSMKhuqO?startTime=1709651695000) - Video of your first shot at self introductions. Watch yourself and see how you could improve. Story? Energy Level? Confidence?

1. Slides to accompany your verbal articulation of:

   - Problem
   - Solution
   - Persona
   - App Name

   **Note:** Refer to the [slide prep instructions](./slide-prep.md) for clarity

1. Presentation of the working application.

1. Each person must speak to the application or the application introduction in addition to giving their own solo 30 second introductions.

1. Every member must describe a piece of code that they contributed to, either from the frontend or the back. Not both. For time's sake. You should use line numbers and technical vocabulary when describing the code.

### EXTRA RESOURCES:

**Checklist:**
Here is a [Checklist](checklist.md) of requirements. It is not a comprehensive list. Feel free to update and use this list at your convenience.

**Deployment Videos and Resources:**

- [Backend Deployment using Render.com pt.1](https://github.com/10-3-pursuit/10-3-resources/blob/main/render-deployment.md)

- [Frontend Deployment using Netlify](https://github.com/10-3-pursuit/10-3-resources/blob/main/netlify-deployment.md)

- [How To Create A Great Readme File](https://github.com/matiassingers/awesome-readme)

- [Design Tools](https://github.com/10-3-pursuit/10-3-resources/tree/main/project-tools)

- [UX Tools](https://github.com/10-3-pursuit/10-3-resources/blob/main/ux-tools.md)

- [UI/UX Resources](https://github.com/10-3-pursuit/10-3-resources/blob/main/user-experience.md)
