*[Home](./index.md) > [Android Guideline (en)](./android_guideline.md)*

+ [Android Guideline](#Android-Guideline)
+ [Why choosing the right apps matters](#Why-choosing-the-right-apps-matters)
+ [Donations](#Donations)
+ [App Store](#App-Store)
  - [Installation](#Installation)
+ [The Cloud](#the-cloud)
  - [Remove cloud services]()
  - [Get a trustworthy cloud provider]()
  - [Sync your device with your cloud]()

# Android Guideline

> **WARNING:** I take absolutely no responsibility for any damage done by following this guideline. Think for
> yourself before applying any of the suggested steps.


# Why choosing the right apps matters

Closed source apps often contain trackers to display the the right advertisements, identify you throughout
the web, to analyze where you go, what you like and who you know. This might seem ok, as long as the only
use is to display you the right advertisements. But this means you allow anyone to known almost anything
about you. 

Its not about seeing no ads but has much wider implications like freedom and human rights. Enough has been
written on the matter and I don't want to do it again here.

Read [why privacy matters at privacyinternational.org](https://privacyinternational.org/learning-resources/privacy-matters) to learn more.


# Donations

The reason these apps are listed here is because they are trustworthy and open source.
Their developers have no intention to spy on you and no financial interest in your data. On the other
and this means they give away their time and hard work for free. Pleaser consider at least 1, 2 or even
5€ to them. Of course more is better.

Many of the apps in the curated list are from the **SimpleMobileTools** app suite. Please donate some money at the
[SimpleMobileTools](https://www.simplemobiletools.com/) website if you plan to use the pro features. You can get the pro
features for free on F-Droid. But it's just fair to donate some € if you can afford it (and I think everyone can).


# App Store

Using a trustworthy app store is the first step to a safer, privacy and security friendly Android experience.

F-Droid is an open source Android app store that applies strict rules on included apps - including tests to
make sure the does not spy on you, has not trackers and so on. You probably won't find a place where you can
be as sure as here that the apps you get are safe to use.

If you have more questions, refer to [F-Droid's FAQ](https://f-droid.org/en/docs/FAQ_-_General/).


## Installation

Download the F-Droid APK from the [official website](https://f-droid.org/en/). Do not install it directly from 
the downloads section (you don't want your browser to have permission to install apps). Open your file manager,
navigate to your downloads folder and open `F-Droid.apk`. Now give your file manager the permission to install
apps from unknown sources and install it. After the installation has finished, withraw the permission from your
file manager again. We don't need it anymore.

Now open **F-Droid** and draw the first page from the top. This will refresh the package sources and check if
there is an update for F-Droid. If so, you'll see a bubble with a number on the bell icon in the tool bar at
the bottom. Click it and apply the update.

You will have to give F-Droid the permission to install apps from unknown sources. Keep it like that.

After restarting F-Droid you are ready to explore its list of apps and install whatever you like.


# The Cloud

It's convenient to have your contatcs, photos, notes and calendars in the cloud. You may lose your phone or pc,
but your data is still accessible. By default all this is automatically uploaded to Google or other services
pre-installed by your smartphone manufacturer. The cloud provider then analyzes your data to show you advertisements,
incluence what you see in a search engine or even change the route your navigation app calculates, to lead you along
a store you might like.

In a country where data protection laws are weaker than in the EU your provider might hand over your data to political
opponents or the government which can use it to put you to jail.

Long story short, there are many reasons why you should stay in charge of your own data. There is a handful of steps
you need to follow, to gain back control over your data.

## Remove cloud services

Uninstall all apps and services that might upload your data against your will to some companies servers.
Navigate to *"Android Settings" > "Apps" > "Show system apps"* and remove or de-activate at least the following apps:

+ GMail
+ Google
+ Google Calendar
+ Google Photos
+ Google Calendar-Syncing
+ Google Contact-Syncing

No worries. You'll find apps to replace these in the app list in the next chapter.


## Get a trustworthy cloud provider

If you don't want to use a cloud, you can stop here and go to the next chapter.

Else you need a new cloud provider. Either search the web for a trustworthy **Nextcloud** provider or setup your own cloud
with a Raspberry Pi or a pre-configured home cloud device.

If you just want to synchronize Contacts, Calendars and Tasks there are many free choices online. If you want to backup
your photos as well, you'll probably need a paid plan.


## Sync your device with your cloud

In the last step we install **DavX5**. This app synchronizes your Nextcloud instance with your smartphone/tablet and even PC.

1. Install [DevX5](https://f-droid.org/de/packages/at.bitfire.davdroid/) from F-Droid
2. Go through the setup assistent
3. Disable battery optimization for this app

That's it. You can now sync your data with a cloud service you can trust. See the [curated app list](#Curated-App-List) for
apps to use with this setup.



# Curated App List

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


## QR Code Scanner

Scanning QR codes and opening links.

+ **Name:** QR Scanner
+ **Availability:** [QR Scanner](https://f-droid.org/packages/com.secuso.privacyFriendlyCodeScanner/) on F-Droid
+ **Feature highlights:** Displays link before opening it
+ **Source code:** [github.com/SecUSo/privacy-friendly-qr-scanner](https://github.com/SecUSo/privacy-friendly-qr-scanner)
