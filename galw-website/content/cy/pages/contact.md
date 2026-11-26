---
title: Cysylltu
date: 2026-11-26
draft: false
eleventyNavigation:
  key: contact
  title: Cysylltu
  order: 3
---

<!-- 
    =======================================================================

    This is a working contact form. To receive email, 
    Replace YOUR_ACCESS_KEY_HERE with your actual Access Key.

    Create Access Key here 👉 https://web3forms.com/

    =======================================================================
 -->

<form action="https://api.web3forms.com/submit" method="POST" id="form" style="max-width: 65ch;">
  <fieldset>
    <legend>Ffurflen Gyswllt</legend>

    <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE" />
    <input type="hidden" name="subject" value="Neges Newydd o Ffurflen Gyswllt GALW" />
    <input
      type="hidden"
      name="redirect"
      value="https://web3forms.com/success"
    />

    <input type="checkbox" name="botcheck" style="display: none;" />

    <div>
      <label for="name">Enw Llawn</label><br />
      <input
        type="text"
        name="name"
        id="name"
        placeholder="Siôn Jones"
        required
      />
      <br /><br />
    </div>

    <div>
      <label for="email">Cyfeiriad E-bost</label><br />
      <input
        type="email"
        name="email"
        id="email"
        placeholder="chi@cwmni.cymru"
        required
      />
      <br /><br />
    </div>

    <div>
      <label for="phone">Rhif Ffôn</label>
      <br />
      <input
        type="text"
        name="phone"
        id="phone"
        placeholder="01234 567890"
        required
      />
      <br /><br />
    </div>

    <div>
      <label for="message">Eich Neges</label>
      <br />
      <textarea
        rows="5"
        name="message"
        id="message"
        placeholder="Ysgrifennwch eich neges yma..."
        required
        style="width: 100%"
      ></textarea>
      <br /><br />
    </div>

    <button type="submit">Anfon Neges</button>
  </fieldset>
</form>