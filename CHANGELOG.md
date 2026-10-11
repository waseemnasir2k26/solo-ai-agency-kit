# Changelog

All notable changes to this project are documented in this file.

## [2026.10] - 2026-10-12

- Public GitHub Pages host for the SkynetLabs 'Solo AI Agency Kit' lead magnet: `kit.html` (A4 print-ready), the exported PDF, and an `index.html` redirect stub to skynetjoe.com/edit-videos-with-claude.
- Reviewed October 2026: the only README link (skynetjoe.com/edit-videos-with-claude) responds 200. Kit content, PDF and redirect unchanged; last functional commit 2026-06-20.
- README appended with the standard 'Work with SkynetLabs' section.
- Known gaps: no build step ties `kit.html` to the committed PDF so they can drift; no LICENSE; the root no longer serves the kit directly, so the repo is mainly a file host.

## [2026.09] - 2026-09-16

- Maintenance review of solo-ai-agency-kit — the SkynetLabs "Solo AI Agency Kit" lead magnet, served as a static GitHub Pages site.
- Status: three artefacts only — `kit.html` (the A4 print-ready kit document on the SkynetLabs cream/ink/terracotta brand, Bricolage Grotesque + Fraunces + Inter + IBM Plex Mono), `SkynetLabs-Solo-AI-Agency-Kit.pdf` (the exported PDF), and `index.html`, which is now a `noindex` redirect stub sending all traffic to https://skynetjoe.com/edit-videos-with-claude after the kit funnel was consolidated into that page. `.nojekyll` is present for Pages.
- Reviewed September 2026: a README and CHANGELOG were added and the repo versioned as v2026.09. No changes to the kit content, PDF or redirect.
- Known gaps: the repo had no README, CHANGELOG or LICENSE before this release; there is no build step or automation linking `kit.html` to the committed PDF, so the two can drift apart; `index.html` no longer serves the kit directly, so the repo is effectively an archive plus a redirect.
