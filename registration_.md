---
layout: single
title: "Registration & Fees"
permalink: /registration/
---
Only **50 places** are available for the Summer School.
Applications are open from **April 1st to May 31st, 2026**.

Applicants must submit a **motivation letter** and may also include a **poster abstract** if they wish to present a poster.


### Registration Fees
The registration fee includes access to all scientific sessions, hands-on tutorials, accommodation at the Centre Paul Langevin, and all meals (breakfast, lunch, dinner, and coffee breaks) for the duration of the school.

**Registration is free for all CNRS agents.**

For non CNRS agents:
* **Academic / Public Research:** 550 €
* **PhD Students:** 350 €
* **Industry / Private Sector:** 700 €


### Payment Methods
Accepted applicants will receive a confirmation email by the end of June 2026, including a link for payment. Payment must be completed by **July 15th, 2026**.

### Ready to Register?

<div id="countdown-container" style="text-align: center; background: #f9f9f9; padding: 25px; border-radius: 10px; border: 1px dashed #ccc; margin-top: 20px;">
  <h4 id="timer-title" style="margin-top: 0;">Applications open in:</h4>
  
  <div id="timer" style="display: flex; justify-content: center; gap: 20px; font-family: 'Courier New', Courier, monospace; font-weight: bold;">
    <div style="text-align: center;"><span id="days" style="font-size: 2rem; color: #004a99;">00</span><br><small style="color: #666; text-transform: uppercase;">Days</small></div>
    <div style="text-align: center;"><span id="hours" style="font-size: 2rem; color: #004a99;">00</span><br><small style="color: #666; text-transform: uppercase;">Hrs</small></div>
    <div style="text-align: center;"><span id="minutes" style="font-size: 2rem; color: #004a99;">00</span><br><small style="color: #666; text-transform: uppercase;">Min</small></div>
    <div style="text-align: center;"><span id="seconds" style="font-size: 2rem; color: #004a99;">00</span><br><small style="color: #666; text-transform: uppercase;">Sec</small></div>
  </div>
</div>

<script>
// Target: April 1st, 2026
const targetDate = new Date("2026-04-01T00:00:00").getTime();

const timerInterval = setInterval(function() {
  const now = new Date().getTime();
  const distance = targetDate - now;

  // Time calculations
  const d = Math.floor(distance / (1000 * 60 * 60 * 24));
  const h = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  const m = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  const s = Math.floor((distance % (1000 * 60)) / 1000);

  // Update display
  document.getElementById("days").innerText = d.toString().padStart(2, '0');
  document.getElementById("hours").innerText = h.toString().padStart(2, '0');
  document.getElementById("minutes").innerText = m.toString().padStart(2, '0');
  document.getElementById("seconds").innerText = s.toString().padStart(2, '0');

  // When countdown ends
  if (distance < 0) {
    clearInterval(timerInterval);
    document.getElementById("countdown-container").innerHTML = `
      <h4 style="margin: 0; color: #d9534f;">Registration is opening now... Please refresh the page.</h4>
    `;
  }
}, 1000);
</script>
