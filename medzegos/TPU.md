# 3. TPU (Termoplastinis poliuretanas) – Išsamus Techninis Vadovas

### 3.1. Bendras aprašymas (Santrauka)

TPU yra lankstus, guminis elastomeras, priklausantis termoplastinių elastomerų (TPE) šeimai. Jis unikaliai **sujungia plastiko tvirtumą ir gumos elastingumą**, todėl iš jo atspausdintos detalės gali būti lankstomos, tempiamos ir spaudžiamos neprarandant pradinės formos. TPU yra kietesnis ir stabilesnis už tradicinį TPE, todėl jį kur kas lengviau spausdinti naudojant FDM technologiją.

### 3.2. Chemija ir gamyba

- **Struktūra:** Tai blokinis kopolimeras, sudarytas iš kietų (suteikiančių tvirtumą) ir minkštų (suteikiančių lankstumą) segmentų.
- **Kietumas:** Matuojamas Shore skale (dažniausiai 95A, 90A arba 85A). Mažesnis skaičius reiškia minkštesnę, labiau gumą primenančią medžiagą.
- **Savybės:** Pasižymi itin dideliu pailgėjimu iki trūkimo (virš 600 %) ir puikiu terminiu stabilumu.

### 3.3. Kainodara (2025–2026 m. prognozės)

- **Mažmeninė kaina (1 kg):** €31 – €55 už 1 kg (aukšto srauto „High-Flow“ TPU gali kainuoti €40–€50).
- **Didmeninė kaina (perkant urmu):**
    - **Mažos partijos (10–20 vnt. po 0,5 kg):** ~€11 už vienetą.
    - **Didelės partijos (100 kg+):** €15 – €25 už kg, priklausomai nuo gamintojo ir kietumo klasės.

### 3.4. Pranašumai ir trūkumai

#### **Pranašumai:**

- **Indestruktyvumas:** TPU pasižymi **tobulu sluoksnių sukibimu** ir yra beveik neįmanomas sulaužyti ar sudaužyti smūgiu.
- **Atsparumas:** Itin atsparus trinčiai, plyšimui, alyvoms, tepalams ir įvairiems tirpikliams.
- **Vibracijų slopinimas:** Puikiai sugeria smūgius ir triukšmą, todėl tinka mechaniniams izoliatoriams.
- **Saugumas:** Kai kurios rūšys yra sertifikuotos sąlyčiui su oda.

#### **Trūkumai:**

- **AMS nesuderinamumas:** TPU yra **per minkštas Bambu Lab AMS sistemai** – jis gali užstrigti padavimo kanaluose, todėl turi būti spausdinamas iš išorinės ritės laikiklio.
- **Higroskopiškumas:** Labai greitai sugeria drėgmę; drėgnas TPU spausdinant stipriai styguojasi, burbuliuoja ir praranda mechaninį tvirtumą.
- **Spausdinimo greitis:** Reikalauja lėto spausdinimo (dažnai 15–30 mm/s), kad išvengtumėte gijų susisukimo ekstruderyje.
- **Apdaila:** Beveik neįmanoma šlifuoti ar mechaniškai apdirbti po spausdinimo dėl medžiagos lankstumo.

### 3.5. Kur naudoti / Kur nenaudoti

#### **Naudoti:**

- **Apsauginėms detalėms:** Telefonų dėklams, dronų buferiams, kampų apsaugoms.
- **Pramoniniams komponentams:** Sandarikliams, tarpinėms, lanksčioms jungtims, vamzdeliams.
- **Avalynei:** Batų padams (midsoles), ortopediniams vidpadžiams.
- **RC modeliams:** Didelio sukibimo padangoms.

#### **Nenaudoti:**

- **Struktūrinėms detalėms:** Kurios turi išlaikyti svorį nesideformuodamos.
- **Modeliams su daug palaikymų:** TPU palaikymus nuimti yra itin sunku dėl stipraus sluoksnių sukibimo.

### 3.6. Bambu Lab P1S specifika

- **AMS statusas:** **Griežtai nenaudoti su AMS**.
- **Temperatūros:** Purkštukas: 200–250 °C, Pagrindas: 30–45 °C.
- **Klijai:** Rekomenduojama naudoti klijus (glue stick) kaip barjerą, nes TPU gali **per stipriai prikibti prie PEI pagrindo** ir jį sugadinti.
- **Ventiliacija:** Jei pagrindo temperatūra viršija 45 °C, rekomenduojama **atidaryti dureles arba nuimti viršutinį stiklą**, kad TPU nesuminkštėtų ekstruderyje.
- **Džiovinimas:** **Privalomas** (Required) prieš naudojimą: 70 °C krosnelėje 8 val. arba 80–90 °C ant P1S pagrindo 12 val..

### 3.7. Verslo idėjos

- **Individualizuoti ortopediniai sprendimai:** Vidpadžių gamyba pagal pėdos skeną.
- **Skubus pramoninis remontas:** On-demand tarpinių ir sandariklių gamyba gamybos linijoms.
- **Aukšto lygio RC sportas:** Specializuotų padangų spausdinimas naudojant „VarioShore“ technologiją.
- **Taktinė įranga:** Nedūžtančių dėklų ir laikiklių gamyba ekstremalioms sąlygoms.

---

### Šaltinių turinys (TPU)

1. **AMFG TPU Guide:** Techninė sudėtis, elastomero savybės ir pramoninis pritaikymas. [Puslapis 1183, 1185-1187].
2. **Bambu Lab Filament Guide:** P1S suderinamumas, AMS apribojimai ir temperatūriniai nustatymai. [Puslapis 679, 685, 689, 1492].
3. **Filament Drying Recommendations:** Išsamios TPU džiovinimo instrukcijos naudojant P1S. [Puslapis 662, 698].
4. **Zack Freedman Tier List:** TPU kaip „nesunaikinamos“ medžiagos statusas ir kietumo (Shore) palyginimas. [Puslapis 1265-1267].
5. **Frankly Built Testing:** TPU elasticity ir atsparumo testai (Iron Man projekto kontekste). [Puslapis 1216, 1223].
6. **Bambu Lab Wiki - Quality Problems:** TPU spausdinimo greičio ir užsikimšimų prevencija. [Puslapis 397, 417].
7. **3D Printer Filament Prices 2025:** Didmeninių ir mažmeninių TPU kainų analizė rinkoje. [Puslapis 59, 1036].
8. **Siraya Tech Bulk Catalog:** Specializuotų TPU (95A, 64D) techniniai duomenys. [Puslapis 285, 289].
9. **Polymaker TDS:** PolyFlex TPU serijos mechaniniai duomenys (Z-axis strength, Tensile modulus). [Puslapis 563, 569].
10. **UL Research Report:** VOC emisijų tyrimas spausdinant lanksčius polimerus. [Puslapis 33, 35].
