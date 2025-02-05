# Keeper App

Keeper App is a simple note-taking application built using React. It allows users to add and delete notes dynamically.

## Features
- Add new notes with a title and content.
- Delete notes when they are no longer needed.
- Responsive and user-friendly UI.

## Installation


1. Install dependencies:
   ```sh
   npm install
   ```

2. Run the project:
   ```sh
   npm start
   ```

## File Structure
```
📂 src
 ┣ 📂 components
 ┃ ┣ 📜 App.jsx
 ┃ ┣ 📜 Header.jsx
 ┃ ┣ 📜 Footer.jsx
 ┃ ┣ 📜 Note.jsx
 ┃ ┗ 📜 CreateArea.jsx
 ┣ 📜 index.js
 ┣ 📜 styles.css
```

## Components

### App.jsx
- Manages the state of notes.
- Includes functions to add and delete notes.
- Renders `Header`, `CreateArea`, `Note`, and `Footer` components.

### CreateArea.jsx
- Handles user input for new notes.
- Calls `onAdd` function to add notes to the list.

### Note.jsx
- Displays individual notes.
- Calls `onDelete` function to remove notes from the list.

## Usage
1. Enter a title and content in the input fields.
2. Click **Add** to save the note.
3. Click **Delete** to remove the note.

## Deployment Link 
https://2y7l6p.csb.app/

## License
This project is open-source and free to use under the MIT License.
