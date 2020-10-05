# Title :: Note Taker

  ## Table of Contents
  * [Title](#Title)
  * [Description](#Description)
  * [Installation](#Installation)
  * [License](#license)
  * [Contributors](#Contributors)
  * [Preview](#Preview)
  * [Questions](#Questions)

  ## Description:
  This application can be used to write, save, and delete notes. This application will use an express backend and save and retrieve note data from a JSON file.

  * The following API routes can do the following:

  * GET `/api/notes` - Should read the `db.json` file and return all saved notes as JSON.

  * POST `/api/notes` - Should receive a new note to save on the request body, add it to the `db.json` file, and then return the new note to the client.

  * DELETE `/api/notes/:id` - Should receive a query parameter containing the id of a note to delete. This means you'll need to find a way to give each note a unique `id` when it's saved. In order to delete a note, you'll need to read all notes from the `db.json` file, remove the note with the given `id` property, and then rewrite the notes to the `db.json` file.

  
  ## Installation
  Clone the repository to your local development environment.

  git clone https://github.com/sxiong6901/NoteTaker
  Navigate to the developer-profile-generator folder using the command prompt.

  Run npm install to install all dependencies. To use the application locally, run node server.js in your CLI, and then open http://localhost:3000 in your preferred browswer. The Note Taker app is live on Heroku for you to use as well.

  ## License
  MIT License - URL: https://github.com/sxiong6901/GoodReadMeGenerator/blob/master/LICENSE
  
  ## Contributors
  https://github.com/sxiong6901
  
  ## Preview
  ![Testing](https://github.com/sxiong6901/GoodReadMeGenerator/blob/master/assets/Generating%20README.md%20File.gif)
  
  ## Questions
  If you have any questions, contact sxiong6901 on GitHub.