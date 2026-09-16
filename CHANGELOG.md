# Changelog

All notable changes to this project are documented in this file.

## [2026.09] - 2026-09-16

- Maintenance review of solo-ai-agency-kit — the SkynetLabs "Solo AI Agency Kit" lead magnet, served as a static GitHub Pages site.
- Status: three artefacts only — `kit.html` (the A4 print-ready kit document on the SkynetLabs cream/ink/terracotta brand, Bricolage Grotesque + Fraunces + Inter + IBM Plex Mono), `SkynetLabs-Solo-AI-Agency-Kit.pdf` (the exported PDF), and `index.html`, which is now a `noindex` redirect stub sending all traffic to https://skynetjoe.com/edit-videos-with-claude after the kit funnel was consolidated into that page. `.nojekyll` is present for Pages.
- Reviewed September 2026: a README and CHANGELOG were added and the repo versioned as v2026.09. No changes to the kit content, PDF or redirect.
- Known gaps: the repo had no README, CHANGELOG or LICENSE before this release; there is no build step or automation linking `kit.html` to the committed PDF, so the two can drift apart; `index.html` no longer serves the kit directly, so the repo is effectively an archive plus a redirect.
