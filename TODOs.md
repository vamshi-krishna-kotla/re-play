Terminal Command(s)
- trigger code when "replay" is run from terminal
- need to take parameters along with the command
- whenever the command is run, need to check if the executing path is a "re-play" project or not
    - should not run replay commands (other than template generation outside of a project)

Template
- a boiler plate template with basic elements on the main page
- if given a router option then add a routes file and corresponding handler logic
```
basic-template-example

- needed by default
├── .gitignore
├── node_modules
├── package.json
├── package-lock.json

- specifically generated from boilerplate
├── README.md
├── index.html
└── src
    ├── App.scss
    ├── App.jsx
    ├── index.scss
    ├── index.js
    ├── routes.js
    └── components
        └── hello.jsx
```
- allow SCSS and JSX file compatibility for first version

Background
- a dev server running with hot module replacement or auto reload feature
- a build step runner that packages the entire application code
    - target HTML for building should be taken from `index.html`
- server and client side build configs
- a production server that runs the app, after build step
