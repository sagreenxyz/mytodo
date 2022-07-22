# My To-Do App

This is a application that is intended to explore the full-stack web development paradigm.  At the time of this initial writing, I intend to develop a simple todo application that will take in new tasks to be performed.  The app will also allow the user to view-edit-delete tasks to fully explore CRUD operations.  In addition, to explore database joins, the application will have the ability to maintain a dataset of users and allow the user who is signed-in to delegate a task to another user.

# Technologies

## Backend

The backend will be constructed of an Express.js server providing an API service.  Initially, the backend will also serve the pages in HTML and JavaScript to allow quick prototyping development.  The database will initially be an array of objects, and later migrated to a local instance of a relational database (SQLite) and then ultimately a separate PostgreSQL database.  Prisma will be the ORM, and seeding functionality will be provided.  As a polishing step, the HTML/JavaScript work will be replaced with a React view engine design.  And finally, the design will be enhanced to provide an outside user the ability to acquire an API key for a separate front-end to be developed.

## Front-End

Two front-ends will be developed.  To make the project quick to develop, the first front-end will be developed in React.  Afterwards, for comprehensiveness, an HTML and JavaScript version will also be created.

The styling for this project will be performed lastly with TailwindCSS and a proper UI library that is to be determined.  This will possibly be Material-UI (MUI).

## Technology Stack Links
**Backend**
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Prisma](https://www.prisma.io/)

**Database**
- [SQLite](https://www.sqlite.org/)
- [PostgreSQL](https://www.postgresql.org/)

**Front-End**
- [React](https://reactjs.org/)
- [Netlify Identity Widget](https://github.com/netlify/netlify-identity-widget)
- [TailwindCSS](https://tailwindcss.com/)
- [Material-UI (MUI)](https://mui.com/)

**Additional Items**
- [Git](https://git-scm.com/)
- [VS Code](https://code.visualstudio.com/)

# Development Phases

See [link](https://github.com/sagreenxyz/mytodo/wiki/Project-Progress#project-plan)
