# *Spotify Browser*

This web app: **Allows users to browse music on Spotify, including searching for artists, albums, and tracks, and viewing detailed information about them. The app communicates with Spotify's API via a backend Express webserver.**

## Features

The following functionality is implemented:

- [x] **Login and API Communication:** Authenticate and authorize with Spotify using OAuth, and make API requests through an Express webserver.
- [x] **Home Page:**
  - Display user account information, including name, profile picture, and a link to their Spotify profile.
  - Search functionality for artists, albums, and tracks, with search results displayed in carousels or tables.
- [x] **Artist Page:**
  - Display detailed information about an artist, including top tracks, albums, and similar artists.
  - Reuse of carousel and track-list components for clean, modular design.
- [x] **Album Page:**
  - Display album details, including tracks and associated metadata.
  - Reuse of track-list components for consistency.
- [x] **Track Page:**
  - Display track details, including audio features.
  - Use of a custom thermometer component with progress bars and dynamic color blending for visualizing track audio features.
- [x] **Custom Page - Top Tracks:**
  - Display the logged-in user's top tracks with engaging Bootstrap card styling.
  - Link added from the home page for easy navigation.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='./SpotifyBrowserDemo.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Kap](https://getkap.co/) for macOS