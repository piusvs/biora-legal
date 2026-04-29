# Biora Privacy Policy

Static GitHub Pages site for Biora's privacy policy. Apple requires a working privacy policy URL for any app that collects user data.

## Contents

- `index.html` — rendered policy page (light + dark mode CSS, no JS)
- `policy.md` — same text in plain Markdown for editing convenience

## Deploying via GitHub Pages

1. Create a new repo (e.g. `biora-privacy-policy`) and push this folder's contents to the root.
2. In repo settings → Pages, source: `Deploy from a branch` → `main` → `/ (root)`.
3. Once it goes live, GitHub gives you a URL like `https://<your-handle>.github.io/biora-privacy-policy/`.
4. Update the `BioraPrivacyPolicyURL` constant in `Biora/Models/AppLinks.swift` to point at that URL.
5. The "Privacy Policy" row in Settings → Other already opens that URL via `Link`.

## Updating

Bump the "Last updated" date in `index.html` and `policy.md` whenever the policy changes. Replace `TBD` with a real support email when one's available.
