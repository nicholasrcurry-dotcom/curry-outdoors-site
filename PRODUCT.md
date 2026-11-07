# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

- **Members of the app** — hunters already in a shared property (individuals, families,
  leases, hunting groups) who need help: joining a property, understanding who sees their
  data, deleting their account.
- **App Store reviewers** — Apple checks the Support URL (`index.html`) and Privacy Policy
  URL (`privacy.html`) during every submission.
- **Open decision:** whether the site should also win new users (a public home for the app
  with features, screenshots and download links). Not decided; until it is, treat the site
  as support and policy only.

## Product Purpose

This site is the public face of **Curry Outdoors**, a cross-platform (iOS + Android)
deer-hunting app. The app gives a hunting group one shared workspace for a property:
satellite map, stands and blinds, trail-camera photos, sightings, buck profiles, weather and
wind, and a group chat.

The site exists so the app can ship: it provides the support and privacy URLs App Store
Connect requires, and answers members' questions in plain language. Success is a reviewer
or member finding the answer, or the support address, within seconds.

## Positioning

The app is a *shared* record of the land: everything saved to a property is visible to that
property's members and nobody else, and stand recommendations are explainable (wind fit,
recent activity, history in plain language) rather than opaque AI.

## Operating Context

- Served as static files by GitHub Pages from this public repo:
  `https://nicholasrcurry-dotcom.github.io/curry-outdoors-site/`. The app repo
  (`curry-outdoors`) stays private.
- The privacy policy's source of truth is `docs/PRIVACY.md` in the app repo. Any change must
  be mirrored here and in the App Privacy answers in App Store Connect — Apple compares the
  declarations against observed behaviour.
- Support email `support@currysoutdoors.com` (spelling confirmed) forwards to the owner.

## Capabilities and Constraints

- Plain static HTML/CSS, deliberately dependency-free: no build step, no frameworks, no
  external fonts or scripts, styles inline per page.
- Two pages today: `index.html` (support) and `privacy.html` (privacy policy).
- iPad is not supported by the app; only iPhone and Android.
- Policy wording is legal/factual copy: do not change claims without the owner and without
  updating `docs/PRIVACY.md` and App Store Connect to match.

## Brand Commitments

- Name: **Curry Outdoors**.
- Official tagline: **"Know the Land. Hunt Smarter."**
- Voice: plain language, direct, no marketing hedging ("We do not sell your data, we do not
  show ads").

## Evidence on Hand

- Product spec, phase status, App Store review notes and privacy policy in the app repo's
  `docs/`.
- An app mockup image: `docs/curry_outdoors_hunting_app_showcase.png` in the app repo.
- No testimonials, user counts, ratings, press, pricing, or store listing links exist yet;
  do not fabricate them.

## Product Principles

1. Answer first: a member or reviewer should reach the answer or the support address without
   hunting for it.
2. Truth over persuasion: every claim on the site matches what the app actually does.
3. Group data is shared and private to the property — say so clearly wherever data comes up.
4. Stay dependency-free and fast.
