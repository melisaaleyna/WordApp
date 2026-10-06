# WordApp 

WordApp is a Progressive Web App (PWA) designed to enhance vocabulary retention by implementing the **Leitner spaced repetition algorithm**. 

##  Features
* **Leitner Algorithm:** Words are sorted into boxes with review intervals of 1, 3, 7, or 15 days based on user performance ("Fail", "Hard", "Easy").
* **PWA & Offline Mode:** Powered by a Service Worker (`sw.js`), the app functions flawlessly without an internet connection and can be installed directly on the home screen.
* **Data Persistence:** All user progress and state management are handled seamlessly via the browser's `localStorage` API, eliminating the need for an external database.
* **Daily Limitations:** To maintain learning discipline, sessions are capped at 100 words per day. The system synchronizes and resets precisely at midnight local time.
* **3D UI/UX:** Features an interactive, double-sided flashcard interface built with CSS transformations for an engaging user experience.

##  Tech Stack
* HTML5, CSS3, Vanilla JavaScript (ES6+)
* PWA (Manifest.json, Service Workers)
* Caching & LocalStorage API

##  Installation & Usage
Since the application is entirely client-side, it does not require any package managers or backend setup. Simply download the source code and open `index.html` in your browser.
