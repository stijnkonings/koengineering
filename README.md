# KOEngineering dienstenpagina’s

Statische pagina’s voor onderhoud en herstellingen van 3D-printers en voor 3D-ontwerp en printwerk op maat. De bestanden voor publicatie staan onder `public/diensten/`.

## Lokaal controleren

```sh
python3 -m http.server 8080 --directory public
```

Open http://localhost:8080/diensten/onderhoud-en-herstellingen/ of http://localhost:8080/diensten/3d-ontwerp-en-printen/.

## Cloudflare

Voor een afzonderlijke Cloudflare Pages-test gebruik je geen buildcommando en kies je `public` als uitvoermap. Voeg voor productie de map `diensten` toe aan de volledige publicatiemap van de bestaande website. Deze repository bevat alleen de nieuwe dienstenpagina’s. Een productie-deploy met uitsluitend deze bestanden zou de huidige homepage verwijderen. Maak daarom eerst een preview van de volledige publicatiemap en test daarin ook de homepage. Voeg bij publicatie een link naar beide diensten toe aan de navigatie van de hoofdsite.

De pagina’s tonen de publieke bedrijfsgegevens uit de KBO. Voeg een bevestigd zakelijk e-mailadres of een aangesloten formulier toe als online aanvragen rechtstreeks vanaf de pagina’s moeten kunnen worden ingestuurd.
