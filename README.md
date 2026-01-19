# EssentialsPractice

A small Angular practice project I put together while learning and experimenting with Angular features and the CLI. It started from the default scaffold and I added a few small files and demos to play with layouts, component wiring, and a tiny calculation example.

> Quick note: this is a personal practice repo — nothing fancy or production-ready. It’s mainly here so I can tinker, test ideas, and have a simple app to show when I’m explaining things.

What’s in this repo

- An Angular application scaffolded with the Angular CLI.
- A minimal app shell (index.html, main.ts) and global styles in src/styles.css.
- A small example file src/investment-results.ts that I used to experiment with calculations and TypeScript exports.
- A public folder for static assets.
- Standard Angular config files: angular.json, tsconfig.json and a package.json with dev/build scripts.

If you open the src/ folder you’ll see the basic pieces of an Angular app. I kept things intentionally light so it’s easy to follow when I come back to it.

Getting started (how I run it locally)

1. Clone the repo:

   git clone https://github.com/RajhansMore/Angular-Practice-Website.git

2. Install dependencies:

   npm install

   (I use Node 18+ and npm 9+, but it should work fine with other recent versions.)

3. Run the dev server:

   ng serve

   Then open http://localhost:4200 in your browser. The app live-reloads when I change files.

Common commands I use

- npm install — install dependencies
- ng serve — run a local dev server
- ng build — build the app into the dist/ folder
- ng generate component <name> — scaffold a new component
- ng test — run unit tests with Karma (if you want to add tests)

Notes about the code

- The project was created with the Angular CLI. I left the default CLI scaffolding in place and added a couple of files for practice.
- src/investment-results.ts is just a tiny TypeScript module I used to play with some calculation logic.
- There aren’t any complex services or routing setups here — that was intentional so the app stays easy to explore.

Want me to tidy things up?

If you want, I can:
- Add a short demo component that shows the investment calculation in the browser.
- Add basic README badges and a clearer list of scripts from package.json.
- Convert this into a small tutorial with step-by-step commits.

If you’d like any of those, tell me which one and I’ll update the repo accordingly.