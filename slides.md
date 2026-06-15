---
theme: default
title: "All by Myself – Martin Brandal"
colorSchema: light
fonts:
  sans: Arial
  mono: Courier New
transition: slide-left
---

<!-- PRESENTER: Trykk [P] for presenter-modus, [F] for fullskjerm, piltaster for navigering -->

---
layout: cover
---

<div class="cover-inner">
  <div class="cover-logo">Epinova</div>
  <div class="cover-title-area">
    <h1>All by Myself</h1>
    <p class="cover-subtitle">🎵 Eric Carmen, 1975 — en guide til å overleve (og trives) som solo-utvikler</p>
    <p class="cover-presenter">Martin Brandal &nbsp;·&nbsp; Epinova Academy 2026</p>
  </div>
</div>

<div class="cover-pattern">
  <svg viewBox="0 0 420 130" preserveAspectRatio="xMinYMax meet" fill="white" xmlns="http://www.w3.org/2000/svg">
    <!-- Epinova E-mark -->
    <rect x="0"   y="4"   width="53" height="53"/>
    <rect x="0"   y="57"  width="266" height="53"/>
    <rect x="53"  y="110" width="213" height="53"/>
    <rect x="0"   y="163" width="266" height="53"/>
    <rect x="0"   y="216" width="53" height="54" transform="scale(0.5) translate(0 -80)"/>
    <!-- Avtagende rutemønster -->
    <rect x="300" y="20"  width="18" height="18" opacity="0.45"/>
    <rect x="322" y="20"  width="32" height="18" opacity="0.35"/>
    <rect x="358" y="20"  width="18" height="18" opacity="0.28"/>
    <rect x="380" y="20"  width="38" height="18" opacity="0.2"/>
    <rect x="300" y="42"  width="54" height="18" opacity="0.35"/>
    <rect x="358" y="42"  width="60" height="18" opacity="0.25"/>
    <rect x="300" y="64"  width="22" height="18" opacity="0.28"/>
    <rect x="326" y="64"  width="42" height="18" opacity="0.22"/>
    <rect x="372" y="64"  width="46" height="18" opacity="0.15"/>
    <rect x="300" y="86"  width="70" height="18" opacity="0.18"/>
    <rect x="374" y="86"  width="44" height="18" opacity="0.12"/>
    <rect x="300" y="108" width="118" height="20" opacity="0.1"/>
  </svg>
</div>

<div class="cover-bar-right"></div>

<!-- START: Spill 3 sek av "All by Myself" fra mobilen – eller syng de fire første ordene. Isbryter garantert. -->

---
layout: two-cols
---

<div style="padding-top:2.4rem;">

# 👋 Hvem er jeg?

<div class="slide-body" style="padding-top:0.8rem;">
<div class="ep-card" v-click>
  <span class="ep-card-icon">💻</span>
  <div class="ep-card-body">Konsulent i <strong>Epinova</strong> — spesialist på e-handel og .NET</div>
</div>
<div class="ep-card" v-click>
  <span class="ep-card-icon">🌱</span>
  <div class="ep-card-body">Utvikler på <strong>Granngården</strong> — nordisk netthandel for hage og landbruk</div>
</div>
<div class="ep-card" v-click>
  <span class="ep-card-icon">🏃</span>
  <div class="ep-card-body">Hobbyer: Løping, og å debugge produksjon kl 07:00</div>
</div>
<div class="ep-quote" v-click style="margin-top:1.2rem;">
  Det fine med å jobbe alene?<br/>Ingen ser deg debugge i pysjamasen.
</div>
</div>
</div>

::right::

<div style="display:flex;flex-direction:column;align-items:center;justify-content:center;height:100%;gap:0.8rem;padding-top:2rem;">
  <!-- Bytt med: <img src="/images/martin.jpg" style="border-radius:50%;width:200px;border:4px solid #146E6E;" /> -->
  <div style="width:180px;height:180px;border-radius:50%;background:#D0E6E5;display:flex;align-items:center;justify-content:center;font-size:4.5rem;border:4px solid #146E6E;">🧑‍💻</div>
  <div style="font-size:1rem;font-weight:700;color:#146E6E;">Martin Brandal</div>
  <div style="margin-top:1rem;display:flex;flex-direction:column;align-items:center;gap:0.4rem;">
    <div style="font-size:2.2rem;">🦆</div>
    <div style="font-size:0.75rem;color:#999;font-style:italic;">Min kollega (mer om denne snart)</div>
  </div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

<!-- NOTER: Introduser gummianda tidlig – den er en rød tråd gjennom hele presentasjonen -->

---
layout: default
---

# 🌾 Setting the scene

<div class="slide-body">
<div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin-bottom:1rem;">
  <div style="background:#f0fafa;border-radius:8px;padding:1.2rem;border:1px solid #D0E6E5;">
    <div style="font-size:0.72rem;font-weight:800;color:#146E6E;text-transform:uppercase;letter-spacing:0.08em;margin-bottom:0.5rem;">Prosjektet</div>
    <div style="font-size:1rem;font-weight:700;color:#161616;margin-bottom:0.3rem;">Granngården</div>
    <div style="font-size:0.88rem;color:#444;">Nordisk e-handelsplattform for hage, dyr og landbruk</div>
  </div>
  <div style="background:#f0fafa;border-radius:8px;padding:1.2rem;border:1px solid #D0E6E5;">
    <div style="font-size:0.72rem;font-weight:800;color:#146E6E;text-transform:uppercase;letter-spacing:0.08em;margin-bottom:0.5rem;">Stack</div>
    <div style="font-size:0.88rem;color:#444;line-height:1.6;">Optimizely CMS + Commerce<br/>.NET 8 · Vue.js · Azure</div>
  </div>
</div>
<div class="ep-card">
  <span class="ep-card-icon">🔌</span>
  <div class="ep-card-body">Integrasjoner: <strong>nShift, Klarna, Svea, PinMeTo, Google Vertex AI</strong> — og mer til</div>
</div>
<div class="ep-card">
  <span class="ep-card-icon">🎲</span>
  <div class="ep-card-body">Kompleks prislogikk: kampanjer, X-for-Y tilbud, kundegrupper, sesongpriser</div>
</div>
<div class="ep-card" style="background:#e8f4f4;border-left-color:#146E6E;">
  <span class="ep-card-icon">👤</span>
  <div class="ep-card-body"><strong>Mitt ansvar: hele <code>ecommerce-web</code>-stacken</strong> &nbsp;·&nbsp; Teamstørrelse: <strong style="font-size:1.2em;">1</strong></div>
</div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

<!-- NOTER: Poenget er at dette IKKE er et lite hobbyprosjekt. Det er en seriøs plattform – det gjør solo-rollen enda mer dramatisk. -->

---
layout: two-cols
---

<div style="padding-top:2.4rem;">
# Det var ikke planen...

<div class="slide-body" style="padding-top:0.8rem;">
<div style="font-size:0.72rem;font-weight:800;color:#146E6E;text-transform:uppercase;letter-spacing:0.08em;margin-bottom:0.7rem;">Forventet</div>
<div class="ep-card"><span class="ep-card-icon">👨‍💻</span><div class="ep-card-body"><strong>5 utviklere</strong> — full kapasitet</div></div>
<div class="ep-card"><span class="ep-card-icon">🎨</span><div class="ep-card-body"><strong>2 designere</strong></div></div>
<div class="ep-card"><span class="ep-card-icon">🧠</span><div class="ep-card-body"><strong>1 tech lead</strong> + 1 prosjektleder</div></div>
<div class="ep-card"><span class="ep-card-icon">☕</span><div class="ep-card-body">Daily standup med 8 folk</div></div>
</div>
</div>

::right::

<div style="padding-top:2.4rem;">
<div style="font-size:0.72rem;font-weight:800;color:#c0392b;text-transform:uppercase;letter-spacing:0.08em;margin-bottom:0.7rem;padding:0 1.2rem 0 2.8rem;">Virkelighet</div>

<div style="padding:0 1.2rem 0 2.8rem;">
<div class="ep-card" style="background:#e8f4f4;border-left-color:#146E6E;"><span class="ep-card-icon">👨‍💻</span><div class="ep-card-body"><strong>Martin</strong></div></div>
<div v-click class="ep-card ep-card-muted"><span class="ep-card-icon">🦗</span><div class="ep-card-body" style="color:#999;font-style:italic;">...</div></div>
<div v-click class="ep-card ep-card-muted"><span class="ep-card-icon">🦗🦗</span><div class="ep-card-body" style="color:#999;font-style:italic;">...</div></div>
<div v-click class="ep-card ep-card-muted"><span class="ep-card-icon">🦗🦗🦗</span><div class="ep-card-body" style="color:#999;font-style:italic;">...</div></div>

<!-- Bytt med: <img src="/images/this-is-fine.jpg" style="width:90%;border-radius:8px;margin-top:0.8rem;"/> -->
<div v-click style="margin-top:1rem;background:#fff5e0;border-radius:8px;padding:1rem;text-align:center;border:1px solid #f0c060;">
  <div style="font-size:2.5rem;">🐕🔥</div>
  <div style="font-size:0.82rem;color:#888;font-style:italic;margin-top:0.3rem;">This is fine.</div>
</div>
</div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

---
layout: default
---

# 😎 De uventede fordelene

<div class="slide-body">
<div class="ep-grid-2">
<div>
<div class="ep-card" v-click><span class="ep-card-icon">🏗️</span><div class="ep-card-body"><strong>Full arkitekturkontroll</strong><br/><span style="color:#555;font-size:0.9rem;">Ingen «men vi pleide alltid å...»</span></div></div>
<div class="ep-card" v-click><span class="ep-card-icon">🚀</span><div class="ep-card-body"><strong>Deploy når du vil</strong><br/><span style="color:#555;font-size:0.9rem;">Fredag kl 16:59? Sure.</span></div></div>
<div class="ep-card" v-click><span class="ep-card-icon">🏆</span><div class="ep-card-body"><strong>All æren er din</strong><br/><span style="color:#555;font-size:0.9rem;">Når det går bra, er det din fortjeneste</span></div></div>
</div>
<div>
<div class="ep-card" v-click><span class="ep-card-icon">☮️</span><div class="ep-card-body"><strong>Ingen tabs vs spaces-krig</strong><br/><span style="color:#555;font-size:0.9rem;">Aldri. Noensinne.</span></div></div>
<div class="ep-card" v-click><span class="ep-card-icon">🌙</span><div class="ep-card-body"><strong>Commit-meldinger kl 23:00</strong><br/><code style="font-size:0.8rem;">wip fixes maybe idk</code></div></div>
<div v-click class="ep-quote" style="font-size:1rem;margin:0.5rem 0 0;">
  «Ja. Ubegrenset makt.»<br/><span style="font-size:0.8rem;font-weight:400;color:#888;">— Meg, etter å ha merget til main uten review</span>
</div>
</div>
</div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

---
layout: default
---

# 😅 De genuine utfordringene

<div class="slide-body">
<div class="ep-grid-2">
<div>
<div class="ep-card ep-card-danger" v-click><span class="ep-card-icon">🦆</span><div class="ep-card-body"><strong>Rubber duck debugging</strong><br/><span style="color:#555;font-size:0.9rem;">Men anden svarer ikke tilbake</span></div></div>
<div class="ep-card ep-card-danger" v-click><span class="ep-card-icon">🔍</span><div class="ep-card-body"><strong>Code review av deg selv</strong><br/><span style="color:#555;font-size:0.9rem;">«Denne koden er perfekt!» — (den er det ikke)</span></div></div>
<div class="ep-card ep-card-danger" v-click><span class="ep-card-icon">☠️</span><div class="ep-card-body"><strong>All risen er din</strong><br/><span style="color:#555;font-size:0.9rem;">Når det går dårlig, er det din feil</span></div></div>
</div>
<div>
<div class="ep-card ep-card-danger" v-click><span class="ep-card-icon">🤔</span><div class="ep-card-body"><strong>Ingen å sparre med</strong><br/><span style="color:#555;font-size:0.9rem;">Hvem vet hva de andre tenker?</span></div></div>
<div class="ep-card ep-card-danger" v-click><span class="ep-card-icon">📈</span><div class="ep-card-body"><strong>Teknisk gjeld akkumuleres</strong><br/><span style="color:#555;font-size:0.9rem;">Ingen til å si «kanskje vi ikke bør?»</span></div></div>
<div v-click style="background:#fff0f0;border:1px solid #fcc;border-radius:6px;padding:0.85rem 1rem;margin-top:0.2rem;font-size:0.88rem;">
  <span style="color:#c0392b;font-weight:700;">Hvem satte opp denne integrasjonen uten dokumentasjon?</span><br/>
  <span style="color:#666;font-style:italic;">Det var meg. For 8 måneder siden. Jeg husker ingenting.</span>
</div>
</div>
</div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

---
layout: cover
class: drama-bg
---

<div class="cover-inner" style="align-items:center;justify-content:center;text-align:center;gap:0.5rem;">
  <div style="font-size:4.5rem;line-height:1;">💥</div>
  <h1 style="font-size:3.8rem;color:#FFB3B3;border:none;margin:0.2rem 0;">Den Store Dagen</h1>
  <div style="font-size:1.4rem;color:rgba(255,255,255,0.8);margin-top:0.3rem;font-style:italic;">
    «Granngården gikk ned i 6 timer»
  </div>
  <div v-click style="margin-top:1.5rem;font-size:1.6rem;font-weight:900;color:#fff;">
    ...og det var meg.
  </div>
</div>

<!-- NOTER: La sliden sitte stille. Klikk for å avslsøre «org det var meg.» – la folk le. -->

---
layout: default
---

# Hva skjedde?

<div class="slide-body">
<div style="display:flex;flex-direction:column;gap:0.55rem;">

<div class="ep-card" v-click>
  <div style="background:#146E6E;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">1</div>
  <div class="ep-card-body">Deployerte en <strong>«liten» endring</strong> til produksjon en vanlig dag</div>
</div>

<div class="ep-card ep-card-danger" v-click>
  <div style="background:#c0392b;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">2</div>
  <div class="ep-card-body"><strong>Alt gikk ned</strong> — 404 på alle sider, ingenting fungerte</div>
</div>

<div class="ep-card ep-card-danger" v-click>
  <div style="background:#c0392b;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">3</div>
  <div class="ep-card-body">Telefonen ringte. Epinova. Kunden. Epinova igjen. <strong>Ingen visste hva som skjedde.</strong></div>
</div>

<div class="ep-card" v-click style="background:#fff5e0;border-left-color:#f39c12;">
  <div style="background:#f39c12;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">4</div>
  <div class="ep-card-body">Jo — <strong>én person visste</strong> 😅</div>
</div>

<div class="ep-card" v-click style="background:#e8f4f4;border-left-color:#146E6E;">
  <div style="background:#146E6E;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">5</div>
  <div class="ep-card-body"><strong>6 timer later:</strong> Fixed, deployert, og overraskende rolig etterpå</div>
</div>

</div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

<!-- NOTER: Fortell sakte. Pause mellom hvert trinn. "Ingen visste hva som skjedde." — pause. "Jo — én person visste." — pek på deg selv. -->

<div v-click style="margin-top:0.7em;">

3. Telefonen ringte. Epinova. Kunden. Epinova igjen.  
   Ingen visste hva som skjedde.

</div>

<div v-click style="margin-top:0.7em;">

4. Jo – **én person visste** 😅

</div>

<div v-click style="margin-top:0.7em;">

5. **6 timer later:** Fixed. Deployert. Stein rolig etterpå.

</div>

<div v-click style="margin-top:1.5em; text-align:center;">
  <!-- BILDE: "disaster girl" meme eller lignende kaos-bilde -->
  <!-- <img src="/images/disaster.jpg" style="width:45%; border-radius:8px;" /> -->
  <div style="font-size:2.5em;">🔥👧🔥</div>
  <p style="color:#888; font-size:0.8em;"><em>Disaster girl. Men mer overraskende.</em></p>
</div>

<!--
  NOTER:
  Tell historien sakte. Bruk pauser mellom hvert punkt.
  "Telefonen ringte. Epinova. Kunden. Epinova igjen." – pause.
  "Ingen visste hva som skjedde." – pause.
  "Jo – én person visste." – peke på deg selv.
  La folk le.
-->

---
layout: default
---

# 💡 Det som skjedde etter

<div class="slide-body">
<div class="ep-quote" style="font-size:1.3rem;margin:0 0 1rem;">
  «After that, what are they gonna do? Fire me twice?»
</div>
<div v-click style="font-size:1rem;color:#333;margin-bottom:1rem;font-weight:600;">
  Etter et tilstrekkelig katastrofalt feil — mister frykten sin makt.
</div>
<div class="ep-grid-2" v-click>
  <div class="ep-card"><span class="ep-card-icon">🔬</span><div class="ep-card-body"><strong>Lærte feilsøking</strong> på dypeste nivå — vet nå nøyaktig hva som kan gå galt</div></div>
  <div class="ep-card"><span class="ep-card-icon">🚨</span><div class="ep-card-body"><strong>Monitoring</strong> ble min aller beste venn — vet om feil før kunden gjør det</div></div>
  <div class="ep-card"><span class="ep-card-icon">↩️</span><div class="ep-card-body"><strong>Rollback-strategi</strong> — ikke lenger valgfritt, men standard prosedyre</div></div>
  <div class="ep-card" style="background:#e8f4f4;border-left-color:#146E6E;"><span class="ep-card-icon">💪</span><div class="ep-card-body"><strong>Feil er ikke slutten</strong> — det er begynnelsen på ekte forståelse</div></div>
</div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

<!-- NOTER: Vendepunktet. Skift tone — fra komisk til ekte og faglig. Ta deg tid her. -->

---
layout: default
---

# 🧰 Verktøy som reddet meg

<div class="slide-body">
<table>
  <thead><tr><th>Verktøy</th><th>Hvorfor det hjalp</th></tr></thead>
  <tbody>
    <tr v-click><td><strong>📝 Gode commit-meldinger</strong></td><td>Dagbok til fremtidig-meg — fremtidig-deg er ikke deg</td></tr>
    <tr v-click><td><strong>🤖 GitHub Copilot</strong></td><td>Den eneste som «code reviewer» meg (nesten)</td></tr>
    <tr v-click><td><strong>🚨 Application Insights</strong></td><td>Vet om feil i produksjon før kunden ringer</td></tr>
    <tr v-click><td><strong>📄 Dokumentasjon</strong></td><td>«Hvem satte opp dette?» — Heldigvis meg, og jeg skrev det ned</td></tr>
    <tr v-click><td><strong>👥 Kollegaer i andre prosjekter</strong></td><td>Mental helse 💚 — ikke vær en øy</td></tr>
  </tbody>
</table>

<div class="ep-quote" v-click style="margin-top:1rem;font-size:0.95rem;">
  <code>«fikset race condition i cart – se PR #442 for context»</code><br/>
  <span style="font-size:0.85rem;font-weight:400;color:#888;">vs. bare</span> <code style="font-size:0.85rem;">«fix»</code>
</div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

---
layout: two-cols
---

<div style="padding-top:2.4rem;">
# 🧠 Hold deg sane

<div class="slide-body" style="padding-top:0.6rem;">
<div style="font-size:0.72rem;font-weight:800;color:#146E6E;text-transform:uppercase;letter-spacing:0.08em;margin-bottom:0.5rem;">✅ Ting som hjelper</div>
<div class="ep-card" v-click><span class="ep-card-icon">💬</span><div class="ep-card-body"><strong>Snakk med kollegaer</strong> i andre prosjekter — ikke bare jobb-prat</div></div>
<div class="ep-card" v-click><span class="ep-card-icon">🚫</span><div class="ep-card-body"><strong>Si nei til scope creep</strong> — ingen andre gjør det for deg</div></div>
<div class="ep-card" v-click><span class="ep-card-icon">🎉</span><div class="ep-card-body"><strong>Feir småseirene</strong> — deploy uten nedetid teller</div></div>
<div class="ep-card" v-click><span class="ep-card-icon">📓</span><div class="ep-card-body"><strong>Dokumenter nesten-ulykker</strong>, ikke bare suksesser</div></div>
</div>
</div>

::right::

<div style="padding-top:2.4rem;">
<div style="font-size:0.72rem;font-weight:800;color:#c0392b;text-transform:uppercase;letter-spacing:0.08em;margin-bottom:0.5rem;padding:0 0 0 1.2rem;">❌ Ting som ikke hjelper</div>
<div style="padding:0 2.8rem 0 1.2rem;">
<div class="ep-card ep-card-danger" v-click><span class="ep-card-icon">😵</span><div class="ep-card-body"><strong>Jobbe 14 timer</strong> fordi «det er bare meg som kan»</div></div>
<div class="ep-card ep-card-danger" v-click><span class="ep-card-icon">🙋</span><div class="ep-card-body"><strong>Si ja til alt</strong> fordi du ikke vil skuffe noen</div></div>
<div class="ep-card ep-card-danger" v-click><span class="ep-card-icon">🤫</span><div class="ep-card-body"><strong>Skjule at noe er vanskelig</strong> — be om hjelp</div></div>
<!-- Bytt med: <img src="/images/boat-cat.jpg" style="width:90%;border-radius:8px;margin-top:0.8rem;"/> -->
<div v-click style="margin-top:0.8rem;background:#fff5e0;border-radius:8px;padding:0.8rem;text-align:center;border:1px solid #f0c060;">
  <div style="font-size:2rem;">🐱⛵</div>
  <div style="font-size:0.78rem;color:#888;font-style:italic;">«I should buy a boat» — meg, mellom to sprinter</div>
</div>
</div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

---
layout: default
---

# 📌 5 ting jeg lærte

<div class="slide-body">
<div style="display:flex;flex-direction:column;gap:0.55rem;">

<div class="ep-card" v-click>
  <div style="background:#146E6E;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">1</div>
  <div class="ep-card-body"><strong>Feil er bra</strong> — du lærer mer av én 6-timers nedetid enn 6 måneder uten feil</div>
</div>
<div class="ep-card" v-click>
  <div style="background:#146E6E;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">2</div>
  <div class="ep-card-body"><strong>Skriv det ned</strong> — fremtidig-deg er ikke deg, han husker ingenting</div>
</div>
<div class="ep-card" v-click>
  <div style="background:#146E6E;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">3</div>
  <div class="ep-card-body"><strong>Be om hjelp</strong> — å jobbe alene betyr ikke å være isolert</div>
</div>
<div class="ep-card" v-click>
  <div style="background:#146E6E;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">4</div>
  <div class="ep-card-body"><strong>Monitoring first</strong> — du bør vite om feilen før kunden gjør det</div>
</div>
<div class="ep-card" v-click style="background:#e8f4f4;border-left-color:#146E6E;border-left-width:5px;">
  <div style="background:#146E6E;color:white;border-radius:50%;width:2rem;height:2rem;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:0.9rem;flex-shrink:0;">5</div>
  <div class="ep-card-body" style="font-size:1.02rem;"><strong>Det er OK å eie det</strong> — all risen, all æren. Det er ditt. Og det er faktisk ganske kult.</div>
</div>

</div>
</div>

<div class="ep-footer">
  <span class="ep-logo-text">Epinova</span>
  <span>All by Myself · Academy 2026</span>
</div>

<!--
  NOTER:
  Siste punkt er det viktigste. Avslutt med det positivt.
  "Faktisk ganske kult" – si det med overbevisning.
-->

---
layout: cover
class: outro-bg
---

<div class="cover-inner">
  <div class="cover-logo">Epinova</div>
  <div class="cover-title-area">
    <h1 style="color:#D0E6E5;">All by Myself...</h1>
    <p class="cover-subtitle" style="color:rgba(255,255,255,0.9);font-size:1.5rem;font-style:normal;font-weight:700;">...ikke helt 🦆</p>
    <p class="cover-presenter">Martin Brandal &nbsp;·&nbsp; martin.brandal@epinova.no</p>
    <p style="color:rgba(255,255,255,0.45);font-size:0.85rem;margin-top:0.5rem;font-style:italic;">🎵 Don't wanna be... all by myself... anymore</p>
  </div>
</div>

<div class="cover-pattern">
  <svg viewBox="0 0 420 130" preserveAspectRatio="xMinYMax meet" fill="white" xmlns="http://www.w3.org/2000/svg" opacity="0.35">
    <rect x="0"   y="4"   width="53" height="53"/>
    <rect x="0"   y="57"  width="266" height="53"/>
    <rect x="53"  y="110" width="213" height="53"/>
    <rect x="300" y="20"  width="18" height="18" opacity="0.7"/>
    <rect x="322" y="20"  width="32" height="18" opacity="0.5"/>
    <rect x="300" y="42"  width="54" height="18" opacity="0.5"/>
    <rect x="300" y="64"  width="80" height="18" opacity="0.35"/>
    <rect x="300" y="86"  width="60" height="18" opacity="0.25"/>
    <rect x="300" y="108" width="100" height="20" opacity="0.18"/>
  </svg>
</div>

<div class="cover-bar-right" style="background:rgba(255,255,255,0.12);"></div>

<!-- OUTRO: Gummianda-referansen knytter tilbake til slide 2. Spill sangen mens folk forlater rommet. -->
