---
layout: section
subtitle: ISO 27001 — Opatření 8.9
---

# Správa konfigurací

---
layout: default
---

# 8.9 Správa konfigurací

Cíl: zajistit, aby konfigurace systémů, aplikací a zařízení byly:

<div class="icon-grid">
  <div class="icon-card">
    <div class="icon">🎛️</div>
    <div class="label"><strong>Řízené</strong><br/>Kontrolované a schválené procesy</div>
  </div>
  <div class="icon-card">
    <div class="icon">🔄</div>
    <div class="label"><strong>Konzistentní</strong><br/>Stejné standardy v celé organizaci</div>
  </div>
  <div class="icon-card">
    <div class="icon">🛡️</div>
    <div class="label"><strong>Bezpečné</strong><br/>V souladu s doporučeními pro hardening a osvědčenými postupy</div>
  </div>
</div>

<div class="callout warning">
Chybná konfigurace patří k nejčastějším příčinám bezpečnostních incidentů.
</div>

---
layout: default
---

# 8.9 Klíčové principy

- **Existují schválené základní konfigurace** pro všechny klíčové typy aktiv
- Změny konfigurací jsou:
  - Řízené (8.32 — Change Management)
  - Zdokumentované
- Konfigurace odpovídají:
  - Bezpečnostním požadavkům
  - Doporučením pro hardening
  - Osvědčeným postupům
  - Aktuálnímu rizikovému prostředí

---
layout: default
---

# 8.9 Vztahuje se na

| Kategorie aktiv | Příklady |
|----------------|---------|
| **Infrastruktura** | Servery, síťová zařízení, cloudové služby |
| **Operační systémy** | Windows, Linux, macOS |
| **Aplikace a middleware** | Webové servery, databáze, API |
| **Bezpečnostní komponenty** | Firewally, IAM systémy, platformy pro logování |

---
layout: default
---

# 8.9 Cílový stav

Konfigurace **nejsou**:
- Uložené pouze „v hlavě administrátora"
- Výsledkem improvizace

Organizace **umí**:
- Na vyžádání prokázat jakoukoli konfiguraci
- Vysvětlit každou provedenou změnu
- Rychle opravit chyby

---
layout: default
---

# 8.9 Metriky

| Metrika | Co odhaluje |
|---------|------------|
| Změny za období | Objem a rychlost konfiguračního posunu |
| Vrácení změn | Jak často bylo nutné změny vrátit |
| Poměr rutinních vs. ad-hoc změn | Zralost procesů (týdenní/měsíční vs. hasičské akce) |
| Incidenty způsobené chybnou konfigurací | Dopad kvality konfigurací na bezpečnost |

---
layout: default
---

# 8.9 Typické problémy

<div class="callout warning">
„Někdo něco změnil a nikam to nezapsal" — nejčastější příběh v popisu průběhu incidentu
</div>

- Ignorování osvědčených postupů a doporučení pro hardening
- Chybějící nebo špatný základní obraz pro nasazení
- **Nekonzistence v organizaci** — stejný typ zařízení, různá nastavení
  - WPA2 vs. WPA3
  - Windows 7 vs. 10 vs. 11
- **Shadow IT** — nespravovaná zařízení, nesledované konfigurace
