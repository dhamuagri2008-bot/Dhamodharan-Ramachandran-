# Dhamodharan Artfolio

A responsive drawing community and portfolio site.

## Features
- Responsive Explore and Artists pages
- Drawing upload and review workflow
- Profiles, likes, ratings and comments
- Firebase Authentication + Firestore integration
- GitHub Pages deployment through GitHub Actions

## Deploy
Pushes to `main` automatically run the Pages deployment workflow. In the repository settings, enable GitHub Pages with **GitHub Actions** as the source if it is not already enabled.

## Firebase
The frontend uses the Firebase Web SDK. The web configuration is intentionally client-side; access control must be enforced with Firebase Authentication and Firestore Security Rules.
