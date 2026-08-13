---
layout: default
title: Email updates
description: Get TABConf 8 announcements by email.
noindex: true
---

<!--
  THIS REPO IS PUBLIC. Everything here, comments included, is served to anyone who views
  source, and this file is readable in git history whether or not the page is linked.
  noindex plus no inbound link keeps it out of search results. It does not make it private.

  The form posts straight to Mailchimp. Audience "TABConf Attendees".

  Trimmed from the Mailchimp classic embed on purpose. Everything removed was inert:
    - The SMS phone country-code script, several hundred lines, drives smsphone fields.
      This audience has none, and FNAME, LNAME, ADDRESS, PHONE and BIRTHDAY are all
      disabled in the form config, so only EMAIL is live.
    - mc-validate.js and its jQuery dependency, replaced by the browser's own
      type="email" required validation.
    - The Mailchimp CDN stylesheet, which fights this site's styles.
  What was kept and MUST stay:
    - The exact form action including u, id and f_id.
    - The hidden honeypot input b_<u>_<id>. It must stay empty and stay off screen.
      Bots fill it, humans cannot see it, Mailchimp drops anything that arrives with it set.
-->

# Get TABConf 8 updates

**This is the last TABConf.** October 12 to 15, 2026, Georgia Tech Exhibition Hall, Atlanta.

Drop your email in and we will send you the things that actually matter: when the schedule lands, when tickets change, and the logistics you need the week of the event. Nothing else.

<style>
.signup { max-width: 460px; margin: 2rem 0; }
.signup__label { display: block; font-weight: 600; margin-bottom: .4rem; }
.signup__row { display: flex; gap: .6rem; flex-wrap: wrap; }
.signup__input {
  flex: 1 1 240px; padding: .7rem .8rem; font-size: 1rem; font-family: inherit;
  border: 1px solid rgba(128,128,128,.5); border-radius: 6px; background: transparent;
  color: inherit; min-width: 0;
}
.signup__input:focus { outline: 2px solid currentColor; outline-offset: 1px; }
.signup__btn {
  padding: .7rem 1.3rem; font-size: 1rem; font-family: inherit; font-weight: 600;
  border: 1px solid currentColor; border-radius: 6px; background: transparent;
  color: inherit; cursor: pointer;
}
.signup__btn:hover { opacity: .75; }
.signup__note { font-size: .85rem; opacity: .65; margin-top: .7rem; }
.signup__hp { position: absolute; left: -5000px; }
</style>

<div class="signup">
  <form action="https://tabconf.us19.list-manage.com/subscribe/post?u=2a4c90ba34d8f78afe747baf5&amp;id=8eb7c5f78e&amp;f_id=007d74e7f0" method="post" target="_blank" rel="noopener">
    <label class="signup__label" for="mce-EMAIL">Email address</label>
    <div class="signup__row">
      <input class="signup__input" type="email" name="EMAIL" id="mce-EMAIL" required autocomplete="email" placeholder="you@example.com">
      <button class="signup__btn" type="submit" name="subscribe">Keep me posted</button>
    </div>

    <div class="signup__hp" aria-hidden="true">
      <input type="text" name="b_2a4c90ba34d8f78afe747baf5_8eb7c5f78e" tabindex="-1" value="" autocomplete="off">
    </div>

    <p class="signup__note">One list, low volume, unsubscribe in one click from any email. We do not sell or share it.</p>
  </form>
</div>

Already have a ticket? You do not need to sign up here. Ticket buyers are added automatically and get their confirmation and event logistics either way.

Questions: [hello@tabconf.com](mailto:hello@tabconf.com)
