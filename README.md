# The Individual & Society — IDHUB

**Live site:** [justinsteinmetz.github.io/IDHUB](https://justinsteinmetz.github.io/IDHUB/)

A hub page for a ten-instrument interactive strand built for the KMK Themenfeld **"The Individual and Society"** (Abitur 2027–29), Deutsche Schule Prag, English Department, Grades 11–12. Each instrument is a standalone single-file HTML tool; this page links them together into a sequenced, clustered strand and frames the question that runs through all of them.

> **Central question:** *Which of your choices are actually yours?*
> Every instrument approaches it from a different angle. None of them answers it.

## What this is

A single static HTML page (`idhub-final.html`) — no build step, no dependencies beyond Google Fonts. It organises the ten instruments into four clusters, each opening in a new tab via `target="_blank"`:

**Cluster 1 — Self-Knowledge**
- Who Are You, Really — behaviour, origin & conformity
- Default Settings — inherited assumptions, behavioural self-audit
- The Danger Room — argument under pressure

**Cluster 2 — Identity Construction**
- BIRTHMARKS — race, culture & inherited identity (archival instrument)
- SELF v SELFIE — curated vs. real self-presentation
- RPG4LIFE — assigned vs. chosen role

**Cluster 3 — Civic & Social Position**
- Social Contract — assigned-role civic simulation
- When Yes Means No — consent vs. performed willingness

**Cluster 4 — Information & Data**
- Input / Output — data, consent & behavioural shaping
- Surveillance — privacy, power & chilling effects

The page also includes a recommended sequence, five cross-cutting threads connecting the instruments, five Abitur-style essay questions, and an explicit "where the framework fails" section naming the strand's own limitations (risk of sliding into determinism; the contested assumption of a stable "real" self beneath the performed/inherited/surveilled self).

## Design philosophy

- **Experience before framework** — each instrument puts students inside a situation before naming what it is.
- **Inward before outward** — the sequence moves from personal self-knowledge toward structural critique, not the reverse.
- **No resolved answer** — the strand is built to make the central question harder to ignore, not to settle it.
- **Self-aware limitations** — the hub names where its own framing could mislead, rather than presenting the strand as complete.

## Structure

```
idhub-final.html   — single-file hub page (HTML + embedded CSS, no JS dependencies)
```

Visual style: warm paper aesthetic (cream/parchment palette, Cormorant Garamond + DM Sans + DM Mono), subtle paper-texture overlay, colour-coded cluster accents. Links back to the [DSP English Hub](https://justinsteinmetz.github.io/DSP_English_Hub/).

## Deployment

Hosted via GitHub Pages directly from this repo. To update, edit `idhub-final.html` and push to the default branch — no build step required.

## Context

Part of a broader set of interactive HTML classroom instruments developed for DSP Prague's English/Politics & Society curriculum, alongside strands such as *Britain · Identity · Power · Memory · Narrative* and the Year 10 Punishment & the State unit.
