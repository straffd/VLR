# Valorant Map Veto

A live map pick-and-ban site for Valorant matches. Two devices join as teams, a coin toss decides Team A and Team B, and anyone with the lobby link can watch live.

## Setup

1. Create a Firebase project, add a Web app, and copy its config.
2. Paste the config into `FIREBASE_CONFIG` near the top of `index.html`.
3. In Firebase, create a Firestore database and paste `firestore.rules` into its Rules tab, then publish.
4. Push this folder to GitHub and turn on GitHub Pages (Settings > Pages > Deploy from branch > `main`, root).

Your site will be at `https://<your-username>.github.io/<repo-name>/`.
