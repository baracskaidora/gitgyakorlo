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