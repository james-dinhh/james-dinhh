---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span id="greeting" style="display: inline-block; transition: opacity 0.5s ease-in-out; font-size: 2em; font-weight: bold; color: #52adc8;">Hola 👋🏻</span>

I'm James - a fresher in the field of product management with over 2 years of experience in technology, specializing in B2B enterprise solutions, and SaaS.

I specialize in translating user insights into actionable product improvements. I've contributed to cross-functional projects in test automation, logistics, and data forecasting - bridging the gap between users and engineering.

Skilled in R, Python, SQL, and tools like <i>JIRA, Confluence</i>, I bring a product mindset to data-driven problem solving, with recent work involving macroeconomic forecasting and automation reporting for global clients like Intel and DHL.

---

<script>
const greetings = ["Hola 👋🏻", "Xin chào 👋🏻", "Hello 👋🏻", "你好 👋🏻", "Hallo 👋🏻"];
let idx = 0;
const greetingElement = document.getElementById("greeting");

function updateGreeting() {
  greetingElement.style.opacity = "0";
  setTimeout(() => {
    greetingElement.textContent = greetings[idx];
    greetingElement.style.opacity = "1";
    idx = (idx + 1) % greetings.length;
  }, 500);
}

setInterval(updateGreeting, 1500);
</script>
