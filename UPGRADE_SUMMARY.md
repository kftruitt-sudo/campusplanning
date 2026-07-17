---
layout: default
title: Upgrade Summary
---

## Upgrade Summary
- **From:** 1.5.0
- **To:** 1.6.1
- **Date:** 2026-07-17
- **Automated changes:** 119
- **Manual steps:** 9

## Automated Changes Applied

### Configuration (2 files)

- [x] Updated _data/katex.yml — KaTeX configuration (new) — CDN URLs, version, delimiters in one place
- [x] Updated assets/js/telar-story/iiif-card.js — IIIF card — dead viewer-config fallback removal

### Layouts (19 files)

- [x] Updated _layouts/story.html — Story layout — validation banner heading no longer repeated
- [x] Updated _layouts/index.html — Home layout — warning banners read from the language pack
- [x] Updated _layouts/default.html — Default layout — title_key resolver and seo title=false
- [x] Updated _layouts/index.html — Home layout — Google Sheets/theme banners and loading placeholders from the pack
- [x] Updated _layouts/object.html — Object layout — back link, coordinate tool, copy tooltips, viewer alert from the pack
- [x] Updated _layouts/objects-index.html — Objects index — heading and facet labels from the pack
- [x] Updated _layouts/glossary-index.html — Glossary index — heading from the pack
- [x] Updated _layouts/glossary.html — Glossary entry — back link from the pack
- [x] Updated _layouts/upgrade-summary.html — Upgrade summary — message from the pack
- [x] Updated _layouts/default.html — Default layout — design-token layer completion, header i18n
- [x] Updated _layouts/glossary.html — Glossary entry layout — dead glossary-shim removal
- [x] Updated _layouts/index.html — Home layout — object-grid-item and IIIF-thumbnail extraction
- [x] Updated _layouts/object.html — Object layout — inline algorithm extraction (theme, video embed, viewer coordinates), protected-story re-key
- [x] Updated _layouts/objects-index.html — Objects index — object-grid-item extraction, shared IIIF thumbnail module
- [x] Updated _layouts/story-fragment.html — Protected-story fragment layout (new) — rendered envelope, unlocked client-side
- [x] Updated _layouts/story.html — Story layout — KaTeX loader / Christmas-tree decorator extraction, shared story-steps loop, protected-story re-key
- [x] Updated _layouts/upgrade-summary.html — Upgrade summary layout — i18n completion
- [x] Updated _includes/object-grid-item.html — Objects-index gallery card (new, extracted from index/objects-index layouts)
- [x] Updated _sass/_layout.scss — Layout styles — design-token layer

### Includes (17 files)

- [x] Updated _includes/footer.html — Footer — translatable "Built with Telar" credit
- [x] Updated _includes/story-step.html — Story step — viewer alert and learn-more fallback from the pack
- [x] Updated _includes/viewer.html — Viewer overlay — loading text from the pack
- [x] Updated _includes/header.html — Header include — localized fallback menu
- [x] Updated _includes/iiif-url-warning.html — IIIF URL warning include — diagnostic extracted to a standalone script
- [x] Updated _includes/katex.html — KaTeX include — reads _data/katex.yml
- [x] Updated _includes/panels.html — Panels include — Offcanvas reuse guard
- [x] Updated _includes/share-embed-controls.html — Share-panel embed-size controls (new, extracted from share-panel.html)
- [x] Updated _includes/share-panel.html — Share panel — local language resolution, extracted embed/site-tab blocks
- [x] Updated _includes/share-site-tab.html — Share-panel "whole site" tab (new, extracted from share-panel.html)
- [x] Updated _includes/story-steps.html — Shared story-step loop (new) — used by both story.html and story-fragment.html
- [x] Updated _includes/upgrade-alert.html — Upgrade alert include — localized success alert
- [x] Updated _includes/widgets/accordion.html — Accordion widget — comment cleanup
- [x] Updated _includes/widgets/bibliography.html — Bibliography widget — comment cleanup
- [x] Updated _includes/widgets/carousel.html — Carousel widget — image src resolved in the widget parser, not the template
- [x] Updated _includes/widgets/tabs.html — Tabs widget — comment cleanup
- [x] Removed dead file _includes/viewer.html

### Styles (10 files)

- [x] Updated _sass/_embed.scss — Embed styles — nav-position breakpoint alignment
- [x] Updated _sass/_latex.scss — LaTeX styles — KaTeX consolidation
- [x] Updated _sass/_mixins.scss — Mixins — design-token layer additions
- [x] Updated _sass/_panels.scss — Panel styles — Offcanvas/panel fixes
- [x] Updated _sass/_responsive.scss — Responsive variable system — design-token layer completion
- [x] Updated _sass/_share.scss — Share styles — embed-controls/site-tab extraction
- [x] Updated _sass/_story.scss — Story styles — token-layer cleanup
- [x] Updated _sass/_viewer.scss — Viewer styles — chrome cleanup
- [x] Updated _sass/_widgets.scss — Widget styles — dead-rule removal, token layer
- [x] Updated assets/css/telar.scss — Main stylesheet entry — token-layer imports

### Scripts (60 files)

- [x] Updated scripts/telar/glossary.py — Glossary — case-insensitive matching + plain-text strip helper
- [x] Updated scripts/telar/processors/stories.py — Story processor — resolve [[term]] in the step answer
- [x] Updated scripts/telar/core.py — Pipeline core — strip glossary markup from protected-story answers
- [x] Updated assets/js/telar.js — Site JS — delegated glossary-link click handling
- [x] Updated scripts/telar/glossary.py — Glossary — warning call matches the message template
- [x] Updated assets/js/telar-story.js — Rebuilt story bundle (Lenis 1.3.23)
- [x] Updated assets/js/telar-story.js.map — Story bundle sourcemap
- [x] Updated assets/js/telar-story/audio-card.js — Audio card — clip-start seek fix on ready
- [x] Updated assets/js/telar-story/card-pool.js — Card pool — registry/interpolation vocabulary renamed to match lifecycles
- [x] Updated assets/js/telar-story/deep-link.js — Deep linking — dead fallback removal
- [x] Updated assets/js/telar-story/iiif-viewer.js — Viewer wrapper — cleanup
- [x] Updated assets/js/telar-story/main.js — Story bootstrap — cleanup
- [x] Updated assets/js/telar-story/navigation.js — Button navigation — cleanup
- [x] Updated assets/js/telar-story/panels.js — Panels — Offcanvas reuse guard
- [x] Updated assets/js/telar-story/scroll-engine.js — Scroll engine — dead code removal
- [x] Updated assets/js/telar-story/state.js — Runtime state — title-card state fields declared
- [x] Updated assets/js/telar-story/test-hook.js — Centring measurement hook — de-staled header comment
- [x] Updated assets/js/telar-story/text-card.js — Text card — content escaping, dead code removal
- [x] Updated assets/js/telar-story/utils.js — Utilities — dead code removal
- [x] Updated assets/js/telar-story/video-card.js — Video card — minor fix
- [x] Updated assets/js/telar-story/viewer.js — Viewer helpers — cleanup
- [x] Updated assets/js/christmas-tree-decorator.js — Christmas Tree Mode warning decorator (new, extracted from story.html)
- [x] Updated assets/js/embed.js — Embed bootstrap — nav-position breakpoint alignment
- [x] Updated assets/js/iiif-thumbnails.js — Shared IIIF thumbnail resolution (new) — sorted size pick, direct-URL fallback
- [x] Updated assets/js/iiif-url-warning.js — IIIF URL mismatch diagnostic (new, extracted from iiif-url-warning.html)
- [x] Updated assets/js/katex-loader.js — Lazy KaTeX loader for story pages (new, extracted from story.html)
- [x] Updated assets/js/object-theme.js — Object-page theme contrast helpers (new, extracted)
- [x] Updated assets/js/objects-filter.js — Objects filter — skip IIIF thumbnail fetch for video/audio objects
- [x] Updated assets/js/share-panel.js — Share panel — extracted embed-controls/site-tab blocks
- [x] Updated assets/js/story-unlock.js — Story unlock — rewritten for the rendered protected-story envelope
- [x] Updated assets/js/telar.js — Site JS — dead code removal
- [x] Updated assets/js/video-embed.js — Object-page video embed resolution (new, extracted)
- [x] Updated assets/js/wavesurfer-loader.js — Vendored WaveSurfer loader (new, extracted from object.html)
- [x] Updated assets/js/widgets.js — Widgets bootstrap — minor fix
- [x] Updated scripts/build_local_site.py — Local build orchestration — pipeline consolidation
- [x] Updated scripts/csv_to_json.py — CSV-to-JSON conversion — minor fix
- [x] Updated scripts/discover_sheet_gids.py — Sheet GID discovery — consolidation, dead-code removal
- [x] Updated scripts/encrypt_protected_stories.py — Post-build protected-story encryption (new)
- [x] Updated scripts/fetch_google_sheets.py — Google Sheets fetch — minor fix
- [x] Updated scripts/generate_collections.py — Collection generation — consolidation
- [x] Updated scripts/generate_iiif.py — IIIF tile generation — fallback tile backend (canonical w,h paths, full/max)
- [x] Updated scripts/iiif_utils.py — IIIF tiling utility — fallback tile backend support
- [x] Updated scripts/process_audio.py — Audio processing — ffmpeg requirement dropped; audiowaveform is the only tool
- [x] Updated scripts/process_pdf.py — PDF processing — minor fix
- [x] Updated scripts/telar/__init__.py — Package init — minor fix
- [x] Updated scripts/telar/core.py — Pipeline core — content-gate coverage, protected-story post-build hook
- [x] Updated scripts/telar/csv_utils.py — CSV utilities — minor fix
- [x] Updated scripts/telar/demo.py — Demo content handling — minor fix
- [x] Updated scripts/telar/encryption.py — Protected-story encryption — post-build support
- [x] Updated scripts/telar/iiif_metadata.py — IIIF metadata — dead-code removal
- [x] Updated scripts/telar/markdown.py — Markdown processing — consolidation
- [x] Updated scripts/telar/media_type.py — Media-type detection — uppercase audio-extension fix
- [x] Updated scripts/telar/processors/objects.py — Object processor — alt_text fix, cleanup
- [x] Updated scripts/telar/processors/stories.py — Story processor — protected-story frontmatter re-keying
- [x] Updated scripts/telar/search.py — Search index — minor fix
- [x] Updated scripts/telar/widgets.py — Widgets — carousel src resolution, comment-rendering fix
- [x] Updated NOTICE — Third-party notices — telar-icons.js attribution removed
- [x] Updated package.json — Dependency metadata (Lenis 1.3.23 pin)
- [x] Removed dead file assets/js/telar-icons.js
- [x] Upgrade-chain wiring fix (internal): the v1.5.4 -> v1.6.0 migration is now registered in scripts/upgrade.py, so upgrades starting below v1.6.0 no longer stop early at 1.5.4. No files in this site changed.

### Documentation (2 files)

- [x] Updated assets/js/README.md — JS directory README (new) — generated-bundle note
- [x] Updated README.md — README — contributor credits

### Other (9 files)

- [x] Updated _data/languages/en.yml — English language pack (reworded glossary warning; story_or key)
- [x] Updated _data/languages/es.yml — Spanish language pack (reworded glossary warning; story_or key)
- [x] Updated _data/languages/en.yml — English language pack (loading, objects.medium, footer.built_with; __THEME__ token)
- [x] Updated _data/languages/es.yml — Spanish language pack (same three keys at parity; __THEME__ token)
- [x] Build workflow concurrency group: add the `concurrency` block to .github/workflows/build.yml by hand (or recopy the file). The in-Actions upgrade cannot modify workflow files; the Telar Compositor applies it automatically. See the manual step below.
- [x] Updated _data/languages/en.yml — English language pack (new keys — see manual step)
- [x] Updated _data/languages/es.yml — Spanish language pack (same new keys at parity)
- [x] Updated CITATION.cff — Citation metadata — contributor addition
- [x] Added .gitattributes — marks the generated story bundle as linguist-generated

## Manual Steps Required

Please complete these steps:

1. **No action needed.** This is a runtime-only fix.

- **If you use GitHub Pages:** your site picks up the fix automatically the next time it builds.
- **If you work with your site locally:** just rebuild your site to use the updated glossary linking. ([guide](https://telar.org/docs))
2. **No action needed.** This is a display-only fix.

- **If you use GitHub Pages:** your site picks up the fix automatically the next time it builds.
- **If you work with your site locally:** just rebuild your site to use the updated warning messages. ([guide](https://telar.org/docs))
3. **No action needed.** This is a display-only fix.

- **If you use GitHub Pages:** your site picks up the translated chrome strings automatically the next time it builds.
- **If you work with your site locally:** just rebuild your site to use them. ([guide](https://telar.org/docs))
4. **Optional — fully translated page titles.** This release also translates the browser-tab titles of the home, objects, and glossary pages through a new `title_key` field. New sites get it automatically. To enable it on your existing site, add `title_key: navigation.home` to the front matter of `index.md`, `title_key: navigation.objects` to `pages/objects.md`, and `title_key: navigation.glossary` to `pages/glossary.md`. Without this, only those three browser-tab titles stay in English; every other string, including the page headings, already follows your site language. ([guide](https://telar.org/docs))
5. **If you use the Telar Compositor: no action needed.** The Compositor updates your build workflow automatically when it upgrades your site. ([guide](https://telar.org/docs))
6. **If you use GitHub Pages with the "Upgrade Telar" workflow, or work locally:** GitHub does not allow the automated upgrade to change workflow files, so your build workflow is not updated for you. Add the following block to `.github/workflows/build.yml`, just before the `jobs:` line (or recopy the file from the latest template):

```yaml
concurrency:
  group: "pages-${{ github.ref }}"
  cancel-in-progress: true
```

Until you do, your site keeps building and deploying correctly — you may just get an occasional spurious "build failed" email when two builds start at the same time. ([guide](https://telar.org/docs))
7. **Update `.github/workflows/build.yml` by hand (required if you use private stories).** v1.6.0 encrypts private stories in a new build step that GitHub does not allow this upgrade to add for you. Copy the current `build.yml` from the Telar repository over yours (open it on GitHub, use "Copy raw contents", replace the whole file, commit). Until you do, marking any story `private: yes` will fail your build on purpose rather than publish it unprotected. Details: https://telar.org/docs/setup/upgrading/#v160-upgrade-notes ([guide](https://telar.org/docs/setup/upgrading/#v160-upgrade-notes))
8. **If you customized the language packs, re-apply your changes.** The upgrade refreshed the framework language packs (`en.yml` / `es.yml`). This release adds several keys — the private-story unlock messages (empty/incorrect key), the embed banner's site-name fallback, audio-player control labels, and widget/glossary strings, among others — which the updated packs already include. ([guide](https://telar.org/docs))
9. **No action needed.** v1.6.1 only fixes the upgrade tooling itself (a missing registration that made upgrades stop at v1.5.4 and report success, instead of continuing to v1.6.0); it does not change anything in your site. ([guide](https://telar.org/docs))

## Resources

- [Full Documentation](https://telar.org/docs)
- [CHANGELOG](https://github.com/UCSB-AMPLab/telar/blob/main/CHANGELOG.md)
- [Report Issues](https://github.com/UCSB-AMPLab/telar/issues)
