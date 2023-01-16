# Verziókezelés alapjai
## 1. git letöltése
- [git for windows](https://gitforwindows.org/)
- [git scm](https://git-scm.com/)
## 2. Konfigurációs parancsok
- git config --global user.name baracskaidora
- git config --global user.email baracskai.dora@students.jedlik.eu
- git config --global credential.helper wincred
## 3. Reponsitory létrehozása
- git init
## 4. Állomány hozzáadása a stage-hez (stageing area)
> A stagen lévő állományokról tudunk állapotfelvételt (commit-ot) készíteni
> Üres mappa nem kerül stage-re
- git add állomány_neve
- git add . (összes állomány és mappa hozzáadása)
## 5. Állapotfelvétel (commit) készítése
- git commit -m "commit message"
  ## 6. Git állapot és log lekérdezése
-  git status
-  git log
  ## 7. Lokális változások szinkronizálása a távoli repróba
  - git push
  ## 8. Távoli repó másolása (klónozása) a lokális repóba
  - git clone "távoli repó URL címe"
  ## 9. Ágak (branches) kezelése
  > Lokális ágak listázása
  - git branch
  > Lokális és távoli ágak listázás
  - git branc -av
  > Ág létrehozása (-b és váltása)
  - git branch új_ág_neve
  - git checout -b új_ág_neve
  > Váltás másik ágra
  - git checkout új_ág_neve
  > Ág törlése (aktuális ág nem törölhető)
  - git branch - törlendő_ág_neve
  ##  