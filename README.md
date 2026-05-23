<p align="center">
  <img src="./media/branding/istilezz-labs-logo.png" alt="istilezz Labs" width="320" />
</p>

<p align="center"><strong>istilezz Labs</strong></p>

# Elden Ring Weakness Guide

[English](./README.md) | [Español](./README.es.md)

Project presentation for a mobile companion app focused on boss-weakness lookup, encounter reference, and game-aligned mobile UX for *Elden Ring Nightreign* players.

## Project Summary

*Elden Ring Weakness Guide* is a mobile companion app designed for players who want fast, readable combat reference during gameplay preparation or active runs. Instead of relying on spreadsheets, scattered notes, and community pages, the app brings core Nightreign information into one structured mobile experience.

This public repository exists to present the project. It does **not** include the source code. Its purpose is to present the product, explain how it was built, show the current interface, and provide an installable Android APK.

## Why This Project Exists

Nightreign reference material is useful, but the original information sources are not optimized for quick mobile consultation. The project reframed that problem as a product challenge:

- make weakness and encounter lookup faster
- reduce friction during player decision making
- turn dense source material into a clearer mobile interface
- preserve depth without preserving spreadsheet complexity

## APK Download

The app is not currently distributed through the Play Store.

- Local APK included in this project package: [`downloads/android/elden-ring-weakness-guide.apk`](./downloads/android/elden-ring-weakness-guide.apk)
- Current APK size: about `80.2 MB`
- Official Play Store publication line represented here: `3.0.1 / 31`

## What The App Does

The app helps players quickly check combat reference information without leaving the gameplay context to dig through spreadsheets, notes, or community pages.

It brings together:

- Nightlord weakness and resistance reference
- Night Boss encounter browsing
- Nightlord detail views with combat-reference data
- movement timing and recovery information
- Scholar item reference
- Recluse cocktail combinations

## My Contribution

I built the project end to end:

- product framing
- information architecture
- mobile UI direction
- content integration
- data cleanup and transformation
- release-oriented Android packaging and validation

## How It Was Built

The project was built as an Expo + React Native mobile app using TypeScript and structured local JSON data derived from spreadsheet-based and manually curated reference material.

The main challenge was not only implementation, but translation: taking information that was inconsistent, dense, and partially visual in its original form, then converting it into a cleaner mobile product with searchable sections, reusable detail views, and a stronger visual system.

For a dedicated breakdown, see [docs/how-it-was-built.md](./docs/how-it-was-built.md).

## Screens

### Home

<img src="./media/screens/home.jpeg" alt="Home screen" width="320" />

### Nightlords

<img src="./media/screens/nightlords.jpeg" alt="Nightlords screen" width="320" />

### Night Bosses

<img src="./media/screens/bosses.jpeg" alt="Night Bosses screen" width="320" />

### Nightlord Detail

<img src="./media/screens/nightlord-detail.jpeg" alt="Nightlord detail screen" width="320" />

### Recluse

<img src="./media/screens/recluse.jpeg" alt="Recluse screen" width="320" />

## Product Decisions

- Prioritized mobile browsing over dense table-style presentation.
- Used section identity and visual framing to make navigation faster.
- Focused on actionable reference instead of mirroring every raw spreadsheet field.
- Structured the content so the app could scale without losing clarity.

## Release Context

- Current app line: `3.0.1 / 31`
- Android package: `nightreign.w.g`
- Public repo purpose: project presentation and app download
- Source code: intentionally private

## Case Study

For the short project walkthrough, see [docs/case-study.md](./docs/case-study.md).
