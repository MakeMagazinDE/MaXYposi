![GitHub Logo](http://www.heise.de/make/icons/make_logo.png)

Maker Media GmbH und c't, Heise Zeitschriften Verlag

***

# MaXYposi

### Schneller 2D/3D-Positionierer und Portalroboter

![Picture](https://github.com/heise/MaXYposi/blob/master/maxyposi.JPG)

Projekt für einen sehr leicht nachzubauenden Portalroboter, der je nach Werkzeug zum Bohren, Fräsen, Bestücken, Lasern oder Folienschneiden geeignet ist. Es verwendet Kunststoff-Gleitlager der Fa. **[igus](http://www.igus.de)**. Bitte beachten Sie unbedingt 

- den Artikel in **[Make: 1/2017](https://shop.heise.de/katalog/make-1-2017)**
- den Artikel in **[Make: 2/2017](https://shop.heise.de/katalog/make-2-2017)**
- das Github-Repository zur **[MaXYposi-Schrittmotorsteuerung](https://github.com/heise/MaXYposi_Grbl_644)**
- unsere **[MaXYPosi-Projektseite](http://www.make-magazin.de/maxyposi)**
- die ständig aktualisierte **[FAQ-Seite](https://heise.de/-3676050)** und das zugehörige Forum.

Zum Öffnen und Bearbeiten der CAD-Datei benötigen Sie das kostenlose [Designspark Mechanical 2.0](https://www.rs-online.com/designspark/mechanical-software) von RS Components. Zur Ansicht der 3D-Vorschau ist ein aktueller Acrobat Reader (ggf. 3D-Ansicht freischalten) nötig, die Vorschau im Github-Browser funktioniert nicht! Zu den anzufertigenden Trägerplatten gibt es bemaßte Zeichnungen sowie Bohrschablonen als "normales" PDF.

### Plan und Stückliste Z-Achse

Der Plan für die Z-Achse ist wegen Maker-Faire-Vorbereitungen noch nicht ganz 
fertig. In der Design-Spark-Zeichnung fehlen noch die Wellenkupplung 5mm/10mm, 
Befestigungsbohrungen und die Bemaßung.

- 1 Linearschlitten SLW-1040, komplett mit Endplatten und Gewindespindel TR10x2
- 1 Aluminium-Rechteckprofil 40x40 mm, 74 mm lang, Wandstärke 2 mm

Wir werden die vollständigen Pläne bis Ende April 2017 nachliefern. 

### Stückliste X-Schlitten

- 1 Phenolharz- oder HPL-Kompaktplatte 120 x 120 mm, 6 mm dick
- 4 [Gehäuselager Igus](https://www.igus.de/wpck/2003/DryLin_W_Doppelschiene) WJ200UM-01-10 (Standard) oder WJUME-01-10 (einstellbares Spiel)
- 4 Abstandsbolzen M3, 12 mm lang, Innen- und Außengewinde kurz oder 
- 4 Distanzhülsen Kunststoff, 12 mm lang (z.B. [Reichelt DK 12MM](https://www.reichelt.de/Distanzhuelsen-etc-/DK-12MM/3/index.html?ACTION=3&LA=446&ARTICLE=44733&GROUPID=7758&artnr=DK+12MM&SEARCH=DK%2B12mm) plus 4 Schrauben M3x20
- 8 Schrauben M6 x 16, Innensechskant
- 2 Schrauben M6 x 25, Innensechskant
- 2 Muttern M6
- 4 Federscheiben DIN 137, M6
- 4 Kotflügel-/Karosseriescheiben 6,4 x 20 mm
- 1 Aluminium-Vierkantstab 10 x 10 mm, insg. 4 Abschnitte je 40 mm lang
- 3 Schrauben M4 x 25
- 3 Muttern M4
- 3 Zahnscheiben (Fächerscheiben), M4
- 2 Kugellager 606-2RS (z.B. [EKugellager](https://www.ekugellager.de) oder [Kugellager-Express](https://www.kugellager-express.de))

### Stückliste XY-Traverse

- 1 [Igus-Linearschiene WS-10-40](https://www.igus.de/wpck/2003/DryLin_W_Doppelschiene), 500 mm lang, **nicht** vorgebohrt
- 2 Phenolharz- oder HPL-Kompaktplatten 150 x 70 mm, 6 mm dick
- 4 [Gehäuselager Igus](https://www.igus.de/wpck/2003/DryLin_W_Doppelschiene) WJ200UM-01-10 oder optional 4 Hybridlagerlager Igus WJRM-01-10 (mit zusätzlichen Rollen) - siehe Anmerkung unten
- 6 Schrauben M6 x 16, Innensechskant
- 6 Schrauben M6 x 25, Innensechskant
- 4 Schrauben M6 x 20, Innensechskant, flacher Kopf
- 2 Schrauben M6 x 50, Innensechskant (70 mm bei WSX-Profil)
- 10 Muttern M6
- 12 Federscheiben DIN 137, M6
- 12 Zahnscheiben (Fächerscheiben), M6
- 12 Kotflügel-/Karosseriescheiben 6,4 x 20 mm (z.B. Hornbach)
- 6 Kugellager 606-2RS
- 2 Abstandsröllchen 18 mm lang, 6,5 mm Innendurchmesser (z.B. Hornbach, Möbelbeschläge, ggf. zusammensetzen)

Bohren der Traverse (Igus WS-10-40-Profil) nach Zeichnung "Bohren_XY-Traverse.pdf". Die Traverse kann auch mit der verstärkten extrahohen igus-Linearschiene WSX-10-40 aufgebaut werden, was bei Längen über 500 mm empfehlenswert ist. Die 6 Befestigungsschrauben sind dann 20 mm länger zu wählen. Die Maße der Trägerplatten ändern sich dadurch nicht. 

Die Igus-Hybridlager WJRM-01-10 haben etwas andere Abmessungen als die Standardlager WJ200UM-01-10 (Lochabstand 22 statt 16 mm). Die zwei Bohrungen an den Enden der Trägerplatte sind hierfür um 6 mm nach außen zu verlegen; die Trägerplatte muss dann 162 x 70 mm groß sein (siehe Bohrschablone "Bohren_Y-Platte_hybrid.pdf").

### Stückliste Grundplatte

Wir haben das Igus WS-10-Profil in der vorgebohrten Ausführung verwendet.

- 2 [Igus-Linearschienen WS-10](https://www.igus.de/wpck/2002/DryLin_W_Einzelschiene_rund), 500 mm lang, vorgebohrt
- 1 Phenolharz- oder HPL-Kompaktplatte 100 x 70 mm, 6 mm dick (z.B. Hornbach)
- 1 MDF- oder Multiplex-Siebdruckplatte, 60 x 60 cm, 22 mm dick
- 2 MDF- oder Multiplex-Siebdruckplatten, 60 x 10 cm, 22 mm dick (Aufstockung für mehr Z-Durchlasshöhe nach Bedarf)
- 6 Schrauben M6 x 16, Innensechskant
- 6 Schrauben M6 x 25, Innensechskant
- 4 Schrauben M6 x 20, Innensechskant, flacher Kopf
- 10 Muttern M6
- 4 Federscheiben DIN 137, M6
- 4 Zahnscheiben (Fächerscheiben), M6
- 4 Kotflügel-/Karosseriescheiben 6,4 x 20 mm
- 2 Kugellager 606-2RS
- 1 Abstandsröllchen 24 mm lang, 6,5 mm Innendurchmesser (z.B. Hornbach, Möbelbeschläge, ggf. zusammensetzen)
- 4 Abstandsröllchen 18 mm lang (z.B. [DK 18MM von Reichelt](https://www.reichelt.de/?ACTION=3;ARTICLE=44736))
- 2 Winkelbeschläge 30 x 60 x 60 mm, (z.B. Lux 492575, div. Baumärkte) (2)
- 20 Spanplattenschrauben Rundkopf 4 x 16 mm (2)
- 4 Spanplattenschrauben Rundkopf 3,5 x 35 mm (2)
- 8 Spanplattenschrauben Senkkopf 3,5 x 40 mm
- 1 Einschlagmutter M6 mit Schraube M6 x 70, Innensechskant (1)

(1) Länge abhängig von Grundplattendicke und Auflage<p>
(2) Länge unkritisch. Spax-Schrauben sollten nur so lang sein, dass sie auf der anderen Seite nicht herausgucken!

### Sonstiges

- 4 m Zahnriemen Profil GT2, 6mm breit, Meterware (3D-Druckerzubehör, div. Shops)
- 2 Zahnriemenräder (Pulley) GT2-Profil, 20 Zähne, für 5-mm-Achse (3D-Druckerzubehör, div. Shops)
- 2 Schrittmotoren Baugröße NEMA17, min. 1,5A Strangstrom, 5 mm Achsdurchmesser, z.B. [ACT 17HS5425](http://www.act-motor.com/product/17hs_en.html)
- 2 Mikroschalter [Marquardt 1050.0202](https://www.marquardt-shop.com/de/produkte/schalter/schnappschalter/1050/1050.0202.html) oder ähnlich, z.B. von [Reichelt](https://www.reichelt.de/?ACTION=3;ARTICLE=166855)

### Alternatives Design mit SLW-1040

Das alternative Design **igus-portal-SLW1040_3.rsdoc** verwendet die fertig aufgebauten Lineareinheiten SLW-1040 von igus. Die Spindeln der X-Traverse werden hier von einem Zahnriemen synchron angetrieben (Zahnriemen und Zahnriemenscheiben von Mädler, www.maedler.de). Ein Aufbau mit zwei Schrittmotoren für die Y-Achse anstelle des Synchronriemens bewährte sich weniger, da es nach mehreren Ein- und Ausschaltvorgängen zu Asynchronitäten und damit zum Verkanten der Traverse kommen kann. 

Für dieses (deutlich teurere) Design sind lediglich zwei Träger aus 60 x 60 mm Alu-Rechteckrohr anzufertigen, die Abmessungen der Grundplatte bleiben gleich bzw. werden der Länge der Y-Traverse angepasst. Der Zahnriemen kann durch eine Rolle aus zwei übereinandergelegten Kugellagern 606-2RS gespannt werden. Als Antrieb für die Y-Achse (Zahnriemen) empfehlen wir wegen der höheren Reibungsverluste einen NEMA23-Motor.

Die Spindeln mit der Standard-Steigung TR10x2 lassen nur eine Geschwindigkeit von rund 1500 mm/m zu. Auf Anfrage baut igus die SLW-1040-Einheiten aber auch mit Steilgewindespindeln.

- 2 Maedler #17023000 HTD-Zahnriemenräder Profil 3M, 30 Zähne (aufbohren auf 10 mm für Spindeln bzw. Wellendurchmesser des Schrittmotors)
- HTD-Zahnriemen Neopren Profil 3M Breite 9mm Wirklänge 1125mm Zähnezahl 375, #17118000
- 3 igus-Lineareinheiten SLW-1040, Länge 500 mm
- 2 Aluminium-Rechteckprofil 60 x 60 mm, 74 mm lang

### MaXYposi-SchrittmotorsteuerungL

Unser auf GRBL basierendes Steuerungs-Projekt für 4 Achsen und vielen I/Os finden Sie in unserem [Github-Repository MaXYposi_Grbl_644](https://github.com/heise/MaXYposi_Grbl_644) - näheres dort.

Natürlich ist als Bahnsteuerung auch ein normaler Arduino-328 mit dem Standard-GRBL geeignet. Wir haben unser 644-GRBL allerdings auf 4 Achsen erweitert und 32 I/Os hinzugefügt, außerdem ein Handrad- und Joystick-Jog-Anschluss sowie eine Echtzeit-Positionsanzeige mit LDC 16x2 auf einem (optionalen) Bedienfeld. 
