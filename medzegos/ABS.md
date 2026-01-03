# 7. ABS (Akrilnitrilo butadieno stirolas) – Išsamus Techninis Vadovas

### 7.1. Bendras aprašymas (Santrauka)

ABS yra vienas seniausių ir labiausiai paplitusių inžinerinių termoplastikų, dešimtmečius naudojamas masinėje gamyboje (pavyzdžiui, LEGO kaladėlėms). 3D spausdinimo bendruomenėje ABS vertinamas dėl savo **tvirtumo, atsparumo smūgiams ir aukštai temperatūrai**. Nors spausdinimas yra techniškai sudėtingas dėl didelio medžiagos traukimosi (_warping_), tai išlieka viena pigiausių ir geriausiai mechaniškai apdirbamų medžiagų rinkoje.

### 7.2. Chemija ir gamyba

- **Kilmė:** Naftos pagrindo terpolimeras, sudarytas iš trijų monomerų: **akrilnitrilo** (suteikia cheminį atsparumą ir terminį stabilumą), **butadieno** (suteikia smūginį atsparumą) ir **stirolio** (suteikia standumą bei blizgesį).
- **Savybės:** ABS yra amorfinis polimeras, pasižymintis mažesniu tankiu (~1,04 g/cm³) nei PLA, todėl detalės yra lengvesnės.
- **Modifikacijos:** Šiuolaikinės versijos, tokios kaip **ABS+** arba **ABS-GF** (su stiklo pluoštu), yra sukurtos siekiant sumažinti traukimąsi ir padidinti struktūrinį stabilumą.

### 7.3. Kainodara (2025–2026 m. prognozės)

- **Mažmeninė kaina (1 kg):** €20 – €35. Specializuoti variantai (pvz., ABS-CF ar ABS-FR) gali kainuoti €45 – €80.
- **Didmeninė kaina (perkant >100 kg):**
    - Azijos importas (ES sandėlis): **€14 – €19** už kg.
    - Perdirbtas (Recycled) ABS urmu: gali siekti tik **~$10** už kg (pvz., Sunlu perdirbtų medžiagų linija).

### 7.4. Pranašumai ir trūkumai

#### **Pranašumai:**

- **Karščio atsparumas:** Išlaiko formą iki **95–100 °C**.
- **Po-apdorojimas:** Geriausiai šlifuojamas ir gręžiamas plastikas. Unikali savybė – galimybė lyginti paviršių **acetono garais**, išgaunant veidrodinį blizgesį, panašų į lietas detales.
- **Tvirtumas:** Puikus atsparumas smūgiams – detalė linkusi deformuotis, o ne subyrėti.
- **Klijavimas:** Detalės gali būti lengvai sujungiamos „acetono klijais“ (acetono ir ABS tirpalu), sukuriant cheminę jungtį.

#### **Trūkumai:**

- **Terminis traukimasis (_Warping_):** ABS stipriai traukiasi vėsdamas, todėl be uždaros kameros detalės dažnai atšoka nuo pagrindo ar skyla tarp sluoksnių.
- **Toksiškumas:** Spausdinant išsiskiria nemalonus kvapas ir kenksmingi **VOC** (lakieji organiniai junginiai), įskaitant stireną, todėl būtina gera ventiliacija arba filtrai.
- **Neatsparumas UV:** Veikiamas tiesioginių saulės spindulių, ABS geltonuoja ir tampa trapus (lauko sąlygoms rekomenduojama rinktis ASA).

### 7.5. Kur naudoti / Kur nenaudoti

#### **Naudoti:**

- **Funkciniams prototipams:** Kurie patirs mechaninį stresą ar šilumą (pvz., laikikliai prie variklių).
- **Elektronikos korpusams:** Dėl gero terminio stabilumo ir galimybės naudoti ugniai atsparias (FR) versijas.
- **Automobilių interjerui:** Detalėms, kurios nėra veikiamos tiesioginės saulės šviesos.
- **Judantiems mechanizmams:** Dėl gero atsparumo trinčiai.

#### **Nenaudoti:**

- **Maisto sąlyčiui:** ABS nėra laikomas saugiu maistui dėl cheminių išskyrų.
- **Lauko detalėms:** Dėl jautrumo UV spinduliams.
- **Vaikų žaislams:** Jei nėra užtikrinta, kad spausdinimo metu nebuvo viršyta temperatūra ir neliko kenksmingų garų likučių.

### 7.6. Bambu Lab P1S specifika

- **Palaikymas:** P1S yra **uždaro tipo**, todėl idealiai tinka ABS spausdinimui, nes išlaiko stabilų kameros temperatūros lygį, būtiną traukimosi prevencijai.
- **Temperatūros:** Purkštukas: **240–280 °C**, Pagrindas: **90–100 °C**.
- **AMS suderinamumas:** Standartinis ABS yra suderinamas su AMS.
- **Džiovinimas:** Rekomenduojama džiovinti **80 °C temp. 8 valandas** krosnelėje arba naudoti P1S pagrindą.
- **Ventiliacija:** P1S turi aktyvuotos anglies filtrą, tačiau spausdinant didelius ABS kiekius, rekomenduojama papildoma išorinė ventiliacija.

### 7.7. Verslo idėjos

- **Automobilių detalių atkūrimas:** Retų ar nebegaminamų plastikinių interjero apdailos detalių gamyba.
- **Industriniai korpusai:** Individualizuotos dėžutės elektronikai, kurios atrodo profesionaliai po acetono lyginimo.
- **3D spausdintuvų komponentai:** Pačių 3D spausdintuvų detalių (pvz., Voron projekto dalių) gamyba, nes jos turi atlaikyti karštį kameros viduje.

---

### Šaltinių turinys (ABS)

1. **UL Research Report (2020):** Išsamūs duomenys apie ABS VOC emisijas (stireną) ir dalelių toksiškumą. [Šaltinis 33, 35, 37].
2. **Bambu Lab Filament Guide:** P1S nustatymai, AMS suderinamumas ir uždaros kameros reikalavimai. [Šaltinis 679, 682, 685, 688].
3. **Filament Drying Recommendations:** ABS džiovinimo instrukcijos naudojant P1S pagrindą (100°C). [Šaltinis 660, 662, 697].
4. **Zack Freedman Tier List:** ABS palyginimas su ASA ir jo, kaip "senosios mokyklos" inžinerinio plastiko, statusas. [Šaltinis 1250-1251].
5. **Strategic Market Research 2030:** ABS rinkos dalis, pramoninis segmentavimas ir paklausos tendencijos. [Šaltinis 124, 127, 128].
6. **3D Printer Filament Prices 2025 (Fabbaloo):** Didmeninių ABS-CF ir standartinių ABS kainų analizė (Azija vs Vakarai). [Šaltinis 57, 59].
7. **CNC Kitchen (Stefan Hermann):** ABS mechaninio stiprio bandymai ir palyginimas su Nylon/ASA. [Šaltinis 369].
8. **Simplify3D Materials Guide:** ABS savybių santrauka ir geriausios spausdinimo praktikos. [Šaltinis 1341, 1250].
9. **Pasaulinės rinkos analizė (2025–2030):** Didmeninės kainos Europoje (PL/CZ) ir Azijos importo modeliai. [Šaltinis 1017, 1018, 1036].
10. **Sunhokey Electronics TDS:** ABS fizinių savybių lentelė (tankis, tempimo stipris, spausdinimo greičiai). [Šaltinis 79, 987, 988].
