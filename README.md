# Quick Quiz - CPAN144 Assignment 1

A small Next.js (React) web app built for CPAN144 Assignment 1.

## Features
- Home page with a welcome message
- Navigation menu (with a mobile menu toggle that uses state)
- Quiz page: multiple choice questions, hints, a score, and a results message
- Feedback page: a form with validation and a conditional thank-you message
- Reusable components that receive data through props

## How to run
1. Install Node.js (version 18 or newer).
2. Open a terminal in this folder and run `npm install`.
3. Run `npm run dev`.
4. Open http://localhost:3000 in your browser.

## Folder structure
- `app/` - pages (App Router). `layout.js` wraps every page.
- `components/` - reusable components (NavBar, QuizQuestion, ScoreBoard, FeedbackForm).
- `data/` - quiz questions kept in a separate file.
- `app/globals.css` - styles for the whole app.
