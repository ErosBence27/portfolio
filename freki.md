# FrekiSzámoló

---

## Bevezetés

A FrekiSzámoló egy egyszerű eszköz, amely lehetővé teszi a rezonanciafrekvencia kiszámítását az induktivitás (L) és a kapacitás (C) értékei alapján. Ez a számítás különösen hasznos lehet LC-oszcillátorok és szűrők tervezésénél.

---

## Képlet

A rezonanciafrekvenciát az alábbi képlet adja meg:

\[
f = \frac{1}{2\pi\sqrt{L \cdot C}}
\]

ahol:
- **f** a rezonanciafrekvencia (Hz)
- **L** az induktivitás (H)
- **C** a kapacitás (F)

![Rezonanciafrekvencia képlet](img/Rezonancia+frekvencia.jpg)

---

## Használat

### Lépések:
1. Add meg az induktivitás értékét (L) mikrohenry-ben (µH).
2. Add meg a kapacitás értékét (C) mikrofarád-ban (µF).
3. Kattints az **ENTER** gombra a számításhoz.

A program a megadott értékeket átváltja henry (H) és farád (F) egységbe, elvégzi a számítást, és megjeleníti az eredményt Hz-ben.

---

## Példa

### Bemeneti értékek:
- **L** = 10 µH
- **C** = 100 µF

### Számítás menete:
1. Az induktivitást henry-be konvertáljuk: \(L = 10 \cdot 10^{-6} H\).
2. A kapacitást farád-ba konvertáljuk: \(C = 100 \cdot 10^{-6} F\).
3. Számítjuk a \(L \cdot C\)-t:  
   \(L \cdot C = 10^{-6} \cdot 10^{-4} = 10^{-10}\)
4. Gyököt vonunk: \(\sqrt{L \cdot C} = \sqrt{10^{-10}} = 10^{-5}\).
5. Többszörözzük \(2\pi\)-vel, majd vesszük az inverzét:
   \[f = \frac{1}{2 \pi \cdot 10^{-5}} = 15.92 kHz\]

### Kimenet:
- **Freki = 15.92 kHz**
