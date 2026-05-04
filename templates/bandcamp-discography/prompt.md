# Bandcamp Discography

## What this page is
A music discography page for a Bandcamp artist or label. It displays album artwork in a grid, with a detail view that slides in when an album is clicked — showing tracklist, description, and a link to Bandcamp.

## How to customize
The user will provide their Bandcamp artist/label URL (e.g. `https://artist.bandcamp.com`). When they do:

1. Replace the artist name, location, avatar image, and Bandcamp link in the header
2. Replace the placeholder album cards with real albums — each card needs:
   - `data-title` — album name
   - `data-year` — release year
   - `data-artist` — artist name on the release
   - `data-description` — short album description
   - `data-tracks` — JSON array of `[{"title":"...","duration":"..."}]`
   - `data-art` — album artwork URL (Bandcamp uses `https://f4.bcbits.com/img/a{ID}_10.jpg`)
   - `data-bandcamp-url` — direct link to the album on Bandcamp
3. The album grid auto-fills responsively — add as many cards as the user wants

## Section structure
- **Artist header**: Avatar image, name, location, release count, Bandcamp link
- **Discography grid**: Album cards with artwork, title, year, hover-to-play overlay
- **Album detail view**: Slides in with artwork, title, artist, description, tracklist, Bandcamp link
- **Footer**: Credit link to Bandcamp

## Design intent
Dark, music-focused aesthetic inspired by Spotify/Bandcamp. Green accent color. Space Grotesk headings. Clean album grid with smooth hover animations and GSAP scroll reveals. The detail view is a fullscreen slide-in panel.

## 3 suggested first edits
1. "Change the artist name and add your Bandcamp URL"
2. "Update the color scheme to match your brand"
3. "Add more album cards with your release details"
