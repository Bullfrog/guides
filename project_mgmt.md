# Project Management Guide

## Cloud Office

The cloud office web application uses a _continous deployment_ workflow. This means that features are released immediately upon being ready. There are no version numbers or releases. There is no scheduled release hour (except in special circumstances).

As a result we will manage the process using the Trello board: **Cloud Office**.  Each card on the board represents a feature, bug, task, idea, chore, etc; collectively called _stories_.

### Stages

There are 5 stages setup on the board:

1. Backlog - These are stories that are not prioritized, maybe they aren't fully formed or ready to be worked on. Backlog is a dumping ground of ideas or things we should or might work on in the future.
1. Upcoming - These are stories that have been vetted and are ready to be worked on. The stories should be considered in priority when choosing the next story to work on.
1. Active - These are stories currently being worked on.  Make sure your face is on the story if you are working on the story.
1. Staging - Stories that have been completed and are live on the staging server. Any team member that should take a look at the stories result should be added at this point. When the story has been reviewed it can be _green lighted_ for production.
1. Released - Stories that are live on the production site and considered done.  These will periodically be archived.

### Labels

 * Red - High priority: For extremely high priority stories. The queue priority should generally be used to indicate stories priority. Red labelling should only be used in extreme circumstances to draw extra attention to a story.
 * Green - Green Light: This label indicates that a story in staging is ready to be released to production. Stories will not be committed to production until they are green lit.
 * Blue - Bug: Any bugs in the system should be labeled as Blue to help delinate them from other stories.

### Creating Stories

When creating stories, it is very important to ensure that any stakeholders in the story are assigned at the stage they are required. Generally this will be whenever the story is made. Stories can generally be added to Backlog, Upcoming, or Active (if you are immediately working on the story after creating it).

### Creating Boards
