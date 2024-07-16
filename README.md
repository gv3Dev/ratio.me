<div align="left">
  <img src="https://github.com/gv3Dev/ratio.me/blob/main/assets/ratio-clipped.png?raw=true" alt="Ratio App" width="200"/>
</div>

# Ratio App

Ratio is an app where users can receive anonymous ratings on their social media accounts. Users share a unique link on their profiles, allowing friends and followers to rate them anonymously. The app calculates scores based on these ratings and ranks users on a leaderboard.

## Features

- Anonymous Ratings: Users share their unique Ratio link on social media, and friends and followers can rate them anonymously on various attributes (e.g., creativity, friendliness, humor).
- Scoring System: Calculate scores based on the received ratings, with different attributes having different weights.
- Leaderboards: Display global and friends-only leaderboards, showing top-rated users in different categories.
- Notifications: Notify users when they receive new ratings and highlight changes in leaderboard positions.
- Moderation Tools: Allow users to report inappropriate ratings or comments, with a review system for flagged content.

## Tech Stack

- **Frontend:** React Native (Mobile)
- **Backend:** Node.js with Express + Socket.io
- **Database:** Firebase Firestore / MongoDB
- **Storage Bucket:** BackBlaze (image storage)
- **Authentication:** Firebase Auth

