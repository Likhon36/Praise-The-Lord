# Praise the LORD BD - App Design

## Overview
A mobile app for browsing and displaying Bengali Christian hymns and songs with lyrics, chord notations, and music player functionality.

## Screen List

1. **Home Screen** - Browse all songs/hymns with search and filter
2. **Song Detail Screen** - Display full lyrics with chord notations and music player
3. **Favorites Screen** - Saved favorite songs for quick access
4. **Settings Screen** - App preferences (font size, theme, etc.)

## Primary Content and Functionality

### Home Screen
- **Content**: Grid or list of all songs with title, author, and thumbnail
- **Functionality**:
  - Search songs by title or author
  - Filter by category (if available)
  - Tap to view song details
  - Tap heart icon to add to favorites

### Song Detail Screen
- **Content**: 
  - Song title and author
  - Full Bengali lyrics with chord notations (e.g., E, C#m, B)
  - Scrollable lyric view
- **Functionality**:
  - Play/pause music (if audio available)
  - Adjust font size for lyrics
  - Share song
  - Add/remove from favorites
  - Transpose chords (if music player available)

### Favorites Screen
- **Content**: List of saved favorite songs
- **Functionality**:
  - View all favorited songs
  - Remove from favorites
  - Tap to view song details

### Settings Screen
- **Content**: 
  - Font size slider
  - Theme toggle (light/dark)
  - About app
- **Functionality**:
  - Adjust text size
  - Switch between light and dark mode
  - View app version and credits

## Key User Flows

1. **Browse and View Song**
   - User opens app → Home screen displays all songs
   - User searches or scrolls to find song
   - User taps song → Song Detail screen opens
   - User reads lyrics and chords

2. **Save Favorite**
   - User on Song Detail screen
   - User taps heart icon → Song added to favorites
   - User can access from Favorites tab

3. **Search Song**
   - User on Home screen
   - User taps search bar and types song title/author
   - Results filter in real-time
   - User taps result to view details

## Color Choices

- **Primary**: Deep Blue (#0a7ea4) - Represents faith and spirituality
- **Background**: White (#ffffff) for light mode, Dark Gray (#151718) for dark mode
- **Surface**: Light Gray (#f5f5f5) for light mode, Darker Gray (#1e2022) for dark mode
- **Accent**: Gold (#F59E0B) - For highlights and important elements
- **Text**: Dark Gray (#11181C) for light mode, Light Gray (#ECEDEE) for dark mode

## Navigation Structure

- **Tab Bar Navigation**:
  - Home (house icon)
  - Favorites (heart icon)
  - Settings (gear icon)

## Design Principles

- **Mobile-First**: Optimized for portrait orientation and one-handed usage
- **Readability**: Large, clear fonts for lyrics (adjustable)
- **Accessibility**: High contrast ratios, clear touch targets
- **Simplicity**: Minimal UI, focus on content (lyrics)
- **Offline-First**: All songs stored locally, no internet required
