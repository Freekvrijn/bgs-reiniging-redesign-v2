# BGS-Reiniging — redesign (voorbeeld, versie 2)

Tweede herontwerp-voorstel voor [bgs-reiniging.nl](https://bgs-reiniging.nl) — een **warmere,
ambachtelijke** variant naast versie 1 (`bgs-reiniging-redesign`). Zelfde content en
structuur; alleen de visuele stijl verschilt, zodat de klant kan kiezen.

## Bekijken
Open `index.html` in je browser, of:
```bash
cd bgs-reiniging-redesign-v2 && python3 -m http.server 8001
# open http://localhost:8001
```

## Wat verschilt t.o.v. versie 1
| Onderdeel | Versie 1 | Versie 2 (deze) |
|---|---|---|
| Koppen | Modern sans (Hanken Grotesk) | **Serif (Fraunces)** |
| Tekst | Hanken Grotesk | **Mulish** |
| Achtergrond | Helderwit | **Warm papierwit** |
| Accent/knoppen | Emerald-groen | **Terracotta** (warm tweede accent) |
| Kaarten | Zwevend, zachte schaduw | **Plat met hairline-rand** |
| Sfeer | Fris, clean, zakelijk | **Warm, ambachtelijk, persoonlijk** |

Merkgroen blijft de basis; de uitstraling is rustiger en warmer.

## Pagina's & inhoud
Identiek aan versie 1 (home, diensten, resultaten, over, beoordelingen, contact). Alle
teksten, foto's, logo en beoordelingen komen **1:1 van de huidige site**.

## Vervolg (na akkoord)
Zie versie 1: werkend offerteformulier, SEO/analytics, beeldoptimalisatie, cookiebanner.

## Techniek
Pure HTML/CSS/JS, geen build-stap. Extern: Google Fonts (Fraunces + Mulish) en een
OpenStreetMap-embed.
