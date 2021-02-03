*[Home](./index.md) > [Android Guideline (de)](./android_guideline_de.md)*

> Read in [english](./android_guideline.md)

# Android-Leitfaden

> **ACHTUNG:** Ich übernehme keinerlei Verantwortung für etwaige Schäden, die durch das Befolgen dieses Leitfades
> entstehen. Denk selbst nach, bevor du die empfohlenen Schritte durchführst. Lege Updates an um sicherzugehen.


# Warum Datenschutz uns alle etwas angeht

Apps mit nicht veröffentlichtem Quelltext sind nicht automatisch schlecht. Wenn sie kostenlos sind, werden
sie jedoch meist über Werbung und das Auswerten von Nutzer abgezogener Daten finanziert. Das mag in Ordnung
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
Unbefugten Augen und Ohren zu schützen.

Über das Thema wurde schon unglaublich viel geschrieben - und das mit weit tiefgehender Recherche als ich sie
betreiben kann. Daher will ich meine Ausführungen hier beenden und für Interessierte auf folgende Quellen verweisen:



Closed source apps often contain trackers to display the the right advertisements, identify you throughout
the web, to analyze where you go, what you like and who you know. This might seem ok, as long as the only
use is to display you the right advertisements. But this means you allow anyone to known almost anything
about you. 

Its not about seeing no ads but has much wider implications like freedom and human rights. Enough has been
written on the matter and I don't want to do it again here.

+ [Human Rights Watch: Sicherheit und Rechte online schützen](https://www.hrw.org/de/news/2018/12/11/sicherheit-und-rechte-online-schuetzen)


# Donations

Während sich viele Entwickler gezwungen sehen, ihre Software mit Werbung und Trackern zu finanzieren, gibt es auch
Entwickler, die ihre Arbeit ohne jegliche finanziellen Interessen zur Verfügung stellen und durch offenlegen des
Codes jedermann erlauben aus ihrer Arbeit zu lernen und nachzuprüfen, ob es keine versteckten Spähmechanismen gibt.
Um diese Entwickler zu unterstützen, kann ich es jedem nur ans Herz legen, sie mit einer kleinen (oder auch großen)
Spende zu unterstützen. Unter den beigefügten Links sind meist auch Informationen zu finden, wie man an die
Entwickler spenden kann.

Viele der Apps in diesem Leitfaden stammen aus der **SimpleMobileTools**-App-Suite. Bitte ziehe eine Spende in Betracht,
wenn du Pro-Funktionen der Apps nutzen willst. Spenden kann man unter [SimpleMobileTools.com](https://www.simplemobiletools.com/.


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

This list contains apps for everyday use. All entries have been tested for stability, user-friendliness and
privacy and security aspects. Every app is able to replace your pre-installed app for the specific task.

Each entry contains information about:

+ the app store to install it from,
+ what to use it for,
+ where to read its source,
+ feature highlights.


## File Manager

For all file managing tasks (browsing, copying, deleting, moving, ...).

+ **Name:** Simple File Manager Pro
+ **Availability:**
  - [Simple File Manager](https://f-droid.org/packages/com.simplemobiletools.filemanager.pro/) on F-Droid (install [Simple Thank You](https://f-droid.org/en/packages/com.simplemobiletools.thankyou/) as well to get pro features)
  - [Simple File Manager Pro](https://play.google.com/store/apps/details?id=com.simplemobiletools.filemanager.pro) (ca. 1€) on Play Store
+ **Feature highlights:** Theming support
+ **Source code:** [github.com/SimpleMobileTools/Simple-File-Manager](https://github.com/SimpleMobileTools/Simple-File-Manager)


## Browser

Browsing the web.

+ **Name:** Firefox (Fennec)
+ **Availability:**
  - [Fennec (Firefox without proprietary bits)](https://f-droid.org/packages/org.mozilla.fennec_fdroid/) on F-Droid
  - [Firefox](https://play.google.com/store/apps/details?id=org.mozilla.firefox) on Play Store
+ **Feature highlights:** Address and toolbar at the bottom, dark mode, the only trustworthy among the big players
+ **Source code:** [hg.mozilla.org/mozilla-central](https://hg.mozilla.org/mozilla-central/)

**Additional steps**

1. Set your default search engine to **DuckDuckGo**, **Ecosia** or **Qwant**.


## Launcher

Using you smartphone or tablet. Managing you start screen, app drawer, widgets and wallpapers.

+ **Name:** Lawnchair Launcher v2
+ **Availability:** [Lawnchair v2](https://play.google.com/store/apps/details?id=ch.deletescape.lawnchair.plah) on Play Store
+ **Feature highlights:** Almost everything can be customized,
  - custom icons,
  - hiding apps,
  - setting adaptive icon shapes,
  - managing drawer categories,
  - ...
+ **Source code:** [github.com/LawnchairLauncher/Lawnchair](https://github.com/LawnchairLauncher/Lawnchair)

> **HINT:** Unfortunately the development is dead right now and it works only with Android <= 10. For Android >= 11
> use its fork [Omega Launcher](https://github.com/otakuhqz/Omega) which is available via the [IzzyOnDroid](https://www.izzysoft.de/)
> [F-Droid repository](https://apt.izzysoft.de/fdroid/) only. It is not as stable as Lawnchair, but under active
> development.

**Additional steps**

Customize the launcher how you like.


## Traffic Filter

Blocks trackers and domains that are known to undermine privacy, security and performance in a non-tolerable way.

+ **Name:** Blokada 5
+ **Availability:** [Blokada 5](https://f-droid.org/packages/org.blokada.fem.fdroid/) on F-Droid
+ **Feature highlights:** Choose from a whole bunch of block lists
+ **Source code:** [github.com/blokadaorg/blokada](https://github.com/blokadaorg/blokada)

> **HINT:** Blokada creates a local VPN. That means, it does not transfer any of your traffic somewhere else.
> It simply uses the VPN on your phone to filter the traffic directly in your device. If you have trouble using
> a specific app, you can also whitelist it in the Blokada settings.

**Additional steps**

1. Enable always on (*"Blokada Settings" > "VPN Profile" > "Always"*)
2. Disable battery optimization for this app (*"Android Settings" > "Battery Optimization" > "Show all apps" > "Disable" for Blokada*)
3. Choose you blocklists
  + minimum: DuckDuckGo + Phishing Army
  + medium: DuckDuckGo + Phishing Army + Exodus Privacy
  + maximum: DuckDuckGo + Phishing Army + Exodus Privacy + Any Energized List
  
  

## E-Mail

Receiving and sending E-Mails.

+ **Name:** FairEmail
+ **Availability:**
  - [FairEmail](https://f-droid.org/packages/eu.faircode.email/) on F-Droid
  - [FairEmail](https://play.google.com/store/apps/details?id=eu.faircode.email) on Play Store
+ **Feature highlights:** Displays E-Mail in an easy to read layout, block trackers and helps the user with identifying phishing mails
+ **Source code:** [github.com/M66B/FairEmail](https://github.com/M66B/FairEmail/)


## Phone / Dialer & Contacts

Calling people, browsing and editing contacts. This entry consists of two apps that are best used together.

+ **Name:** Simple Dialer and Simple Contacts from the [SimpleMobileTools app suite](https://www.simplemobiletools.com/)
+ **Availability:**
  - [Simple Dialer](https://f-droid.org/packages/com.simplemobiletools.dialer/) and [Simple Contacts Pro](https://f-droid.org/packages/com.simplemobiletools.contacts.pro/) on F-Droid (install [Simple Thank You](https://f-droid.org/en/packages/com.simplemobiletools.thankyou/) as well to get pro features)
  - [Simple Dialer](https://play.google.com/store/apps/details?id=com.simplemobiletools.dialer) and [Simple Contacts Pro](https://play.google.com/store/apps/details?id=com.simplemobiletools.contacts.pro) (ca. 1€) on Play Store
+ **Feature highlights:** Theming, chosing contact sources (cloud, SIM, accounts, ...)
+ **Source code:** [github.com/SimpleMobileTools](https://github.com/SimpleMobileTools)


## Gallery

Managing and viewing your photos and videos.

+ **Name:** Simple Gallery Pro
+ **Availability:**
  - [Simple Gallery Pro](https://f-droid.org/packages/com.simplemobiletools.gallery.pro/) on F-Droid (install [Simple Thank You](https://f-droid.org/en/packages/com.simplemobiletools.thankyou/) as well to get pro features)
  - [Simple Gallery Pro](https://play.google.com/store/apps/details?id=com.simplemobiletools.gallery.pro) (ca. 1€) on Play Store
+ **Feature highlights:** Theming support, excluding and including specific directories
+ **Source code:** [github.com/SimpleMobileTools](https://github.com/SimpleMobileTools)


## Music

Playing your locally stored music.

+ **Name:** Vinyl Music Player
+ **Availability:** [Vinyl Music Player](https://f-droid.org/packages/com.poupa.vinylmusicplayer/) on F-Droid
+ **Feature highlights:** Cover art
+ **Source code:** [github.com/AdrienPoupa/VinylMusicPlayer](https://github.com/AdrienPoupa/VinylMusicPlayer)


## Calendar

Viewing and managing your dates and birthdays.

+ **Name:** Etar
+ **Availability:** [Etar](https://f-droid.org/packages/ws.xsoh.etar/) on F-Droid
+ **Feature highlights:** Includes widgets
+ **Source code:** [github.com/Etar-Group/Etar-Calendar](https://github.com/Etar-Group/Etar-Calendar)

or

+ **Name:** Simple Calendar Pro
+ **Availability:**
  - [Simple Calendar Pro](https://f-droid.org/packages/com.simplemobiletools.calendar.pro/) on F-Droid (install [Simple Thank You](https://f-droid.org/en/packages/com.simplemobiletools.thankyou/) as well to get pro features)
  - [Simple Calendar Pro](https://play.google.com/store/apps/details?id=com.simplemobiletools.calendar.pro) (ca. 1€) on Play Store
+ **Feature highlights:** Theming support, with widgets
+ **Source code:** [github.com/SimpleMobileTools](https://github.com/SimpleMobileTools)


## Instant Messenger

Encrypted secure instant messaging.

+ **Name:** Briar
+ **Availability:** [Briar](https://f-droid.org/packages/org.briarproject.briar.android/) on F-Droid
+ **Feature highlights:** Serverless direct messaging, works even when governments shut down the internet
+ **Source code:** [code.briarproject.org/briar/briar](https://code.briarproject.org/briar/briar)

and

+ **Name:** Signal
+ **Availability:** [Signal Messenger](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms) on Play Store
+ **Feature highlights:** Phone and Video conferences
+ **Source code:** [github.com/signalapp](https://github.com/signalapp)


## Podcasts

Downloading and streaming podcasts.

+ **Name:** AntennaPod
+ **Availability:** [AntennaPod](https://f-droid.org/packages/de.danoeh.antennapod/) on F-Droid
+ **Feature highlights:** Modern interface, theming
+ **Source code:** [github.com/AntennaPod/AntennaPod](https://github.com/AntennaPod/AntennaPod)


## Radio

Listening to online radio stations world wide.

+ **Name:** RadioDroid
+ **Availability:** [RadioDroid](https://f-droid.org/packages/net.programmierecke.radiodroid2/) on F-Droid
+ **Feature highlights:** Modern interface
+ **Source code:** [github.com/segler-alex/RadioDroid](https://github.com/segler-alex/RadioDroid)


## Navigation

Navigation and maps.

+ **Name:** OsmAnd~
+ **Availability:** [OsmAnd~ Plus](https://f-droid.org/packages/net.osmand.plus/) on F-Droid
+ **Feature highlights:** Offline navigation, high customizability
+ **Source code:** [github.com/osmandapp/Osmand](https://github.com/osmandapp/Osmand)


## Calculator

Calculations of any kind.

+ **Name:** Calculator++
+ **Availability:** [Calculator++](https://f-droid.org/packages/org.solovyev.android.calculator/) on F-Droid
+ **Feature highlights:** Real scientific calculator, great UI
+ **Source code:** [github.com/Bubu/android-calculatorpp](https://github.com/Bubu/android-calculatorpp)

## YouTube

Watching videos on YouTube.

+ **Name:** NewPipe
+ **Availability:** NewPipe can be installed from F-Droid
+ **Feature highlights:** Great performance, more privacy
+ **Source code:** [github.com/TeamNewPipe/NewPipe/](https://github.com/TeamNewPipe/NewPipe/)

**Additional steps**

You can install **NewPipe** from F-Droid. But since YouTube often changes its API's it is much better to always
have the latest NewPipe installed. The newest version has some days delay on the official F-Droid repository,
therefore we do the following:

1. Add the official [NewPipe F-Droid Repository](https://newpipe.net/FAQ/tutorials/install-add-fdroid-repo/) to our F-Droid.
2. Refresh the repositories (draw down from the top in the first F-Droid tab)
3. Search for and install NewPipe


## Feed Reader (RSS/Atom)

Keeping up to date with projects you are interested in.

+ **Name:** spaRSS
+ **Availability:** [spaRSS](https://f-droid.org/packages/net.etuldan.sparss.floss/) on F-Droid
+ **Feature highlights:** Great and simple reader
+ **Source code:** [github.com/Etuldan/spaRSS](https://github.com/Etuldan/spaRSS)


## Password Manager

Managing and generating strong passwords and login credentials.

+ **Name:** KeePassDX
+ **Availability:** [KeePassDX](https://f-droid.org/packages/com.kunzisoft.keepass.libre/) on F-Droid
+ **Feature highlights:** Modern UI, compatible with desktop KeePass
+ **Source code:** [github.com/Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX)


**Additional steps**

Take your time to read through the instructions and information in the wiki to properly setup you password manager.


## Document Viewer (PDF, ...)

Viewing several document formats.

+ **Name:** MuPDF
+ **Availability:** [MuPDF](https://f-droid.org/packages/com.artifex.mupdf.viewer.app/) on F-Droid
+ **Feature highlights:** Very lightweight
+ **Source code:** [git.ghostscript.com/?p=mupdf-android-viewer.git;a=summary](https://git.ghostscript.com/?p=mupdf-android-viewer.git;a=summary)


## Keyboard

Writing.

+ **Name:** Open Board
+ **Availability:** [Open Board](https://f-droid.org/packages/org.dslul.openboard.inputmethod.latin/) on F-Droid
+ **Feature highlights:** Lightweight, simple, multi-language
+ **Source code:** [github.com/dslul/openboard](https://github.com/dslul/openboard)


## SMS

Writing and receiving SMS.

+ **Name:** QKSMS
+ **Availability:** [QKSMS](https://f-droid.org/de/packages/com.moez.QKSMS/) on F-Droid
+ **Feature highlights:** Lightweight, archiving function
+ **Source code:** [github.com/moezbhatti/qksms](https://github.com/moezbhatti/qksms)


