# Quiz App

A modern, professional, and responsive quiz platform inspired by real online exam systems.

## Features
- Topic-wise quizzes (HTML, CSS, JS, Python, C++, DBMS, React, Next.js, Git, DSA, Django)
- Clean, responsive UI with dark/light mode
- Exam-style right-side question grid with color-coded status:
  - Not Visited
  - Not Answered
  - Answered
  - Marked for Review
  - Answered & Marked for Review
- Action buttons: Save & Next, Clear, Save & Mark for Review, Mark for Review & Next, Back, Next, Submit
- Final submission confirmation popup with answer summary
- Strict review mode after submission (no changes allowed)
- Exit to Main Menu button after submission

## Screenshots & Workflow

### 1. Home Page (Topic Selection)
![Home Page](./screenshot-home.png)
*The homepage lets users select a quiz topic. The UI is clean, modern, and responsive, with a dark/light mode toggle in the top right.*

### 2. Quiz Page (Question & Navigation)
![Quiz Page](./screenshot-quiz.png)
*The quiz page displays the current question and options. The right panel shows a color-coded grid for all questions and a legend. Action buttons below the question allow saving, clearing, marking for review, and navigation. The "Exit to Main Menu" button appears after submission.*

### 3. Submission Confirmation Modal
![Submission Modal](./screenshot-modal.png)
*When the user clicks Submit, a modal popup appears summarizing the number of answered, not answered, marked for review, and not visited questions. The user must confirm final submission before seeing results.*

### 4. Result/Review Page
![Result/Review Page](./screenshot-result.png)
*After final submission, only the review area, question grid, and legend are visible. The user sees their score and a detailed review of all questions and answers. The quiz is fully locked, and only the "Exit to Main Menu" button is available.*

## Getting Started

1. **Clone or download this repository.**
2. **Open `index.html` in your browser.**
3. **Select a quiz topic to begin.**

## Usage
- Navigate through questions using the grid or navigation buttons.
- Use action buttons to save, clear, or mark questions for review.
- Click **Submit** to see a summary and confirm final submission.
- After submitting, only your score and review are visible. Use **Exit to Main Menu** to return to the topic list.

## Project Structure
- `src/` — All HTML, CSS, and JS files
- `data/` — JSON files with quiz questions for each topic
- `README.md` — This file

## Customization
- Add or edit questions in the `data/` JSON files.
- Update styles in `src/styles.css` for branding or theme changes.

---

**Screenshot note:**
- The images above are representative screenshots of the app in action. Save your screenshots as `screenshot-home.png`, `screenshot-quiz.png`, `screenshot-modal.png`, and `screenshot-result.png` in the project root to display them in the README.

