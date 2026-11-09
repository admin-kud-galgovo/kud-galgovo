# KUD Galgovo – web stranica

Web stranica Kulturno umjetničkog društva Galgovo.

## Sadržaj

| Datoteka / mapa | Što je |
|---|---|
| `index.html` | Cijela web stranica (Početna, O nama, O folkloru, Vijesti, Galerija, Događanja, Upisi, Pravila privatnosti) |
| `upis.html` | Online obrazac za upis (članski karton i izjava o osobnim podacima, preuzimanje PDF-a) |
| `assets/img/` | Grb, fotografije i ukrasi |
| `assets/dokumenti/` | Statut, Izjava o zaštiti podataka, financijski izvještaj |
| `.nojekyll` | Kaže GitHub Pagesu da datoteke objavi točno kakve jesu |

## Objava na GitHub Pages

1. Na GitHubu napravite novi javni repozitorij, npr. `kud-galgovo`.
2. Na stranici repozitorija kliknite **Add file → Upload files** i povucite **sav sadržaj ove mape** (ne samu mapu): `index.html`, `upis.html`, `README.md`, `.nojekyll` i mapu `assets`. Kliknite **Commit changes**.
3. Otvorite **Settings → Pages**. Pod *Build and deployment* odaberite **Source: Deploy from a branch**, zatim **Branch: main** i mapu **/ (root)** te kliknite **Save**.
4. Nakon minute-dvije stranica će biti dostupna na adresi `https://KORISNICKO-IME.github.io/kud-galgovo/`.

Ako želite vlastitu domenu (npr. `kud-galgovo.hr`), upišite je u **Settings → Pages → Custom domain** i kod registra domene postavite DNS zapise prema uputama GitHuba.

## Izmjene

Tekstove i fotografije mijenjajte u `index.html`, a nove fotografije i dokumente stavljajte u mape `assets/img/` i `assets/dokumenti/`. Nakon svake izmjene napravite novi *commit*; GitHub Pages stranicu osvježi automatski.
