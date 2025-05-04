---
title: Let Freedom Reign Foundation
layout: default
---
<!-- TOP -->
<div id="top"></div>

<div class="hero-container">
  <img id="hero-banner" src="/lfrf-mock/assets/graphics/hero-banner/lfrf-hero-banner-key.png" alt="Let Freedom Reign Foundation Banner" class="hero-banner" />
</div>

<div class="sub-banner-container">
  <img src="/lfrf-mock/assets/graphics/sub-banner/lfrf-sub-banner.png" alt="Providing Funds to Those Unable to Afford Mental Health Services" class="sub-banner" />
</div>
---

# ***According to [Mental Health America](https://mhanational.org/resources/quick-facts-and-statistics-about-mental-health/)***
 
 ***19.87%*** of the population of the United States have a diagnosable mental illness. Approximately ***68 MILLION PEOPLE***.

***66%*** of these individuals Cannot afford to pay for Mental Health Service.

## **In Oklahoma**
that means approximately ***500,000*** individuals cannot afford Mental Health Services.

## **In Lawton / Fort Sill**
there are approximately ***13,000*** individuals or families that cannot afford the Mental Health Services they seek.

---
<!-- About Section -->
<div id="about"></div>
# **HOW WE HELP**

- We provide funds to those unable to afford mental health services.
- We partner with Accredited clinics that adhere to strict ethical standards .
- We advocate for underinsured and uninsured individuals.  

> *"FREEDOM IS THE ABILITY TO ASK FOR HELP - AND BE HEARD."*

## *MENTAL HEALTH IMPACT* - **A SURVIVORS STORY**
> **October 20, 2013 my world changed forever due to a very traumatic event in my life.** *I woke up that morning to a gun pointed my direction.* My husband shot me 6 times in my torso area and then committed suicide. I immediately went into fight or flight mode and drove over a mile to seek help. Was med flighted to a trauma hospital and spent 7 days in a medical induced coma and went through three surgeries, then was moved to a regular room and on to a skilled therapy center for two weeks.
> [Read their full story →](/lfrf-mock/impact-story/)

---
---
<!-- Donate Section -->
<a id="donate"></a>
<h1 style="text-align: center;">SUPPORT OUR MISSION</h1>

<p style="text-align: center; max-width: 600px; margin: 0 auto;">
  Your donation helps us provide mental health services to those who otherwise couldn’t afford them. Every dollar contributes to healing in your community.
</p>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 3rem; margin-top: 2rem;">

<!-- PayPal Block -->
  <div class="qr-block" style="text-align: center;">
  <img src="/lfrf-mock/assets/graphics/qr/paypal-qr.png" alt="Donate via PayPal QR" width="150" />
  <p><a href="https://www.paypal.com/donate/?hosted_button_id=2W28XMRRM5CDW&source=qr" target="_blank">Donate via PayPal</a></p>
  <p style="max-width: 300px; margin: 0 auto; font-size: 0.9rem;">
      <em>Support long-term healing with a one-time or recurring donation.</em><br>
      <small>Every dollar makes a difference.</small>
    </p>
</div>

  <!-- GoFundMe Block -->
<div class="qr-block" style="text-align: center;">
  <img src="/lfrf-mock/assets/graphics/qr/gofundme-qr.png" alt="Donate via GoFundMe QR" width="150" />
  <p><a href="https://www.gofundme.com/f/support-mental-health-access-in-oklahoma/cl/s?lang=en_US&utm_campaign=fp_sharesheet&utm_medium=customer&utm_source=copy_link&attribution_id=sl%3Ade062269-2c73-44b4-8c86-f023a193d786" target="_blank">Donate via GoFundMe</a></p>
  <p style="max-width: 300px; margin: 0 auto; font-size: 0.9rem;">
      <em>Help us reach $10,000 to begin funding therapy in your community.</em><br>
      <small>Every dollar makes a difference.</small>
   </p>
</div>

<!-- LFRF Donation Tracker Block -->

<!-- PROGRESS BAR CONTAINER -->
<div id="service-progress" style="max-width: 400px; margin: 2rem auto; background: #e0e0e0; border-radius: 10px; height: 20px;">
  <!-- FILLED BAR - will visually grow with JavaScript below -->
  <div id="progress-bar" style="width: 0%; background: #5c6bc0; height: 100%; border-radius: 10px;"></div>
</div>

<!-- TEXT DISPLAYING PROGRESS COUNT -->
<p style="text-align: center; font-size: 0.9rem;" id="service-count">
  0 of 100 services funded
</p>

<!-- FUTURE AUTOMATION READY SCRIPT -->
<script>
  // Manual entry for now: update this value by hand as needed
  const servicesFunded = 0; // <-- CHANGE THIS NUMBER to current count
  const goal = 100;         // <-- CHANGE THIS if goal ever increases

  // Calculates the % of progress and updates the bar + text
  const percentage = (servicesFunded / goal) * 100;
  document.getElementById("progress-bar").style.width = percentage + "%";
  document.getElementById("service-count").innerText = `${servicesFunded} of ${goal} services funded`;
</script>

<!-- INSTRUCTIONS FOR MAINTAINERS -->
<!--
HOW TO UPDATE:
1. Open index.md
2. Scroll to the donation section where the PayPal and GoFundMe QR blocks are.
3. Paste this entire block right AFTER the second QR code block.
4. Change the "servicesFunded" number inside the <script> tag to the correct total.
5. Optionally change "goal" if the foundation raises or lowers its funding target.

FUTURE AUTOMATION:
- This block is structured to be easily adapted for automation.
- You can replace the "servicesFunded" and "goal" variables with values pulled from:
  - A CMS field
  - A remote JSON file (via fetch)
  - A connected Google Sheet with a public API
  - A server-side variable if integrated into a dynamic site
-->
</div>

---
---
<!-- Contact Section -->
<a id="contact"></a>
# CONTACT INFORMATION

> **8021 SW DEYO MISSION ROAD**

> **LAWTON, OKLAHOMA 73505**

> **580-351-9998**

<h2 style="text-align: center;">EMAIL US</h2>

<form action="https://formspree.io/f/mvgazyzg" method="POST" style="max-width: 600px; margin: 0 auto;">
  <label for="name">Name</label><br/>
  <input type="text" id="name" name="name" required style="width: 100%; padding: 0.5em; margin-bottom: 1em;" />

  <label for="email">Email</label><br/>
  <input type="email" id="email" name="_replyto" required style="width: 100%; padding: 0.5em; margin-bottom: 1em;" />

  <label for="message">Message</label><br/>
  <textarea id="message" name="message" rows="5" required style="width: 100%; padding: 0.5em;"></textarea>

  <br/><br/>
  <button type="submit" style="padding: 0.75em 1.5em; background-color: #222; color: #fff; border: none; border-radius: 4px; font-weight: bold;">
    Send Message
  </button>
</form>

