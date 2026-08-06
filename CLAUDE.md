# CLAUDE.md — highkey21st
Owner: Sammy Wolfson (solo). Audited 2026-07-31 (first-run).

## What this is
Config-driven link-in-bio page (static HTML/CSS/JS). index.html + main.js render links from config.json and switch between themes in styles/ (dark, bright, minimal, kubrik, bulky, core). Bundles crypto-js (likely for a gated/obfuscated link). Same template family as sammylwolfson.github.io. "21st" reads like an event/party landing page.

## Rules
- Branch cody/nightly-YYYY-MM-DD only, never commit to main. No deploys/payments/external services without Sammy approval.
- Update Backlog + Run Log every run; summary to Agent Memory as dated file.

## FIRST-RUN PROTOCOL
1. Read git log, README, docs, code structure. Build on what exists.
2. Rescue any uncommitted work first.
3. Never force-push. Fetch and reconcile with origin before building; push cody/* branches only.

## Backlog (proposed for Sammy's review)
1. Deduplicate against sammylwolfson.github.io — shared template; pick one source of truth.
2. Document config.json fields + what crypto-js gates.
3. Add OG/meta tags for link previews; confirm mobile layout across the theme set.

## Run Log
- 2026-07-31 (first-run audit): filled "What this is", proposed backlog. No code changes.
