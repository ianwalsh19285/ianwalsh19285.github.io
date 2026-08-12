---
layout: page
title: Contact
subtitle: Get in touch
---

<style>
.contact-wrap {
  max-width: 760px;
  margin: 0 auto;
}

.contact-card {
  background: #fafafa;
  border: 1px solid #e7e7e7;
  border-radius: 20px;
  padding: 1.5rem;
  box-shadow: 0 6px 18px rgba(0,0,0,0.04);
}

.contact-form {
  display: grid;
  gap: 1rem;
}

.contact-row label {
  display: block;
  font-size: 0.93rem;
  font-weight: 600;
  margin-bottom: 0.4rem;
  color: #444;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  box-sizing: border-box;
  border: 1px solid #dddddd;
  border-radius: 12px;
  padding: 0.85rem 0.95rem;
  font-size: 0.98rem;
  line-height: 1.5;
  background: #fff;
  color: #333;
}

.contact-form textarea {
  min-height: 180px;
  resize: vertical;
}

.contact-form input:focus,
.contact-form textarea:focus {
  outline: none;
  border-color: #7e9bb8;
  box-shadow: 0 0 0 3px rgba(126, 155, 184, 0.14);
}

.contact-actions {
  margin-top: 0.25rem;
}

.contact-button {
  display: inline-block;
  border: none;
  border-radius: 10px;
  background: #4f6d8a;
  color: #fff;
  padding: 0.75rem 1.05rem;
  font-size: 0.95rem;
  font-weight: 600;
  cursor: pointer;
  transition: background 0.15s ease, transform 0.15s ease;
}

.contact-button:hover {
  background: #3f5b75;
  transform: translateY(-1px);
}

.contact-direct {
  margin-top: 1rem;
  text-align: center;
  font-size: 0.95rem;
  color: #666;
}

.contact-direct a {
  font-weight: 600;
}

.contact-note {
  margin-top: 0.5rem;
  text-align: center;
  font-size: 0.88rem;
  color: #888;
}

@media (max-width: 700px) {
  .contact-card {
    padding: 1.15rem;
  }
}
</style>

<div class="contact-wrap">
  <div class="contact-card">
    <form
      class="contact-form"
      action="https://formspree.io/f/xrpzkapg"
      method="POST"
    >
      <div class="contact-row">
        <label for="name">Name</label>
        <input id="name" type="text" name="name" required>
      </div>

      <div class="contact-row">
        <label for="email">Email</label>
        <input id="email" type="email" name="_replyto" required>
      </div>

      <div class="contact-row">
        <label for="message">Message</label>
        <textarea id="message" name="message" required></textarea>
      </div>

      <input type="hidden" name="_subject" value="New message from website contact form">
      <input type="hidden" name="_next" value="https://ianwalsh19285.github.io/contact-success/">

      <div class="contact-actions">
        <button class="contact-button" type="submit">Send message</button>
      </div>
    </form>

    <div class="contact-direct">
      Or email me directly at
      <a href="mailto:ianwalsh19285@gmail.com">ianwalsh19285@gmail.com</a>
    </div>

    <div class="contact-note">
      The form sends directly to my inbox.
    </div>
  </div>
</div>