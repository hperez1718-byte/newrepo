# Daily Boost

Daily Boost is a playful, browser-based compliment and encouragement app. Choose how you feel, select a boost mode, and receive a personalized message with animated feedback and confetti.

## Features

- Four moods: Tired, Happy, Brave, and Sad
- Exactly 500 mood-based compliments, split evenly at 125 per mood
- Boost modes for compliments, affirmations, silly jokes, tiny challenges, and calm moments
- Candy, Ocean, Sunset, and Space visual themes
- Animated compliment and emoji transitions
- Confetti celebration with an optional browser-generated chime
- Responsive layout for desktop and mobile screens
- No build process or backend required

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

## How to use

1. Choose a mood.
2. Select a theme and boost mode.
3. Click **Give Me a Compliment**.
4. Enjoy the message and confetti celebration.

The page uses browser storage for small interface preferences where applicable. Audio features may require the first interaction with the page because of browser autoplay rules.

## Technologies

- HTML5
- Tailwind CSS via CDN
- Vanilla JavaScript
- Canvas Confetti
- Web Audio API

## Customization

The app is intentionally contained in `index.html`. To customize it:

- Add or edit mood content in `complimentsByMood`.
- Update alternate messages in `modeMessages`.
- Change colors and layouts with Tailwind utility classes.
- Adjust animations in the `<style>` section.
- Modify theme backdrops in the theme-specific CSS rules.

## License

This project is provided as-is for personal and educational use.
