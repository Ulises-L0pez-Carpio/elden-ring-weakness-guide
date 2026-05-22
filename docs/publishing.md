# Publishing Guide

This folder is structured to be published as a standalone portfolio repo without exposing the implementation codebase.

## Recommended public contents

- `README.md`
- `docs/case-study.md`
- `docs/how-it-was-built.md`
- `docs/publishing.md`
- `media/screens/`
- `downloads/android/`

## Keep private

Do not publish the implementation repo contents if the goal is portfolio presentation only:

- `src/`
- `android/`
- `scripts/`
- `data/`
- `data elden ring/`
- `node_modules/`
- workbook files
- internal development notes

## Suggested public repo name

`elden-ring-weakness-guide-portfolio`

## Suggested description

Portfolio presentation of a mobile companion app for Elden Ring Nightreign, focused on boss weaknesses, encounter reference, and mobile UX.

## APK note

The current APK intended for direct installation should live at `downloads/android/elden-ring-weakness-guide.apk`.

- The current direct-install APK from `releases/play-store-v3.0.1/` is about `80.2 MB`, so it fits within GitHub's normal file-size limit.
- The store-distribution artifact remains the `.aab`, but the public portfolio repo should highlight the APK because it is the correct format for easy reviewer installation.
- If later APK size grows past GitHub's limit, move distribution to a GitHub Release asset.
