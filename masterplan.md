## masterplan.md

### 30-Second Elevator Pitch

**CineTrack** is a calm, minimal **movie tracking journal** for cinephiles.
Users search films, add them to a watchlist, mark them watched, rate them across **five cinematic parameters**, and write a **50-word reflection**.
The experience feels like **a personal cinema notebook**, not a noisy social network.

---

## Problem & Mission

### Problem

Film lovers often track movies in:

* messy notes
* spreadsheets
* social platforms built for engagement, not reflection

These tools:

* prioritize **feeds and social metrics**
* bury **personal reflection**
* lack **structured rating systems**

### Mission

Create a **quiet digital film journal** that helps people:

* track what they watch
* reflect on cinema
* build a personal archive of film experiences

---

## Target Audience

### Primary Users

**Cinephiles & film enthusiasts**

Traits:

* track films they watch
* enjoy rating and reflecting on movies
* maintain yearly watchlists

Examples:

* film students
* Letterboxd users wanting a calmer space
* people tracking “100 movies this year”

### Secondary Users

* casual movie watchers organizing watchlists
* critics building personal rating archives

---

## Core Features

### Movie Discovery

Users can:

* search movies by **title or director**
* filter by **genre, year, country**
* browse poster grid

---

### Watchlist Management

Users can:

* add movies to **Watchlist**
* drag movies between lists

Lists:

* **To Watch**
* **Watched**

---

### Structured Movie Rating

After watching a movie, users rate it using **five cinematic parameters**:

* Story / Screenplay
* Direction
* Cinematography
* Acting / Performances
* Emotional Impact

Each parameter:

⭐ 1–5 stars

System calculates **average rating automatically**.

---

### Short Film Review

Each movie allows a **50-word reflection**.

Purpose:

* encourage **concise thoughts**
* keep the experience **journal-like**

Example:

> Quietly devastating storytelling with breathtaking visual poetry.

---

### Movie Detail Pages

Each film includes:

* poster
* title
* director
* genre
* country
* runtime
* release year

User section:

* watched status
* rating
* parameter breakdown
* short review

---

### Hybrid Profiles

Users can choose:

**Private mode**

* reviews visible only to themselves

**Public mode**

* optional public profile
* others can view ratings & reviews

This supports both:

* personal journaling
* community discovery

---

### Optional Stats Dashboard

Personal insights such as:

* total movies watched
* average rating
* favorite genres
* highest rated films

---

### AI Movie Suggestion Assistant

Suggests films based on:

* rating patterns
* genres watched
* emotional impact scores

Tone:

> calm cinema guide rather than algorithmic feed.

Example:

> “You seem to enjoy atmospheric dramas. You might like *In the Mood for Love*.”

---

## High-Level Tech Stack

### Frontend

**React + TypeScript**

Reason:

* scalable component architecture
* strong developer ecosystem

---

### UI System

**shadcn/ui + Tailwind CSS**

Benefits:

* consistent component system
* fast UI development
* flexible styling

---

### Build Tool

**Vite**

Benefits:

* fast dev server
* simple configuration

---

### Backend

**Lovable Cloud**

Handles:

* database
* serverless functions
* hosting

---

### Authentication

Email login or magic link.

Simple onboarding keeps friction low.

---

## Conceptual Data Model (ERD in Words)

### User

Fields:

* id
* name
* email
* profile_visibility
* created_at

---

### Movie

Fields:

* id
* title
* director
* year
* genre
* country
* runtime
* poster_url

---

### Watchlist Entry

Fields:

* id
* user_id
* movie_id
* status (watchlist / watched)
* added_date
* watched_date

---

### Rating

Fields:

* story_score
* direction_score
* cinematography_score
* acting_score
* emotional_impact_score
* average_score

---

### Review

Fields:

* user_id
* movie_id
* review_text
* word_count

---

## UI Design Principles

Inspired by **Steve Krug’s usability laws**.

### Self-Evident Navigation

Users should instantly understand:

* where to search movies
* where watchlist lives
* how to mark a movie watched

---

### Calm Interface

Use:

* whitespace
* simple navigation
* minimal colors

Goal:

> the film content should be the focus.

---

### Fast Actions

Actions should require **≤3 clicks**:

Example:

Search → Add → Done

---

### Editorial Reading Experience

Movie pages should feel like:

* reading a **film journal**
* browsing a **curated archive**

---

## Security & Compliance

### Authentication

Secure login with encrypted credentials.

---

### Privacy Controls

Users control:

* review visibility
* profile visibility

---

### Data Protection

Store:

* minimal personal data
* encrypted passwords
* secure session tokens

---

## Phased Roadmap

### MVP

Core functionality:

* movie search
* watchlist
* mark watched
* rating system
* 50-word review
* movie pages

---

### Version 1

Enhancements:

* public profiles
* stats dashboard
* filtering improvements
* better search

---

### Version 2

Expansion:

* AI movie recommendations
* public discovery
* curated lists
* film challenges

---

## Risks & Mitigations

### Risk: Movie Database Availability

Mitigation:

Use existing APIs:

* TMDB
* OMDb

---

### Risk: Feature Creep

Mitigation:

Maintain focus on:

> **personal film journaling**

---

### Risk: Becoming Another Social Network

Mitigation:

Keep:

* reflection-first design
* minimal engagement mechanics

---

## Future Expansion Ideas

Potential long-term features:

### Film Lists

Users can create lists like:

* “Best Films of 2025”
* “Favorite Sci-Fi Movies”

---

### Director Pages

Explore movies by director.

---

### Film Timeline

Visual timeline of movies watched across years.

---

### Smart Film Insights

Examples:

* your favorite cinematographers
* your most watched decade
* emotional impact patterns

---

✅ **File 1 complete**

Next file:

**`implementation-plan.md`**

This will break the product into **step-by-step build tasks** so you could realistically build CineTrack.

Reply **“continue”** and I’ll generate it.
