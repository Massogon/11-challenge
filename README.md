# Note Taker

## Description

The Note Taker application allows users to write, save, and delete notes. It uses an Express.js back end, saves and retrieves note data from a JSON file, and has a front end already created for the user.

## User Story

```md
AS A small business owner,
I WANT to be able to write and save notes,
SO THAT I can organize my thoughts and keep track of tasks I need to complete.
```

## Acceptance Criteria

```md
GIVEN a note-taking application,
WHEN I open the Note Taker,
THEN I am presented with a landing page with a link to a notes page.
WHEN I click on the link to the notes page,
THEN I am presented with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column.
WHEN I enter a new note title and the note’s text,
THEN a Save button appears, and the note is saved.
WHEN I click on an existing note in the list,
THEN the note appears in the right-hand column.
WHEN I click on the Write New Note button,
THEN I am presented with empty fields to enter a new note.
```

## Installation

To run this application locally:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/note-taker-app.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   npm start
   ```

4. Open `http://localhost:3001` in your browser to use the app.

## Usage

- Click "Get Started" to begin creating notes.
- Enter a note title and note content, then click the save icon to save the note.
- View saved notes by clicking them in the left sidebar.
- Add a new note by clicking the "+" icon.

## Technologies Used

- Express.js
- Node.js
- UUID (for generating unique note IDs)
- Bootstrap (for front-end styling)
- Render (for deployment)

## Deployed Application

You can access the deployed application here: [Live Application](https://your-app-url-on-render)

## License

This project is licensed under the MIT License.
