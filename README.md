# Taschenrechner – IntelliJ GUI Designer
Author: Sara Kutschi <br>
LBS Eibiswald | 2aAPC

Ein kleines Java-Projekt mit grafischer Oberfläche: ein **Taschenrechner**, erstellt mit dem *IntelliJ GUI Designer*.  
Du kannst Zahlen eingeben, Grundrechenarten (+, -, ×, ÷) ausführen, Vorzeichen ändern, löschen und Ergebnisse direkt im Anzeigefeld sehen.  
Nach der Anleitung: [IntelliJ GUI Designer Example](https://examples.javacodegeeks.com/desktop-java/ide/intellij-gui-designer-example/)

---

## Umsetzung

### 1) Neues GUI-Form anlegen
- In IntelliJ: `File ▸ New ▸ GUI Form`
- Namen und Klasse vergeben (`Calculator`)
- Layout-Manager auswählen (z. B. `GridLayoutManager`)
- IntelliJ erzeugt `.form` + `.java` Datei

![Neues Form anlegen](./Images/Screenshot%202025-09-18%20114747.jpg)

---

### 2) Oberfläche entwerfen
- Oben ein **JTextField** für die Anzeige (`results`)  
- Darunter ein **Grid** mit Buttons (0–9, +, -, *, /, =, AC, +/-, , )  
- Buttons sprechend benennen (z. B. `oneBtn`, `plusBtn`)

![GUI-Designer Oberfläche](./Images/Screenshot%202025-09-21%20121506.jpg)

---

## Ergebnis

**Laufender Taschenrechner**

![App Screenshot](./Images/Screenshot%202025-09-18%20121936.jpg)

---

## Fazit
Mit dem **GUI-Designer von IntelliJ** lassen sich schnell grafische Oberflächen entwerfen.  
Die *Bound Class* verbindet Design und Logik → ideal für **Swing-Demos** wie diesen Taschenrechner.  
