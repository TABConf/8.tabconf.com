---
layout: default
title: Our Sponsors
description: The companies and people backing the final TABConf.
noindex: true
---

<!--
  THIS REPO IS PUBLIC. Everything here, including comments, is served to anyone who views
  source. Never put a sponsor's payment status, amount, negotiation history, or the reason
  somebody is or is not on this page into this file. None of that belongs in this repo, in
  the markup, in a comment, or in a commit message.

  Unlinked page, still a work in progress. When it is ready, link it from sponsors.md and
  remove the noindex flag above. noindex is set because an unlinked page is a public URL,
  not a private one; it is undiscovered, and gets indexed the moment anything links it.

  NO PRICES AND NO AMOUNTS ON THIS PAGE. Rank is expressed through position and logo size
  alone: premium tiers higher with larger logos, General at the bottom with small ones. The
  size ladder is the .tier-N classes below, largest at tier-1. A new tier takes the class
  matching its rank rather than inventing a size. Pricing lives on /sponsors/.

  Logos are placeholders until the files arrive. To add one, drop it in assets/sponsors/
  and replace the placeholder div with:
  <img src="/assets/sponsors/<file>" alt="<Name>" loading="lazy">

  Who appears here is not derivable from who has supported the conference. The
  authoritative list of who belongs on this page is kept privately, not in this repo.
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

/* Rank is size. tier-1 is the most premium. */
.tier-1 .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(340px, 1fr)); }
.tier-1 .sponsor-card__slot { min-height: 150px; }
.tier-1 .sponsor-card__slot img { max-height: 150px; }
.tier-1 .sponsor-card__name { font-size: 1.35rem; font-weight: 700; }

.tier-2 .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); }
.tier-2 .sponsor-card__slot { min-height: 124px; }
.tier-2 .sponsor-card__slot img { max-height: 124px; }
.tier-2 .sponsor-card__name { font-size: 1.2rem; font-weight: 700; }

.tier-3 .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(230px, 1fr)); }
.tier-3 .sponsor-card__slot { min-height: 100px; }
.tier-3 .sponsor-card__slot img { max-height: 100px; }
.tier-3 .sponsor-card__name { font-size: 1.05rem; font-weight: 600; }

.tier-4 .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(190px, 1fr)); }
.tier-4 .sponsor-card__slot { min-height: 82px; }
.tier-4 .sponsor-card__slot img { max-height: 82px; }
.tier-4 .sponsor-card__name { font-size: .98rem; font-weight: 600; }

.tier-5 .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); }
.tier-5 .sponsor-card { padding: .9rem; }
.tier-5 .sponsor-card__slot { min-height: 62px; }
.tier-5 .sponsor-card__slot img { max-height: 62px; }
.tier-5 .sponsor-card__name { font-size: .9rem; font-weight: 600; }

@media (max-width: 560px) {
  .sponsor-grid { grid-template-columns: 1fr !important; }
  .tier-5 .sponsor-grid { grid-template-columns: repeat(auto-fill, minmax(130px, 1fr)) !important; }
}
</style>

<div class="sponsor-tier tier-1">
<h2>Lunch Sponsor</h2>
<p class="sponsor-tier__note">Feeds the whole conference, all four days.</p>
<ul class="sponsor-grid">
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://contract.design">Digital Contract Design</a></div>
  </li>
</ul>
</div>

<div class="sponsor-tier tier-2">
<h2>Wristband Sponsor</h2>
<p class="sponsor-tier__note">On the wrist of every attendee, all four days.</p>
<ul class="sponsor-grid">
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://wasabiwallet.io">Wasabi Wallet</a></div>
  </li>
</ul>
</div>

<div class="sponsor-tier tier-3">
<h2>Grant Sponsor</h2>
<p class="sponsor-tier__note">Funds travel and tickets for developers who could not otherwise come.</p>
<ul class="sponsor-grid">
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://hrf.org">Human Rights Foundation</a></div>
  </li>
</ul>
</div>

<div class="sponsor-tier tier-4">
<h2>Capture the Bitcoin Sponsor</h2>
<p class="sponsor-tier__note">Backs the puzzle that runs the length of the conference.</p>
<ul class="sponsor-grid">
  <li class="sponsor-card">
    <div class="sponsor-card__slot">logo to come</div>
    <div class="sponsor-card__name"><a href="https://jintek.consulting">Jintek Consulting</a></div>
  </li>
</ul>
</div>

<div class="sponsor-tier tier-5">
<h2>General Sponsors</h2>
<p class="sponsor-tier__note">Backing the last one because they wanted to.</p>
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
