## Hi there I'm Gift 👋

<!--
**Sirada-123/Sirada-123** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<h3 align="left">Entering Last quarter of 2026, Let's countdown!:</h3>
<div id="countdown" style="
  font-family: monospace;
  font-size: 32px;
  font-weight: bold;
  text-align: center;
">
  <span id="days">00</span>d :
  <span id="hours">00</span>h :
  <span id="minutes">00</span>m :
  <span id="seconds">00</span>s
</div>

<script>
  const targetDate = new Date("2027-01-01T00:00:00");

  function updateCountdown() {
    const now = new Date();
    const difference = targetDate - now;

    if (difference <= 0) {
      document.getElementById("countdown").textContent = "🎉 Happy New Year 2027!";
      clearInterval(timer);
      return;
    }

    const days = Math.floor(difference / (1000 * 60 * 60 * 24));
    const hours = Math.floor(
      (difference / (1000 * 60 * 60)) % 24
    );
    const minutes = Math.floor(
      (difference / (1000 * 60)) % 60
    );
    const seconds = Math.floor(
      (difference / 1000) % 60
    );

    document.getElementById("days").textContent =
      String(days).padStart(2, "0");

    document.getElementById("hours").textContent =
      String(hours).padStart(2, "0");

    document.getElementById("minutes").textContent =
      String(minutes).padStart(2, "0");

    document.getElementById("seconds").textContent =
      String(seconds).padStart(2, "0");
  }

  updateCountdown();

  const timer = setInterval(updateCountdown, 1000);
</script>

<h3 align="left">Languages and Tools:</h3>
<img src="https://skillicons.dev/icons?i=react,typescript,javascript,dart,flutter,python,nodejs,vite,tailwind,redux,aws,firebase,supabase,docker,git,github,linux" />
</p>
