# Maths Adventure

A free, single-page maths practice game for children in **Year 3 (ages 7–8)** of the English national curriculum. It focuses on addition and subtraction with a child-friendly, vertical sum layout and an on-screen number pad.

## Play

Open the live page in any modern browser:

`https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

On a phone or tablet you can add it to your Home screen (Chrome: ⋮ menu → *Add to Home screen*; Safari: Share → *Add to Home Screen*) so it opens like an app.

## Features

- **Three modules:** A – Addition, B – Subtraction, C – Mixed
- **Four levels per module**, increasing in difficulty (2-digit numbers up to 3-digit numbers with carrying and borrowing across the hundreds)
- **25 new random questions** every time a level is started, with no repeated sums in a level
- **Pass mark of 20/25** to unlock the next level
- Sums are shown vertically, as written in class, with a 0–9 keypad, Enter and backspace
- Personal greeting using the child's name
- Sounds, animations, streak messages and **Bronze / Silver / Gold badges** with a trophies screen
- **Parent area** with best scores, recent plays and a list of sums answered incorrectly

## Privacy

- No account, no sign-up, no tracking and no data sent to any server.
- The child's name, progress and scores are stored **only in the browser on the device being used** (local storage). Other people who open the link get their own separate, empty copy and cannot see anyone else's progress.
- Clearing the browser's site data on a device deletes that device's progress.
- The Parent area uses a simple maths question to keep young children out. It is a convenience, not a security feature.

## Technical notes

- A single `index.html` file with plain HTML, CSS and JavaScript. No frameworks, no build step and no external libraries.
- Sounds are generated in the browser with the Web Audio API, so there are no audio files.
- To run it locally, open `index.html` in a browser, or serve the folder with `python3 -m http.server 8080`.

## Updating

Replace `index.html` in this repository and commit. GitHub Pages republishes within a couple of minutes.

## Roadmap

- Multiplication and division modules
- A timed times-tables module
- Optional offline installable app

## Curriculum

Content is aligned to the Year 3 addition and subtraction expectations of the national curriculum in England. It is a practice tool and not an official assessment.
