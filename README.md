# Seerat-un-Nabi ﷺ — Interactive Study Guide

[![View Live Site](https://img.shields.io/badge/View_Live_Site-Ready-success?style=for-the-badge&logo=github)](https://mustafa-shah-tech.github.io/Seerat/)
[![Urdu Content](https://img.shields.io/badge/Language-English_%7C_Urdu-blue?style=for-the-badge)](#)

A modern, responsive, and interactive web-based study guide for the **Seerat-un-Nabi ﷺ** course (Islamiat, 1st Semester, BS Economics, University of Malakand).

This project transforms traditional course material into an engaging, self-paced learning experience with progress tracking, interactive quizzes, and beautiful mobile-first design. 

**Hybrid Language Design:** The application features a sleek English user interface (for navigation, progress, and menus) while all the core academic content, definitions, and quizzes have been meticulously translated and formatted in **Urdu** using professional right-to-left (RTL) typography.

## 🌟 Features

*   **Bilingual Academic Structure:**
    *   **English UI:** Easy-to-use modern navigation, progress tracking, and chapter structure.
    *   **Urdu Content:** All 8 study topics, detailed notes, historical timelines, and quiz questions are fully localized in Urdu for accurate academic study.
*   **Interactive Progress Tracking:**
    *   Visual progress ring showing completion percentage.
    *   Progress is automatically saved in your browser's `localStorage` so you can resume where you left off.
*   **Structured Learning Chapters:**
    *   **Chapter 1:** Introduction to Seerat, Differences from Hadith, and Sources.
    *   **Chapter 2:** Core Topics (Khassais-e-Kubra, Makki & Madani periods, Preaching Stages).
    *   **Chapter 3:** Character & Mission (Rights & Beauty of Mustafa ﷺ, Da'wah Methodology).
*   **Mini-Quizzes (Knowledge Checks):** Built-in interactive quizzes at the end of each topic to test comprehension, featuring immediate feedback and retry logic.
*   **Premium UI/UX Design:** "Warm Islamic Night" theme with gold and emerald accents, elegant Arabic typography (Amiri font), and smooth scroll-spy animations.
*   **Fully Responsive:** A hamburger menu and off-canvas sidebar ensure a flawless experience on smartphones and tablets.

## 🚀 Technologies Used

*   **HTML5:** Semantic, single-file structure.
*   **CSS3:** Custom properties, Flexbox/Grid, RTL layout for Urdu sections, and responsive media queries.
*   **Vanilla JavaScript (ES6+):** 
    *   DOM manipulation and event handling.
    *   `IntersectionObserver` for scroll-spy navigation.
    *   Browser `localStorage` APIs for persistent progress.

## 📥 How to Run Locally

This is a single-file application. No build steps, servers, or dependencies are required.

1.  Clone the repository:
    ```bash
    git clone https://github.com/mustafa-shah-tech/Seerat.git
    ```
2.  Open the folder.
3.  Simply double-click `index.html` to open it in any modern web browser.

## 📱 Mobile Experience

The application is fully optimized for mobile viewing:
*   A gold-styled hamburger menu appears on screens under `768px`.
*   The sidebar smoothly slides in as a touch-friendly overlay.
*   Typography and grid layouts automatically adjust for optimal readability on small devices.

## 💾 Progress Persistence

Your progress is saved securely locally using `localStorage` under the `seerat_progress` key. 
*   Checking off a topic saves it permanently to your device.
*   Refreshing or reopening the page instantly restores your previous state.

## 📝 License

This project is created for educational purposes.

---
*اللَّهُمَّ صَلِّ عَلَى مُحَمَّدٍ وَعَلَى آلِ مُحَمَّد*
