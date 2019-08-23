# Land Info Demo - Wednesday, Aug 21st, 2019

### Disclaimers

- [ ] All data is a copy of existing data.  We won't be messing around with the data you're working with now; all changes are for our testing purposes only.
- [ ] Everything is running off my own machine, not online.

### Main outline

- [ ] Register new user (use any email; will have to register new accounts.  Email will not be sent to you, it's just a username)
- [ ] Sign in with the email you just used
- [ ] Drawings
  - [ ] Search, navigate to different pages, change number of entries, change sort order
  - [ ] Create a new drawing
  - [ ] Edit the drawing we just created
  - [ ] Link to drawing file (TBC: I don't have access)
  - [ ] Hover over text to show full text description.
- [ ] Surveyors
  - [ ] Same thing: can view and create new surveyors
  - [ ] Cannot edit existing surveyors, because that wasn't available in the old app either
  - [ ] Can delete surveyors.
- [ ] Marine files
  - [ ] Can only view and delete, not create or edit
- [ ] Plan files
  - [ ] CREATE new plan file
    - [ ] Link to most recent survey file. 
    - [ ] Try to give it the name of an existing plan file, show error
    - [ ] Create and show on table.
  - [ ] EDIT existing plan file
    - [ ] Click on a file to get data
    - [ ] Click on another file to get data; warning modal pops up
  - [ ] PRINT plan file
    - [ ] Show countdown to print
  - [ ] EDIT a parent survey file
  - [ ] VIEW drawings for a given plan file
    - [ ] Show OLD APP
    - [ ] CREATE drawing for this plan file
    - [ ] DELETE a drawing for this plan file.
  - [ ] NEW VERSION is still in development.
- [ ] Survey files
  - [ ] CREATE new survey file, again with existing number
  - [ ] VIEW plan files for given survey file
    - [ ] Option to edit survey files on this screen isn't here
    - [ ] Try to CREATE a plan file to another survey file (4444.01), show modal popup
    - [ ] Try to EDIT and REASSIGN a plan file to another survey file (4444.01), show modal popup
    - [ ] Can edit drawings for a given plan within this.
    - [ ] PRESERVE SEARCH and PAGINATION when exiting out
  - [ ] PRINT survey file
  - [ ] DELETE survey file
  - [ ] NEW VERSION is still in development
- [ ] LOG OUT

### Things we're still working on

- [ ] NEW VERSION: awaiting clarification for plan files
- [ ] Linking to GCDocs for survey files (and drawings?): awaiting clarification
- [ ] Only allowing Approved users to log in after signing up
- [ ] Minor bugfixes and cleanup, testing.
- [ ] Edit surveyors
- [ ] Automatically assign plan numbers, survey file numbers

### Known bugs

- Using a custom alphabetical prefix for a plan file is a little weird (already found a fix)
- Clicking a Survey File when on the plan files screen can still keep the plan file form hidden, and if something goes wrong, the screen goes blank. (already found a fix)
- Visiting the website for the first time takes you to the homepage, no login option (already found a fix)
- Creating a plan file and giving it a survey file that doesn't exist should give you a warning (already found a fix, but not in master branch yet)