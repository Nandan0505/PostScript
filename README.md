# Postscript

Postscript is a reader-to-reader connection platform designed to foster meaningful conversations through books, reflections, and shared reading experiences. Instead of focusing on compatibility scores or popularity-driven recommendations, the platform encourages thoughtful one-to-one interactions where books act as conversation starters rather than filters.

---

## Problem Statement

Despite the growth of digital platforms, reading often remains a solitary experience, with few spaces that encourage meaningful personal connections around books. Existing reading communities primarily focus on reviews, popularity, or recommendation algorithms rather than genuine one-to-one interaction. There is a lack of platforms that help readers connect through shared reflections, emotional resonance, and thoughtful conversations around books.

---

## Features

### Authentication

* User Signup/Login
* Secure authentication using Firebase Auth

### Reader Profiles

Users can create personalized reading profiles containing:

* Name
* Age
* Location
* Favorite genres
* Top 3 books
* Favorite authors
* Resonant book quotes
* Fictional characters they relate to
* Reflective reading prompts

### Discovery System

Profiles are surfaced using:

* Shared reading interests
* Similar age ranges
* Common themes and reflections
* Intentional contrasting perspectives

### Connection Mechanism

Instead of traditional “likes,” users express openness to conversation through a book-themed interaction:

* **Turn the Page**

When mutual interest exists:

* Private conversations are unlocked

### Conversations

* One-to-one text-based chat
* Contextual prompts based on shared books and reflections

---

## Recommendation System

The recommendation engine is intentionally lightweight and human-centered.

### Tier 1 — Hard Signals

* Shared genres
* Shared books
* Shared authors
* Reading pace
* Languages

### Tier 2 — Soft Signals

* Favorite fictional characters
* Resonant quotes
* Reading habits
* Preferred reading formats

### Tier 3 — Contrast Signals

* Different interpretations of the same book
* Contrasting reading preferences with similar emotional themes
* Personal reflections on books

The MVP uses a weighted similarity-based approach instead of machine learning.

---

## Tech Stack

### Frontend

* React.js
* React Router

### Backend

* Firebase

### Database

* Firestore

### Authentication

* Firebase Authentication

### Development Tools

* Vite
* VS Code
* Git & GitHub

---

## Project Structure

```bash id="vt31fj"
postscript/
│
├── public/
│
├── src/
│   │
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── utils/
│   ├── constants/
│   ├── styles/
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── routes.jsx
│
├── package.json
├── vite.config.js
└── README.md
```

---

## Installation

Clone the repository:

```bash id="r2okji"
git clone <your-repository-url>
```

Navigate into the project directory:

```bash id="7wdvrh"
cd postscript
```

Install dependencies:

```bash id="h7wnic"
npm install
```

Start the development server:

```bash id="1n0mtj"
npm run dev
```

---

## Future Improvements

* Real-time notifications
* Better recommendation balancing
* Reading activity tracking
* Book discussion spaces
* AI-assisted conversation prompts
* Mobile application support

---

## Development Philosophy

Postscript is designed around the idea that books can create meaningful human connections without reducing people to compatibility scores. The platform values curiosity, reflection, and thoughtful conversation over engagement-driven interaction patterns.

---

## Status

Currently under active development as an MVP project.
