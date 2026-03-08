## implementation-plan.md

### Build Philosophy

Build CineTrack in **small, mindless steps**.
Each step should produce something **visible and testable**.

Goal:

> Working product early → iterate fast.

---

# Phase 1 — Foundation Setup

### Step 1 — Initialize Project

Tasks:

* Create project using **Vite + React + TypeScript**
* Setup folder structure
* Install dependencies

Core packages:

* React
* Tailwind CSS
* shadcn/ui
* React Router

Checkpoint:

✔ App runs locally
✔ Basic page renders

---

### Step 2 — Setup UI System

Tasks:

* Install **shadcn/ui**
* Configure Tailwind
* Create base layout components

Components to build:

* Navbar
* Page container
* Card layout
* Button styles
* Poster grid component

Checkpoint:

✔ Consistent UI components ready

---

### Step 3 — Global Layout

Create the main application shell.

Pages to scaffold:

* Home
* Movie Directory
* Watchlist
* Movie Detail
* Stats (placeholder)

Navigation:

Home
Directory
Watchlist
Stats

Checkpoint:

✔ Navigation works across pages

---

# Phase 2 — Movie Data Integration

### Step 4 — Connect Movie API

Use a movie data provider such as:

* TMDB API
* OMDb API

Tasks:

* Create API service
* Fetch movie lists
* Fetch movie details

Data needed:

* poster
* title
* director
* year
* genre
* country
* runtime

Checkpoint:

✔ Movies load in the app

---

### Step 5 — Build Movie Directory

Create the searchable movie page.

Components:

* search bar
* filter panel
* poster grid

Filters:

* genre
* year
* country

Each movie card shows:

* poster
* title
* year
* director

Actions:

* Add to Watchlist

Checkpoint:

✔ Movies searchable and browsable

---

# Phase 3 — Watchlist System

### Step 6 — Watchlist Database

Create storage model.

Tables:

User
Movie
WatchlistEntry

Fields:

* user_id
* movie_id
* status (watchlist / watched)
* added_date

Checkpoint:

✔ Movies can be saved to watchlist

---

### Step 7 — Watchlist Page

Create two sections:

**To Watch**

Movies planned.

**Watched**

Movies completed.

Card displays:

* poster
* title
* status
* rating

Checkpoint:

✔ Movies appear in watchlist

---

### Step 8 — Drag & Drop Interaction

Enable:

Movie card drag → watchlist sections.

Libraries to consider:

* dnd-kit
* React Beautiful DnD

Interaction:

Drag movie → move to watched list.

Checkpoint:

✔ Dragging works smoothly

---

# Phase 4 — Rating System

### Step 9 — Rating Modal

When movie becomes **Watched**:

Open rating interface.

Five parameters:

* Story
* Direction
* Cinematography
* Acting
* Emotional Impact

Input:

⭐ 1–5 stars.

Checkpoint:

✔ Ratings save successfully

---

### Step 10 — Average Score Calculation

Logic:

Average =

(story + direction + cinematography + acting + impact) ÷ 5

Display:

Example:

Story: 4
Direction: 5
Cinematography: 5
Acting: 4
Impact: 5

Average: **4.6**

Checkpoint:

✔ Score displayed on movie card

---

# Phase 5 — Review Feature

### Step 11 — Short Review Input

Create review input field.

Rules:

* max 50 words
* simple text area
* word counter

Example:

“Quietly devastating storytelling with breathtaking visual poetry.”

Checkpoint:

✔ Review stored with movie

---

# Phase 6 — Movie Detail Page

### Step 12 — Movie Information Layout

Display:

* poster
* title
* director
* genre
* runtime
* year
* country

User section:

* watched status
* rating
* review

Checkpoint:

✔ Movie page shows full data

---

# Phase 7 — Authentication

### Step 13 — User Accounts

Add simple login system.

Options:

* email + password
* magic link login

User profile includes:

* username
* profile visibility

Checkpoint:

✔ Users can sign in

---

# Phase 8 — Hybrid Profiles

### Step 14 — Public Profile Option

Allow users to toggle:

Private
Public

Public profile displays:

* watched movies
* ratings
* reviews

Checkpoint:

✔ Profile page visible publicly

---

# Phase 9 — Stats Dashboard

### Step 15 — Personal Insights

Metrics:

* total watched
* average rating
* top genres
* highest rated movies

Visual elements:

* simple charts
* film lists

Checkpoint:

✔ Stats page displays insights

---

# Phase 10 — AI Recommendation System

### Step 16 — Recommendation Engine

Analyze:

* genres watched
* average scores
* emotional impact patterns

Output:

Film suggestions.

Example:

> “You seem to enjoy atmospheric dramas. Try *In the Mood for Love*.”

Checkpoint:

✔ AI suggestions appear on dashboard

---

# Timeline (Realistic Solo Builder)

Week 1

* project setup
* UI system
* layout

Week 2

* movie API
* directory page

Week 3

* watchlist
* drag & drop

Week 4

* rating system
* reviews

Week 5

* movie detail pages
* authentication

Week 6

* profiles
* stats dashboard

Week 7

* AI suggestions
* polish UI

---

# Team Roles (If Working With a Team)

### Product Lead

Defines features and roadmap.

---

### Frontend Developer

Builds UI and interactions.

---

### Backend Developer

Handles database, APIs, and auth.

---

### Designer

Maintains the **editorial cinema aesthetic**.

---

# Recommended Rituals

### Bi-Weekly Usability Test

3 users
30 minutes

Test tasks:

* add movie to watchlist
* mark movie watched
* rate movie

Goal:

Find confusion quickly.

---

### Monthly Feature Review

Evaluate:

* feature usage
* user feedback
* UI clarity

Remove unnecessary features.

---

# Optional Integrations

### Movie Data APIs

* TMDB
* OMDb

---

### Image Hosting

For poster caching.

---

### Email Notifications

Optional reminders:

“Still planning to watch this film?”

---

# Stretch Goals

### Film Challenges

Examples:

* 100 movies in a year
* watch every Hitchcock film

---

### Director Insights

Track favorite directors.

---

### Watch Timeline

Visualize films watched across months or years.

---

✅ **File 2 complete**

Next file:

**`design-guidelines.md`**

This will translate your **cinema notebook feeling** into a **complete visual design system** (colors, typography, motion, emotional tone, accessibility).

Reply **“continue”** and I’ll generate it.
