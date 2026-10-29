# Build.exe

**Ideas in. Projects out.**

Build.exe is an independent, student-facing website for discovering a first AI project idea. Students can explore a small project library, answer a short quiz for a personalized starting point, and share a workshop invitation with a friend.

This is a personal front-end project by Harshit Kumar. It is not an official NxtWave product, workshop deliverable, or company assignment. The site mentions NxtWave's **“Build Your First AI Project in 60 Minutes”** workshop as an optional next step; workshop registration details have not been supplied.

## What you can do

- Browse project ideas for AI apps, machine learning, and automation.
- Filter the project library by category.
- Take a three-question quiz about interests, experience, and goals.
- Get a project suggestion with a beginner-friendly explanation and a first-hour plan.
- Generate a demo referral code and copy an invitation message.
- Follow the workshop call to action, which remains unconfigured until an official URL is provided.
- Use the responsive navigation on desktop and mobile.

## Run locally

No build step, package installation, backend, or API key is required.

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Start a local static file server:

   ```bash
   python -m http.server 8000
   ```

4. Visit [http://localhost:8000](http://localhost:8000).

You can also open `index.html` directly in a modern browser. A local server is recommended for consistent browser behavior.

## Project structure

```text
build-exe/
├── index.html   # Complete website: markup, styles, and client-side interactions
└── README.md    # Project overview, architecture, and local run instructions
```

## Front-end architecture

The site is intentionally a small, single-file static application:

- **Views:** Four sections—Home, Project Match, Explore Ideas, and Workshop & Community—are switched client-side using hash-based navigation.
- **Presentation:** Inline CSS defines the responsive layout, dark charcoal palette, coral/lime accents, lavender highlights, typography, and artwork.
- **Interactions:** Inline JavaScript handles quiz state and recommendations, category filtering, navigation/history, referral sharing, and workshop-link validation.
- **Data:** Project suggestions and example project cards are local static content. Quiz answers are held in page memory; there is no server or account system.

This keeps the project easy to run and inspect while making its front-end-only scope clear.

## Configuration and demo limitations

- To configure registration, set `WORKSHOP_REGISTRATION_URL` near the top of the inline script in `index.html` to the official HTTP or HTTPS registration URL. It is intentionally blank until one is supplied.
- Referral codes and invitation actions are prototype sharing features. They do not register or track students.
- The site has no backend, database, authentication, payment flow, API keys, or live analytics. It does not claim that registrations or referrals have been saved.
- Workshop details and availability should be confirmed with the organizer before sharing.

## Technology

- HTML
- CSS
- Vanilla JavaScript
- Optional Google Fonts connection; system font fallbacks are included

## License

No license has been specified yet. All rights remain with the author unless a license is added.
