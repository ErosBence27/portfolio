# Astabil Multivibrátor

---

## Bevezetés

Egy kis bemutatással készültem a multivibrátorokról, hogy milyen alkatrésszel és milyen módon valósítottuk meg ezt az astabil multivibrátort.

Az astabil multivibrátor egy olyan oszcillátor, amely két állapot között folyamatosan váltakozik, és mindkét állapotban időt tölt. Tipikus alkalmazási területei közé tartoznak a LED villogtatók, a jelgenerátorok és az időzítő áramkörök. Ezek a multivibrátoroknak még 2 fajtája van: monostabil és bistabil multivibrátor.

![Multivibrátorok](img/multivibrátorok.jpg)

---

## Alkatrészek

### Felhasznált alkatrészek:
- 4 db ellenállás
- 2 db kondenzátor
- 2 db tranzisztor
- 2 db LED

### Az alkatrészek értékei:
1. R1 = 675 Ω
2. R2 = 670 Ω
3. R3 = 29.62 Ω
4. R4 = 29.52 Ω
5. 2 × 47 µF

### Alkatrészek kiválasztása:
Az ellenállások értékei úgy lettek meghatározva, hogy a LED-ek megfelelő fényerővel világítsanak, anélkül, hogy túl nagy áram folyna rajtuk. A kondenzátorok értéke határozza meg az oszcilláció sebességét, míg a tranzisztorok kapcsolási elemekként működnek.

---

## Kapcsolási rajz

Kapcsolási rajz, ami szerint készítettem:

![Kapcsolási rajz](img/astabil%20rajz.png)

### Az áramkör működése:
Az áramkör két tranzisztorból áll, amelyek egymást felváltva kapcsolják be és ki. A kondenzátorok felelősek az időzítésért, míg az ellenállások a tranzisztorok áramát korlátozzák. Az áramkör folyamatosan váltogatja a LED-ek világítását.

---

## Folyamat képekben

### Az elejéről:

![Első kép](img/Elso%20kep%20multi.jpg)

Ez a kép azt mutatja, hogy hogyan kezdtem az építést, az alkatrészek elhelyezésével.

### Összeszerelt állapot:

**Elölnézet:**  
![Elölnézet](img/összerakva%20előröl.jpg)

**Oldalnézet:**  
![Oldalnézet](img/osszerakva%20oldalrol.jpg)

A képek az áramkör összeállított állapotát mutatják, különböző nézőpontokból.

### Üzem közben:

**Piros LED világít:**  
![Piros LED](img/vilagit%20piros.jpg)

**Kék LED világít:**  
![Kék LED](img/vilagit%20kek.jpg)

A két LED felváltva villog, demonstrálva az áramkör működését.

### Az összeforrasztott áramkör:

**Felülnézet:**  
![Felülnézet](img/forrasztas%20felulrol.jpg)

**Oldalnézet:**  
![Oldalnézet](img/forrasztas%20oldalrol.jpg)

Az összeforrasztott áramkör végleges állapotban van, felül- és oldalnézetből.

### Videó:

<video src="img/20221110_200618.mp4" autoplay muted loop width="500" height="290"></video>

---

## Élmények és tapasztalatok

Én az elkészített áramkörömnek személy szerint nagyon örültem, mert ez volt az első. Az elején nem tűnt olyan nehéznek a kapcsolási rajz alapján.  
Mint minden szakmabelinek, nekem is voltak nehézségeim, főként a forrasztás terén. De végül sikerült megépítenem.

### Tapasztalatok:
- Nem szabad semmit sem elkapkodni, mert azzal csak magamnak csinálok rosszat. Egy elkapkodott munkát újra kellett kezdenem.
- Fontos volt megtanulni az alkatrészek megfelelő elrendezését és a forrasztási technikák alkalmazását.

### Amit élveztem:
- Az első áramkörépítésem során különösen tetszett, hogy kézzelfogható dolgot tudtam alkotni.
- Megtanultam, hogyan lehet az elméletet gyakorlattá alakítani.

### Hibák és tanulságok:
- Az első próbálkozásnál rosszul helyeztem el néhány alkatrészt, ami miatt újra kellett kezdenem a forrasztást.
- Megtanultam, hogy mindig ellenőrizni kell az áramkör működését lépésről lépésre.
