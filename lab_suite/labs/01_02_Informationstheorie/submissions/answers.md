# Fragebogen: Entropie-Analyse (entropy1.py)

Nach dem Ausführen von `entropy1.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

Number of characters: 1307
Character Dictionary: {'A': 7, 'u': 29, 'f': 21, 'g': 34, 'a': 55, 'b': 22, 'e': 165, ':': 3, ' ': 143, 'E': 4, 'n': 103, 't': 79, 'r': 59, 'o': 48, 'p': 19, 'i': 80, '-': 2, 'l': 38, 'y': 9, 's': 62, 'm': 26, '1': 4, '.': 20, '\n': 19, 'W': 3, 'c': 23, 'h': 24, 'd': 35, 'S': 6, 'k': 9, '?': 3, 'D': 5, 'x': 11, '(': 7, 'O': 2, 'w': 8, ')': 7, ',': 4, 'z': 9, 'Ã': 14, '¤': 5, 'H': 1, 'j': 1, 'Z': 5, 'I': 4, '/': 6, 'G': 1, 'K': 7, '_': 6, 'T': 3, '–': 3, '0': 2, '2': 1, 'â': 7, '€': 7, '¯': 1, 'B': 3, 'L': 2, 'N': 1, '“': 2, 'F': 3, '¶': 1, 'ž': 2, 'œ': 2, '¼': 5, 'M': 1, 'v': 3, 'V': 1}

-------Table of characters:----------------
 e     | cnt=165    p=0.126   H=2.986 bit/char  H_av=0.377 bit/char
       | cnt=143    p=0.109   H=3.192 bit/char  H_av=0.349 bit/char
 n     | cnt=103    p=0.079   H=3.666 bit/char  H_av=0.289 bit/char
 i     | cnt= 80    p=0.061   H=4.030 bit/char  H_av=0.247 bit/char
 t     | cnt= 79    p=0.060   H=4.048 bit/char  H_av=0.245 bit/char
 s     | cnt= 62    p=0.047   H=4.398 bit/char  H_av=0.209 bit/char
 r     | cnt= 59    p=0.045   H=4.469 bit/char  H_av=0.202 bit/char
 a     | cnt= 55    p=0.042   H=4.571 bit/char  H_av=0.192 bit/char
 o     | cnt= 48    p=0.037   H=4.767 bit/char  H_av=0.175 bit/char
 l     | cnt= 38    p=0.029   H=5.104 bit/char  H_av=0.148 bit/char
 d     | cnt= 35    p=0.027   H=5.223 bit/char  H_av=0.140 bit/char
 g     | cnt= 34    p=0.026   H=5.265 bit/char  H_av=0.137 bit/char
 u     | cnt= 29    p=0.022   H=5.494 bit/char  H_av=0.122 bit/char
 m     | cnt= 26    p=0.020   H=5.652 bit/char  H_av=0.112 bit/char
 h     | cnt= 24    p=0.018   H=5.767 bit/char  H_av=0.106 bit/char
 c     | cnt= 23    p=0.018   H=5.828 bit/char  H_av=0.103 bit/char
 b     | cnt= 22    p=0.017   H=5.893 bit/char  H_av=0.099 bit/char
 f     | cnt= 21    p=0.016   H=5.960 bit/char  H_av=0.096 bit/char
 .     | cnt= 20    p=0.015   H=6.030 bit/char  H_av=0.092 bit/char
 p     | cnt= 19    p=0.015   H=6.104 bit/char  H_av=0.089 bit/char
 b'\n' | cnt= 19    p=0.015   H=6.104 bit/char  H_av=0.089 bit/char
 Ã     | cnt= 14    p=0.011   H=6.545 bit/char  H_av=0.070 bit/char
 x     | cnt= 11    p=0.008   H=6.893 bit/char  H_av=0.058 bit/char
 y     | cnt=  9    p=0.007   H=7.182 bit/char  H_av=0.049 bit/char
 k     | cnt=  9    p=0.007   H=7.182 bit/char  H_av=0.049 bit/char
 z     | cnt=  9    p=0.007   H=7.182 bit/char  H_av=0.049 bit/char
 w     | cnt=  8    p=0.006   H=7.352 bit/char  H_av=0.045 bit/char
 A     | cnt=  7    p=0.005   H=7.545 bit/char  H_av=0.040 bit/char
 (     | cnt=  7    p=0.005   H=7.545 bit/char  H_av=0.040 bit/char
 )     | cnt=  7    p=0.005   H=7.545 bit/char  H_av=0.040 bit/char
 K     | cnt=  7    p=0.005   H=7.545 bit/char  H_av=0.040 bit/char
 â     | cnt=  7    p=0.005   H=7.545 bit/char  H_av=0.040 bit/char
 €     | cnt=  7    p=0.005   H=7.545 bit/char  H_av=0.040 bit/char
 S     | cnt=  6    p=0.005   H=7.767 bit/char  H_av=0.036 bit/char
 /     | cnt=  6    p=0.005   H=7.767 bit/char  H_av=0.036 bit/char
 _     | cnt=  6    p=0.005   H=7.767 bit/char  H_av=0.036 bit/char
 D     | cnt=  5    p=0.004   H=8.030 bit/char  H_av=0.031 bit/char
 ¤     | cnt=  5    p=0.004   H=8.030 bit/char  H_av=0.031 bit/char
 Z     | cnt=  5    p=0.004   H=8.030 bit/char  H_av=0.031 bit/char
 ¼     | cnt=  5    p=0.004   H=8.030 bit/char  H_av=0.031 bit/char
 E     | cnt=  4    p=0.003   H=8.352 bit/char  H_av=0.026 bit/char
 1     | cnt=  4    p=0.003   H=8.352 bit/char  H_av=0.026 bit/char
 ,     | cnt=  4    p=0.003   H=8.352 bit/char  H_av=0.026 bit/char
 I     | cnt=  4    p=0.003   H=8.352 bit/char  H_av=0.026 bit/char
 :     | cnt=  3    p=0.002   H=8.767 bit/char  H_av=0.020 bit/char
 W     | cnt=  3    p=0.002   H=8.767 bit/char  H_av=0.020 bit/char
 ?     | cnt=  3    p=0.002   H=8.767 bit/char  H_av=0.020 bit/char
 T     | cnt=  3    p=0.002   H=8.767 bit/char  H_av=0.020 bit/char
 –     | cnt=  3    p=0.002   H=8.767 bit/char  H_av=0.020 bit/char
 B     | cnt=  3    p=0.002   H=8.767 bit/char  H_av=0.020 bit/char
 F     | cnt=  3    p=0.002   H=8.767 bit/char  H_av=0.020 bit/char
 v     | cnt=  3    p=0.002   H=8.767 bit/char  H_av=0.020 bit/char
 -     | cnt=  2    p=0.002   H=9.352 bit/char  H_av=0.014 bit/char
 O     | cnt=  2    p=0.002   H=9.352 bit/char  H_av=0.014 bit/char
 0     | cnt=  2    p=0.002   H=9.352 bit/char  H_av=0.014 bit/char
 L     | cnt=  2    p=0.002   H=9.352 bit/char  H_av=0.014 bit/char
 “     | cnt=  2    p=0.002   H=9.352 bit/char  H_av=0.014 bit/char
 ž     | cnt=  2    p=0.002   H=9.352 bit/char  H_av=0.014 bit/char
 œ     | cnt=  2    p=0.002   H=9.352 bit/char  H_av=0.014 bit/char
 H     | cnt=  1    p=0.001   H=10.352 bit/char  H_av=0.008 bit/char
 j     | cnt=  1    p=0.001   H=10.352 bit/char  H_av=0.008 bit/char
 G     | cnt=  1    p=0.001   H=10.352 bit/char  H_av=0.008 bit/char
 2     | cnt=  1    p=0.001   H=10.352 bit/char  H_av=0.008 bit/char
 ¯     | cnt=  1    p=0.001   H=10.352 bit/char  H_av=0.008 bit/char
 N     | cnt=  1    p=0.001   H=10.352 bit/char  H_av=0.008 bit/char
 ¶     | cnt=  1    p=0.001   H=10.352 bit/char  H_av=0.008 bit/char
 M     | cnt=  1    p=0.001   H=10.352 bit/char  H_av=0.008 bit/char
 V     | cnt=  1    p=0.001   H=10.352 bit/char  H_av=0.008 bit/char
-------------------------------------------

Average Entropy H = 4.845 bit/char
Total Entropy of 1307 characters H=6332.90 bit = 792.00 byte
---

Number of characters: 235
Character Dictionary: {'a': 21, 'n': 14, 'd': 16, 'v': 11, 'e': 1, 'w': 1, 'f': 6, 'h': 6, 's': 7, 'i': 3, 'u': 3, 'j': 4, 'l': 4, 'g': 3, 'b': 2, 'Ã': 9, '¶': 3, 'p': 1, '\n': 2, 'A': 11, 'G': 15, 'E': 10, 'K': 9, 'C': 1, 'B': 2, 'L': 6, 'H': 4, 'S': 2, 'D': 4, 'J': 3, 'O': 3, 'U': 2, 'Z': 2, 'I': 2, '–': 3, 'V': 2, '!': 1, '"': 1, 'Â': 1, '§': 1, '$': 2, '%': 2, 'R': 3, 'T': 3, '&': 2, '/': 2, '(': 2, ')': 2, '=': 2, 'P': 2, '?': 2, 'œ': 2, 'W': 1, 'F': 2, '„': 1, '*': 1, 'X': 1, 'Y': 1}

-------Table of characters:----------------
 a     | cnt= 21    p=0.089   H=3.484 bit/char  H_av=0.311 bit/char
 d     | cnt= 16    p=0.068   H=3.877 bit/char  H_av=0.264 bit/char
 G     | cnt= 15    p=0.064   H=3.970 bit/char  H_av=0.253 bit/char
 n     | cnt= 14    p=0.060   H=4.069 bit/char  H_av=0.242 bit/char
 v     | cnt= 11    p=0.047   H=4.417 bit/char  H_av=0.207 bit/char
 A     | cnt= 11    p=0.047   H=4.417 bit/char  H_av=0.207 bit/char
 E     | cnt= 10    p=0.043   H=4.555 bit/char  H_av=0.194 bit/char
 Ã     | cnt=  9    p=0.038   H=4.707 bit/char  H_av=0.180 bit/char
 K     | cnt=  9    p=0.038   H=4.707 bit/char  H_av=0.180 bit/char
 s     | cnt=  7    p=0.030   H=5.069 bit/char  H_av=0.151 bit/char
 f     | cnt=  6    p=0.026   H=5.292 bit/char  H_av=0.135 bit/char
 h     | cnt=  6    p=0.026   H=5.292 bit/char  H_av=0.135 bit/char
 L     | cnt=  6    p=0.026   H=5.292 bit/char  H_av=0.135 bit/char
 j     | cnt=  4    p=0.017   H=5.877 bit/char  H_av=0.100 bit/char
 l     | cnt=  4    p=0.017   H=5.877 bit/char  H_av=0.100 bit/char
 H     | cnt=  4    p=0.017   H=5.877 bit/char  H_av=0.100 bit/char
 D     | cnt=  4    p=0.017   H=5.877 bit/char  H_av=0.100 bit/char
 i     | cnt=  3    p=0.013   H=6.292 bit/char  H_av=0.080 bit/char
 u     | cnt=  3    p=0.013   H=6.292 bit/char  H_av=0.080 bit/char
 g     | cnt=  3    p=0.013   H=6.292 bit/char  H_av=0.080 bit/char
 ¶     | cnt=  3    p=0.013   H=6.292 bit/char  H_av=0.080 bit/char
 J     | cnt=  3    p=0.013   H=6.292 bit/char  H_av=0.080 bit/char
 O     | cnt=  3    p=0.013   H=6.292 bit/char  H_av=0.080 bit/char
 –     | cnt=  3    p=0.013   H=6.292 bit/char  H_av=0.080 bit/char
 R     | cnt=  3    p=0.013   H=6.292 bit/char  H_av=0.080 bit/char
 T     | cnt=  3    p=0.013   H=6.292 bit/char  H_av=0.080 bit/char
 b     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 b'\n' | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 B     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 S     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 U     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 Z     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 I     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 V     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 $     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 %     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 &     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 /     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 (     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 )     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 =     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 P     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 ?     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 œ     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 F     | cnt=  2    p=0.009   H=6.877 bit/char  H_av=0.059 bit/char
 e     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 w     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 p     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 C     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 !     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 "     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 Â     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 §     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 W     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 „     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 *     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 X     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
 Y     | cnt=  1    p=0.004   H=7.877 bit/char  H_av=0.034 bit/char
-------------------------------------------

Average Entropy H = 5.266 bit/char
Total Entropy of 235 characters H=1237.48 bit = 155.00 byte

---------

**2. Deine Kommentierung:**

- Was fällt dir bei der Entropie deines Textes auf?  
  *[z. B. Vergleich mit anderen Texten, Zeichenverteilung, Redundanz]*

Text 1: Aufgabenstellung
Text 2: zufällige Buchstabeneingabe

Obwohl der Zufallstext viel kürzer ist, liegt seine durchschnittliche Entropie mit 5,27 Bit deutlich über der Aufgabenstellung (4,85 Bit), weil das mathematische "Chaos" zunimmt und Zeichen weniger vorhersagbar sind. Während das "e" im ersten Text als häufigster Buchstabe sehr wahrscheinlich war (nur ca. 3 Bit), wird es im Zufallstext durch sein seltenes Vorkommen zu einem hoch-informativen Buchstaben mit fast 8 Bit. Im zweiten Text schwindet die typische Struktur natürlicher Sprache, was ihn für uns zwar sinnlos macht, für die Statistik aber gehaltvoller pro Zeichen erscheinen lässt. Die Auswertung des Angabetexts deckt sich mit der Wahrscheinlichkeitsverteilung der deuztschen Sprache aus dem Skript, wobei "e", "r" und Leerzeichen am häufigsten vorkommen.