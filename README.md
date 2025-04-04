# prague-traffic-accidents
Tento projekt klade za cíl udělat statistiky, heatmap a lokaci nehody, předpovědět (is data weak?) dopravní nehody v Praze na základě historických dat z https://nehody.policie.gov.cz/

- Ukáže statistiky z dat od roku 2024 ledna do 2024 prosince.
- Najde hotspoty s vysokým rizikem nehod, následně označí oblasti za rizikové pro řidiče vyžadující opatrnosti.
- Vyvinout malý model strojového učení, který dokáže předpovídat pravděpodobnost nehody na základě různých faktorů, jako je například místo, čas, způsob nehody, atd.

### nástroje (viz. pyproject.toml):
- programovací jazyk: Python 3.13
- knihovny: Geo/Pandas[statistiky], Folium[mapa], SciKit[machine learning]???

### data

- [Nehody od 1/2024 do 12/2024 - policie.gov] (https://nehody.policie.gov.cz/#11/14.46561/50.05981/1e4GemqeRb225c2) .geojson
