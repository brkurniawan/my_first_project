# Refined Prompt for AI Coding Agent

You are my AI coding agent. Build a complete beginner-friendly simulation web app and prepare it for GitHub + Vercel deployment.

## Project Goal
Create an interactive simulation lab to teach how insulin regulates blood sugar.

## Tech Stack
- HTML
- CSS
- JavaScript (vanilla)
- Tailwind CSS

## Target Users
- Learners (students with basic biology background)

## Core Simulation Requirements
1. Show a visual blood vessel and nearby body cells.
2. Display current values for:
   - Blood glucose concentration
   - Insulin level
   - Cell glucose uptake
3. Add controls/buttons:
   - `Eat` button: increases blood glucose.
   - `Release Insulin` button: increases insulin level.
4. Simulation logic:
   - Blood sugar increases when learner clicks `Eat`.
   - Cells absorb sugar only when insulin binds to receptors on the cell membrane.
   - Without insulin-receptor binding, glucose uptake should be very low or zero.
5. Animate key states:
   - Glucose particles in blood vessel.
   - Insulin binding event at membrane receptor.
   - Glucose moving into cells after binding.
6. Include a short "How it works" panel for learners.

## UX/UI Requirements
- Clean educational layout.
- Responsive for desktop and mobile.
- Use Tailwind utility classes with readable spacing and clear typography.
- Keep controls simple and obvious.

## Learner Input Requirements
1. Add a small form for user identity:
   - `Full Name` (required text input)
   - `Email` (required email input)
2. Validate both fields before enabling simulation buttons.
3. Show a friendly validation message if the form is incomplete/invalid.
4. Display the learner name in the UI after successful input (for personalization).

## Code Requirements
- Organize files as:
  - `index.html`
  - `style.css` (if needed)
  - `script.js`
- Write clean, commented JavaScript for simulation state updates.
- Avoid heavy libraries beyond Tailwind.

## Deployment Requirements
1. Initialize Git repository and commit with a clear message.
2. Provide exact commands to push this project to GitHub.
3. Configure project for Vercel static deployment.
4. Provide exact steps/commands to deploy to Vercel.
5. Include a short README with run/deploy instructions.

## Output Format
- First: brief implementation plan.
- Then: create/update all required files.
- Then: show final project tree.
- Then: provide GitHub push commands and Vercel deploy steps.

Start now and implement the full project end-to-end.
