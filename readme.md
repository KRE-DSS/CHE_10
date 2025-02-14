<!--
author:   KRE-DSS

email:    

version:  0.1

language: de

narrator: Deutsch Female

classroom: disable

mode: Presentation

import: https://github.com/LiaTemplates/KekuleJS/blob/master/README.md

-->

# Vom Alkohol zum Aromastoff

[![Shield](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

## So benutzt du das Lernprogramm

**Herzlich Willkommen**

Dieses „Buch“ soll für dich einen roten Faden bilden, an dem du dich durch alle Teilbereiche der Säure-Base-Chemie entlanghangeln kannst. Es eignet sich als Arbeitsbuch während des Unterrichts, z. B. in Phasen der Einzel-, Partner- oder Gruppenarbeit. Du kannst es aber auch verwenden um dir Inhalte selbstständig zu erarbeiten, z. B. in EVA-Stunden oder wenn du mal krank warst oder vom Unterricht befreit warst.

**Wie du richtig mit diesem Buch arbeitest**

Ein Buch, egal ob klassisches Schulbuch oder interaktives Arbeitsbuch sind KEIN Ersatz für eigene Aufzeichnungen und Mitschriften. Beachte also folgende Tipps:

- Mache eigene Unterrichtsnotizen. Du kannst mit Texten ausgehend von deinen eigenen Gedanken besser lernen, als mit fremden Texten.
- Kopiere gerne einzelne Sätze oder ganze Absätze aus diesem Buch in deine Notizen, wenn es dir hilfreich erscheint. Markiere oder Kommentiere diese aber.
- Arbeite die Checklisten und Übungen im Buch durch. Kopiere Screenshots von deinen Ergebnissen und speichere diese in deinen Notize
- Wenn du Fehler, z. B. in Übungen gemacht hast, kopiere einen Screenshot mit den Fehlern in deine Notizen und kommentiere deine Verbesserung. Daraus lernst du. Fehler zu machen ist in der Lernphase gut und wichtig - ebenso wie die Auseinandersetzung damit.

## Was passiert mit Alkohol im Körper?

Wenn wir im Alltag von Alkohol sprechen, meinen wir immer einen ganz bestimmten Alkohol: **Ethanol**
Das Ethanol-Molekül besitzt die Summenformel $C_{2}H_{5}OH$.

Ethanol ist ein Zellgift. Das bedeutet, es schadet den Zellen im Körper und muss abgebaut werden. Das geschieht in den Zellen der Leber. Nachdem die maximale Alkoholkonzentration im Blut erreicht wurde, sinkt die Blutalkohol-Konzentration um ca. 0,1 - 0,2 ‰ pro Stunde. Es ist nicht möglich die Geschwindigkeit des Abbaus zu beeinflussen.

### Der erste Schritt des Alkoholabbaus

In den Leberzellen existiert ein Enzym mit dem Namen Alkohol-Dehydrogenase (ADH). Es katalysiert eine Reaktion von Ethanol-Molekülen zu Ethanal/Molekülen.

> **Aufgabe**
> Vergleiche den molekularen Aufbau des Ethanol-Moleküls mit dem Ethanal-Molekül. Gehe dabei besonders auf die Unterschiede zwischen den beiden Molekülen ein.

``` text @Kekule.load3d(mol)
702
  -OEChem-01302504523D

  9  8  0     0  0  0  0  0  0999 V2000
   -1.1712    0.2997    0.0000 O   0  0  0  0  0  0  0  0  0  0  0  0
   -0.0463   -0.5665    0.0000 C   0  0  0  0  0  0  0  0  0  0  0  0
    1.2175    0.2668    0.0000 C   0  0  0  0  0  0  0  0  0  0  0  0
   -0.0958   -1.2120    0.8819 H   0  0  0  0  0  0  0  0  0  0  0  0
   -0.0952   -1.1938   -0.8946 H   0  0  0  0  0  0  0  0  0  0  0  0
    2.1050   -0.3720   -0.0177 H   0  0  0  0  0  0  0  0  0  0  0  0
    1.2426    0.9307   -0.8704 H   0  0  0  0  0  0  0  0  0  0  0  0
    1.2616    0.9052    0.8886 H   0  0  0  0  0  0  0  0  0  0  0  0
   -1.1291    0.8364    0.8099 H   0  0  0  0  0  0  0  0  0  0  0  0
  1  2  1  0  0  0  0
  1  9  1  0  0  0  0
  2  3  1  0  0  0  0
  2  4  1  0  0  0  0
  2  5  1  0  0  0  0
  3  6  1  0  0  0  0
  3  7  1  0  0  0  0
  3  8  1  0  0  0  0
M  END
```

``` text @Kekule.load3d(mol)
177
  -OEChem-02142504313D

  7  6  0     0  0  0  0  0  0999 V2000
    1.1443    0.2412    0.0000 O   0  0  0  0  0  0  0  0  0  0  0  0
   -1.2574    0.1815    0.0000 C   0  0  0  0  0  0  0  0  0  0  0  0
    0.1130   -0.4226    0.0000 C   0  0  0  0  0  0  0  0  0  0  0  0
   -1.7938   -0.1493    0.8924 H   0  0  0  0  0  0  0  0  0  0  0  0
   -1.1865    1.2719    0.0016 H   0  0  0  0  0  0  0  0  0  0  0  0
   -1.7928   -0.1468   -0.8938 H   0  0  0  0  0  0  0  0  0  0  0  0
    0.1478   -1.5252   -0.0007 H   0  0  0  0  0  0  0  0  0  0  0  0
  1  3  2  0  0  0  0
  2  3  1  0  0  0  0
  2  4  1  0  0  0  0
  2  5  1  0  0  0  0
  2  6  1  0  0  0  0
  3  7  1  0  0  0  0
M  END
```


