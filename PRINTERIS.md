https://www.anodas.lt/3d-spausdintuvas-bambu-lab-p1s

# Bambu Lab P1S: Eksploatacijos ir Paruošimo Vadovas

## 1. Spausdintuvo paruošimas darbui (Setup)

Sėkmingas P1S paleidimas reikalauja tikslaus mechaninio atblokavimo ir programinės konfigūracijos:

1. **Transportavimo varžtų pašalinimas:** Būtina išsukti **3 varžtus**, kurie fiksuoja šildomą pagrindą (hot bed) transportavimo metu. Naudokite H2 šešiabriaunį raktą.
2. **Ekrano ir ritės laikiklio montavimas:** LCD ekranas įstatomas į lizdą ir užfiksuojamas stumiant į kairę. Ritės laikiklis tvirtinamas galinėje dalyje dviem varžtais.
3. **Surišimas su „Bambu Handy“ programėle:** Atsisiųskite programėlę, nuskaitykite QR kodą ekrane ir susiekite spausdintuvą su savo paskyra per Wi-Fi.
4. **Pirminė kalibracija:** Paleiskite pilną įrenginio kalibraciją (trunka apie 20 min.). Jos metu spausdintuvas tikrina vibracijų kompensavimą, lygina pagrindą ir kalibruoja ekstruderio srautus. **Svarbu:** vibracija ir triukšmas šio proceso metu yra normalus reiškinys.
5. **Priežiūros ciklas (nuolatiniam darbui):**
    - **Kas 2 savaites:** Nuvalykite X ašies anglies pluošto strypus izopropilo alkoholiu.
    - **Kas mėnesį:** Sutepkite Z ašies sriegines svirtis ir patikrinkite guminį purkštuko valiklį (nozzle wiper).

## 2. Filamentų paruošimas (Drying & Handling)

Filamentų drėgmė yra pagrindinė prastos kokybės (stygavimosi, burbuliavimo) priežastis.

### Rekomenduojami džiovinimo parametrai (Appendix I):

|Medžiaga|Džiovinimo temp. (krosnelėje)|Laikas|P1S pagrindo temp. (jei nėra krosnelės)|
|:--|:--|:--|:--|
|**PLA**|50-55 °C|8 val.|60-70 °C (12 val.)|
|**PETG**|60-65 °C|8 val.|75-85 °C (12 val.)|
|**TPU**|65-75 °C|8 val.|80-90 °C (12 val.)|
|**ABS/ASA/PC**|75-85 °C|8 val.|90-100 °C (12 val.)|
|**PA (Nylon)**|80 °C|8-12 val.|90-100 °C (12 val.)|

**Kritinės pastabos:**

- **TPU:** Ši medžiaga yra per minkšta **AMS sistemai**, todėl turi būti tiekiama iš išorinio laikiklio per galinį PTFE vamzdelį.
- **PVA/PA/PC:** Šios medžiagos privalo būti laikomos AMS su šviežiu desikantu, nes sugeria drėgmę per kelias valandas.
- **Abrasinės medžiagos (CF/GF):** Naudojant anglies ar stiklo pluošto užpildus, būtina naudoti **grūdinto plieno (Hardened Steel) purkštuką** (standartinis P1S purkštukas yra nerūdijančio plieno ir greitai dyla).

## 3. Spausdinimo nustatymai (Settings)

### Temperatūros ir Pagrindo (Build Plate) suderinamumas:

|Medžiaga|Purkštuko temp.|Pagrindo temp.|Klijų poreikis (Bambu Glue Stick)|
|:--|:--|:--|:--|
|**PLA**|190 - 240 °C|35 - 65 °C|Pasirinktinai (rekomenduojama Cool Plate)|
|**PETG**|240 - 270 °C|60 - 80 °C|**Būtina** (kaip skiriamasis sluoksnis)|
|**ABS/ASA**|240 - 280 °C|90 - 100 °C|Rekomenduojama (Engineering Plate)|
|**PC/PA**|260 - 300 °C|100 - 120 °C|**Būtina**|

### Kameros valdymas (Terminis režimas):

- **PLA / PETG / TPU:** Jei pagrindo temperatūra viršija 45-60 °C, **rekomenduojama atidaryti priekines dureles arba nuimti viršutinį stiklą**, kad būtų išvengta purkštuko užsikimšimo dėl _heat creep_ (ankstyvo plastiko suminkštėjimo).
- **ABS / ASA / PC / PA:** Kamera privalo būti **sandariai uždaryta**, kad būtų išlaikyta stabili temperatūra ir išvengta detalių skilinėjimo ar rietimosi (_warping_).

## 4. 3D Modeliavimo ir „Slicing“ patarimai komandai

1. **Stiprumo orientacija:** 3D spaudiniai yra anizotropiški – jų stiprumas Z ašies kryptimi (sluoksnių sukibimas) yra žymiai mažesnis nei X/Y ašyse. Jei detalė turi atlaikyti svorį, modeliuokite ją taip, kad jėga veiktų statmenai sluoksniams.
2. **Didelių modelių „warping“ prevencija:**
    - Venkite didelių plokščių paviršių tiesiogiai ant pagrindo. Pakreipkite modelį **45° kampu**, kad sumažintumėte tempimo jėgas.
    - Naudokite **Gyroid** užpildą (infill) – jis suteikia vienodą stiprumą visomis kryptimis ir nesikerta viename sluoksnyje, todėl mažesnė tikimybė, kad purkštukas kliudys detalę.
3. **Sienelių skaičius (Walls) vs. Užpildas:** Didesnį konstrukcinį stiprumą suteikia sienelių skaičiaus didinimas (pvz., nuo 2 iki 5), o ne užpildo tankio didinimas virš 40-50%.
4. **Pagalbinės struktūros (Supports):** Sudėtingiems inžineriniams modeliams naudokite **Tree Supports** (taupo medžiagą ir lengviau nuimami). Jei naudojate AMS, spausdinkite sąlyčio taškus (support interface) iš specialios medžiagos (Support for PLA/PA), kad paviršius būtų idealiai lygus.

---

### Informacijos šaltinių nuorodos

1. **Bambu Lab Maintenance Guide:** [P1 Series Maintenance Guide](https://wiki.bambulab.com/en/p1/maintenance/p1p-maintenance-guide).
2. **Bambu Lab Filament Guide:** [Compatibility & Parameters PDF](https://wiki.bambulab.com/en/filament-acc/filament/filament-guide).
3. **Filament Drying Recommendations:** [Drying Parameters Table](https://wiki.bambulab.com/en/filament-acc/filament/dry-filament).
4. **Quick Start Guide P1S:** [Official Unboxing & Setup](https://bambulab.com/en/p1/manual/quick-start-p1s).
5. **Common Print Quality Problems:** [Troubleshooting Wiki](https://wiki.bambulab.com/en/software/bambu-studio/common-print-quality-problem).
6. **CNC Kitchen Testing:** [PA6 vs PA12 Creep Tests](https://www.cnckitchen.com/blog/carbon-fiber-nylon-in-3d-printing-pa6-vs-pa12-tested).
7. **Zack Freedman Tier List:** [Material Properties Review](https://www.youtube.com/watch?v=1K_S-q_x2h4).
8. **ASTM D638 Tensile Study:** [PLA, PETG, ABS comparison](https://dergipark.org.tr/ij3dptdi).
9. **Bambu Studio Guide:** [Slicing Parameter Settings](https://wiki.bambulab.com/en/software/bambu-studio/parameter-guide).
10. **Wittworks Woodworking Class:** [Workshop Printer Tips](https://www.youtube.com/watch?v=Xh0YF6M3yRE).
