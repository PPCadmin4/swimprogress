SwimProgress PWA v2

Nahraď v GitHub repozitáři původní soubory těmito:
- index.html
- sw.js
- manifest.webmanifest
- icon-192.png
- icon-512.png

Důležitá změna:
Apple Health export.xml se čte pomocí File.stream(), takže se celý soubor nikdy nenačítá do paměti.
Import průběžně zpracovává workouty a ukládá mezivýsledky.

Po nahrání na GitHub Pages:
1. Otevři web v Safari.
2. Pokud máš PWA přidanou na plochu, úplně ji zavři a otevři znovu.
3. Když by se pořád ukazovala stará verze, v Safari otevři webovou adresu přímo.
