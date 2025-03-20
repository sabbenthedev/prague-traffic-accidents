# prague-traffic-accidents
Tento projekt klade za cíl předpovědět dopravní nehody v Praze na základě historických dat z https://nehody.policie.gov.cz/

- Cílem je vyvinout model strojového učení, který dokáže předpovídat pravděpodobnost nehody na základě různých faktorů, jako je například místo, čas, způsob nehody, apod.
- Najde hotspoty s vysokým rizikem nehod, následně označí oblasti za rizikové pro řidiče vyžadující opatrnosti.
- Ukáže statistiky z dat od roku 2024 ledna do 2024 prosince.

### nástroje (viz. pyproject.toml):
- programovací jazyk: Python 3.13
- knihovny: Pandas[statistiky], Folium[mapa], PyTorch[machine learning]

### data

- [Nehody od 1/2024 do 12/2024 - policie.gov] (https://nehody.policie.gov.cz/#11/14.46561/50.05981/1e4GemqeRb225c2) .geojson
  

# git guide

- git clone https://github.com/sabbenthedev/prague-traffic-accidents (zkopírovat do PC)
- cd prague-traffic-accidents (uvnitř vscode)
- git checkout -b feature-branch (místo feature-branch, význam například fix-bug, add-login)
- v klidu modifikuj soubory atd. až hotovo tak
- git add .
- git commit -m "?zpráva?"
- git push origin feature-branch
- jdi na repository tady github
- klikni pull requests => new pull request
- zvol main jako base a feature-branch jako compare branch
- přidej popisek a vytvoř pull request
### druhá osoba
- otevři pull request, klikni, můžeš přídat komentář, pokud vše ok
- klikni merge pull request
- vyber merge commit (nechá historii) nebo squash and merge (kombinuje commits v jednom)
- potvrď merge
- (optimální možnost) smazat branch after merging jako úklid
- pro update, použij git checkout main
- git pull origin main
