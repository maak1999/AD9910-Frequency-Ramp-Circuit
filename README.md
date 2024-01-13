Aufgabenstellung
Allgemein
Bitte	legen	sie	 für	Ihr	Design	nur	jeweils	eine! Bibliothek	 für	die	Schematics	und	eine!
Bibliothek	 für	die	Footprints	an.	Bitte	speichern	sie	 Ihr	Projekt	und	Bibliotheken	unter	
Ihrer	Gruppennummer:
Gruppe_XX_Projektname.Pcb
Gruppe_XX_Projektname.sch
Bitte	 geben	 sie	 ihren	 Namen	 und	 Matrikelnummer	 auf	 dem	 Übersichtsblatt	 ihrer	
Schematics	an.
Beachten	sie,	dass	alle	verwendeten	Bauteile	als	3D	Elemente in	Ihrem	PCB	verfügbar	sein	
müssen. Bitte	legen	sie	jedes	Bauteil	mit	folgenden Attributen	an:
• Designer
• Datum
• Hersteller
• Lieferant
• Datenblatt
Sie	 haben	 unbegrenztes	 Budget,	 erstellen	 sie	 dennoch	 eine	 Übersicht	 aus	 denen	 die	
Kosten	 der	 verwendeten	 Bauteile	 hervorgehen.	 Vernachlässigen	 sie	 hierbei	
Kondensatoren,	Spulen,	Widerstände	und	die	Herstellungskosten	Ihrer	Platinen.	
Zu Beginn des	 Projekts starten	 sie mit	 einer	 Übersicht	 der	 Aufgabe	 in	 dem	 sie	 ein	
Blockschaltbild	 der	 zu	 entwickelten	 Platine	 mit	 den	 notwendigen	 Schnittstellen	 und	
Spannungen	zeichnen.	Diese	Blockschaltbild	ist	Bestandteil	des	Projekts	und	soll	auch	in	
ihrem	PCB-Projekt	aufgenommen	werden.	Als	nächsten	Schritt	erfolgt	die	Auswahl der	
Bauteile.	
Folgende	 Hersteller/Distributoren bieten	 eine	 große	 Auswahl	 verschiedener	
Komponenten:
• Mouser
• DigiKey
• Farnell
• Texas	Instruments
• Analog	Devices
• Linear	Technologies
• Würth



Aufgabenstellung:

Entwickeln	sie	eine	Leiterplatte	mit	der	es	möglich	ist	unterschiedliche	
Frequenzrampen (Sägezahn,	Sinus,	Rechteck) im	Frequenzbereich zwischen	
100 KHz	und	360 MHz zu	erzeugen.	Achten	sie	in	Ihrer	Schaltung	auf	einen	
Ausgangspegel	von	mind.	500mV.	Der	Output soll	über	einen	SMA-Stecker	
(gewinkelt)	erfolgen.	Als	Schnittstelle	zur	Steuerung	soll	ein	Mikrokontroller	
verwendet	werden.	Die	Steuerung	des	Mikrokontrollers	soll	über USB-C-erfolgen.
Tipp: Schauen	sie	sich	das	Bauteil	AD9910 von	Analog	Devices	an.	Es	gibt	aber	
viele	Möglichkeiten	die	Aufgabe	zu	lösen.



Die	Versorgungsspannung	welche	zu	Verfügung	steht,	beträgt	bei	beiden	Designs	
24V	und	15A. Weitere	benötigte	Spannungen	müssen	auf	der	Platine	erzeugt	werden.	
Beachten	Sie	bitte	bei	der	Wahl	der	Leiterbahnbreite	die	Stromaufnahme	ihrer	
Schaltung.	Ein	Verpolungsschutz	sowie	eine	Sicherung sollen	Ihre Schaltung	
schützen.	Die	Schaltung	soll	für	den Spannungsbereich	zwischen	18V	und	26V
ausgelegt	werden.	Spannungen	größer	oder	kleiner	dieser	Grenzwerte	führen	ggf.	zur	
Zerstörung	der	Bauteile	auf	Ihrer	Platine.	Beachten	sie	dies.
Als	Spannungsstecker	für	die	Zuleitung	sowie	für	alle	weiteren	Schnittstellen	sollen	
Stecker	der	Firma	Würth verwendet	werden.	Diese	Voraussetzungen	gelten	auch	für	
Ihre	eigenen	Designvorschläge.	
Erstellen	 sie	 Testpunkte um	 die	 Funktion	 Ihrer	 Platine	 nach der	 Fertigstellung	 zu	
überprüfen (Dokumentieren	 sie	 Ihre	Testpunkte	und	 beschriften	 sie	diese	 sinnvoll auf	
dem	PCB	und	in	den	Schematic).	
Bei jedem verwendeten Layer	 müssen	 die	 Freiflächen vollständig mit	 einem	 auf	
Systemmasse	 bezogenen	Polygon	 „gefüllt“ werden. „Inseln“	aus	Kupfer	 sollen	aus	 dem	
finalen	Design	entfernt	werden (Einstellung	im	Polygonmanager).	
Verwenden	sie,	sofern	nichts	Funktionales dagegenspricht, ausschließlich	SMD-Bauteile
(surface	 mount	 devices).	 Ausnahmen hier	 von: ggf. Spannungsstecker,	 Spannungsbereich	der	Bauteile etc.).	
Im	Vorfeld	fertigen	sie	eine	schematische	Übersicht	(Blockdiagram)	ihrer	Schaltung	an.	
Hierdurch	 behalten	 sie	 die	 Übersicht	 und	 haben	 ein	 gutes	 Instrument	 ihre	 Arbeit	 zu	
strukturieren.	Dieses	Blockdiagram	ist	Bestandteil	der	Abgabe	und	fließt	in	die	Note	mit	
ein.
WICHTIG:
Die	Größe	und	Form	der	Platine	ist frei	wählbar. Bedenken	sie	auch,	dass	Ihre	Platine	in	
einem	Gehäuse	montiert	werden	soll.	Sehen	sie	hierfür	zwingend Befestigungslöcher	vor.	
Die	 Kühlung	 der	 Platine	 kann	 sowohl	 aktiv	 als	 auch	 passiv	 erfolgen.	 Bei	 einer	 aktiven	
Kühlung	(Lüfter)	müssen auf	Ihrer Platine	die	notwendigen	Spannungen	bzw.	Signale	zu	
Verfügung	stehen.	Beachten	sie	das	Thermomanagement	und	stellen	sie	sicher, dass	ihre	
Platine	nicht	zu	heiß	wird.	
