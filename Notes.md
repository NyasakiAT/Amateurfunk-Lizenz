# Zusammenfassung

[TOC]

## Funktechnik

### Ohm'sches und Kirchhoff'sches Gesetz

| Name        | Formelzeichen | Maßeinheit  |
| ----------- | ------------- | ----------- |
| Spannung    | U             | V (Volt)    |
| Strom       | I             | A (Ampere)  |
| Wiederstand | R             | Ω (Ohm)     |
| Leitwert    | G             | S (Siemens) |



#### Ohm'sches Gesetz

$$
U=I*R
$$

$$
I = \frac{U}{R}
$$

$$
R = \frac{U}{I}
$$



#### Erstes Kirchhoff'sches Gesetz

Bei der Parallelschaltung ist der Gesamtstrom gleich der Summe der Teilströme.
$$
I = I_1 + I_2 + I_3 ...
$$
Der Gesammtwiederstand ist somit:
$$
\frac{I}{R_{Ges}}=\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_3}...
$$



#### Zweites Kirchhoff'sches Gesetz

Bei Reihenschaltung ist die Gesamtspannung gleich der Summe der Teilspannungen.
$$
U_{Ges}=U_1+U_2+U_3...
$$
Der Gesamtwiederstand ist somit:
$$
R_{Ges}=R_1+R_2+R_3...
$$



### Leiter, Halbleiter und Nichtleiter

#### Leiter...

... sind Materialien, die den elektrischen Strom sehr gut leiten
z.B. Alle Metalle, Säuren, Kohlen



#### Halbleiter...

... sind Materialien, die ihre Leitfähigkeit aufgrund physikalischer (Druck, Temperatur, Licht, etc.) oder
elektrischer Einflüsse verändern 
z.B. Silizium, Germanium
(Siehe Frage 22)



#### Nichtleiter...

... sind Materialien, die den elektrischen Strom sehr schlecht leiten
z.B. Kunststoff, Glas, Keramik, Gummi



### Kondensator

| Name             | Formelzeichen | Maßeinheit |
| ---------------- | ------------- | ---------- |
| Blindwiederstand | $X_L$         |            |
| Wirkwiederstand  | R             |            |
| Kapazität        | C             |            |

Bei **Gleichspannung** verhält sich ein Kondensator wie ein Speicher
Bei **Wechselspannung** kommt es durch die dauernde Umladung zu einem Stromfluss 

Je höher die Frequenz, umso grösser der Strom.
Der Blindwiederstand nimmt mit steigender Frequenz ab.



### Spule und Induktivität

| Name         | Formelzeichen | Maßeinheit |
| ------------ | ------------- | ---------- |
| Induktivität | L             |            |

Bei **Gleichspannung** baut der Strom ein Magnetfeld auf,
die Energie ist im Magnetfeld gespeichert.

An **Wechselspannung** kommt es durch die dauernde Ummagnetisierung (Durch Polaritätwechsel) zu einem Stromfluss, der mit steigender Frequenz abnimmt.
Das bedeutet dass der Blindwiederstand $X_L$ mit steigender Frequenz zunimmt.

**Induktivität** bedeutet, das ein Leiter oder Bauteil aufgrund der Änderung des elektrischen Stroms ein Magnetfeld aufbaut das der Stromänderung entgegenwirkt.
$$
X_L = 2 * \pi * f * L
$$


### Wärmeverhalten elektrischer Bauelemente

**PTC (Positive Temperature Coefficient)** 
Erhöht mit steigender Temperatur den widerstand
z.B. Glühwendel einer Glühbirne

**NTC (Negative Temperature Coefficient)** 
Verringert mit steigender Temperatur den widerstand
z.B. Diode zum messen von Temperatur



### Stromquellen

**Primärzellen** sind elektro**chemische** Energiespeicher und können nicht wieder Aufgeladen werden.
**Senkundärzellen** (Akkumulatoren) können fast beliebig oft geladen und entladen werden.

Zwischen den Elektroden befindet sich ein leitfähiger Elektrolyt
Die Spannung hängt von den verwendeten Elementen der Elektroden ab

Beim Akkumulator wird die gespeicherte Ladungsmenge in Amperestunden (Ah) angegeben



### Sinus- und nicht-sinusförmige Signale

**Sinusförmige** Signale haben einen Amplitudenverlauf, der exakt einer mathematischen Sinusfunktion entspricht

**Nicht-sinusförmige** Signale bestehen aus mehreren **Sinus-schwingungen**, und besitzen deshalb einen erheblichen Anteil an Oberwellen (= vielfache Frequenzen der Grundwelle)
*1 Hz = 1 Schwingung pro Sekunde*



### Skin Effect

Jeder leiter stellt eine Induktivität dar, d.h. durch Änderung des elektrischen Stroms
wird ein Magnetfeld aufgebaut, das dieser Stromänderung entgegenwirkt.

Bei höheren Frequenzen wird der Stromfluss durch die Gegeninduktion immer mehr aus der Mitte des Leiters zum Rand hin abgedrängt.
Strom fließt praktisch nur mehr auf der Außenhaut des Leiters (skin).



### Gleich- und Wechselspannung

**Gleichspannung:**
Die Spannung ist konstant, die Polarität verändert sich nicht.

**Wechselspannung:**
Bei Wechselspannung verändert sich die Polarität der Spannung.
Das bekannteste Beispiel ist die 230 Volt-Wechselspannung aus der Steckdose

Der **Spitzen- oder Scheitelwert** ist der größte Betrag der Augenblickswerte eines
Wechselsignals

Der **Spitze-Spitze-Wert** gibt die höhe der Auslenkung vom niedrigsten zum höchsten Wert.
Bei **symmetrischen** Wechselgrößen entspricht der Spitze-Spitze-Wert dem doppelten Maximalwert.

Unter dem **Effektivwert** (root mean square, **RMS**) versteht man die Wurzel aus dem Quadratischen Mittelwert eines zeitlich veränderlichen Signals.
Zu einer Wechselgröße (Wechselstrom, Wechselspannung) gibt der Effektivwert 
denjenigen Wert einer Gleichgröße an, die an einem ohmschen Verbraucher in einer vorgegebenen Zeit dieselbe Leistung umsetzt.
Der Effektivwert hängt sowohl vom Scheitelwert (Amplitude) als auch von der 
Kurvenform ab.

**Periodendauer:** ist jene Zeit bis sich die Periode von neuem wiederholt.

Weitere wichtige Kenngrößen des Wechselstroms sind die **Spannung** (Amplitude),
**Frequenz** (Schwingungen pro Sekunde), **Kurvenform** (Sinus, Dreieck, Rechteck) und
**Strombelastbarkeit** der Quelle.