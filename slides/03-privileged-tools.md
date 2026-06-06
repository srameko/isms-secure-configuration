---
layout: section
subtitle: ISO 27001 — Opatření 8.18
---

# Privilegovaná administrátorská nástroje

---
layout: default
---

# 8.18 Používání privilegovaných administrátorských nástrojů

Cíl: omezit rizika spojená s nástroji vyžadujícími zvýšená oprávnění.

Předcházet:
- **Obcházení bezpečnostních opatření**
- **Neúmyslným chybám** způsobeným výkonnými nástroji
- **Zneužití** administrátorských utilit

<div class="callout warning">
<strong>Living off the Land</strong> — legitimní aplikace, které může útočník zneužít pro své účely.
</div>

---
layout: default
---

# 8.18 Co jsou privilegované nástroje?

<div class="icon-grid">
  <div class="icon-card">
    <div class="icon">🗄️</div>
    <div class="label">Nástroje pro správu databází a systémů/služeb</div>
  </div>
  <div class="icon-card">
    <div class="icon">⚙️</div>
    <div class="label">Utility pro změnu konfigurace</div>
  </div>
  <div class="icon-card">
    <div class="icon">💾</div>
    <div class="label">Nástroje pro zálohy a obnovu dat</div>
  </div>
  <div class="icon-card">
    <div class="icon">📜</div>
    <div class="label">Skripty spouštěné se zvýšenými oprávněními</div>
  </div>
  <div class="icon-card">
    <div class="icon">🔬</div>
    <div class="label">Diagnostické a servisní nástroje</div>
  </div>
</div>

---
layout: default
---

# 8.18 Klíčové požadavky

- Používány **pouze oprávněnými osobami**
- Pro **schválený účel**, po **minimálně nutnou dobu**
- Použití je:
  - Řízeno
  - Monitorováno
  - **Logováno**
- Přímo navazuje na opatření **PAM/PIM**

---
layout: default
---

# 8.18 Cílový stav

Privilegované nástroje **nejsou**:
- Volně přístupné komukoli
- Spustitelné „jen tak"

Organizace:
- Ví, **kde** jsou používány
- Ví, **kdo** je používá
- Umí jejich použití **prokázat** na vyžádání

---
layout: default
---

# 8.18 Metriky

| Metrika | Účel |
|---------|-----|
| Frekvence použití | Baseline — jsou nástroje používány, jak se očekává? |
| Použití mimo administrátory | Jak často je používá někdo jiný než admin? |
| Incidenty spojené se zneužitím | Kolik incidentů zahrnovalo zneužití privilegovaného nástroje? |

---
layout: default
---

# 8.18 Typické problémy

<div class="callout warning">
Pokud nikdo nehlídá, všichni předpokládají, že je vše v pořádku.
</div>

- Použití privilegovaných nástrojů **vůbec není monitorováno**
- Použití privilegovaných nástrojů je **ve výchozím stavu povoleno pro všechny**

---
layout: center
---

# ☕ Přestávka — 15 minut
