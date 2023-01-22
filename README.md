Repository klónozása github-ról:
- git clone https://github.com/szabopeter92/git-vizsga0104.git
  -> (a klónozott mappa git mappa, ebben az esetben nincs szükség a git init parancsra)


Új ág létrehozása:
- git branch console


Váltás az új ágra:
- git checkout console


A README.md és a .gitignore fájl létrehozása után mentés:
- git add . -> fájlok hozzáadása a staging area-hoz
- git commit -m "console ág létrehozva, readme.md, gitignore fájl létrehozva" -> aktuális verzió lokális mentése, rögzítése


Gitignore fájl szerkesztése után
- git add . 
- git commit -m "gitignore fájl szerkesztve"


App.js módosítása után:
- git add .
- git commit -m "app.js console ág elkészítve"


Style.css módosítása után:
- git add .
- git commit -m "style.css console ág elkészítve"


Readme fájl szerkesztése után
- git add .
- git commit -m "readme fájl szerkesztve"

Readme fájl mentése a main ágban is
- git checkout main
- git add .
- git commit -m "Readme mentve a main ágban"


Repo létrehozása a GitHub-on
Main és Console ág mentése távoli repo-ba:
- git push https://github.com/PriskinZsuzsanna/GitVizsga0121.git main
- git push https://github.com/PriskinZsuzsanna/GitVizsga0121.git console


--------
plusz parancsok:

clear: terminálablak törlése
git init: git inicializálása új projekt indításakor
git status: státusz lekérése

