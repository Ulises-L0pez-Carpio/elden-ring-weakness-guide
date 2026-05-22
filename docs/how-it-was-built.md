# How It Was Built

## Product Goal

The app was built as a mobile companion for *Elden Ring Nightreign* players who need quick access to weakness, encounter, and combat-reference information without leaving the game flow to search through spreadsheets or scattered notes.

## Stack

- Expo
- React Native
- TypeScript
- structured local JSON data
- Android release packaging for Play Store submission

## Build Approach

The project was developed around three main workstreams:

1. **Information architecture**
   The source material was reorganized into player-facing sections such as Nightlords, Night Bosses, Recluse, Scholar, and dodge timing.

2. **Data transformation**
   Spreadsheet-based and manually curated reference material was normalized into app-friendly data structures so the UI could render consistent cards, detail views, filters, and section navigation.

3. **Mobile UI implementation**
   The interface was designed to feel closer to a finished game companion product than to a raw database viewer, with section-specific backgrounds, stronger visual framing, and faster scan patterns for mobile use.

## Interface Priorities

- make lookup faster than the original source
- reduce visual noise
- keep information comparable across entries
- support navigation under quick-consultation use cases
- maintain a game-aligned presentation layer

## Final Output

The result was an Android-ready mobile app intended to be presented as a polished public project, with the source code kept private and the public repo focused on the product story, screenshots, the direct APK download, and evidence of the official `3.0.1 / 31` release line.
