# KOEngineering websitepreview

De statische website in `public/` bevat de homepage, onderhoud en herstellingen, en 3D-ontwerp en printen op maat. Het webshopmenu verwijst naar https://shop.koengineering.be/.

## Lokaal controleren

```sh
python3 -m http.server 8080 --directory public
```

Open http://localhost:8080/ en volg de links naar de twee dienstenpagina’s.

## Cloudflare

De branch `preview-diensten` gebruikt `public/` als statische uitvoermap. Gebruik hem voor een previewbuild van de Worker. Controleer vóór een productie-uitrol welke bestanden of routes van de bestaande website mee moeten verhuizen.

De pagina’s tonen de publieke bedrijfsgegevens uit de KBO. Voeg een bevestigd zakelijk e-mailadres of een aangesloten formulier toe als online aanvragen rechtstreeks vanaf de pagina’s moeten kunnen worden ingestuurd.
