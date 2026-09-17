# Daydot Calc (day2dot.com)

A progressive web application (PWA) designed to calculate, search, and display food-safety expiry dates and daydot label details. Built with a liquid-glass UI to match its sister app, Tip Split.

---

## Features

* **Instant Dynamic Daydots**: Generates date-stamped stickers with standard weekday header colour coding and DD/MM formatting.
* **Natural-Language Duration Parser**: Search any time interval directly (e.g., `12 weeks`, `56 days`, `48h`, `3 months`) to calculate real-time expiration stickers on the fly.
* **Product Search & Fuzzy Matching**: Search store ingredients, sauces, powders, and dairy items by name, acronym, or shelf-life length.
* **Quick Reference Grid**: Instant access to standard store shelf-life intervals (24 Hours, 48 Hours, 3 Days, 5 Days, 4 Weeks, 8 Weeks, 12 Weeks, 3 Months).
* **Sister-App Navigation Dock**: Centered, flush bottom dock to toggle between **Day Dot** and **Tip Split** (`tip2split.com`) without layout shift.
* **Offline-First PWA**: Fully functional without network connectivity using service worker caching and local Jost typography.

---

## File Structure

```text
├── fonts/
│   ├── jost-v18-latin-regular.woff2
│   ├── jost-v18-latin-700.woff2
│   └── jost-v18-latin-800.woff2
├── icon.png
├── index.html
├── manifest.json
└── sw.js
