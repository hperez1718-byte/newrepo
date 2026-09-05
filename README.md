# Will you?

A cute, shareable date-planning game for a crush: answer five low-pressure questions about an ideal day, then get a playful personality result and a personalized date card.

## Features

- A single, self-contained HTML page with no build process or external services
- Responsive layout for phones, tablets, and desktops
- Keyboard-friendly controls, visible focus states, semantic labels, and reduced-motion support
- An invitation first, followed by a single date-planner screen with combined activity and food/drink choices, plus day of the week, time of day, vibe, meeting place, and conversation
- A polished planner layout with a submit button that activates after every date preference is selected
- A centered final planner step places a clear “Reveal our date plan” action directly at the bottom of the question list
- A dedicated sharing section at the end of the submitted date card
- Three playful personality results: Cozy Spark, Curious Comet, and Daydream Explorer
- A personalized ideal-date card with a gentle invitation
- A clear no-thank-you option that ends with a respectful, no-pressure response
- Native share, copy, and email actions for sending the result; email drafts accept a recipient address, while copy remains available when browser or device sharing is unavailable
- A soft inline SVG Cupid illustration in the background with a reduced-motion-friendly wing animation
- Soft romantic colors, handwritten-style note treatment, and lightweight CSS animation

## Getting started

Clone the repository and open `index.html` in a modern web browser:

```bash
git clone https://github.com/hperez1718-byte/newrepo.git
cd newrepo
```

You can double-click `index.html`, or serve the project locally with any static web server. For example, if Python is installed:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Technologies

- HTML5
- Vanilla JavaScript

## Customization

The app is intentionally contained in `index.html`. To customize it:

- Edit the copy in the `<h1>`, intro, questions, answers, and result messages.
- Add or remove questions by changing the `questions` array near the bottom of the file.
- Change the final date-card wording in `showResult()`.
- Adjust the color variables and layout rules in the `<style>` section.

## License

This project is provided as-is for personal and educational use.
