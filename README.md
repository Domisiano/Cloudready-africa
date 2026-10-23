# CloudReady Africa

An AZ-900 (Microsoft Azure Fundamentals) exam-preparation learning site.

## Live website
- Wix deployment: https://headless-jofjgsjpbcv-okongodomisia1-140e.wix-site-host.com/
- GitHub repository: https://github.com/Domisiano/Cloudready-africa

## Features
- Smart Quiz Coach with original practice questions and explanations
- Study Buddy with curated explainers and practical examples
- Flashcards and topic-based review
- Personal Study Planner
- Readiness Tracker, topic mastery, attempt history and missed-answer review
- Browser-local progress persistence using localStorage
- Responsive desktop and mobile layout

Practice questions are original study material, not official Microsoft exam questions. Study Buddy is curated content, not a connected live AI model.

## Repository contents
- `index.html` — complete single-page application (HTML, CSS and JavaScript) recovered from the current Wix deployment
- `_wix/pages.json` — Wix static route configuration recovered from the deployment
- `README.md` — project documentation

The Wix deployment inventory reported two site files. Both were transferred to this repository and read back from GitHub after commit. The live Wix deployment was not modified by the transfer.

## Run locally
Open `index.html` in a browser or serve the repository root with a static web server. Progress is stored in the current browser and is not synced between devices.

## Deployment notes
The source includes the Wix Headless site-script loader. The current production site remains hosted on Wix. Before deploying to another host, test there first and determine whether that Wix-specific script is required; do not remove it without verification.

## Verification
- Confirmed the Wix deployment contains `index.html` and `_wix/pages.json`.
- Committed both source files to `main` and read them back from GitHub.
- Left the live Wix site unchanged.
- Browser testing on a separate host has not yet been performed.
