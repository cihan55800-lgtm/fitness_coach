# Project Architecture & Context: AI Pro Fit & Autonomous Coach

## Overview
A comprehensive web-based Progressive Web App (PWA) fitness, nutrition, and anatomical tracking system. Built with Tailwind CSS (via CDN), Chart.js, and browser LocalStorage for data persistence.

## Core Modules & Features Implemented
1. **Workout & Group Planner:**
   - Custom day selection (Monday to Sunday).
   - Frequency options (Weekly, Daily, Monthly, Custom).
   - Group-based exercise input with automated web-agent muscle activation tagging and verification checkmarks ($\checkmark$).
2. **Anatomical Heatmap (Anatomy Model):**
   - Interactive front and back human body model visualization[cite: 1].
   - Period-based filtering (Daily, Weekly, Monthly) reflecting high (Red), moderate (Orange), and low (Green) muscle activation intensities.
3. **Visual Nutrition & Tabular Logs:**
   - Image/visual simulation and text-based input for meals.
   - Columnar data tables displaying Calories (kcal), Protein (g), Carbs (g), Fats (g), and source attribution.
4. **Autonomous Health & Security Agent:**
   - Periodic background auditing of user metrics (e.g., body weight, height, and water intake efficiency).
   - Automated diagnostic alerts and warnings (e.g., insufficient hydration warnings based on body mass).
5. **Grouped Analytics & Charts:**
   - Categorized analytics views via interactive dropdown selectors (Weight progress, Calorie/Protein distribution, Water intake trends) preventing visual clutter.

## Technical Constraints & Deployment
- **Tech Stack:** HTML5, Tailwind CSS, JavaScript (ES6+), Chart.js.
- **Deployment:** Hosted and synchronized via GitHub Pages (`index.html`).
- **Data Persistence:** Client-side `localStorage` under keys like `ai_pro_fit_system`.