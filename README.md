# Project Startup Challenge FULLSTACK

<img src="startup.png" width="400" height="600">

You've now participated in a simple 'Startup Challenge' with user research, user stories and pitches. Then you created modified fullstack 'Startuup Challenge' using React and json-server. Now it's time to put it all together with React, Express & PostgreSQL.

You and your team now have the technical and intellectual capability to build out an MVP that solves an actual problem.

You are ultimately going to give a presentation showing the problem you are trying to solve, the user (persona), for whom, you are trying to solve this problem, as well as the actual MVP application representing the first iteration of the solution.

This project has three parts:

1. The Pitch
1. Non-Coding Deliverables
1. The Application

### Part One: The Pitch

**You should have already completed this part and can skip to Part Two**

[Startup Challenge Pitch Instructions](https://github.com/10-3-pursuit/project-startup-challenge/blob/main/README.md)

### Part Two: Non-Coding Deliverables

For Final Presentation, you will create 5 slides using Google Slides or any other power point type application.

**Slide Requirements:**

1. Team Name

1. The problem you are trying to solve

1. The solution to the problem

1. A persona representing a user of the application

1. Name of the app

Please refer to the [Slide Preparation](slide-prep.md) section to understand the details of this task.

#### Planning Deliverables

In the readme.md your Frontend Github Repo:

- You will create at least 5 User Stories
- You will create 2 User Personas showcasing users with similar but different needs

Post your Github repo address on your team channel in Slack.

1. Revisit your group norms and see if there are revisions that need to be made or new norms that need to be added. Post your Group Norms Link in the team Slack channel.

1. You will create wireframes for each view of the application. Try to include responsive wireframes as well.

1. You will set up a trello board where you invite your team members as well as the instructors. The trello board must have 3 minimum cards: `To Do`, `Doing`, and `Done`. You will post the link to your Trello Board to your Team Channel

1. Diagram your component architecture. Clearly define how components will interact, including how state and props will flow. This visual representation will help your team better understand the structure of your application.

<img src="purple-matrix.png" width="400" height="250">

<sub>Shoutout Purple Cobras CodeRhythm</sub>

### Part Three: The Application

You will create and deploy an application that uses Vite, ReactJS, React Router 6.2.1 `npm install react-router-dom@6.2.1`, Express, PostgreSQL, CSS, and JavaScript. The application must have full CRUD functionality for one part of the application (comments, shopping cart, favorites, etc, your choice). You may also incorporate a 3rd party api to give you data that is already created.

> **Note**: Your contributions to this group project must be equitable.
> Please also note that team members should work _across_ the stack. One team member should not be solely responsible for the CSS or non-coding deliverables, for example.

### Github requirements

1. Your team should be working on branches
1. Teams should commit and push often (we will monitor the repo commits)
1. No hot fixes on the main branch without consulting a coach

### Frontend Requirements:

1. The front-end application should be successfully deployed to the web using netlify.com. To enable page refreshing, you will need to add an extra file called \_redirects. Please take a look at the [Netlify Deployment Resources](https://github.com/10-3-pursuit/10-3-resources/blob/main/netlify-deployment.md) for the solution, explanation and resources.

1. Your front-end repository should have a readme.md file with: - User Stories - Wireframe images - Setup instructions for your application. - Links to your deployed application.

1. Your front-end repository should be built collaboratively. There should be commits from you and other developers on your team.

1. The application should have a coherent design and appear clean and easy to understand.

1. Responsive CSS is required with at least one breakpoint.

#### View Requirements

To complete the application, you will need to build a React application that implements the following features.

1. The application includes _at least_ five separate views:

   - Landing Page - [Landing Page Examples & Suggestions](https://www.wix.com/blog/best-landing-page-examples?utm_source=google&)
   - Header/Nav
   - About - You may transfer your about page from your former project or create one that aligns with the style of your new project
   - Main View
   - Detailed View
   - One Other View - this will be based on the architecture of your application

1. The application must fetch to your JSON Server to `create`, `read`, `update` and `delete` data.

1. For the `read` of CRUD the team must include both an `Index` view and a `Show` view.

1. The app may, optionally, fetch and incorporate third party api data.

#### Differentiation goals

This section of the project measures your ability to go above and beyond. To score points in this section, you should incorporate two features, technologies, or skills not explicitly required by the instructions.

_Make sure to include a description of any differentiating features you implemented inside your readme.md._ You may choose from the list below or come up with features or tasks that are more relevant to your specific implementation of the project.

- Shopping Cart
- Favorites Feature
- Filtering and showing results by subject e.g. genres, tags, favorites, items in cart
- Comments on a resource that persist in the JSON server
- Sorting some data
- Searching for data
- Light Mode/Dark Mode
- Error Components
- 404 Page
- Implement more than one API, using both datasets to create a new use case.
- Programmatically upload and store images on Cloudinary and in your JSON as a string.
- Integrate an external React package such as [React DnD](https://react-dnd.github.io/react-dnd/about) or [Styled Components](https://styled-components.com/) or some other package. (research carefully)
- Use CSS Animations for your landing page and/or other views

#### Routing

Use of React Router v6.2.1 is required. `npm install react-router-dom@6.2.1`

You must have a minimum of 4 Routes.

### Backend Requirements:

1. You will create a backend server.

1. You will setup routes and database.

1. You will seed data into your database in order to have data that can load on to a view.

1. A minimum of two tables will be needed for this project.

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
