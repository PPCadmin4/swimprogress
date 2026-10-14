# SwimProgress PWA

## Publikace zdarma přes GitHub Pages
1. Vytvoř nový GitHub repozitář, například `swimprogress`.
2. Nahraj do kořene repozitáře všechny soubory z tohoto balíčku.
3. GitHub → Settings → Pages.
4. Source: `Deploy from a branch`.
5. Branch: `main`, folder `/ (root)`.
6. Ulož.
7. Otevři vzniklou HTTPS adresu v Safari.

## Přidání na plochu iPhonu
Safari → Sdílet → Přidat na plochu.

## Apple Health
V aplikaci Zdraví exportuj zdravotní data, ZIP rozbal a v PWA vyber `apple_health_export/export.xml`.
Web nemůže číst HealthKit přímo, proto je import XML ruční.
