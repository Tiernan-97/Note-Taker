# 11 Express.js: Note Taker

## Your Task

Your assignment is to modify starter code to create an application called Note Taker that can be used to write and save notes. This application will use an Express.js back end and will save and retrieve note data from a JSON file.

The application’s front end has already been created. It's your job to build the back end, connect the two, and then deploy the entire application to Heroku.


## User Story

```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```


## Acceptance Criteria

```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```


## Methodology

I frist created a 404.html page to redirect users if they try to access a route that doesn't exist. Next I added fsUtils, express and uuid into my json package. Next, I focussed on the back-end connectivity. I modualrised the back-end by putting the notes get, delet and post requests into its own JS file. I looked at the name of the 'id' of the notes and used that in my get, delete and post requests. I exported the module and imported into my index.js file for the routes.

## Links

Repo: https://github.com/Tiernan-97/Note-Taker
Deployed Link: https://note-taker-tiernan-97-a72e549c1e13.herokuapp.com/