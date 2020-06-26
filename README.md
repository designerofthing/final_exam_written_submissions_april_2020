## Written submission
Please provide written answers to / explanations on the following topics.

Make a PR with your submission to this repository.

## Product/System features
Please explain the steps you think are necessary to perform to get a feature done, from an idea to an implemented solution that is running in production. Be as detailed as possible.


Assuming their is a product owner that provides the initial idea:  
Start with a design sprint to establish lo-fis, from them a list of features are created and then epics, chores and user stories are to be created.  These are then entered into the icebox of say pivitol tracker.  Then the fun part, deciding on the amount of stories for a sprint, then for each story, acceptance criteria are made.  Once the acceptance criteria are made the team votes on the complexity and they are placed into the current iteration for the sprint.
they work on the stories, having scrums daily at the same time, once the sprint is completed, a retro is held to discuss what has happened, what went well, what can be improved for the next sprint.  
This process is repeated until the time allowed is up or the stories are finished.  After all iterations are retro's held. 



## Scrum vs Kanban
Please explain the major differences between the named Agile frameworks. Which one did we practice during the bootcamp? Can you see any arguments for using a different framework in a specific project or projects?


Kanban uses no defined roles, special workboards and no required timeboxes, scrum has a master, team members and product owner, use iterations that are timeboxed and have heavy emphasis on complexity points.

## Continuous Integration
Explain what continuous integration is and what benefits you can see it brings for teams development workflow. Please refer to your own experience.

CI is using an automated process to continually test your work as you incrementally increase the size of the project, it ensures that everything you add to the project is tested before being intergrated into the main branch hus causing less catosrophic problems as the problems can be localised and identified easily.  I have used semaphore and it is very easy to set up and runs in the background, it is the last tick before I successfully submit a pr for merging.


## Automated tests
What are the various types of testing strategies covered under automated testing? What benefits do each of them bring to the table?

Unit/Component tests for logic and functionality, small parts of a project.  allow problems to be seen quickly and more scoped down.
Acceptance testing for the whole project covers all of those parts and how they interact.  Ideally both should be used in a project depending upon how involved it is.   