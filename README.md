# Goggles — Art History + Primary Sources (Brave Search)

Custom **Brave Search Goggles** for research-heavy browsing: **museums + archives + primary sources go up**, and the usual search-result barnacles (Pinterest, Quora, content-farms) go down—or get tossed overboard.

This repo contains two Goggles:

- **Balanced**: boosts high-quality sources while still letting the broader web show up.
- **Strict**: “guest list” mode — defaults to discard unless a result matches your approved sources.

---

## What are Brave Search Goggles?

A **Goggle** is a plain-text ruleset that changes how Brave Search ranks results.
You can:
- **boost** sites you trust
- **downrank** low-quality domains
- **discard** sources you never want to see

Think of it as training a search engine to stop eating crayons.

---

## Files in this repo

- `robert_art_history_primary_sources_balanced.goggle`  
  A practical daily driver: museums, archives, libraries, and scholarly sources get boosted; common junk gets removed or pushed down.

- `robert_art_history_primary_sources_strict.goggle`  
  Research mode: a default discard + explicit allowlist/boosts.

---

## Use these Goggles

### Step 1 — Copy the RAW file URL
Brave needs the **raw** GitHub-hosted URL (not the normal GitHub file page).

Balanced (RAW):
```text
https://raw.githubusercontent.com/rgrantham82/Goggles-/refs/heads/main/robert_art_history_primary_sources_balanced.goggle
