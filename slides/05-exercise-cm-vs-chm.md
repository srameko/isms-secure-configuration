---
layout: center
---

# 🛠️ Úkol na 15 min

<div class="callout">
Pro každou níže uvedenou aktivitu rozhodněte: jde o <strong>Change Management</strong>, nebo <strong>Configuration Management</strong>? Proč?
</div>

<div class="exercise-table">

| Aktivita | CM nebo CHM? |
|----------|-------------|
| Nastavení standardní konfigurace nového serveru | ? |
| Ruční změna pravidla firewallu v produkci | ? |
| Úprava TLS nastavení na webovém serveru | ? |
| Instalace nového monitorovacího agenta | ? |
| Dočasné otevření portu „jen pro testování" | ? |
| Obnovení konfigurace ze zálohy po incidentu | ? |

</div>

<style>
.exercise-table table {
  font-size: 0.78em;
}
</style>

---
layout: center
---

# 🛠️ Úkol na 15 min — řešení

<div class="callout">
<span class="tag-chm">Configuration Management</span> = definice nebo obnova schválené základní konfigurace.
<span class="tag-cm">Change Management</span> = jakákoli řízená změna nastavení běžícího produkčního systému.
</div>

<div class="exercise-table">

| Aktivita | Řešení |
|----------|-------------|
| Nastavení standardní konfigurace nového serveru | <span class="tag-chm">Configuration</span> |
| Ruční změna pravidla firewallu v produkci | <span class="tag-cm">Change</span> |
| Úprava TLS nastavení na webovém serveru | <span class="tag-cm">Change</span> |
| Instalace nového monitorovacího agenta | <span class="tag-cm">Change</span> |
| Dočasné otevření portu „jen pro testování" | <span class="tag-cm">Change</span> |
| Obnovení konfigurace ze zálohy po incidentu | <span class="tag-chm">Configuration</span> |

</div>

<style>
.exercise-table table {
  font-size: 0.78em;
}
.tag-cm, .tag-chm {
  display: inline-block;
  padding: 0.15em 0.6em;
  border-radius: 999px;
  font-weight: 700;
  color: #ffffff;
  white-space: nowrap;
}
.tag-cm {
  background: var(--czechitas-blue);
}
.tag-chm {
  background: var(--czechitas-pink);
}
</style>
