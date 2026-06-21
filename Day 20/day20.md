# Day 20 – AI Face Puzzle Game 🧩📷

## Overview

For Day 20 of my AI learning challenge, I explored how generative AI can assist in building interactive browser games.

Using a single detailed prompt, I generated a complete **Face Puzzle Game** that captures a user's photo using their webcam and transforms it into a playable sliding puzzle.

The entire application is built as a **single self-contained HTML file** with inline CSS and JavaScript.

---

## Objective

Build a responsive browser-based puzzle game that:

* Captures a photo using the device camera
* Converts the photo into puzzle pieces
* Supports multiple difficulty levels
* Works seamlessly on desktop and mobile devices
* Tracks performance metrics such as time and moves
* Stores best scores locally

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* Canvas API
* MediaDevices API (`getUserMedia`)
* Local Storage API

---

## Features

### 📷 Camera Access

* Requests webcam permission on load
* Supports front-facing camera
* Displays live video preview
* Captures user photo directly in the browser

### 🧩 Puzzle Generation

* Difficulty options:

  * 3×3
  * 4×4
  * 5×5

* Slices captured image into puzzle pieces

* Scrambles pieces while ensuring solvability

* Generates a playable puzzle board

### 👆 Drag & Touch Controls

* Desktop drag-and-drop support
* Mobile touch gesture support
* Tile swapping and snapping
* Visual indicators for active and correct pieces

### ⏱️ Game Tracking

* Live timer (`mm:ss.t`)
* Move counter
* Correct piece counter

### 🏆 Results & Leaderboard

* Automatic win detection
* Results overlay
* Top 5 scores saved using localStorage
* Difficulty, moves, and completion time tracking

### 🎨 UI & Experience

* Responsive layout
* Modern design
* Retake photo option
* Play again option
* New photo option

---

## Prompt Used

```text
You are an expert front-end developer. Build me a complete, fully working face puzzle game as a single self-contained HTML file (no external dependencies except what can load from cdnjs.cloudflare.com, cdn.jsdelivr.net, or unpkg.com).

FEATURES REQUIRED — deliver ALL of these in one complete response:

1. CAMERA ACCESS
   - On load, request webcam permission using getUserMedia()
   - Show a live video preview (front-facing camera preferred)
   - Display a 'Take Photo' button to snapshot the user's face onto a canvas

2. PUZZLE GENERATION
   - After snapshot, let the user choose difficulty: 3×3, 4×4, or 5×5 grid
   - Slice the captured face image into equal puzzle pieces
   - Randomly scramble the pieces (guarantee it is solvable)
   - Render each piece as a draggable tile at its scrambled position

3. DRAG & TOUCH GESTURE CONTROLS
   - Support both mouse drag (desktop) and touch drag (mobile/tablet)
   - When a piece is dropped onto another piece's cell, swap their positions
   - Snap pieces to the nearest grid cell on release
   - Highlight a piece with a coloured border while it is being dragged
   - Show a green border on pieces that land in their correct position

4. TIMER & MOVE COUNTER
   - Start the timer the moment the puzzle begins
   - Display elapsed time live (format: mm:ss.t)
   - Count and display total moves made
   - Show how many pieces are correctly placed out of the total

5. WIN DETECTION & RESULTS SCREEN
   - Detect automatically when all pieces are in the correct position
   - Stop the timer immediately on win
   - Show a results overlay with: final time, total moves, and difficulty
   - Save the top 5 best times to localStorage with date, time, moves, and difficulty
   - Display a leaderboard of saved best times

6. UI & POLISH
   - Clean, modern design
   - Works on desktop and mobile
   - 'Retake Photo' button
   - 'Play Again' button
   - 'New Photo' button
   - Responsive layout

TECHNICAL REQUIREMENTS:
- Single HTML file
- All CSS and JS inline
- No frameworks
- Must work in Chrome, Firefox, and Safari
- Camera must work over HTTPS or localhost
- Handle camera permission denied gracefully
- Do NOT leave placeholder comments

Output the complete HTML file in one code block. Do not truncate or summarise any section.
```

---

## Key Learnings

* AI can accelerate rapid prototyping of complete applications.
* Detailed prompts produce more accurate and production-ready outputs.
* Browser APIs enable powerful experiences without external frameworks.
* Combining Canvas, Camera APIs, and localStorage creates engaging web applications.
* Mobile-first interaction design is essential for modern web games.

---

## How to Run

1. Download the `face-puzzle-game.html` file.

2. Open it using:

   * `localhost`
   * HTTPS deployment

3. Allow camera permissions.

4. Capture your photo.

5. Select a difficulty level.

6. Solve the puzzle and beat your best score.

> Note: Camera access requires HTTPS or localhost.

---

## Conclusion

This project demonstrated how AI can help build complete interactive experiences from a single prompt.

From camera integration to game mechanics and performance tracking, the entire application was generated using prompt engineering and refined through testing.

> "The best way to learn AI is to build with it."

#Day20 #AI #PromptEngineering #JavaScript #GameDevelopment #HTML #CSS #WebDevelopment #BuildInPublic
