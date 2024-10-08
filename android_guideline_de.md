*[Home](./index.md) > [Android Guideline (de)](./android_guideline_de.md)*

> Read in [english](./android_guideline.md)

# Android-Leitfaden

> **ACHTUNG:** Ich übernehme keinerlei Verantwortung für etwaige Schäden, die durch das Befolgen dieses Leitfades
> entstehen. Denk' selbst nach, bevor du die empfohlenen Schritte durchführst. Lege Datensicherungen an, um sicherzugehen.


# Warum Datenschutz uns alle etwas angeht

Apps mit nicht veröffentlichtem Quelltext sind nicht automatisch schlecht. Wenn sie kostenlos sind, werden
sie jedoch meist über Werbung und das Auswerten der von Nutzern abgezogenen Daten finanziert. Das mag in Ordnung
sein, solange es wirklich nur um die Anzeige von Werbung geht. Sobald dadurch aber Freiheit und Leben von
Menschen bedroht werden - z.B. weil Betreiber Daten an repressive Regierungen weitergeben - hört der Spaß auf.
Als Nutzer müssen wir handeln, bevor es so weit kommt. Niemand hat das Recht uns ohne unser Wissen auszuhorchen,
unsere Bewegungen zu verfolgen oder gar unser Aussehen, unser Verhalten und unsere Stimme zu erlernen.

Selbst wenn wir persönlich für uns entscheiden, dass wir all dem zustimmen wollen, können wir diese Entscheidung
nicht einfach für andere Menschen (z.B. Freunde, Familie, Bekannte) mit treffen - indem wir z.B. Fotos, Adressbücher
und Kalender mit Konzernen wie Google teilen. Dadurch setzen wir uns über das Selbstbestimmungsrecht unserer
Mitmenschen hinweg. Wir sind also nicht nur für unsere eigenen Daten, sondern auch für die Daten anderer Menschen,
die wir auf unseren Geräten haben verantwortlich.

Dieser Leitfaden gibt einen kurzen Überblick, was jeder Einzelne ohne viel Aufwand tun kann und welche Apps man
statt der weithin bekannten und weit verbreiteten verwenden kann um seine Daten zumindest ein Stück weit vor
unbefugten Augen und Ohren zu schützen.

Über das Thema wurde schon unglaublich viel geschrieben - und das mit weit tiefgehender Recherche als ich sie
betreiben kann. Daher will ich meine Ausführungen hier beenden und für Interessierte auf folgende Quellen verweisen:

+ [Human Rights Watch: Sicherheit und Rechte online schützen](https://www.hrw.org/de/news/2018/12/11/sicherheit-und-rechte-online-schuetzen)


# Spenden

Während sich viele Entwickler gezwungen sehen, ihre Software mit Werbung und Trackern zu finanzieren, gibt es auch
Entwickler, die ihre Arbeit ohne jegliche finanziellen Interessen zur Verfügung stellen und durch offenlegen des
Codes jedermann erlauben aus ihrer Arbeit zu lernen und nachzuprüfen, ob es keine versteckten Spähmechanismen gibt.
Um diese Entwickler zu unterstützen, kann ich es jedem nur ans Herz legen, sie mit einer kleinen (oder auch großen)
Spende zu unterstützen. Unter den beigefügten Links sind meist auch Informationen zu finden, wie man an die
Entwickler spenden kann.

Viele der Apps in diesem Leitfaden stammen aus der **Fossify**-App-Suite. Bitte ziehe eine Spende in Betracht,
wenn du Pro-Funktionen der Apps nutzen willst. Spenden kann man unter [Fossify](https://github.com/FossifyOrg).


# App-Store

Einen vertrauenswürdigen App-Store zu verwenden ist der erste Schritt zu einem sicheren, privatsphäre- und
datenschutzfreundlichen Android-System.

F-Droid ist ein freier, quelloffener Android-App-Store für freie und quelloffene Apps. Diese unterliegen
strengen Qualitätsrichtlinien und werden auf Tracker und Spyware geprüft.

Aktuell gibt es vermutlich keinen vertrauenswürdigeren Ort um sichere Apps zu beziehen.

Bei weiteren Fragen, konsolutiere [F-Droid's FAQ](https://f-droid.org/de/docs/FAQ_-_General/).


## Installation

Lade die F-Droid-APK von der [offiziellen Internetseite](https://f-droid.org/de/) herunter. Installiere es nicht
direkt aus dem Downloadmanager deines Browsers heraus (du willst nicht, dass dein Browser die Erlaubnis hat, Apps
zu installieren). Öffne dann deinen Dateimanager, navigiere in dein Download-Verzeichnis und öffne `F-Droid.apk`.
Nun wirst du gefragt, ob du deinem Dateimanager das Recht geben willst, Apps zu installieren. Aktiviere dazu in
den geöffneten Einstellungen den Eintrag "Unbekannte Quellen zulassen". Nach Fertigstellung der Installation solltest
du dem Dateimanager dieses Recht in den App-Einstellungen wieder entziehen.

Öffne nun **F-Droid**. Die App sollte nun die aktuellsten Paketquellen beziehen. Falls nicht, ziehe im ersten Reiter
von oben den Bildschirm herab und das Aktualisieren der Paketquellen anzustoßen. Sollte F-Droid sich selbst aktualisieren
wollen, wird im zweiten Reiter von Rechts (Glocke rechts unten) eine rote Blase mit einer Ziffer angezeigt. Wechsle
dorthin und bestätige die Aktualisierung.

Bei der ersten Installation einer App aus F-Droid wirst du aufgefordert, F-Droid das Recht zur Installation von Apps
aus unbekannten Quellen zu gewähren. Tu das.

Jetzt ist F-Droid für den Einsatz bereit. Stöbere ein bisschen im Katalog und installiere, was dir gefällt.

# New app store (optional)

Obwohl F-Droid für die meisten Fälle genügt, fehlen einige Funktionen wie Audo-Updates. Hier kommt [Neo Store](https://github.com/NeoApplications/Neo-Store) ins Spiel - welcher wiederum über F-Droid installiert werden kann.


# Die Cloud

Es ist sehr angenehm Kontakte, Fotos, Notizen und Kalender in der Cloud zu haben. Auch wenn man sein Handy, Tablet
oder gar PC verliert, sind die Daten weiterhin über die Cloud verfügbar. Standardmäßig laden Smartphones all diese
Daten auf Server von Google oder einem anderen vorinstallierten Cloud-Anbieter hoch. Der Cloud-Anbieter wertet die
Daten dann aus um dir z.B. Werbung anzuzeigen, welche bei dir besonders große Aussicht auf Erfolg hat, um dir
bestimmte Suchergebnisse in einer Suchmaschine bevorzugt anzuzeigen oder gar um dich bei der Navigation an Läden
vorbeizuführen, die hohe Aussicht darauf haben, dass du in ihnen einkaufst.

Kurz gesagt: Es gibt viele Gründe Königum über deine eigenen Daten zu bleiben. Dazu musst du einige Schritte befolgen.


## Cloud-Dienste entfernen

Entferne alle Apps und Dienste, die deine Daten gegen deinen Willen auf irgendwelche Server hochladen. Navigiere dazu
zu *"Android-Einstellungen" > "Apps" > "Zeige System-Apps"* und installiere oder deaktiviere mindestens die folgenden: 

+ GMail
+ Google
+ Google Kalender
+ Google Fotos
+ Google Kalender-Synchronisierung
+ Google Kontak-Synchronisierung

Keine Sorge. Im nächsten Kapitel stelle ich Apps vor, welche diese Apps ersetzen können.


## Hol' dir einen vertrauenswürdigen Cloud-Anbieter

Wenn du keine Cloud brauchst, kannst du direkt zum nächsten Kapitel gehen.

Andernfalls brauchst du einen neuen Cloud-Anbieter. Suche entweder im Netz nach einem vertrauenswürdigen **Nextcloud**-Anbieter
oder setze deine eigene Cloud mit einem Raspberry Pi oder einem gekauften Nextcloud-kompatiblen Heimcloud-Gerät ein.

Wenn du nur Kontakte, Kalender und Aufgaben synchronisieren willst, findest du zahlreiche kostenlose Anbieter. Sollen auch
Fotos gesichert werden, wirst du einen kostenpflichtigen Service verwenden müssen.


## Synchronisiere dein Gerät mit der Cloud

Im letzten Schritt installieren wir **DavX5**. Diese App synchronisiert deine Nextcloud mit deinem Smartphone/Tablet oder gar PC.

1. Installiere [DevX5](https://f-droid.org/de/packages/at.bitfire.davdroid/) von F-Droid
2. Folge dem Einrichtungs-Assistenten
3. Deaktiviere die Akku-Optimierung für DavX5

Das war's. Du kannst nun deine Daten mit dem Cloud-Anbieter deines Vertrauens synchronisieren. Sieh dir die von mir
[ausgewählten Apps](#Ausgew&umla;hlte-Apps) an, um Apps zu finden, die mit diesem Setup harmonieren.


# Ausgewählte Apps

Diese Liste enthält Apps die für die tagtägliche Nutzung geeignet sind. Ich selbst verwende alle Apps
regelmäßig und habe nur solche ausgewählt, die besonders stabil, intuitiv zu bedienen, halbwegs ästhetisch
ansprechend und überwiegend aktiv entwickelt sind. Die Apps sind entsprechend ihres Einsatzzwecks aufgelistet.

Jeder Eintrag enthält Information über:

+ den App-Store, in dem die App zu erhalten ist,
+ den Einsatzweck,
+ wo man den Quelltext einsehen kann,
+ etwaige Alleinstellungsmerkmale.

## Allgemeiner Nutzen

### Launcher (Desktop)

Verwenden deines Smartphones oder Tablets. Verwaltung des Startbildschirms, der App-Übersicht, von Widgets und Hintergründen.

> Leider kann ich aktuell keinen Open Source Launcher vollumfänglich für jede und jeden empfehlen. Natürlich gibt es tolle open source-Apps, aber keine, die ich der breiten Masse empfehlen würde. Dennoch stelle ich ein paar Beispiele vor.

+ [KISS Launcher](https://f-droid.org/de/packages/fr.neamar.kiss/) - einfach, schnell, funktional - auf Kosten der Anpassbarkeit
+ [Kvaesito Launcher](https://f-droid.org/packages/de.mm20.launcher2.release/) - interessanter Launcher, der eventuell meine neue Empfehlung wird



### Browser

Browsing the web.

+ **Name:** Firefox (Fennec)
+ **Verfügbarkeit:**
  - [Fennec (Firefox ohne proprietäre Komponenten)](https://f-droid.org/de/packages/org.mozilla.fennec_fdroid/) in F-Droid
  - [Firefox](https://play.google.com/store/apps/details?id=org.mozilla.firefox) im Play Store
+ **Alleinstellungsmerkmal:** Adress- und Werkzeugleiste unten, dunkler Modus, einziger vertrauenswürdiger Browser unter den "Großen"
+ **Quellcode:** [hg.mozilla.org/mozilla-central](https://hg.mozilla.org/mozilla-central/)

**Weitere Schritte**

Ändere die Standardsuchmaschine auf **DuckDuckGo**, **Ecosia** oder **Qwant**.


### Dateimanager

Für alle Dateiverwaltungsaufgaben (durchsuchen, kopieren, löschen, verschieben, ...).

+ **Name:** Fossify File Manager
+ **Verfügbarkeit:**
 - [Fossify File Manager](https://f-droid.org/de/packages/org.fossify.filemanager/) in F-Droid
 - [Fossify File Manager](https://play.google.com/store/apps/details?id=org.fossify.filemanager&hl=gsw) in Google Play
+ **Alleinstellungsmerkmal:** Themes
+ **Quellcode:** [Fossify on GitHub](https://github.com/FossifyOrg/)


## Werkzeuge

### Kalender

Termine und Geburtstage verwalten.

+ **Name:** Etar
+ **Verfügbarkeit:** [Etar](https://f-droid.org/de/packages/ws.xsoh.etar/) in F-Droid
+ **Alleinstellungsmerkmal:** Mit Widgets
+ **Quellcode:** [github.com/Etar-Group/Etar-Calendar](https://github.com/Etar-Group/Etar-Calendar)

oder

+ **Name:** Fossify Calendar
+ **Verfügbarkeit:**
  - [Fossify Calendar](https://f-droid.org/de/packages/org.fossify.calendar/) in F-Droid
  - [Fossify Calendar](https://play.google.com/store/apps/details?id=org.fossify.calendar&hl=gsw) in Google Play
+ **Alleinstellungsmerkmal:** Themes, Widgets
+ **Quellcode:** [Fossify on GitHub](https://github.com/FossifyOrg/)


### Navigation

Karten und Navigation.

+ **Name:** OsmAnd~
+ **Verfügbarkeit:** [OsmAnd~ Plus](https://f-droid.org/de/packages/net.osmand.plus/) in F-Droid
+ **Alleinstellungsmerkmal:** Offline-Navigation, hochkonfigurierbar
+ **Quellcode:** [github.com/osmandapp/Osmand](https://github.com/osmandapp/Osmand)

und


+ **Name:** Organic Maps
+ **Verfügbarkeit:**
  - [Organic Maps](https://f-droid.org/de/packages/app.organicmaps/) in F-Droid
  - [Organic Maps](https://play.google.com/store/apps/details?id=app.organicmaps&hl=gsw) in Google Play
+ **Alleinstellungsmerkmal:** Schick, sehr einfach zu benutzen
+ **Quellcode:** [Organic Maps on GitHub](https://github.com/organicmaps/organicmaps)



### Taschenrechner

Alle mögliche Berechnungen.

+ **Name:** Calculator++
+ **Verfügbarkeit:** [Calculator++](https://f-droid.org/de/packages/org.solovyev.android.calculator/) in F-Droid
+ **Alleinstellungsmerkmal:** Echter wissenschaftlicher Taschenrechner
+ **Quellcode:** [github.com/Bubu/android-calculatorpp](https://github.com/Bubu/android-calculatorpp)


### Tastatur

Schreiben.

+ **Name:** Heli Board
+ **Verfügbarkeit:** [Heli Board](https://f-droid.org/de/packages/helium314.keyboard/) in F-Droid
+ **Alleinstellungsmerkmal:** Mehrere Sprachen gleichzeitig
+ **Quellcode:** [GitHub](https://github.com/Helium314/HeliBoard)

### QR Code Scanner

Einlesen von QR-Codes und deren Link folgen.

+ **Name:** QR Scanner
+ **Verfügbarkeit:** [QR Scanner](https://f-droid.org/de/packages/com.secuso.privacyFriendlyCodeScanner/) in F-Droid
+ **Verfügbarkeit:** Zeigt Link an, damit er vor dem Öffnen geprüft werden kann
+ **Quellcode:** [github.com/SecUSo/privacy-friendly-qr-scanner](https://github.com/SecUSo/privacy-friendly-qr-scanner


## Kommunikation

### Telefon & Kontakte

Anrufen, Durchsuchen und Verwalten von Kontakten. Dieser Eintrag besteht aus zwei Apps, die am besten zusammen installiert werden.
Calling people, browsing and editing contacts. This entry consists of two apps that are best used together.

+ **Name:** Fossify Telefon und Fossify Kontakte
+ **Verfügbarkeit:**
  - [Phone](https://f-droid.org/de/packages/org.fossify.phone/) und [Contacts](https://f-droid.org/de/packages/org.fossify.contacts/) in F-Droid
  - [Phone](https://play.google.com/store/apps/details?id=org.fossify.phone&hl=gsw) und [Contacts](https://play.google.com/store/apps/details?id=org.fossify.contacts&hl=gsw) in Google Play
+ **Alleinstellungsmerkmal:** Themes, Kontaktlisten wählen (Cloud, SIM, Konten, ...)
+ **Quellcode:** [Fossify on GitHub](https://github.com/FossifyOrg/)


### E-Mail

Empfangen und Versenden von E-Mails.

+ **Name:** FairEmail
+ **Verfügbarkeit:**
  - [FairEmail](https://f-droid.org/de/packages/eu.faircode.email/) in F-Droid
  - [FairEmail](https://play.google.com/store/apps/details?id=eu.faircode.email) im Play Store
+ **Alleinstellungsmerkmal:** Konvertiert E-Mails in eine gut lesbare Form, blockiert Tracker und hilft dabei Phishing-Mails zu erkennen
+ **Quellcode:** [github.com/M66B/FairEmail](https://github.com/M66B/FairEmail/)


### Sofortnachrichten

Verschlüsselte Sofortnachrichten (Alternative zu WhatsApp und Telegram).

+ **Name:** Briar
+ **Verfügbarkeit:** [Briar](https://f-droid.org/de/packages/org.briarproject.briar.android/) in F-Droid
+ **Alleinstellungsmerkmal:** Serverlose Direktnachrichten, Blogs und Foren, funktioniert sogar, wenn Regierungen das Internet abschalten
+ **Quellcode:** [code.briarproject.org/briar/briar](https://code.briarproject.org/briar/briar)

und

+ **Name:** Signal
+ **Verfügbarkeit:** [Signal Messenger](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms) im Play Store
+ **Alleinstellungsmerkmal:** Chats, Gruppenchats, Telefon- und Videokonferenzen
+ **Quellcode:** [github.com/signalapp](https://github.com/signalapp)


### SMS

Schreiben und Empfangen von SMS.

+ **Name:** QKSMS
+ **Verfügbarkeit:** [QKSMS](https://f-droid.org/de/packages/com.moez.QKSMS/) in F-Droid
+ **Alleinstellungsmerkmal:** Leicht, Themes
+ **Quellcode:** [github.com/moezbhatti/qksms](https://github.com/moezbhatti/qksms)


## Multimedia

### Galerie

Betrachten und Verwalten eigener Fotos und Videos.

+ **Name:** Fossify Gallery
+ **Verfügbarkeit:**
  - [Fossify Gallery](https://f-droid.org/de/packages/org.fossify.gallery/) in F-Droid 
  - [Fossify Gallery](https://play.google.com/store/apps/details?id=org.fossify.gallery&hl=gsw) in Google Play
+ **Alleinstellungsmerkmal:** Themes, Ein- und Ausschließen bestimmter Verzeichnisse
+ **Quellcode:** [Fossify on GitHub](https://github.com/FossifyOrg/)


### Musik

Lokal gespeicherte Musik abspielen.

+ **Name:** Vinyl Music Player
+ **Verfügbarkeit:** [Vinyl Music Player](https://f-droid.org/de/packages/com.poupa.vinylmusicplayer/) in F-Droid
+ **Alleinstellungsmerkmal:** Cover Art
+ **Quellcode:** [github.com/AdrienPoupa/VinylMusicPlayer](https://github.com/AdrienPoupa/VinylMusicPlayer)


### Podcasts

Download und Streamen von Podcasts.

+ **Name:** AntennaPod
+ **Verfügbarkeit:** [AntennaPod](https://f-droid.org/de/packages/de.danoeh.antennapod/) in F-Droid
+ **Alleinstellungsmerkmal:** Themes, modernes Interface
+ **Quellcode:** [github.com/AntennaPod/AntennaPod](https://github.com/AntennaPod/AntennaPod)


### Radio

Online-Radio weltweit hören.

+ **Name:** RadioDroid
+ **Verfügbarkeit:** [RadioDroid](https://f-droid.org/de/packages/net.programmierecke.radiodroid2/) in F-Droid
+ **Alleinstellungsmerkmal:** Moderne Oberfläche
+ **Quellcode:** [github.com/segler-alex/RadioDroid](https://github.com/segler-alex/RadioDroid)


### YouTube

Videos auf YouTube anschauen.

+ **Name:** NewPipe
+ **Verfügbarkeit:** NewPipe kann mit F-Droid installiert werden
+ **Alleinstellungsmerkmal:** Gute Performance, mehr Privatsphäre
+ **Quellcode:** [github.com/TeamNewPipe/NewPipe/](https://github.com/TeamNewPipe/NewPipe/)

**Weitere Schritte**

> Bei der Verwendung von Neo Store kann die Update-Quelle einfach in den Einstellungen aktiviert werden. Die nächsten Schritte sind dann überflüssig.

**NewPipe** kann via F-Droid installiert werden. Da YoutTube oft die APIs verändert, sollte man jedoch stets die
aktuellste Version verwenden. Daher ist es besser die offizielle Paketquelle von NewPipe in F-Droids Einstellungen
einzutragen:

1. Offizielle [NewPipe F-Droid-Paketquelle](https://newpipe.net/FAQ/tutorials/install-add-fdroid-repo/) zu F-Droid hinzufügen
2. Paketquellen aktualisieren (in erstem Reiter von oben runterziehen)
3. Nach NewPipe suchen und installieren


### Feed Reader (RSS/Atom)

Immer auf dem neuesten Stand zu Projekten, die dich interressieren, bleiben.

+ **Name:** Flym
+ **Verfügbarkeit:** [Flym](https://f-droid.org/de/packages/net.frju.flym/) in F-Droid
+ **Alleinstellungsmerkmal:** Zuverlässiger Reader
+ **Quellcode:** [GitHub](https://github.com/FredJul/Flym)
+ **Hinweise:** Leider vom Entwickler eingestellt


### Documenten-Betrachter (PDF, ...)

Verschiedene Dokumentformate betrachten.

+ **Name:** MuPDF
+ **Verfügbarkeit:** [MuPDF](https://f-droid.org/de/packages/com.artifex.mupdf.viewer.app/) in F-Droid
+ **Alleinstellungsmerkmal:** Leichtgewichtig
+ **Quellcode:** [git.ghostscript.com/?p=mupdf-android-viewer.git;a=summary](https://git.ghostscript.com/?p=mupdf-android-viewer.git;a=summary)


## Privatsphäre und Sicherheit

### Datenverkehr filtern

Verfolgung stoppen und Adressen blockieren, die dafür bekannt sind Privatsphäre, Sicherheit und Performance in nicht zu rechtfertigender
Weise zu unterlaufen.

> **ACHTUNG:** Nur verwenden, wenn du weißt, was du tust und wie du es wieder deaktivieren kanns. Andernfalls könnte es durch Bugs oder Fehlkonfiguration passieren, dass deine Apps keine Verbindung zum Internet mehr herstellen können.

+ **Name:** [RethinkDNS](https://rethinkdns.com/app)
+ **Verfügbarkeit:**
  - [RehtinkDNS](https://f-droid.org/de/packages/com.celzero.bravedns/) on F-Droid
  - [RethinkDNS](https://play.google.com/store/apps/details?id=com.celzero.bravedns) on Google Play
+ **Alleinstellungsmerkmal:** Aus vielen Blockierungslisten wählen.
+ **Quellcode:** [GitHub](https://github.com/celzero)
+ **Hinweis:** Unterstützt durch mozilla builders

> **HINWEIS:** RethinkDNS erzeugt ein lokales VPN. Das bedeutet, es werden keine Daten an irgendwelche Server übertragen sondern lediglich
> lokal im eigenen Gerät gefiltert. Sollten Probleme mit einer App bei aktiviertem Blokada auftreten, kann diese App in den
> RethinkDNS-Einstellungen auf eine Ausnahmen-Liste gesetzt werden.


**Weitere Schritte**

1. Um lokale Blocklisten zu verwenden:
2. *"Konfigurieren" > "DNS"*
3. Aktiviere "System DNS"
4. Aktiviere "Nutzer In-App-Downloader"
5. *"Geräteinterne Blocklisten" > "Konfigurieren"*
6. Download abwarten
7. Listen aktivieren
  

### Passwort-Manager

Verwalten und Generieren starker Passwörter und Logins.

+ **Name:** KeePassDX
+ **Verfügbarkeit:** [KeePassDX](https://f-droid.org/de/packages/com.kunzisoft.keepass.libre/) in F-Droid
+ **Alleinstellungsmerkmal:** Modernes UI, kompatible mit Desktop-KeePass, automatisches Ausfüllen von Login-Feldern
+ **Quellcode:** [github.com/Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX)


**Weitere Schritte**

Nimm dir die Zeit dich durch die Anleitungen und Informationen im Wiki zu lesen, um den Passwort-Manager korrekt aufzusetzen.




