Diese Vorlage ist für die Community Kiel angepasst, aber Ihr könnt sie gerne für eure Zwecke benutzen.

# Anpassen an deine Community
Um dieses Faltblatt anzupassen einfach dieses Git Repository klonen und die Frontseite und Rückseite anpassen. 

Die Quell-Datei ist `flyer-6-seiten_scribus1.5/flyer_6_seiten.sla`, für die Bearbeitung ist **Scribus 1.5** nötig (hier benutze Version: 1.5.1), dies ist unter Debian in dem paket `scribus-trunk` erhältlich, das man sich aus einem ppa installieren muss, siehe http://askubuntu.com/questions/639070

Um das Layout anzupassen muss nur der Titel auf der Frontseite geändert werden und die Rückseite. Alle anderen Seiten sind Community-unspezifish und können so bleiben wie sie sind.

Alle Quellen für den Flyer sind im Repository enthalten, also könnt ihr auch einfach weitere Änderungen einbauen.
Im Ordner exports ist unter anderem eine svg version, die man z.B. mit Inkskape weiterbearbeiten kann.


# Drucken
Das Layout ist ursprünglich angelegt worden für Flyer-Alarm, aber noch nicht getestet, ob diese das korrekt verarbeiten können (das Anforderungs-PDF von Flyer Alarm ist im Entwicklungsordner).

Wenn du den Flyer **selbst drucken** willst (ohne Duplex), dann kannst du einfach das PDF `flyer_6_seiten_rueckseite_gedreht.pdf` benutzen. Dabei kann man die einseitig bedruckten Blätter so gedreht wieder in den Drucker einlegen, dass das erneute Bedrucken jeweils die passende Hälfte ergänzt und man so nur einen Schnitt in der Mitte braucht um 2 vollständige Faltblätter zu trennen.

## Druckvorlage neu erzeugen mit Gimp:
* in Gimp das pdf importieren mit 600dpi
* Leinwandgrösse verdoppeln auf 4724 px
* die 2. Ebene (Innenseiten) nach unten schieben
* Die untere Ebene transformieren: um 180° drehen
* Exportieren als pdf: `flyer_6_seiten_rueckseite_gedreht.pdf`
## Prewiew png erzeugen
* in Gimp die untere Ebene wieder um 180° zurückdrehen
* Bildgröße ändern: 72dpi, 992x670 px
* exportieren als `flyer_6_seiten_preview.png`

# Danksagungen
Dieser Flyer ist entstanden aus einem gekürzten Text aus dem Möhne Flyer, der hier veröffentlicht wurde: 

 - https://forum.freifunk.net/t/pocket-flyer-8-seiter-jetzt-auf-betterplace-spenden/1005 
 - https://www.dropbox.com/s/kwytvedboxhw8h7/Flyer_8seiter_moehne_Druck.pdf?dl=0
 - Und Teile vom hamburger Flyer: http://www.vonbroeckel.de/download/flyer.ffhh.v08.pdf

# Fonts installieren
Die benötigten Fonts sind im Ordner `/flyer-6-seiten_scribus1.5/fonts`, in Linux kann man fonts installieren, z.b. mit:

	sudo mkdir -p ~/.fonts/truetype/minionpro
	sudo cp quellen/FF_Flyer_8seiter.indd/FF_Flyer_8seiter\ Ordner/Document\ fonts/MinionPro-Regular.otf ~/.fonts/truetype/minionpro/


# Neuer Text:

Obere Reihe
----

**Abschnitt 1 (hinten innen)** 
---
**Häufige Fragen**

**Ist das sicher für mich?**
Ja! Der Datenverkehr aus dem Freifunk-Netz ist   
vollständig von dem eigenen Netz bzw. Computer   
getrennt.

**Kann ich meinen Anschluss weiter nutzen?**
Ja, der Freifunk-Router nutzt nur einen einstell­baren Teil deiner Bandbreite, wobei du selbst bestimmst, wieviel du zur Verfügung stellst.

**Wie günstig ist es mitzumachen?**
Wie ein Kinobesuch mit Popcorn: die Kosten für die Anschaf­fung des Freifunk-Routers plus ca. 3 € im Jahr für Strom.

**Abschnitt 2: (Rückseite)**
---
**Mitmachen - Austauschen**

* Webseite      http://kiel.freifunk.net/
* Online Chat   auf unserer Webseite!
* Mail          freifunk@in-kiel.de
* Twitter       @ff_kiel

**Abschnitt 3 (Front)**
---
wird an die COMMUNITY angepasst mit Logo, etc. Schriftsatz: Alternate Gothic 2

---

Untere Reihe
---

**Abschnitt 4: (erste Seite innen)**
---
**„Freies Netz überall und für alle“**

**Was bietet das Freifunk-Netz?**
Freie digitale Kommu­nikation! Dezentralität! Ein unabhängiges Bürgernetz – und jeder kann es erweitern. Über deinen Internet­anschluss verbunden kannst du der Öffentlichkeit eine **Grundversorgung an Internet** zur Verfügung zu stellen. Freifunk ist eine Geste der Gast­freund­schaft, ein digitales Glas Wasser für jeden.

**Wie funktioniert Freifunk?**
Freifunk-Router in Reichweite verbinden sich automatisch zu einem großen, unabhängigen WLAN Netz. Falls du noch kein Freifunk in Reich­weite hast, kannst du ihn über dein Internet anschließen. 


**Abschnitt 5:**
---
**Router für 15 €**

1. Freifunk Router besorgen (nur bestimmte Modelle) - Einstiegsmodell ca. 15€  
2. Freifunk-Software aufspielen (Anleitungen dazu ...)
3. Freifunk-Router mit privatem Router verbinden.
4. Freifunk-Router aufstellen (möglichst in Fensternähe)

WLAN wird für jeden ohne Störerhaftung freigegeben!

untere Reihe:

  * Privater Internetanschluss 
  * Freifunk-Router
  * Fenster

**Abschnitt 6:**
---
**Hafte ich nicht für die Freigabe?**

Wenn Gäste über deinen Freifunk-Router ins Internet gehen, werden diese ganz legal per Verschlüsselungs-Tunnel (VPN) durchs Freifunk-Netz geleitet:
    
-- Schaubild --

Fazit: Gäste deines Freifunk-Netzes surfen nicht mit deiner Identität. Durch diese Anonymisierung wird die Rückverfolgbarkeit auf deinen Freifunk-Router vermieden.


---

*Alter Abschnitt 8: (fiel weg bei 6 Abschnitten)*
---
**Freifunk Netz vergrößern**

Das war aber noch nicht alles! Sie können anderen Leuten von  
Freifunk erzählen. Diese können Ihnen helfen das Freifunk-Netz zu  
erweitern. Sie müssen nur einen Freifunk-Router in Reichweite zu Ihrem  
jetzigen Router aufstellen, die beiden Geräte werden sich automatisch  
verbinden (meshen) und so das Freifunk-Netz vergrößern.  
So können sogar Orte mit Internet versorgt werden, die keinen eigenen  
Anschluss besitzen. Ist in einer Kette von Routern auch nur ein  
Internetanschluss vorhanden, kann dieser die gesamte Kette mit  
Internet versorgen.  
Wir erzählen es Ihnen durch diesen Flyer,  
erzählen Sie es Ihren Freunden und Bekannten!  

Ihr Haus / Ihr nächster Nachbar


*Alter Abschnitt 3 (hinten innen - fiel weg bei 6 Abschnitten)*
---
**Warum Freifunk?**

  * Kommunikation ist ein Grundbedürfnis,elektronische Kommunikation wird immer wichtiger
  * Freifunk ist dezentral, starte es von jedem Ort aus
  * Soziale Einrichtungen können profitieren.  
  * schafft Gemeinschaft  
  * Freifunk auch dann,wenn der Anbieter streikt
  
