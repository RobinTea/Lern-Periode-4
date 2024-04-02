# Lernperiode 4

Robin Taing

20.02.24 - 02.04.2024

## Grob-Planung
Uns wurde in der letzten Lernperiode mitgeteilt, dass wir eine Webseite auf Github erstellen kann. In dieser Lernperiode habe ich vor mich mit html, css und Javascript auseinander zu setzen. Ich möchte Tabellen, Knöpfe und ein Menü erstellen. Wenn dies erflogreich (oder nicht) verfolgte, werde ich versuchen Bilder hinzu zu fügen.

Mein Ziel ist es zu Experimentieren und mich für das nächste Jahr vorbereiten.

## 27.02.2024

(code in file with date)

07:30 Ich komme in den Unterricht und setze mich hin.   
07:45 Der Input von Herr Colic ist fertig und ich fange an, die Webseite auf Github aufzusetzen  
08:00 Dank Tutorial im Internet (notfalls meine Kollegen) konnte ich die Webseite aufsetzen und fange an ein Texteditor zu installieren  
08:15 Ich habe mich für Visual Studio Code entschieden, und werde nun die erweiterung "im Browser öffnen" installieren  
08:30 Ich fange an die ersten Zeilen in html zu schreiben.  
09:30 Pause  
09:45 Ich versuche mit css den Text farbig zu machen
10:00 falls ich keine verspätung (fehler) habe und keine Bugs aufgetreten sind werde ich daran arbeiten, Buttons oder Bilder hinzuzufügen  
11:00 Ich arbeite an meiner Dokumentation  

used in this session:  
https://www.w3schools.com/html/default.asp  
https://www.youtube.com/watch?v=Z4pCqK-V_Wo

- [x] html Text
- [x] den Text farbig machen
- [x] Bild einfügen
- [ ] den Text auf der Webseite veröffentlichen

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 1               |  funktioniert        |   funktioniert |     gut        |  👍      |
| 2               | Programm in Browser geöffnet          | Text Rot       |Robin ist happy             |    yes      |

## 05.03.2024

- [x] svg tutorial https://www.w3schools.com/graphics/svg_animation.asp / https://www.youtube.com/watch?v=UgIwjLg4ONk (zu schwierig im moment)
- [ ] Menu (wenn es geht) https://www.youtube.com/watch?v=NQSeLm7MqtA / https://www.youtube.com/watch?v=2DVkNvVcQAU
- [ ] content, paddle, border, margin vertraut machen (min2 "Boxen" erstellen)
- [ ] Paging und Struktur von Github anschauen https://docs.github.com/de/pages

Für das erste Arbeitspaket habe ich einen Roten Kreis mit svg gemacht und versucht ihn hin und her zu bewegen. Am Anfang dachte ich es bräuchte zwei <animate/> blöcke dafür. Später fand ich heraus das es mit nur einem einzigen funktionniert.
Ich war dann daran interessiert wie der Code funktioniert. Da im w3 Tutorial dies nicht sher ausführlich erklährt war, musste ich mich an Ai wenden. Mithilfe der Ai konnte ich den Code verstehen. Ich hatte sehr viel spass daran den roten Kreis zu verändern und ihn zu "animieren". Weil die Zeit so schnell lief, war es nicht mehr möglich die anderen Arbeitspakete zu lösen. Jedoch habe ich in dieser Periode sehr viel gelernt.

## 12.03.24

- [x] Schlangen artiges Ding erstellen 
- [x] TV Text der an den Wänden abprallt
- [ ] herausfinden was Copilot gemacht hat

Drei Kreise wurden nahe aneinander gesezt und bewegen sich versetzt nach Links und Rechts. Ich verstehe immer noch nicht wieso es diesen abstand zwischen den Kreisen gibt. Ich wollte jedoch nicht nur bewegende Kreise haben. Ich wollte einen Text der von den Wänden abprallt und immer weiter geht. Er soll diagonal gehen um es spannender zu machen. Es gab keine genaue Anleitungen und nach langem versuchen habe Copilot (KI von Microsoft) gefragt. Er gab mir einen funktionierenden Code. Ich verstehe den Mathe Teil noch nicht ganz aber das entziffern kommt gut voran. 

für das nächste mal: https://www.w3schools.com/graphics/svg_scripting.asp

Es ist das erste Mal, dass ich js benutzt habe. Ich werde versuchen mehr damit zu arbeiten.

## 19.03.2024

- [x] Buttons und ihre Funktionen
- [ ] https://www.w3schools.com/graphics/svg_scripting.asp
- [x] Google maps

![image](https://github.com/RobinTea/Lern-Periode-4/assets/142886484/a4aaf88d-49dd-403f-a609-6d5ad1f7ed34)

Bankdaten müssen angegeben werden. Habe ich nicht gemacht

![image](https://github.com/RobinTea/Lern-Periode-4/assets/142886484/e1bc16f1-42bb-422c-accb-811d33d9e6ec)

Ein Button wurde erstellt. Wenn man mit dem Cursor darüber geht verändert sich der Button.

Liste von Links im Ordner 19.03.24

## 26.03.24

- [x] Leiste am oberen Rand erstellen (min. 2 Links oben)
- [x] disply: felx; (benutzen/ Kennenlernen)
- [x] hover effect verwenden
- [x] ein bild als "logo" hinzufügen

https://fonts.google.com/specimen/Montserrat?query=mont

Ich war sehr erfolgreich mit dem Tutorial und hatte genügend Zeit um viele verschiedene funktionen auszuprobieren. Ich habe es noch nicht geschafft etwas zu verlinken. Nun kann ich auch von Google font Schriftarten importieren.
Wenn man auf einer der Menuoptionen klickt passiert nur der Hover-Effekt, und die Webseite ist noch leer.
Das "Logo" das ich hinzugefügt habe sieht nicht gut aus, das möchte ich verändern.

## 02.04.2024

- [x] Leiste oben mit Mitte abgrenzen
- [x] Leiste sichtbar machen (andere Farbe)
- [ ] Drop-down für menu
- [x] Curser zu pointer wechseln wenn ich über den contact button bin

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 1               |  Webseite offen      | Maus hovert über Menu| liste von Links in Textform |  nein     |

Das erstellen der Leiste hat mir viele Probleme bereitet. Wenn ich ein gewissen Teil der Webseite färben möchte müssen die anderen Elemente es erlauben (keine margin/padding haben). Das Problem wurde ganz einfach aufgehoben indem ich einfach den header eine Farbe zuwies. Beim Drop-down Menu war es jedoch eine Herausforderung diese Funktionen in mein bestehendes Programm zu implementieren. Deshalb werden sie das Programm von heute nur mit der Leiste auffinden. 

## Reflexion
In dieser Lernperiode konnte ich verschiedenen Elementen einer Webseite Kennenlernen. Ich konnte in dieser Zeit vieles herum Experimentieren und ausprobieren ohne gross Zeit zu verschwenden, da dass ja mein Ziel war. Ich kann jetzt stolz sagen, dass ich ein bisschen mehr erfahrung mit html als meine Kollegen habe. Jedoch hatte ich noch nicht die Chance mit Java scipt arbeiten zu können (nur kurz und ein paar zeilen). Ich konnte erfolgreich ein Menu erstellen. und ich habe ein paar animationen zusammen bekommen. meine erste Demoseite sieht sehr farbig aus. Es ist enttäuschend dass ich nicht eine Webseite mit Parallexen Effekt erstellen konnte. Es ist aber auch eine Liga über meinen jetzigen Skills. So kann man diese Lernperiode zusammenfassen:

html? Check. css? naja, mehr oder weniger. java? nicht so sehr, nein.

## VBV
Im vergleich zum letzten mal bin ich viel Produktiver gewesen. Es kann daran legen, dass es weniger Fehler gab. Jedoch sind meine Arbeitpakete nocht nicht gut definiert (zB. Schlangen artiges Ding) Ich werde sie in Zukunft verbessern müssen. Ich muss mehr mit Testfällen arbeiten und sie auch besser Formulieren. Es währe schön wenn ich in Zukunft auch mit Java script arbeiten könnte.
