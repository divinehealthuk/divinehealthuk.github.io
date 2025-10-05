---
layout: default
title: Contact
permalink: /contact.html
nav_order: 4
---

<h2>Contact &amp; Booking</h2>

<p>For bookings, collaborations or enquiries, please get in touch below. Kamila will respond personally within 1–2 working days.</p>

<ul class="contact-meta">
  <li>Phone: <a href="tel:+447969472054">07969 472054</a></li>
  <li>Email: <a href="mailto:kamila.divinehealth@gmail.com">kamila.divinehealth@gmail.com</a></li>
  <li>Location: <strong>Based in Frome</strong> — offers both in-person and online consultations.</li>
</ul>

<div class="form-wrap">
  <form id="contactForm" method="POST" action="https://formspree.io/f/your-id-here">
    <label for="name">Name</label>
    <input id="name" name="name" required>

    <label for="email">Email</label>
    <input id="email" name="_replyto" type="email" required>

    <label for="message">Message</label>
    <textarea id="message" name="message" rows="6" required></textarea>

    <input type="text" name="_gotcha" style="display:none">

    <button type="submit" class="cta gold">Send message</button>
  </form>

  <div id="formMessage" class="form-message" aria-live="polite" hidden>
    Thank you for your message. Kamila will reply within 1–2 working days.
  </div>
</div>
