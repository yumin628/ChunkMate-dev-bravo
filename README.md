# ChunkMate
> A simple notebook to save, track, and master conversational English chunks.

## Authorship + Version
- **Author:** Yumin Choi
- **Project:** dev|bravo
- **Version:** 0.1
- **Date:** 2026-09-17

## User Story
- **As a** non-native English speaker studying in the US,
- **I want** to quickly save useful conversational phrases (chunks) I hear in daily life,
- **So that** I can review them later and track which ones I have fully memorized.

## Narrative
International students often hear natural, useful English phrases in class or conversations, but easily forget them if they aren't written down immediately. **ChunkMate** is a web app designed to solve this problem by providing a quick, accessible interface to log new English "chunks", their meanings, and a status checkbox (memorized/learning). 

The current version dev-bravo establishes the front-end interface, including a card layout to display the chunks, a form to add new phrases, and filter controls. Future versions will store this data persistently (using localStorage or a database) and implement real search/filter functionality.

## 🧪 Simple Test
- [ ] 🧪 **TEST:** Can a user visually locate the form to add a new English phrase?
- [ ] ✅ **PASS:** The user immediately sees the input fields for "Phrase" and "Meaning" with a clear "Save" button.
- [ ] ❌ **FAIL:** The user cannot figure out where or how to input a newly learned phrase.

## Technology Stack
`HTML5` | `CSS3` | `JavaScript` | `Bootstrap 5` | `Bootstrap Icons` | `Normalize.css` | `Google Fonts` | `Git` | `GitHub Pages`

## Project Structure
```text
dev-bravo/
├── index.html
├── pages/
│   ├── signin.html
│   └── add-chunk.html
├── styles/
│   └── style.css
├── scripts/
│   └── app.js
└── README.md
```
## Validation + Accessibility
- Checked HTML syntax using W3C Validator.
- Reviewed color contrast for readability.
- Added proper IDs and hooks for future JavaScript integration.

## Attribution
- **Bootstrap Documentation:** Used for card components and grid layout.
- **Course Repo:** Adapted the initial directory structure from Professor Cumbie's `dom-time` repository.
- **AI Assistance:** Used AI to brainstorm the 'ChunkMate' app concept, draft the User Story for this README, and generate the initial Bootstrap 5 HTML boilerplate.


