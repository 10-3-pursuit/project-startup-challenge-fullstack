# Project Startup Challenge

<img src="ads_600x400.png" width="600" height="400">

Remember the fun [Startup Challenge](https://github.com/10-3-pursuit/startup-challenge) that we had a while ago? Well your team is going to take this a step futher in the `Project Startup Challenge.`

You and your team now have the technical and intellectual capability to build out an MVP that solves a solid business problem.

You are ultimately going to give a presentation showing the problem you are trying to solve, the user, for whom, you are trying to solve this problem, as well as the actual MVP application representing the first iteration of the solution.

This project has three parts:

1. The Pitch
1. Non Coding Deliverables
1. The Application

### Part One: The Pitch

Your team will conceptualize two web app startup ideas and application, focusing on a unique problem-solving approach.

You can use this Slide (or create your own) to present your ideas.
[Pitch Slide](https://docs.google.com/presentation/d/1qK14oA9yGXFtaGepRByEBg_T0r2IblGUeZTuUw8fdNw/edit#slide=id.g232c0c426ca_0_200)

Each idea will answer three questions:

1. What does the app do?

1. What problem does the app solve

1. Who is this app for?

You will pitch these ideas to the full cohort and instructor. Afterwards, there will be a vote.

Based on the vote, you will build out both a presentation and an application.

\*\*\* Note: Based on feasibility and uniqueness the instructors may choose against the vote.

### Part Two: Non-coding Deliverables

For Final Presentation, you will create a Google Slides (or any other power point type application) with exactly 5 slides

1. Team Name - with Team members names also written on it

1. The problem you are trying to solve

1. The solution to the problem

1. A persona of a user who's problem this app will solve

1. Name of the app

Please refer to the [Slide Preparation](slide-prep.md) section to understand the scope of this task.

#### Planning Deliverables

1. In your Frontend Github Repo:

- You will create at least 5 User Stories
- You will create 2 User Personas

Send your instructors your Github repo address in one thread in Slack.

1. You will create wireframes for each page of the application. Try to include responsive wireframes as well.

1. You will set up a trello board where you invite your team members as well as the instructors. The trello board must have 3 minimum cards: `To Do`, 'Doing`, and  `Done`. You will post the link to your Trello Board in your Team Channel

1. Diagram your component architecture. Clearly define how components will interact, including how state and props will flow. This visual representation will help your team better understand the structure of your application.

1. Revisit your group norms and see if there are revisions that need to be made or new norms that need to be added. Post your Group Norms Link in the team Slack channel.

### Part Three: The Application

You will create and deploy an application that uses Vite, ReactJS, React Router 6.2.1 `npm install react-router-dom@6.2.1`, JSON Server, CSS, and JavaScript. The application must full CRUD functionality for one part of the application (comments, shopping cart, favorites, etc). You may also encorporate a 3rd party api to give you data that is already created.

> **Note**: Your contributions to this group project must be equitable. Failure to make meaningful individual contributions to this project may lead to a separate assessment of some kind or a failing grade.
>
> Please also note that team members should work _across_ the stack. One team member should not be solely responsible for the CSS or non-coding deliverables, for example.

### Frontend Requirements:

1. The front-end application should be successfully deployed to the web using netlify.com.

Your front-end repository should have a readme.md file with: - User Stories - Wireframe images - Setup instructions for your application. - Links to your deployed application.

1. Your front-end repository should be built collaboratively. There should be commits from you and other developers on your team.

1. The application should have a coherent design and appear clean and easy to understand.

#### View Requirements

To complete the application, you will need to build a React application that implements the following features.

1. The application includes _at least_ five separate views:

   - Landing Page - [Landing Page Examples & Suggestions](https://www.wix.com/blog/best-landing-page-examples?utm_source=google&)
   - Header/Nav
   - About - You may port your about page from your former project or create one that aligns with the style of your new project
   - Main View
   - Detailed View
   - One Other View - this will be based on the architecture of your application

1. The application must fetch to JSON Server to `create`, `read`, `update` and `delete` data.

1. For the `read` of CRUD the team must include both an `Index` view and a `Show` view.

1. The app may also fetch a 3rd party api data if it will add to the application.

1. You must choose at least 2 of these options ( or submit options of your own) outside of the CRUD functionality:

   - Shopping Cart
   - Favorites Feature
   - Filtering and showing results by subject e.g. genres, tags, favorites, items in cart
   - Comments on a resource that persist in the server
   - Sorting some data
   - Searching for data

#### Routing

Use of React Router v6.2.1 is required. `npm install react-router-dom@6.2.1`

#### Stretch goals

This section of the project measures your ability to go above and beyond in creating your project. To score points in this section, you should incorporate a feature, technology, or skill not explicitly required by the project instructions.

_Make sure to include a description of any stretch goals you implemented inside your readme.md._ You may choose from the list below or come up with features or tasks that are more relevant to your specific implementation of the project.

- Implement more than one API, using both datasets to create a new use case.
- Integrate an external React package such as [React DnD](https://react-dnd.github.io/react-dnd/about) or [Styled Components](https://styled-components.com/) or some other package. (research carefully)
- Programmatically upload images to Cloudinary
- Use a modal for your forms
- Use CSS Animations for your landing page and/or other views

### Backend Requirements:

- You will `fork` and `clone` the [JSON Server Starter](https://github.com/10-3-pursuit/json-server-starter) to be deployed, later, to render.com
- You will create (seed) data into your JSON Server in order to have data that can load on to a view. We call this seeding the data.

- You will place this data in two separate files as noted in the JSON Server Videos. The `db.json` file and the `originalData.json` file.

- Reference these videos to understand how to seed your data: [JSON Server Videos](https://github.com/10-3-pursuit/10-3-resources/blob/main/json-server.md)

### EXTRA RESOURCES:

Deployment Videos:

- [Backend Deployment using Render.com](https://github.com/10-3-pursuit/10-3-resources/blob/main/render-deployment.md)
- [Frontend Deployment using Netlify](https://github.com/10-3-pursuit/10-3-resources/blob/main/netlify-deployment.md)

[How To Create A Great Readme File](https://github.com/matiassingers/awesome-readme)

[Design Tools](https://github.com/10-3-pursuit/10-3-resources/tree/main/project-tools)

[UX Tools](https://github.com/10-3-pursuit/10-3-resources/blob/main/ux-tools.md)
