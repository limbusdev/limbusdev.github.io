*[Home](./index.md) > [Android Guideline (en)](./android_guideline.md)*

# Android Guideline

> [Auf deutsch lesen](./android_guideline_de.md)

> **WARNING:** I take absolutely no responsibility for any damage done by following this guideline. Think for
> yourself before applying any of the suggested steps.


# Why privacy matters

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

Many of the apps in the curated list are from the **Fossify** app suite. Please donate some money at the
[Fossify](https://github.com/FossifyOrg) website if you plan to use the pro features. You can get the pro
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

# New app store (optional)

Although F-Droid is enough for most use cases it lacks some functions like auto-updates. Here comes [Neo Store](https://github.com/NeoApplications/Neo-Store)
to the rescue, which again can be installed via F-Droid.

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

## General purpose


### Launcher

> Right now there is no open source launcher which I can recommend for everyone. Of course there are great apps. But many of them might not suite everyone. Therefore I'll just give some examples.

+ [KISS Launcher](https://f-droid.org/de/packages/fr.neamar.kiss/) - simple, fast, functional - at the cost of customizability
+ [Kvaesito Launcher](https://f-droid.org/packages/de.mm20.launcher2.release/) - interesting launcher which might become the new recommendation


### Browser

Browsing the web.

+ **Name:** Firefox (Fennec)
+ **Availability:**
  - [Fennec (Firefox without proprietary bits)](https://f-droid.org/packages/org.mozilla.fennec_fdroid/) on F-Droid
  - [Firefox](https://play.google.com/store/apps/details?id=org.mozilla.firefox) on Play Store
+ **Feature highlights:** Address and toolbar at the bottom, dark mode, the only trustworthy among the big players
+ **Source code:** [hg.mozilla.org/mozilla-central](https://hg.mozilla.org/mozilla-central/)

**Additional steps**

Set your default search engine to **DuckDuckGo**, **Ecosia** or **Qwant**.


### File Manager

For all file managing tasks (browsing, copying, deleting, moving, ...).

+ **Name:** Fossify File Manager
+ **Availability:**
  - [Fossify File Manager](https://f-droid.org/de/packages/org.fossify.filemanager/) on F-Droid
  - [Fossify File Manager](https://play.google.com/store/apps/details?id=org.fossify.filemanager&hl=gsw) on Play Store
+ **Feature highlights:** Theming support
+ **Source code:** [Fossify on GitHub](https://github.com/FossifyOrg/)


## Tools

### Calendar

Viewing and managing your dates and birthdays.

+ **Name:** Etar
+ **Availability:** [Etar](https://f-droid.org/packages/ws.xsoh.etar/) on F-Droid
+ **Feature highlights:** Includes widgets
+ **Source code:** [github.com/Etar-Group/Etar-Calendar](https://github.com/Etar-Group/Etar-Calendar)

or

+ **Name:** Fossify Calendar
+ **Availability:**
  - [Fossify Calendar](https://f-droid.org/de/packages/org.fossify.calendar/) on F-Droid
  - [Fossify Calendar](https://play.google.com/store/apps/details?id=org.fossify.calendar&hl=gsw) on Play Store
+ **Feature highlights:** Theming support, with widgets
+ **Source code:** [Fossify on GitHub](https://github.com/FossifyOrg/)


### Navigation

Navigation and maps.

+ **Name:** OsmAnd~
+ **Availability:** [OsmAnd~ Plus](https://f-droid.org/packages/net.osmand.plus/) on F-Droid
+ **Feature highlights:** Offline navigation, high customizability
+ **Source code:** [github.com/osmandapp/Osmand](https://github.com/osmandapp/Osmand)

and

+ **Name:** Organic Maps
+ **Availability:**
  - [Organic Maps](https://f-droid.org/de/packages/app.organicmaps/) on F-Droid
  - [Organic Maps](https://play.google.com/store/apps/details?id=app.organicmaps&hl=gsw) on Google Play
+ **Feature highlights:** Beautifuly, easy to use
+ **Source code:** [Organic Maps on GitHub](https://github.com/organicmaps/organicmaps)


### Calculator

Calculations of any kind.

+ **Name:** Calculator++
+ **Availability:** [Calculator++](https://f-droid.org/packages/org.solovyev.android.calculator/) on F-Droid
+ **Feature highlights:** Real scientific calculator, great UI
+ **Source code:** [github.com/Bubu/android-calculatorpp](https://github.com/Bubu/android-calculatorpp)


### Keyboard

Writing.

+ **Name:** Heli Board
+ **Availability:** [Heli Board](https://f-droid.org/de/packages/helium314.keyboard/) on F-Droid
+ **Feature highlights:** Lightweight, simple, multi-language
+ **Hints:** Fork of "Open Board" which I recommended earlier
+ **Source code:** [GitHub](https://github.com/Helium314/HeliBoard)


### QR Code Scanner

Scanning QR codes and opening links.

+ **Name:** QR Scanner
+ **Availability:** [QR Scanner](https://f-droid.org/packages/com.secuso.privacyFriendlyCodeScanner/) on F-Droid
+ **Feature highlights:** Displays link before opening it
+ **Source code:** [github.com/SecUSo/privacy-friendly-qr-scanner](https://github.com/SecUSo/privacy-friendly-qr-scanner)


## Communication

### Phone / Dialer & Contacts

Calling people, browsing and editing contacts. This entry consists of two apps that are best used together.

+ **Name:** Fossify Phone
+ **Availability:**
  - [Phone](https://f-droid.org/de/packages/org.fossify.phone/) and [Contacts](https://f-droid.org/de/packages/org.fossify.contacts/) on F-Droid
  - [Phone](https://play.google.com/store/apps/details?id=org.fossify.phone&hl=gsw) and [Contacts](https://play.google.com/store/apps/details?id=org.fossify.contacts&hl=gsw) on Google Play
+ **Feature highlights:** Theming, chosing contact sources (cloud, SIM, accounts, ...)
+ **Source code:** [Fossify on GitHub](https://github.com/FossifyOrg/)


### E-Mail

Receiving and sending E-Mails.

+ **Name:** FairEmail
+ **Availability:**
  - [FairEmail](https://f-droid.org/packages/eu.faircode.email/) on F-Droid
  - [FairEmail](https://play.google.com/store/apps/details?id=eu.faircode.email) on Play Store
+ **Feature highlights:** Displays E-Mail in an easy to read layout, block trackers and helps the user with identifying phishing mails
+ **Source code:** [github.com/M66B/FairEmail](https://github.com/M66B/FairEmail/)


### Instant Messenger

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


### SMS

Writing and receiving SMS.

+ **Name:** QKSMS
+ **Availability:** [QKSMS](https://f-droid.org/de/packages/com.moez.QKSMS/) on F-Droid
+ **Feature highlights:** Lightweight, archiving function
+ **Source code:** [github.com/moezbhatti/qksms](https://github.com/moezbhatti/qksms)


## Multimedia

### Gallery

Managing and viewing your photos and videos.

+ **Name:** Fossify Gallery
+ **Availability:**
  - [Fossify Gallery](https://f-droid.org/de/packages/org.fossify.gallery/) on F-Droid 
  - [Fossify Gallery](https://play.google.com/store/apps/details?id=org.fossify.gallery&hl=gsw) on Google Play
+ **Feature highlights:** Theming support, excluding and including specific directories
+ **Source code:** [Fossify on GitHub](https://github.com/FossifyOrg/)


### Music

Playing your locally stored music.

+ **Name:** Vinyl Music Player
+ **Availability:** [Vinyl Music Player](https://f-droid.org/packages/com.poupa.vinylmusicplayer/) on F-Droid
+ **Feature highlights:** Cover art
+ **Source code:** [github.com/AdrienPoupa/VinylMusicPlayer](https://github.com/AdrienPoupa/VinylMusicPlayer)


### Radio

Listening to online radio stations world wide.

+ **Name:** RadioDroid
+ **Availability:** [RadioDroid](https://f-droid.org/packages/net.programmierecke.radiodroid2/) on F-Droid
+ **Feature highlights:** Modern interface
+ **Source code:** [github.com/segler-alex/RadioDroid](https://github.com/segler-alex/RadioDroid)


### Podcasts

Downloading and streaming podcasts.

+ **Name:** AntennaPod
+ **Availability:** [AntennaPod](https://f-droid.org/packages/de.danoeh.antennapod/) on F-Droid
+ **Feature highlights:** Modern interface, theming
+ **Source code:** [github.com/AntennaPod/AntennaPod](https://github.com/AntennaPod/AntennaPod)


### YouTube

Watching videos on YouTube.

+ **Name:** NewPipe
+ **Availability:** NewPipe can be installed from F-Droid
+ **Feature highlights:** Great performance, more privacy
+ **Source code:** [github.com/TeamNewPipe/NewPipe/](https://github.com/TeamNewPipe/NewPipe/)

**Additional steps**

> If you use Neo Store you can enable the NewPipe source from its settings.

You can install **NewPipe** from F-Droid. But since YouTube often changes its API's it is much better to always
have the latest NewPipe installed. The newest version has some days delay on the official F-Droid repository,
therefore we do the following:

1. Add the official [NewPipe F-Droid Repository](https://newpipe.net/FAQ/tutorials/install-add-fdroid-repo/) to our F-Droid.
2. Refresh the repositories (draw down from the top in the first F-Droid tab)
3. Search for and install NewPipe


### Feed Reader (RSS/Atom)

Keeping up to date with projects you are interested in.

+ **Name:** Flym
+ **Availability:** [Flym](https://f-droid.org/de/packages/net.frju.flym/) on F-Droid
+ **Feature highlights:** Great and simple reader
+ **Source code:** [GitHub](https://github.com/FredJul/Flym)
+ **Hints:** Unfortunately the developer stopped working on the app


### Document Viewer (PDF, ...)

Viewing several document formats.

+ **Name:** MuPDF
+ **Availability:** [MuPDF](https://f-droid.org/packages/com.artifex.mupdf.viewer.app/) on F-Droid
+ **Feature highlights:** Very lightweight
+ **Source code:** [git.ghostscript.com/?p=mupdf-android-viewer.git;a=summary](https://git.ghostscript.com/?p=mupdf-android-viewer.git;a=summary)


## Privacy and security

### Traffic Filter

Blocks trackers and domains that are known to undermine privacy, security and performance in a non-tolerable way.

> **ATTENTION:** Do only use this if you know what you are doing and how to disable it. Sometimes this app may cause your apps to not get any internet connection at all. This might happen due to wrong configuration but also because of bugs. **USE AT YOUR OWN RISK**

+ **Name:** [RethinkDNS](https://rethinkdns.com/app)
+ **Availability:**
  - [RehtinkDNS](https://f-droid.org/de/packages/com.celzero.bravedns/) on F-Droid
  - [RethinkDNS](https://play.google.com/store/apps/details?id=com.celzero.bravedns) on Google Play
+ **Feature highlights:** Choose from a whole bunch of block lists, isolate single apps, exclude others
+ **Source code:** [GitHub](https://github.com/celzero)
+ **Hints:** member of the mozilla builders program

> **HINT:** RethinkDNS creates a local VPN. That means, it does not transfer any of your traffic somewhere else.
> It simply uses the VPN on your phone to filter the traffic directly in your device. If you have trouble using
> a specific app, you can also whitelist/exclude it in the Apps settings.

**Additional steps**

1. Use local blocklists
2. *"Configure" > "DNS"*
3. Enable "System DNS"
4. Enable "Use In-App downloader"
5. *"Device internal blocklists" > "Configure"*
6. Await download
7. Select the blocklists you want to use
  

### Password Manager

Managing and generating strong passwords and login credentials.

+ **Name:** KeePassDX
+ **Availability:** [KeePassDX](https://f-droid.org/packages/com.kunzisoft.keepass.libre/) on F-Droid
+ **Feature highlights:** Modern UI, compatible with desktop KeePass
+ **Source code:** [github.com/Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX)


**Additional steps**

Take your time to read through the instructions and information in the wiki to properly setup you password manager.
