---
layout: section
subtitle: ISO 27001 — Opatření 8.24
---

# Kryptografie

---
layout: default
---

# 8.24 Kryptografie

Kryptografie musí být používána **správně a cíleně** k ochraně:

<div class="icon-grid">
  <div class="icon-card">
    <div class="icon">🔒</div>
    <div class="label"><strong>Důvěrnosti</strong><br/>Data čitelná pouze oprávněnými stranami</div>
  </div>
  <div class="icon-card">
    <div class="icon">✔️</div>
    <div class="label"><strong>Integrity</strong><br/>Data nebyla pozměněna</div>
  </div>
  <div class="icon-card">
    <div class="icon">🪪</div>
    <div class="label"><strong>Autentičnosti</strong><br/>Původ dat lze ověřit</div>
  </div>
</div>

<div class="callout warning">
<strong>Špatná kryptografie je často horší než žádná kryptografie.</strong>
Vytváří falešný pocit bezpečí, aniž by poskytovala skutečnou ochranu.
</div>

---
layout: default
---

# 8.24 Klíčové principy

Definovaná politika zahrnující:
- **Kdy** se kryptografie používá
- **Za jakým účelem** — data v klidu vs. data při přenosu

Používané schválené algoritmy a délky klíčů:
- Odpovídají osvědčeným postupům (doporučení NÚKIB / NIST)
- Jsou v souladu s možnostmi cílového zařízení

Klíče jsou:
- Bezpečně **generovány, chráněny a spravovány** po celou dobu jejich životního cyklu

**Typické příklady:** TLS · šifrování disků · šifrování záloh · digitální podpisy

---
layout: default
---

# 8.24 Cílový stav

Kryptografie je v organizaci **řízená a konzistentní**.

Organizace:
- Ví, **kde** se kryptografie používá
- Má ji **zdokumentovanou**
- Umí svá rozhodnutí **odůvodnit** z pohledu rizik

---
layout: default
---

# 8.24 Metriky

| Metrika | Popis |
|---------|-------|
| Poměr šifrovaného vs. nešifrovaného provozu | Jak velká část dat cestuje nechráněna |
| Podpora šifer na zařízeních | Kolik zařízení podporuje / nepodporuje požadované sady šifer |

---
layout: default
---

# 8.24 Typické problémy

<div class="callout warning">
MD5, DES, RSA 1024 — algoritmy, které jsou v roce 2025 stále v produkčním nasazení.
</div>

**Zastaralé / nebezpečné algoritmy stále v použití:**
- MD4 / MD5, DES, RSA 1024

**Chybějící šifrování:**
- Disky na přenosných zařízeních (notebooky, telefony, tablety)
- Webový provoz (HTTP místo HTTPS)
- Citlivé soubory odeslané **nešifrovaným e-mailem**

---
layout: center
---

# ☕ Přestávka
