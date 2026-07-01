# TrustAudio Workshop Website

Static GitHub Pages site for TrustAudio: Workshop on Secure, Safe, and
Privacy-Preserving Speech and Audio AI.

## Structure

- `index.html`: homepage
- `assets/`: shared CSS and site mark
- `call-for-papers/`, `dates/`, `program/`, etc.: one folder per public page

Each page folder contains an `index.html`, so GitHub Pages serves clean URLs such
as `/program/` and `/organizers/`.

## Local Preview

```bash
python -m http.server 8765
```

Then open `http://127.0.0.1:8765/`.
