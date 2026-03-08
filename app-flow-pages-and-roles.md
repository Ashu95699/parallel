## app-flow-pages-and-roles.md

### Site Map (Top-Level Pages)

```
Home
Movie Directory
Watchlist
Movie Detail
Stats
Profile
```

Each page serves a **single clear purpose** to reduce cognitive load.

---

# Page Purposes

### Home

Purpose:
Introduce CineTrack as a **personal cinema journal**.

Key elements:

* tagline
* quick stats
* navigation entry points

Example sections:

* Hero
* Personal stats preview
* Recent watched films

---

### Movie Directory

Purpose:
Help users **discover and search movies quickly**.

Main components:

* search bar
* filters
* poster grid

User actions:

* open movie page
* add movie to watchlist
* drag movie to watchlist panel

---

### Watchlist

Purpose:
Organize movies the user wants to watch and has watched.

Layout sections:

```
TO WATCH
WATCHED
```

User actions:

* drag movies between lists
* mark movie watched
* open rating panel

---

### Movie Detail

Purpose:
Show **film information and personal reflection**.

Content sections:

Film info

* poster
* title
* director
* year
* genre
* runtime

User section

* watch status
* rating breakdown
* short review

---

### Stats

Purpose:
Give users **insight into their film habits**.

Examples:

* total movies watched
* average rating
* favorite genres
* highest rated movies

Visuals:

* simple charts
* ranked lists

---

### Profile

Purpose:
Allow users to manage identity and visibility.

Options:

* public profile toggle
* username
* profile stats
* shared reviews

Public profile shows:

* watched films
* ratings
* reviews

---

# User Roles

### Guest

Access level:

* browse movie directory
* view public profiles
* view movie pages

Limitations:

* cannot rate movies
* cannot create watchlists

---

### Registered User

Full CineTrack experience.

Abilities:

* create watchlist
* mark movies watched
* rate movies
* write reviews
* view personal stats

Users can also:

* toggle profile visibility

---

### Public Viewer

Any visitor viewing a public profile.

They can see:

* ratings
* reviews
* watched films

They cannot modify anything.

---

# Primary User Journeys

All flows follow the **three-step clarity rule**.

---

### Journey 1 — Add Movie to Watchlist

Step 1
User searches for a movie.

Step 2
User clicks **Add to Watchlist** or drags card.

Step 3
Movie appears in **To Watch** list.

Outcome:

Movie saved to personal watchlist.

---

### Journey 2 — Mark Movie as Watched

Step 1
User drags movie from **To Watch** to **Watched**.

Step 2
Rating panel opens.

Step 3
User submits ratings and review.

Outcome:

Movie logged in film journal.

---

### Journey 3 — Write Film Reflection

Step 1
User opens movie detail page.

Step 2
User enters rating and review.

Step 3
Review saved to journal.

Outcome:

Personal reflection recorded.

---

### Journey 4 — Discover Movies

Step 1
User opens Movie Directory.

Step 2
User searches or filters.

Step 3
User opens movie page or adds to watchlist.

Outcome:

Film discovery.

---

### Journey 5 — View Personal Film Stats

Step 1
User opens Stats page.

Step 2
User views insights.

Step 3
User explores top films or genres.

Outcome:

User understands film preferences.

---

# Core Interaction Loops

### Film Tracking Loop

```
Discover Movie
→ Add to Watchlist
→ Watch Film
→ Rate Film
→ Write Review
```

This loop builds the **personal cinema archive**.

---

### Reflection Loop

```
Watch Film
→ Rate Parameters
→ Write 50-word reflection
→ Review personal stats
```

Encourages **thoughtful engagement with cinema**.

---

# Permissions Overview

| Action           | Guest | User |
| ---------------- | ----- | ---- |
| Search Movies    | ✓     | ✓    |
| View Movie Pages | ✓     | ✓    |
| Add to Watchlist | ✗     | ✓    |
| Rate Movies      | ✗     | ✓    |
| Write Reviews    | ✗     | ✓    |
| View Stats       | ✗     | ✓    |
| Public Profile   | ✓     | ✓    |

---

# UX Simplicity Rules

To keep the interface effortless:

* main actions visible immediately
* no hidden menu layers
* rating system always in same place
* watchlist always accessible

This follows the **“Don’t Make Me Think” principle**.

---

# Future Page Expansions

Possible additions:

### Film Lists

Users create themed lists.

Examples:

* Favorite Sci-Fi Films
* Best Films of 2025

---

### Director Pages

Users explore films by director.

---

### Film Timeline

Visual timeline of watched movies.

---

✅ **All four documents are now complete**

You now have:

1. **masterplan.md** — product blueprint
2. **implementation-plan.md** — build roadmap
3. **design-guidelines.md** — brutalist cinema design system
4. **app-flow-pages-and-roles.md** — product structure

---

💡 **If you want, I can also generate one more extremely useful thing:**

A **single Lovable “Super Prompt”** that produces **a much better UI and database structure instantly inside Lovable** (much cleaner than typical prompts).

Just say:

**“Generate the Lovable Super Prompt.”** 🎬
