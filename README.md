# 📝 QuickNotes - Simple Web-Based Notes App

## Project Overview
**QuickNotes** is a lightweight, browser-based note-taking application designed to help users to take notes quickly. It features a clean, two-column interface with a dedicated sidebar for creating notes and a main dashboard for viewing and managing them.

The application operates entirely on the client side, utilizing the browser's **LocalStorage** to ensure your notes persist even after you refresh or close the page.

## Features Implemented
* **Create Notes:** Easily add new notes with a title and description.
* **Storage:** Uses `localStorage` to save data; notes are not lost on page reload.
* **Edit & Update:** Functionality to modify existing notes seamlessly.
* **Delete Notes:** Remove individual notes with a confirmation prompt.
* **Word Count:** Automatically counts and displays the number of words in a note.
* **Timestamps:** Displays the date and time when a note was created or last updated.
* **Clear All:** One-click button to wipe all saved notes.

## Tech Stack Used
* **HTML5:** Structure of the application.
* **CSS:** Styling, Flexbox layout, CSS Grid, and responsive design.
* **JavaScript:** DOM manipulation, event handling, and LocalStorage logic.

## Steps to Run the Project Locally

Follow these steps to get the project up and running on your machine:

1. **Create the Project File:**
   - Create a new folder on your computer.
   - Inside the folder, create a new file named `index.html`.
   - Paste the source code into `index.html` and save it.

2. **Add Image Assets**
   - The code references two background images: space.png (sidebar) and unnamed.jpg (main background).
   - Place two image files with these names into the same folder

3. **Run the Application:**
   - Navigate to the folder where you saved the file.
   - Double-click index.html to open it in your default web browser (Chrome, Firefox, Edge, etc.).

4. **Usage:**
   - Type a title and description in the sidebar and click "Add Note".
   - Your note will appear on the right side.
   - Refresh the page to see that your data remains saved!
