# szoftvertech-projekt
# 🧩 H1 – Projektterv

## 👥 Csapattagok és szerepek

| Név | Szerepkör | Felelősségek |
|------|----------|--------------|
| *Matyi Bernát* | Fejlesztő & Dokumentáció felelős | Python modulok implementálása, dokumentációk (SRS, Vízió, tervek) formázása és előkészítése leadásra |
| *Bodnár Dániel* | Csapatvezető & Tesztelési felelős | Ütemezés, GitHub repo kezelése, mérföldkövek nyomon követése, tesztelési terv és automatizált tesztek |

*Csapatkommunikáció:*  
- Belső megbeszélés: *Discord/Messenger*
- Feladatkövetés: *GitHub Issues + Project board*
- Heti 1 státusz egyeztetés + mérföldkő előtti külön review

---

## 📆 Fejlesztési terv – Mérföldkövek (12 hetes ütemezés)

| Mérföldkő | Leszállítandó | Határidő |
|----------|--------------|----------|
| *H1* | Projektterv (README formában) | ✅ *1. hét* |
| *H2* | Vízió dokumentum + frissített terv + munkanapló indítása | *3. hét* |
| *H3* | SRS, Fogalomtár, Felhasználói kézikönyv v1 | *6. hét* |
| *H4* | Analízis modell + rendszertervezési dokumentum (UML / architektúra) | *9. hét* |
| *H5* | Python prototípus + Tesztelési terv + GitHub-ra feltöltött működő verzió | *12. hét* |
💬 Megjegyzés: H4 előtt buffer idő fenntartva (vizsgák / egyéb terhelés miatt)
)

---

## 🛠 Technológiák és eszközök

| Terület | Választott megoldás |
|--------|--------------------|
| *Programozási nyelv* | Python (3.11+) |
| *Framework* | (FastAPI / Flask – döntés alatt) |
| *Adatkezelés (prototípus)* | Egyszerű JSON / SQLite |
| *IDE / fejlesztői eszközök* | Visual Studio Code |
| *Verziókezelés* | Git + GitHub (branch: feature/... + Pull Request workflow) |
| *Tesztelés* | pytest + manuális forgatókönyvek |
| *CI (később)* | GitHub Actions |

---

## ⚙ Módszertan és technikák

- *Fejlesztési megközelítés:* Könnyített Agile (heti célkitűzések)
- *Feladatkezelés:* GitHub Issues + címkék (todo, in progress, done)
- *Tesztelési stratégia:*
  - Unit tesztek: pytest
  - Validációs teszt: bemeneti adatok ellenőrzése
  - Integrációs teszt: legalább egy API endpoint/részfunkció

---

## 🗂 Dokumentumok és felelősségek

| Dokumentum | Felelős | Határidő |
|------------|--------|----------|
| Vízió dokumentum | Matyi Bernát | 3. hét |
| Projektterv frissítés | Bodnár Dániel | 3. hét |
| SRS | Matyi Bernát | 6. hét |
| Fogalomtár | Bodnár Dániel | 6. hét |
| Analízis modell | Matyi Bernát | 9. hét |
| Rendszertervezés | Bodnár Dániel | 9. hét |
| Felhasználói dokumentáció | Matyi Bernát | 12. hét |
| Tesztelési terv | Bodnár Dániel | 12. hét |
| *Python prototípus (GitHub repo)* | *Mindkettő* | 12. hét |

---

## ✅ Tesztelési követelmények

- *Cél lefedettség:* legalább *70%* a fő modulokra
- Teszttípusok:
  - Unit tesztek (pytest)
  - Input-validáció teszt
  - Egy egyszerű endpoint / funkció integrációs teszt
- Minőségi kritérium: kritikus hiba nélkül lehessen futtatni a bemutató előtt

---

## 🖥 Leszállítás & bemutatás

- *Bemutatás módja:* Élő demo – Python backend futtatása, funkció bemutatása tesztadatokkal
- *Végső leadás:* GitHub repo link + rövid futtatási útmutató (README.md)
- (*Opcionális:* .zip export beadási rendszerbe)
- *Végső prezentáció tervezett ideje:*
*12. hét vége*

---

## 📚 Források

- https://fastapi.tiangolo.com (ha FastAPI lesz kiválasztva)
- https://docs.pytest.org (pytest dokumentáció)
- Clean Code – Robert C. Martin
- GitHub Docs – https://docs.github.com/

---

fastapi.tiangolo.com
