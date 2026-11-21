# Habitly — Habit Tracker Dashboard

A clean, modern, and responsive Habit Tracker dashboard built for the **CodGen Frontend Development Internship – Week 1**.

> **Note:** This is strictly the **Week 1** static frontend implementation built exclusively with semantic **HTML5** and modern **CSS3**. No JavaScript, external UI frameworks, or backend technologies were used.

---

## 🌟 Overview

**Habitly** is a minimalist and responsive web dashboard designed to help individuals build better habits, one day at a time. The project adheres to strict design system guidelines, semantic markup, accessible typography, and responsive layouts across all device form factors.

---

## 🚀 Features

- **Professional Header**:
  - Branded logo with custom emoji styling.
  - Website title (**Habitly**) and motivating tagline (*"Build better habits, one day at a time."*).
  - Current date badge displayed as clean, static plain text (*"Friday, 21 November"*).
  - Styled with the required Primary Navy (`#0B1F3A`).
- **3 Summary Statistic Cards**:
  1. **Done Today**: Tracks daily progress (`3/5` completed habits) with an illustrative progress indicator.
  2. **Best Streak**: Highlights milestone consistency (`12 Days` streak record).
  3. **This Week**: Summarizes overall weekly completion rate (`78%`).
- **Active Habit Cards Grid**:
  - Displays 6 habit cards (exceeds the 5-habit requirement for a perfectly balanced multi-column grid layout):
    1. **Reading** (📚) — 7 Day Streak
    2. **Drinking Water** (💧) — 12 Day Streak
    3. **Exercise** (🏋️) — 5 Day Streak
    4. **Coding Practice** (💻) — 15 Day Streak
    5. **Meditation** (🧘) — 3 Day Streak
    6. **Healthy Sleep** (😴) — 9 Day Streak
  - Each card includes:
    - Clear visual icon/emoji.
    - Habit title and concise description.
    - Teal streak badge highlight.
    - High-contrast, styled **"Complete"** button.
    - Interactive CSS hover states and subtle card elevation transitions.
- **Responsive Layout**:
  - Mobile (360px): Stacked single-column card layout with zero horizontal overflow.
  - Tablet (768px): Balanced 2-column habit grid.
  - Desktop / Laptop (1280px): Multi-column 3-card grid for optimal screen utilization.
- **Consistent Design System**:
  - Spacing strictly organized in multiples of 8px (8px, 16px, 24px, 32px, 48px, etc.).
  - Primary Navy: `#0B1F3A`
  - Accent Teal: `#14B8A6`
  - Page Background: `#F8FAFC`
  - Cards: White (`#FFFFFF`) with 12px rounded corners and subtle drop shadows.
  - Google Fonts: `Inter` typography.
- **Professional Footer**:
  - Contains the exact required credit text:  
    `Built with the CodGen Frontend Internship | codgen.in`

---

## 🛠️ Technologies Used

- **HTML5**: Semantic elements (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, accessible `<button>` tags, ARIA labels).
- **CSS3**: Modern Flexbox, CSS Grid, CSS Custom Properties (`:root` variables), smooth transitions, media queries.
- **Google Fonts**: Inter font family.

*Strictly excluded:* No JavaScript, no TypeScript, no Tailwind CSS, no Bootstrap, no React/Next.js, no backend or database.

---

## 📁 Project Structure

```text
habitly/
├── index.html       # Semantic HTML5 dashboard markup
├── style.css        # Pure CSS3 stylesheet with design variables & media queries
└── README.md        # Documentation, requirements, and deployment instructions
```

---

## 💻 Instructions to Run Locally

You do not need a web server, bundler, or build tool to run this project.

### Method 1: Direct File Opening
1. Clone or download this repository to your local machine.
2. Navigate to the `habitly/` directory.
3. Double-click `index.html` (or right-click and choose **Open with Google Chrome / Firefox / Edge / Safari**).

### Method 2: Using VS Code Live Server (Optional)
1. Open the `habitly/` folder in Visual Studio Code.
2. Install the **Live Server** extension if not already installed.
3. Click **"Go Live"** in the bottom status bar or right-click `index.html` and select **"Open with Live Server"**.
4. The dashboard will launch at `http://127.0.0.1:5500`.

---

## 🌐 GitHub Pages Deployment Instructions

To deploy this website live using GitHub Pages:

### Step 1: Initialize Git and Commit
Open a terminal in the `habitly` project directory:
```bash
git init
git add .
git commit -m "Initial commit: Habitly Week 1 static dashboard"
```

### Step 2: Create a Remote GitHub Repository
1. Log in to your [GitHub](https://github.com/) account.
2. Create a new repository named **`habitly`**.
3. Leave it public and do not initialize with a README (since one is already present).

### Step 3: Push to GitHub
Link your local repository and push the code:
```bash
git branch -M main
git remote add origin https://github.com/<YOUR-GITHUB-USERNAME>/habitly.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub: `https://github.com/<YOUR-GITHUB-USERNAME>/habitly`.
2. Click on the **Settings** tab.
3. In the left navigation sidebar, select **Pages** (under the "Code and automation" section).
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` and keep the folder set to `/(root)`.
5. Click **Save**.

### Step 5: Obtain Your Live Website URL
- GitHub Actions will automatically build and publish the site within 1–2 minutes.
- Refresh the **Pages** settings tab. You will see a banner at the top:
  > **Your site is live at https://&lt;YOUR-GITHUB-USERNAME&gt;.github.io/habitly/**
- You can now test and share your live Habitly tracker URL!

---

## 📋 CodGen Internship Week 1 Checklist

- [x] Primary Navy `#0B1F3A` used for header & theme accents.
- [x] Accent Teal `#14B8A6` applied to streaks and interactive complete buttons.
- [x] Background `#F8FAFC` and white cards with `12px` border radius.
- [x] Multiples of 8px spacing system maintained throughout CSS.
- [x] Professional header with emoji logo, site title, subtitle, and plain-text current date.
- [x] Exactly 3 summary statistic cards (Done Today: 3/5, Best Streak: 12 Days, This Week: 78%).
- [x] At least 5 habit cards present (6 habits implemented for symmetrical layout).
- [x] Visual "Complete" buttons without JavaScript functionality.
- [x] Fully responsive across Mobile (360px), Tablet (768px), and Laptop/Desktop (1280px).
- [x] Semantic HTML5 tags (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- [x] Zero horizontal scrolling or overflow at any viewport size.
- [x] Exact required footer text: `Built with the CodGen Frontend Internship | codgen.in`.

---

© 2026 Habitly. Built for the CodGen Frontend Internship.
