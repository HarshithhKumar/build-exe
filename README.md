# Build.exe

**Ideas in. Projects out.**  
A small, student-friendly project discovery website.

<p align="center">
  <a href="https://buildexe.netlify.app"><strong>Open the live website →</strong></a>
</p>

## About the project

Build.exe is a personal, just-for-fun front-end project created by **Harshith Kumar**. It is an interactive website concept for students who want to explore beginner-friendly AI and software project ideas.

The goal is simple: make it easier for students to move from browsing ideas to choosing something they might enjoy building. This is an interface prototype and learning project—not a production service, company product, or officially affiliated platform.

## Website preview

These screenshots show the main interface:

| Home | Project Match |
| --- | --- |
| ![Build.exe home page](https://image.thum.io/get/width/1200/crop/800/https://buildexe.netlify.app/) | ![Build.exe Project Match quiz](https://image.thum.io/get/width/1200/crop/800/https://buildexe.netlify.app/#match) |

| Explore Ideas | Workshop and Community |
| --- | --- |
| ![Build.exe Explore Ideas page](https://image.thum.io/get/width/1200/crop/800/https://buildexe.netlify.app/#explore) | ![Build.exe workshop and community page](https://image.thum.io/get/width/1200/crop/800/https://buildexe.netlify.app/#community) |

[Visit the live website](https://buildexe.netlify.app)

## What you can explore

- **Home:** An introduction to the project and its “Less scrolling. More building.” idea.
- **Project Match:** A short interactive quiz that suggests a starting project based on a student's interests and experience.
- **Explore Ideas:** A browsable collection of example project ideas, with category filters.
- **Workshop & Community:** A concept section for sharing the next steps and inviting friends.

## How it is built

Build.exe is intentionally a small static website rather than a full-stack application.

```text
build-exe/
├── index.html                 # Page structure, styles, and browser-side interactions
├── README.md                  # Project overview and documentation
└── screenshots/
    ├── home.jpg               # Home page preview
    ├── project-match.jpg      # Project Match preview
    ├── explore-ideas.jpg      # Explore Ideas preview
    └── workshop-community.jpg # Workshop and Community preview
```

### Simple front-end architecture

- **Structure:** HTML provides the page content and interface sections.
- **Styling:** CSS handles the visual design, responsive layout, typography, colours, and cards.
- **Interactions:** Vanilla JavaScript powers the quiz, recommendations, navigation, category filters, and demo sharing interactions.
- **Content:** Example project ideas and interface data are included in the front end.

The interface is designed to be easy to inspect and experiment with, without a complicated setup.

## What is—and isn't—implemented

This is a **front-end-only prototype made for fun and practice**. It demonstrates how the experience could look and feel, but it is not a complete functional product.

- There is no backend, database, account system, or authentication.
- The website does not collect or save student registrations.
- Demo referral codes do not provide real referral attribution or analytics.
- The workshop area is informational UI; it is not a live registration system.
- There are no production analytics, email automations, or server-side workflows.

Please treat the interactions as a demonstration of the concept, not as a promise of a live service.

## Live demo

**Website:** https://buildexe.netlify.app

The deployed site is a static front-end demo. The source code for the interface is in `index.html`.

## Built with

- HTML
- CSS
- Vanilla JavaScript
- Netlify for static hosting

## Why I made it

I wanted to make a clean, interactive place where students can discover project ideas and get a starting point without feeling overwhelmed. Build.exe is a small personal experiment in interface design, simple browser interactions, and presenting technical ideas in a student-friendly way.

---

Made by **Harshith Kumar** as a personal project for fun and learning.
