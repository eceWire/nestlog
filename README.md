# NestLog 🐾

A cool, single page web dashboard for managing multi pet logistics, health logs, and caregiver communication. Built entirely from scratch from raw frontend primitives. This project can only conatin dog's so far, but I'm working on having more animals (this includes people as well!).

> **Note for Reviewers:** This is a submission for **#horizons**. Although built inside **PyCharm**, this is entirely a standalone frontend Web Playable project (HTML/CSS/JS) and **not** a Python script :)

---

### Motivation

As a pet owner, I at first thought that raising my dog would be quite simple. It was the COMPLETE opposite from that. I was very disorganized, missing times to feed my dog (don't worry, my sister did) or not taking him on walks. From that day on, Nestlog was born :O.

I wanted to build a fast, ultra lightweight interface that runs entirely in the browser, stores data instantly without complex databases, and gives caregivers a clear, interactive summary of a dog's day to day routine at a single glance. This made life a WHOLE lot easier for me, and once I gave it to one of my dog sitters (we where going on vacation and they had around 9 other dogs) it made their life much more easier.

---

###  Features & What It Does

* **Multi-Profile Switching:** Instantly cycle between different dogs (like the preloaded sandbox profile for *Buddy*), each featuring updated theme states.
* **Interactive Day-to-Day Checklist:** Check off morning walks, feeding times, and vet pills in real time with auto-updating progress metrics.
* **Global Month-at-a-Glance Calendar:** A clean, grid based layout mapping out upcoming vet checkups, medical deadlines, and custom milestones.
* **Live Notification Ticker:** A simulated real-time alert system at the top of the screen that pushes care reminders sequentially.
* **Auto-Saving Care Notebook:** A markdown-ready digital notepad where owners can leave critical notes (triggers, routines, emergency contacts) that persist automatically as you type.
* **Adaptive Dual Themes:** Fully styled light and dark modes optimized for night-time care visibility.

---

###  Tech Stack & How It Works

The architecture is intentionally minimal, designed as an optimized single-file web application (`Bruh.html`) to maximize speed and zero-dependency portability.

* **Development Environment:** Formatted, written, and structured entirely using **PyCharm**.
* **Structure:** Semantic HTML5 to handle views dynamically.
* **Styling Engine:** Pure Vanilla CSS3 using custom CSS variables (`--bg`, `--card`, `--t1`) for real-time theme swapping, coupled with Flexbox and Grid configurations for total mobile responsiveness.
* **Typography:** Clean font rendering using Google Fonts (`Fraunces` for headings, `DM Sans` for status trackers).
* **State & Persistence Engine:** Vanilla ES6+ JavaScript. The state is driven by a single JavaScript dictionary (`state`) which hooks into browser `localStorage`. Every checkbox mutation, new profile initialization, calendar click, or keystroke in the care notes automatically serializes and writes back to disk, making it 100% offline-resilient.

---

### How to Run & Use

Since this is a client side Web Playable project, it requires zero node module compilation, local servers, or Python environments:

1. Open `index.html` in GitHub or go to your browser and type `https://ecewire.github.io/nestlog/` directly into your browser
2. Use the **"+" button** to add a custom dog profile, or use the preloaded **Buddy** dashboard.
3. Tap on the calendar grid cells to see upcoming schedules, flip the **Light/Dark** switch to change themes, and check off daily chores to watch the completion metrics update live.

---

Screenshots
> **Note** In these screenshots, Buddy is not included in here as I put my own dog :)

<img width="1916" height="977" alt="image" src="https://github.com/user-attachments/assets/2c15a2d2-fae6-4a2c-b2cc-931b5bf3886b" />

<img width="1916" height="983" alt="image" src="https://github.com/user-attachments/assets/f114ead4-0e25-4a5c-805d-6af4bb88b92a" />

<img width="1915" height="973" alt="image" src="https://github.com/user-attachments/assets/ac6b414b-a0e4-4f34-a34c-218ef350b374" />

<img width="1918" height="980" alt="image" src="https://github.com/user-attachments/assets/ea4c63b9-f16c-4eaf-ad81-b5b092ba6ad3" />









Credits for AI:
No AI was used in the process of coding. AI was used to add comments to code however, not to update or catch errors.

