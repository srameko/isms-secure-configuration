---
layout: section
subtitle: ISO 27001 — Opatření 8.19
---

# Instalace softwaru na operační systémy

---
layout: default
---

# 8.19 Instalace softwaru

Cíl: zajistit, aby instalace softwaru na produkční systémy byla:

<div class="icon-grid">
  <div class="icon-card">
    <div class="icon">🎛️</div>
    <div class="label"><strong>Řízená</strong><br/>Kontrolovaný proces, nikoli ad-hoc</div>
  </div>
  <div class="icon-card">
    <div class="icon">✅</div>
    <div class="label"><strong>Schválená</strong><br/>Povolená správnými osobami</div>
  </div>
  <div class="icon-card">
    <div class="icon">🛡️</div>
    <div class="label"><strong>Bezpečná</strong><br/>Ověřené zdroje, žádné riziko PUA/malwaru</div>
  </div>
</div>

Předcházet: neoprávněným instalacím · zavedení škodlivého kódu (PUA) · provozní nestabilitě

---
layout: default
---

# 8.19 Požadavky

- Instalaci smí provádět pouze **oprávněné osoby** podle **schváleného procesu**
- Pouze **schválený software** z **ověřených zdrojů**
- Produkční prostředí:
  - **Není** testovací plocha
  - Všechny změny procházejí přes **Change Management (8.32)**

---
layout: default
---

# 8.19 Cílový stav

V organizaci **neexistuje**:
- Shadow IT
- Uživatelé stahující a instalující cokoliv chtějí

Organizace:
- Ví, co běží na jejích systémech (licenční politika)
- Umí vysvětlit každou instalaci
- Umí **rychle reagovat** při zjištění problému

---
layout: default
---

# 8.19 Metriky

| Metrika | Co prozrazuje |
|---------|--------------|
| Licencovaný vs. nelicencovaný software | Výše rizika shody a objem shadow IT |
| Aplikace nespravované IT | Slepá místa v softwarové základně |

---
layout: default
---

# 8.19 Typické problémy

<div class="callout warning">
Každý instaluje cokoliv odkudkoliv — klasický nespravovaný endpoint.
</div>

- IT nespravuje aplikace ani jejich aktualizace
  - Zejména prohlížeče a jejich rozšíření
- **Obcházení politiky přes app story** (App Store / Microsoft Store)
  - Schválená politika, ale store není zablokován
