# 3 Amigos Check-in

## 🧭 Formål

Vi bruger **3 Amigos Check-in** til at

- sikre fremdrift
- øge kvaliteten
- undgå spildt arbejde ved at fange ting tidligst muligt

### 🎯 Outcome

> Afklare om et item er klar til næste step — og hvis ikke, hvad der mangler.

Det er ikke tænkt som en tung godkendelsesproces.
Det er en struktureret samtale mellem UX, UI og Dev.

---

## ⭐ Rules of engagement

- Max 45 minutter

- Vi udvælger X PBI'er

- Processen kan bruges på to måder:
  - Når en Amigo mener, at et PBI er klar til næste fase
  - Når en Amigo har brug for sparring eller validering
- Det er ikke et krav, at et PBI skal være “færdigt”, før det tages op

- For hvert PBI spørger vi:
  - Hvilken fase er vi i?
  - Stil de relevante spørgsmål
  - Er det godt nok til at gå videre?
  - Hvis nej: hvad mangler helt konkret?

- Output er altid en af:
  - ✅ Klar til næste fase
  - ❌ Ikke klar endnu — med konkret næste skridt og ansvarlig
- HUSK: et PBI kan af historiske årsager være i en fase UDEN af tidligere faser er gennemgået.
  - Vær konstruktiv
  - Vær åben for feedback
  - Hold en god tone
- Følg nedenstående skabeloner til at strukturere samtalen omkring hvert PBI

---

# 🔄 Fase 1: UX

## 🧭 Formål

Sikre at problemet og brugerflowet er klart

## ❓ Spørgsmål

**UX**

- Giver flowet mening fra et brugerperspektiv?
- Er vigtigste use cases dækket?

**UI**

- Er der noget her, der bliver svært visuelt eller inkonsistent?
- Mangler der states (error, loading, empty, open, closed)?

**Dev**

- Forstår jeg flowet uden at gætte?
- Er der noget teknisk uklart eller risikabelt?

## ✅ Klar til næste fase når:

- Flowet er forstået af alle
- Ingen store åbne spørgsmål
- Dev kan se, hvordan det skal bygges

## 📦 Deliverables

- Wireframe
- Evt klikbar prototype
- PBI til UI

---

# 🔄 Fase 2 - Design Iteration 1

## 🧭 Formål

Fastlægge første visuelle retning (ikke perfekt)

## ❓ Spørgsmål

**UX**

- Understøtter designet flowet korrekt?
- Er noget blevet forvirrende ift. UX?

**Dev**

- Er det realistisk at bygge?
- Mangler der komponenter eller struktur?

**UI**

- Er retningen konsistent med design system?

## ✅ Klar til næste fase når:

- UX ikke ser brud i flowet
- Dev ikke ser blockers
- Design er godt nok til at arbejde videre på

## 📦 Deliverables

- Mockup / low-fi design
- PBI til UI

---

# 🔄 Fase 3 - Design Iteration 2

## 🧭 Formål

Gøre design klar til udvikling

## ❓ Spørgsmål

**UX**

- Er alle flows og edge cases dækket?
- Er interaktioner tydelige?

**Dev**

- Mangler jeg noget for at implementere?
- Er alle states dækket (hover, loading, errors, required fields)?

**Fælles**

- Er der noget vi stadig er i tvivl om?

## ✅ Klar til næste fase når:

- Ingen åbne spørgsmål
- Dev kan bygge uden gætværk
- UX vurderer oplevelsen som korrekt

## 📦 Deliverables

- High Fidelity design
- PBI til Dev

---

# 🔄 Fase 4 - Development

## 🧭 Formål

Sikre at implementeringen matcher intentionen

## ❓ Spørgsmål

**UX**

- Matcher det flow og adfærd?
- Føles det rigtigt i brug?

**UI**

- Matcher det designet visuelt?
- Er der visuelle afvigelser?

**Dev (selv-check)**

- Er edge cases håndteret?
- Er der kompromiser vi skal være enige om?

## ✅ Klar når:

- UX siger: det virker
- UI siger: det matcher designet
- Ingen kritiske afvigelser

## 📦 Deliverables

- Afhænger af produkt
- Code Review oprettet i Test kanalen

---
