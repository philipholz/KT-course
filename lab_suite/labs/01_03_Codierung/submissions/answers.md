# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

Enter the string to compute Huffman Code Tree: ASDFGHJKJHGFDSASASASASASGGGGGBBVBV
---------------------------------------------------------
Dictionary of Characters with char frequency:       {'A': 6, 'S': 7, 'D': 2, 'F': 2, 'G': 7, 'H': 2, 'J': 2, 'K': 1, 'B': 3, 'V': 2}
Dictionary converted into a list:                   dict_items([('A', 6), ('S', 7), ('D', 2), ('F', 2), ('G', 7), ('H', 2), ('J', 2), ('K', 1), ('B', 3), ('V', 2)])
List of characters sorted to descending frequency:  [('S', 7), ('G', 7), ('A', 6), ('B', 3), ('D', 2), ('F', 2), ('H', 2), ('J', 2), ('V', 2), ('K', 1)]
Huffman Code Dictionary:                            {'G': '00', 'S': '01', 'F': '1000', 'D': '1001', 'J': '1010', 'H': '1011', 'K': '11000', 'V': '11001', 'B': '1101', 'A': '111'}

 Char | Huffman code
----------------------
 'S'  |          01
 'G'  |          00
 'A'  |         111
 'B'  |        1101
 'D'  |        1001
 'F'  |        1000
 'H'  |        1011
 'J'  |        1010
 'V'  |       11001
 'K'  |       11000

---

**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?  

  Die Codes zeigen eine Binärkodierung mit absteigender Zeichenwahrscheinlichkeit. Aufgrund der Baumstruktur hat kein Code der Anfang eines anderen ist (z. B. fängt kein anderer Buchstabe mit 01 an, außer das 'S'). Dadurch kann die Bitfolge später wieder eindeutig in Buchstaben zurückübersetzt werden.

- Warum haben häufigere Zeichen kürzere Codewörter?  
  
  Es wird eine Binärbaum aller vorkommenden Zeichen erstellt, die jeweils per 0/1 erreicht werden. Um Speicherplatz zu sparen, wird die Codierung immer kürzer, je öfter ein Zeichen vorkommt.
