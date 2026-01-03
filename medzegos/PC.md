# 6. PC (Polikarbonatas) – Išsamus Techninis Vadovas

### 6.1. Bendras aprašymas (Santrauka)

PC yra aukšto naudingumo inžinerinis termoplastikas, 3D spausdinimo pasaulyje žinomas kaip viena tvirčiausių prieinamų medžiagų. Jis pasižymi **ekstremaliu atsparumu smūgiams, dideliu standumu ir puikiu terminiu stabilumu**. Dėl savo optinio skaidrumo ir gebėjimo atlaikyti dideles mechanines apkrovas be lūžių (priešingai nei trapus PLA), PC dažnai lyginamas su „neperšaunamu stiklu“.

### 6.2. Chemija ir gamyba

- **Struktūra:** Polikarbonatas yra polimeras, turintis karbonatines grupes savo cheminėje grandinėje. Tai amorfinis plastikas, kas suteikia jam natūralų skaidrumą.
- **Savybės:** Pasižymi aukšta stiklėjimo temperatūra (~145–150 °C), todėl išlaiko struktūrinį vientisumą aplinkoje, kurioje kiti plastikai (PLA, PETG) suminkštėtų.
- **Modifikacijos:** Dažnai sutinkami PC lydiniai (pvz., **PC-ABS** dėl geresnio spausdinamumo) arba armuoti variantai (pvz., **PC-CF** su anglies pluoštu, kuris dar labiau padidina standumą ir sumažina traukimąsi).

### 6.3. Kainodara (2025–2026 m. prognozės)

- **Mažmeninė kaina (1 kg):**
    - Standartinis PC: **€40 – €60** ($40–$60 USD).
    - Aukščiausios kokybės ar specializuoti (pvz., ugniai atsparūs PC-FR): **€60 – €90**.
    - PC-CF (su anglies pluoštu): **€80 – €220**.
- **Didmeninė kaina (perkant >100 kg):**
    - Orientacinis įkainis: **€40 – €55** už kg.
    - Kai kurie gamintojai (pvz., Anycubic) siūlo specialius „deals“, kur kaina gali būti žymiai žemesnė vykdant masinius pirkimus.

### 6.4. Pranašumai ir trūkumai

#### **Pranašumai:**

- **Atsparumas smūgiams:** Viena geriausių medžiagų apsauginėms detalėms; ji linkusi deformuotis, o ne shattering (subyrėti).
- **Karščio atsparumas:** Gali būti naudojamas temperatūroje iki **110–140 °C** (HDT prie 0.45 MPa).
- **Skaidrumas:** Geriausias optinis skaidrumas tarp visų tvirtų inžinerinių plastikų.
- **Standumas:** PC detalės pasižymi dideliu struktūriniu tvirtumu, ypač jei naudojami užpildai.

#### **Trūkumai:**

- **Sunkus spausdinimas:** Didelis terminis susitraukimas sukelia stiprų **warping'ą** (detalių rietimąsi nuo pagrindo) ir sluoksnių skilinėjimą.
- **Higroskopiškumas:** PC „siurbia“ drėgmę itin agresyviai. Drėgna medžiaga spausdinant burbuliuoja, o sluoksnių sukibimas dramatiškai suprastėja.
- **Trapumas po džiovinimo:** Per daug kartojami džiovinimo ciklai dėl sukaupto terminio streso gali padaryti patį filamentą trapų dar prieš spausdinimą.
- **Klijavimo reikalavimai:** Be tinkamų klijų PC gali negrįžtamai pažeisti PEI pagrindą dėl per stipraus sukibimo.

### 6.5. Kur naudoti / Kur nenaudoti

#### **Naudoti:**

- **Apsauginei įrangai:** Skydams, akiniams, pramoninių mašinų langams.
- **Elektronikai:** Korpusams, kurie turi būti atsparūs karščiui ir galimai ugniai (PC-FR versijos).
- **Automobilių detales:** Komponentams po kapotu, kurie patiria didelį karštį, bet ne tiesioginę trintį.
- **Funkciniams prototipams:** Kurie turi atlaikyti realius mechaninius bandymus.

#### **Nenaudoti:**

- **Maisto sąlyčiui:** PC sudėtyje dažnai yra bisfenolio A (BPA), kuris nėra saugus maistui.
- **Lauko detalėms be UV stabilizatorių:** Standartinis PC geltonuoja ir degraduoja nuo tiesioginių saulės spindulių (tam geriau tinka PC/PBT lydiniai arba ASA).
- **Dideliems ploniems objektams:** Tokios formos yra linkusios į nepataisomą warping'ą net ir uždaroje kameroje.

### 6.6. Bambu Lab P1S specifika

- **Palaikymas:** P1S oficialiai palaiko PC.
- **Kameros svarba:** Kadangi PC yra itin jautrus temperatūros svyravimams, **BŪTINA** laikyti P1S dureles ir viršutinį stiklą uždarytus.
- **Temperatūros:** Purkštukas: **260–290 °C**, Pagrindas: **100–120 °C**. _Pastaba: P1S maksimali pagrindo temperatūra yra 100 °C, todėl PC spausdinimas vyksta ties galimybių riba_.
- **AMS suderinamumas:** Standartinis PC yra suderinamas su AMS.
- **Džiovinimas (Privalomas):** Reikalauja 8 valandų 80 °C temp. krosnelėje arba 12 valandų 90–100 °C temp. ant P1S pagrindo po gaubtu.

### 6.7. Verslo idėjos

- **Specializuotų korpusų gamyba:** Atsparūs karščiui korpusai individualiems dronams ar robotikos projektams.
- **Apsauginiai skydai pramonėms:** Mažos partijos specifinės formos skydų laboratorijoms ar gamybos linijoms.
- **Elektros komponentų laikikliai:** Detalės, kurioms reikalingas V0 nedegumo sertifikatas (naudojant PC-FR).
- **Optinių dalių prototipavimas:** Skaidrūs dangteliai ir lęšiai (po poliravimo), kurie yra tvirtesni už PMMA.

---

### Šaltinių turinys (PC)

1. **Snapmaker Lab Testing:** PC mechaninis stipris (virš 67 MPa tensile strength) ir skaidrumo savybės. [Šaltinis 1170, 1172, 1179].
2. **Bambu Lab Filament Guide:** P1S nustatymai, AMS suderinamumas ir uždaros kameros reikalavimai PC warping'ui valdyti. [Šaltinis 679, 685, 689].
3. **Filament Drying Recommendations:** Detalios PC džiovinimo instrukcijos ir įspėjimai dėl trapumo po pakartotinio kaitinimo. [Šaltinis 662, 665, 697].
4. **Zack Freedman Tier List:** PC kaip "beefiest standard filament" analizė ir palyginimas su super-polimerais (PEEK/ULTEM). [Šaltinis 1259-1261].
5. **3D Printer Filament TDS:** Techniniai PC duomenys: tankis 1.18–1.20 g/cm³, HDT 110–140°C. [Šaltinis 189].
6. **Polymaker Download Center:** TDS duomenys apie PolyMax PC ir PC-FR (ugniai atsparaus) savybes. [Šaltinis 563, 568].
7. **SABIC / Lexan Data:** Informacija apie pramoninį PC pritaikymą ir jo pranašumus prieš ABS. [Šaltinis 219, 1050].
8. **3DXTech Practical Guide:** Inžinerinių plastikų (PC, PEI) spausdinimo iššūkiai ir hardware reikalavimai. [Šaltinis 1044, 1047, 1051, 1055].
9. **Common Print Quality Problems (Bambu Wiki):** Interlayer cracking sprendimo būdai spausdinant PC medžiagas. [Šaltinis 428, 429].
10. **Pasaulinės rinkos analizė (2025–2030):** PC pozicionavimas inžinerinių medžiagų segmente ir didmeninės kainos. [Šaltinis 1019, 1020].
