---
layout: default
title: Our Sponsors
description: The companies and people backing the final TABConf.
noindex: true
---

<!--
  THIS REPO IS PUBLIC. Everything here, comments included, is served to anyone who views
  source. Nothing about payment, amounts, or the reasoning behind who is listed and where
  belongs in this repo, in the markup, in a comment, or in a commit message.

  Unlinked work in progress. When ready, link from sponsors.md and drop the noindex flag.

  Tiers rank by size and position: larger and higher is more prominent. The ladder is the
  .tier-* classes below, sized tier-xl > tier-lg > tier-md > tier-sm. tier-xl is defined
  but unused, so a new top group can be added without touching the others.

  Logo slots are placeholders until image files land in assets/sponsors/. To fill one:
  <img src="/assets/sponsors/<file>" alt="<Name>" loading="lazy">
-->

# Our Sponsors

**The final TABConf runs on these people.** October 12-15, 2026, Georgia Tech Exhibition Hall, Atlanta.

Want your name here? See [sponsorship packages](/sponsors/) or email [hello@tabconf.com](mailto:hello@tabconf.com).

<style>
.sponsor-tier { margin: 3rem 0 1rem; }
.sponsor-tier h2 { margin-bottom: .2rem; }
.sponsor-tier__note { opacity: .6; font-size: .88rem; margin-top: 0; }
.sponsor-grid { display: grid; gap: 1.1rem; margin: 1.1rem 0 0; padding: 0; list-style: none; }
.sponsor-card { border: 1px solid rgba(128,128,128,.28); border-radius: 8px; padding: 1.2rem; display: flex; flex-direction: column; gap: .6rem; align-items: center; justify-content: center; text-align: center; }
.sponsor-card__slot { width: 100%; display: flex; align-items: center; justify-content: center; border: 1px dashed rgba(128,128,128,.4); border-radius: 6px; font-size: .68rem; letter-spacing: .05em; text-transform: uppercase; opacity: .45; }
.sponsor-card__slot img { max-width: 100%; height: auto; display: block; }
.sponsor-card__name a { text-decoration: none; }

/* Size ladder. Larger is more prominent. tier-xl is reserved for a future top group. */
.tier-xl .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(400px, 1fr)); }
.tier-xl .sponsor-card__slot { min-height: 180px; }
.tier-xl .sponsor-card__slot img { max-height: 180px; }
.tier-xl .sponsor-card__name { font-size: 1.5rem; font-weight: 700; }

.tier-lg .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(320px, 1fr)); }
.tier-lg .sponsor-card__slot { min-height: 140px; }
.tier-lg .sponsor-card__slot img { max-height: 140px; }
.tier-lg .sponsor-card__name { font-size: 1.3rem; font-weight: 700; }

.tier-md .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); }
.tier-md .sponsor-card__slot { min-height: 96px; }
.tier-md .sponsor-card__slot img { max-height: 96px; }
.tier-md .sponsor-card__name { font-size: 1.05rem; font-weight: 600; }

.tier-sm .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); }
.tier-sm .sponsor-card { padding: .9rem; }
.tier-sm .sponsor-card__slot { min-height: 60px; }
.tier-sm .sponsor-card__slot img { max-height: 60px; }
.tier-sm .sponsor-card__name { font-size: .9rem; font-weight: 600; }

@media (max-width: 560px) {
  .sponsor-grid { grid-template-columns: 1fr !important; }
  .tier-sm .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(130px, 1fr)) !important; }
}
</style>

<div class="sponsor-tier tier-lg">
<h2>Headline Sponsors</h2>
<ul class="sponsor-grid">
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://contract.design">Digital Contract Design</a></div>
  </li>
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://wasabiwallet.io">Wasabi Wallet</a></div>
  </li>
</ul>
</div>

<div class="sponsor-tier tier-md">
<h2>Supporting Sponsors</h2>
<ul class="sponsor-grid">
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://hrf.org">Human Rights Foundation</a></div>
  </li>
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://jintek.consulting">Jintek Consulting</a></div>
  </li>
</ul>
</div>

<div class="sponsor-tier tier-sm">
<h2>Community Sponsors</h2>
<ul class="sponsor-grid">
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://river.com">River</a></div>
  </li>
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://bitcointutorials.org">Bitcoin Tutorials</a></div>
  </li>
</ul>
</div>

---

Sponsorship is open until the conference, though **the sponsor board goes to print on September 25, 2026**. See [sponsorship packages](/sponsors/).
