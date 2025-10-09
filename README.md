# Interactive Quiz Builder

A React + TypeScript app (Vite) that allows creating quizzes and playing them.

Features:
- Create quizzes with multiple questions (each has 4 options and one correct answer).
- Edit and delete quizzes.
- Play mode: one question at a time, progress bar, submit to see score and review answers.
- Data persisted in localStorage (no backend required).

## How to run

1. Install dependencies:
```bash
npm install
```

2. Start dev server:
```bash
npm run dev
```

3. Build:
```bash
npm run build
```

Data keys used in localStorage:
- `quiz-builder.quizzes.v1` — saved quizzes
- `quiz-builder.attempts.v1` — saved attempts
