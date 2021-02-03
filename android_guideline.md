*[Home](./index.md) > [Android Guideline (en)](./android_guideline.md)*

# Android Guideline

> **PLEASE READ:** The reason these apps are listed here is because they are trustworthy and open source.
> Their developers have no intention to spy on you and no financial interest in your data. On the other
> hand this means they give away their time and hard work for free. Pleaser consider at least 1, 2 or even
> 5€ to them. Of course more is better : ).

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

> **HINT:** Please donate some money at [SimpleMobileTools](https://www.simplemobiletools.com/) if you plan to use the pro features. You can get the pro
> features for free on F-Droid. But it's just fair to donate some € if you can afford it (and I think everyone can).


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
+ **Feature highlights:** Almost everything can be customized
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

> **HINT:** Please donate some money at [SimpleMobileTools](https://www.simplemobiletools.com/) if you plan to use the pro features. You can get the pro
> features for free on F-Droid. But it's just fair to donate some € if you can afford it (and I think everyone can).


