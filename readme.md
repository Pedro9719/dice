# GIT verziókezelés

- Helyi REPO inicializálása:
    > git init
- Ellenőrzése:
    > git status
- Előkészítés commitolásra, feltesszük a színpadra(stage), indexelés:
    > git add . (A 'pont' minden állományra vonatkozik)

    > git status
- Commit, az új verzió létrehozása:
    > git commit -m "firstCommit" (Helyi repo inicializálása)

    > git status
- Távoli repo létrehozása (a GitHub oldalon):
- Összekapcsoljuk a távoli repot a helyivel:(legelső alkalommal)
    > git remote add origin https://token@github.com/Pedro9719/Test.git
- Kiválasztjuk az ágat (Brenchet) a távoli repoban:
    > git push -u origin master (ezt csak legelső alkallomal kell)

    > git push ( a további alkalomkor)
- Token használata ( ezzel azonosítjuk magunkat a github-on)

## Publikálás
- A publikálandó fájl neve index.html
- Settings > Pages > Branch non-ból kiválasztottuk a mestert > save
- Actionban látható a publikálási folyamat.