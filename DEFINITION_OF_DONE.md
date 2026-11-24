# Definition of Done (DoD)

Užduotis (Task) laikoma užbaigta tik tada, kai įvykdytos visos jai taikomos sąlygos.

## 1. Kodo kokybė

- Nėra nereikalingo ar užkomentuoto kodo.
- Sukurtas „Pull Request“ (PR) su aiškiu "Jira" užduoties pavadinimu.

## 2. Kodo peržiūra (Code Review) – Developers

- Kodas tvarkingas, suprantamas ir tinkamai suformatuotas.
- Laikomasi visų komandos susitarimų dėl kodo rašymo (klasių/kintamųjų pavadinimai ir pan.)
- Visos kodo peržiūros metu pateiktos pastabos išspręstos.
- „Pull Request“ (PR) patvirtintas („Approved“).

## 3. Funkcionalumo testavimas (QA Testing) – QA Testers

- Įgyvendinti visi užduoties reikalavimai ir priėmimo kriterijai („Acceptance Criteria“).
- Funkcionalumas veikia taip, kaip numatyta.
- Patikrinta, ar pakeitimai nesugadino su užduotimi susijusio anksčiau veikusio funkcionalumo.
- Jei užduotis susijusi su vartotojo sąsaja, įgyvendinimas atitinka „Figma“ dizainą.
- Aptiktos klaidos ištaisytos, o pataisymai patikrinti.

## 4. Užduoties užbaigimas (Done)

- „Pull Request“ (PR) sujungtas („Merged“) į `main` šaką.
- Jira užduotis perkelta į „Done“ skiltį.

**Svarbu!** PR gali būti sujungtas į `main` tik sėkmingai užbaigus „Code Review“ ir „QA Testing“. Jei randama trūkumų, užduotis grąžinama taisymui.

**Pastaba dėl regresinio testavimo:** po kiekvieno PR nereikia iš naujo testuoti visos svetainės. QA tikrina naują funkcionalumą ir anksčiau veikusias funkcijas, kurias pakeitimai galėjo paveikti. Prieš galutinį projekto pristatymą rekomenduojama atlikti platesnį visos svetainės patikrinimą.
