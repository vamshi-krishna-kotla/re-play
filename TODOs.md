1. Create new npm package
2. Add binary scripts to trigger the framework from terminal

Terminal Command(s)
- trigger code when "replay" is run from terminal
- need to take parameters along with the command
- whenever the command is run, need to check if the executing path is a "re-play" project or not
    - should not run replay commands (other than template generation outside of a project)

Template
- a boiler plate template with basic elements on the main page
- if given a router option then add a routes file and corresponding handler logic

Background
- a dev server running with hot module replacement or auto reload feature
- a build step runner that packages the entire application code
- server and client side build configs
- a production server that runs the app, after build step
