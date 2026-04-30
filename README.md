# KOV TAP Turvalisuse Profiili Dashboard

Eesti kohalike omavalitsuste (KOV) turvalisuse profiili interaktiivne dashboard.

## Kasutamine

Ava `index.html` brauseris või kasuta GitHub Pages linki.

## Andmeallikad

- **MinuOmavalitsus** (Rahandusministeerium) — KOV teenustasemed, rahuloluuuringud
- **Tervise Arengu Instituut (TAI)** — politseis registreeritud süüteod, liiklusõnnetused, tulekahjud, uppumissurmad
- **Statistikaamet (STAT)** — alaealiste süüteod, hariduse katkestajad, registreeritud töötud
- **Politsei- ja Piirivalveamet (PPA)** — abivajaduse teated KOVile

## Aastad

Andmed katavad aastaid 2016–2025 (sõltuvalt indikaatorist).

## Tehnoloogia

Üks staatiline HTML-fail, kõik andmed embedded. Ei vaja serverit, andmebaasi ega API-päringuid.
Kasutab Chart.js teeki graafikute kuvamiseks.
