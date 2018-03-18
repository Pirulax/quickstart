## Quickstart

### Hogyan tudok egy meglévő projecthez hozzájárulni?
- Feltelepíted a git verziókezelőt, a telepítőket [itt](https://git-scm.com/downloads) találod.
- Cloneold le az adott repot a gépedre.
- Módosítsd a fájlokat, adj hozzá, törölj, stb.
- Addold a fájlokat a stagingbe a `git add .` paranccsal.
- Commitold a változásokat a `git commit -m "Üzenet"` paranccsal, ahol az üzenet a módosítást írja le. (Pl. Életcsík színkód átírva)
- Told fel a változásokat a `git push origin <branch>` paranccsal. A branch helyére értelemszerűen a branch kerül, a fő branch mindig a `master`.
>Ha nem engedi, mert a változatod nem passzol a fentlévővel, akkor frissítsd le a local repodat az alábbi paranccsal: `git pull --rebase`

>Ha elakarod dobni a módosításaidat, akkor használd a `git checkout` parancsot, a harmadik paraméter értelemszerűen a fájlnév, minden fájl esetén `.`.

>Ha le akarod kérni hogy mik a módosítások, mi van a stagingben, illetve mi nincs, használd a `git status` parancsot.
