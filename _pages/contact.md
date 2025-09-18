---
layout: single
title: 'Contactez moi :'
permalink: /contact/
---

<!-- Formulaire de contact prêt à l'emploi -->

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/mvgbjblq" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Nom complet</label>
    <input type="text" name="name" id="full-name" placeholder="Votre nom" required="">

    <label for="email-address">Adresse email</label>
    <input type="email" name="_replyto" id="email-address" placeholder="VotreEmail@domaine.tld" required="">

    <label for="message">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="Écrivez votre message ici" required=""></textarea>

    <input type="hidden" name="_subject" id="email-subject" value="Soumission du formulaire de contact">
  </fieldset>

  <input type="submit" value="Envoyer" class="btn btn--info">
</form>
