# Seerat-un-Nabi ﷺ — Interactive Study Guide

A modern, responsive, and interactive web-based study guide for the **Seerat-un-Nabi ﷺ** course (Islamiat, 1st Semester, BS Economics, University of Malakand).

This project transforms traditional course material into an engaging, self-paced learning experience with progress tracking, interactive quizzes, and bilingual support (English / Urdu).

## 🌟 Features

*   **Bilingual Translation (English & Urdu):** Seamlessly toggle between English and Urdu. The UI instantly adapts to Right-to-Left (RTL) layout and applies elegant Arabic/Urdu typography.
*   **Interactive Progress Tracking:**
    *   Visual progress ring showing completion percentage.
    *   Top progress bar and topic counter.
    *   Progress is automatically saved in the browser's `localStorage` so you can resume where you left off.
*   **Structured Learning Chapters:**
    *   Chapter 1: Introduction to Seerat, Differences from Hadith, and Sources.
    *   Chapter 2: Core Topics (Makki/Madani periods, Prophetic Miracles - Khassais, Preaching Stages).
    *   Chapter 3: Character & Mission (Rights of the Prophet ﷺ, His Beauty, and Da'wah Methodology).
*   **Mini-Quizzes (Knowledge Checks):** Built-in interactive quizzes at the end of each topic to test comprehension. Features immediate feedback and retry logic for incorrect answers.
*   **Premium UI/UX Design:** Beautiful "Warm Islamic Night" theme with gold and emerald accents, glassmorphism effects, and smooth animations.
*   **Fully Responsive:** Optimized for all devices. Includes a mobile-friendly hamburger menu and off-canvas sidebar for smaller screens.

## 🚀 Technologies Used

*   **HTML5:** Semantic structure and content.
*   **CSS3:** Custom properties (variables), Flexbox/Grid layouts, modern typography (Google Fonts: Crimson Pro, DM Sans, Amiri, Cinzel Decorative), responsive media queries, and dark-mode aesthetics.
*   **Vanilla JavaScript (ES6+):** 
    *   DOM manipulation and event handling.
    *   `IntersectionObserver` for scroll-spy navigation.
    *   `localStorage` for persistent progress saving.
    *   Custom translation engine for on-the-fly English to Urdu switching.

## 📥 How to Run Locally

This is a single-file application. No build steps, servers, or dependencies are required.

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/seerat-interactive-guide.git
    ```
2.  Open the folder.
3.  Simply double-click `index.html` to open it in any modern web browser.

## 📱 Mobile Experience

The application is fully optimized for mobile viewing:
*   A hamburger menu appears on screens under `768px`.
*   The sidebar smoothly slides in as an overlay.
*   Typography and grid layouts automatically adjust for optimal readability on small devices.

## 💾 Progress Persistence

Your progress is saved securely in your own browser using `localStorage`. 
*   Checking off a topic saves it.
*   Refreshing or reopening the page restores your exact progress, updated charts, and navigation state.
*   Language preference (English/Urdu) is also remembered across sessions.

## 📝 License

This project is created for educational purposes.

---
*اللَّهُمَّ صَلِّ عَلَى مُحَمَّدٍ وَعَلَى آلِ مُحَمَّد*
