# 2. PETG (Glikoliu modifikuotas PET) - Išsamus Techninis Vadovas

### 2.1. Bendras aprašymas (Santrauka)

PETG yra vienas universaliausių 3D spausdinimo filamentų, dažnai įvardijamas kaip **aukso vidurys tarp PLA ir ABS**. Jis pasižymi PLA būdingu spausdinimo lengvumu ir ABS mechaniniu tvirtumu bei atsparumu temperatūrai. PETG yra vertinamas dėl savo **smūginio atsparumo, cheminio stabilumo ir puikaus sluoksnių sukibimo**, todėl idealiai tinka funkcinėms detalėms, kurios bus naudojamos realiomis sąlygomis.

### 2.2. Chemija ir gamyba

- **Struktūra:** Tai polietileno tereftalatas (PET), modifikuotas pridedant glikolio ("G").
- **Gamybos tikslas:** Glikolis pakeičia polimero molekulinę struktūrą taip, kad medžiaga kristalizuotųsi lėčiau. Tai padaro plastiką skaidresnį, mažiau trapų ir neleidžia jam tapti „pieniškam“ kaitinimo metu.
- **Savybės:** PETG yra amorfinis termoplastikas, pasižymintis mažu apdorojimo susitraukimu, todėl jis yra kur kas stabilesnis už ABS.

### 2.3. Kainodara (2025–2026 m. prognozės)

- **Mažmeninė kaina (1 kg):** €19 – €35 (specializuoti kompozitai, pvz., PETG-CF su anglies pluoštu, gali kainuoti €35 – €70).
- **Didmeninė kaina (perkant urmu):**
    - **Mažos partijos (10–50 kg):** €13 – €18 už kg.
    - **Didelės partijos (100 kg+):** €9 – €12 už kg (Azijos importas per ES sandėlius gali siekti tik €7.50 – €10 už kg).
    - **Refill (be ritės):** Paprastai yra ~10–15% pigesnis variantas.

### 2.4. Pranašumai ir trūkumai

#### **Pranašumai:**

- **Atsparumas aplinkai:** Itin atsparus vandeniui, UV spinduliams ir daugumai chemikalų (rūgštims, šarmams), todėl tinkamas lauko sąlygoms.
- **Mechaninė ištvermė:** Medžiaga yra elastingesnė už PLA – ji linkusi linkti, o ne lūžti, todėl pasižymi puikiu smūginiu atsparumu.
- **Sluoksnių sukibimas:** PETG pasižymi vienu stipriausių sluoksnių sukibimų (Z-axis strength) tarp visų FDM medžiagų.
- **Maistas ir saugumas:** Dauguma PETG rūšių yra suderinamos su FDA/maisto saugos standartais (tačiau būtina tikrinti gamintojo TDS).

#### **Trūkumai:**

- **Stygavimasis (_Stringing_):** Dėl didelio medžiagos klampumo PETG yra linkęs palikti plonus „plaukelius“ tarp spausdinamų dalių.
- **Higroskopiškumas:** Medžiaga stipriai sugeria drėgmę iš oro, todėl drėgnas filamentas spaudžiant „traška“ ir palieka pūsles.
- **Per stiprus kibimas:** Gali pažeisti stiklinius ar lygų PEI pagrindą, jei nenaudojamas skiriamasis sluoksnis (klijai).
- **Prastas „tiltų“ (_bridging_) formavimas:** Dėl lėto vėsimo PETG linkęs išlinkti spausdinant horizontalias dalis be palaikymo.

### 2.5. Kur naudoti / Kur nenaudoti

#### **Naudoti:**

- **Funkcinėms detalėms:** Skląstims, laikikliams, spyruokliuojantiems elementams.
- **Lauko priedams:** Sodo įrankių dalims, išorinėms iškaboms, dronų rėmams.
- **Talpoms:** Vandeniui atspariems indams, dėžutėms.
- **Apsauginiams dėklams:** Telefonų dėklams ar pramoninės įrangos apsaugoms.

#### **Nenaudoti:**

- **Itin detaliems modeliams:** Kur reikalingas preciziškas tikslumas be stygavimosi (pvz., smulkios miniatiūros).
- **Aukštos temperatūros aplinkoje:** Virš 70–80 °C detalės pradeda minkštėti (pvz., tiesioginis kontaktas su varikliu).

### 2.6. Bambu Lab P1S specifika

- **AMS suderinamumas:** PETG puikiai veikia su AMS sistema.
- **Temperatūros:** Purkštukas: 240–270 °C, Pagrindas: 60–80 °C.
- **Pagrindas:** Rekomenduojama naudoti **Textured PEI Plate** arba **Engineering Plate**. **Būtina naudoti klijus** kaip barjerą, kad nepažeistumėte pagrindo dangos.
- **Džiovinimas:** PETG **rekomenduojama džiovinti** prieš naudojimą: 65 °C temp. 8 valandas krosnelėje arba 75–85 °C temp. 12 valandų ant P1S pagrindo.
- **Srautai:** Naudojant _Generic PETG_ profilį, maksimalus tūrinis greitis paprastai apribojamas iki 10–12 mm³/s, tačiau _Bambu PETG HF_ (High Flow) gali siekti kur kas didesnius greičius.

### 2.7. Verslo idėjos

- **Pramoninės tarpinės ir sandarikliai:** Skubus cheminiam poveikiui atsparių dalių tiekimas gamykloms.
- **Individualizuoti dviračių ar automobilių priedai:** Laikikliai, kurie turi atlaikyti saulės spindulius ir vibraciją.
- **Vandeniui atspari elektronikos pakuotė:** Hermetiškos dėžutės jutikliams lauko sąlygomis.
- **Daugkartinio naudojimo laboratorinė įranga:** Stovai ir laikikliai, kurie nebijo dezinfekcijos priemonių.

---

### Šaltinių turinys (PETG)

1. **3DJake PET/PETG Guide:** PET ir PETG skirtumai, skaidrumas ir naudojimo sritys..
2. **Bambu Lab Filament Guide:** P1S nustatymai, AMS suderinamumas ir paviršių parinkimas..
3. **Filament Drying Recommendations:** Išsamios PETG džiovinimo instrukcijos naudojant P1S pagrindą..
4. **Zack Freedman Tier List:** PETG kaip „darbinio arkliuko“ statusas ir palyginimas su PCTG..
5. **Strategic Market Research 2030:** PETG paklausos augimas ir pramoninis pritaikymas..
6. **3D Print Dood / Frankly Built:** PETG smūginio atsparumo ir terminio stabilumo testai..
7. **Polymaker TDS:** Techniniai duomenys (HDT, Tensile Strength) lyginant su PLA..
8. **Bambu Lab Wiki - Quality Problems:** Stygavimosi (_stringing_) ir kibimo prie purkštuko problemų sprendimai..
9. **Filacraft (Lietuva):** Vietinė gamyba, B2B užsakymai ir AMS suderinamumas..
10. **UL Research Report:** Duomenys apie VOC emisijas spausdinant inžinerinius plastikus..