# Vibe Coding Portfolio Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a GitHub Pages-ready single-page portfolio that presents the user's AI/Vibe Coding product journey for resume delivery.

**Architecture:** Use a static `index.html` with local media assets under `assets/`. The page works without a build step, so it can be opened locally or published directly through GitHub Pages.

**Tech Stack:** HTML, CSS, vanilla JavaScript, local MP4 video assets, GitHub Pages.

---

### Task 1: Prepare Static Assets

**Files:**
- Create: `assets/videos/daily-books.mp4`
- Create: `assets/videos/idle-tracker.mp4`
- Create: `assets/videos/caffeine.mp4`
- Create: `assets/videos/moments.mp4`
- Create: `assets/videos/lumina.mp4`
- Create: `assets/videos/aesthetic-daily.mp4`
- Create: `assets/posters/*.jpg`

- [ ] Copy or transcode source videos into ASCII file names for stable GitHub Pages paths.
- [ ] Compress `审美日课.mp4` below GitHub's 100MB hard limit, preferably below 60MB.
- [ ] Extract poster frames for each portfolio video.

### Task 2: Build Portfolio Page

**Files:**
- Create: `index.html`

- [ ] Add a first-screen summary for resume reviewers.
- [ ] Add a product timeline from 2024-02 through 2026-05.
- [ ] Add one project section per product with problem, product form, core capabilities, AI/product highlights, status, and demo video.
- [ ] Feature `审美日课` as the strongest current live product with a direct online link.
- [ ] Keep all CSS and JavaScript inline to make the page deployable as-is.

### Task 3: Add Publishing Notes

**Files:**
- Create: `README.md`
- Create: `.gitignore`

- [ ] Document local preview and GitHub Pages publishing steps.
- [ ] Ignore macOS metadata files.

### Task 4: Verify Locally

**Files:**
- Read: `index.html`

- [ ] Confirm every referenced video and poster path exists.
- [ ] Confirm the large video is below GitHub's 100MB push limit.
- [ ] Open the page locally and check layout and media playback.
