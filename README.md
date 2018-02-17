# Apps working/not-working under microG.
Here is a list of apps that are working and not working under LineageOS for microG. It's WELCOMED for you to [star](https://github.com/prasadkumar013/apps_under_microG/stargazers) and [fork](https://github.com/prasadkumar013/apps_under_microG/network) this project. If you know something that is not here, it'll be great if you could make a [Pull Request](https://github.com/prasadkumar013/apps_under_microG/pulls).

> Tested on LineageOS for microG.  
> Android Version: 7.1.2  
> Device: Oneplus X (Onyx)  
> Model: E1003  

> **Note:** Chromecast API v2 isn't implemented in microG. So unless specified no app listed below can work with Chromecast.

# Table of Contents
## Communication
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[ConnectBot](#connectbot) | v1.9.2 | Working
[Firefox](#firefox) | v58.0.2 | Working
[FolderSync Pro](#foldersync-pro) | v2.9.12 | Working
[Gmail](#gmail) | v8.1.28.185234908.release | Buggy | Doesn't work with Gmail account but can work fine with non-Gmail addresses (Outlook.com, Yahoo Mail, or any other IMAP/POP email). As an alternative use AOSP email app or K9 mail.
[Google Hangouts](#google-hangouts) | v24.0.182154523 | Not Working | App force closes
[Google Voice](#google-voice) | v5.8.184694519 | Working
[Microsoft Edge](#microsoft-edge) | v1.0.0.1656 | Working
[Telegram](#telegram) | v4.6.0a | Working

## Entertainment
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Atom](#atom) | v2.9.3 | Working
[MoviePass](#moviepass) | v3.0.2A | Working
[Stremio Beta](#stremio-beta) | v0.42.3 | Working

## Finance
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Bank of America Mobile Banking](#bofa) | v7.6.8 | Working
[Chase Mobile](#chase) | v3.43 | Working
[Expense Manager Pro](#expense-manager-pro) | v3.4.7 | Working

## Health & Fitness
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Google Fit](#google-fit) | v1.78.03-138 | Not Working | Can't signin. "Couldn't download account information."

## Lifestyle
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Diaro](#diaro) | v3.40.5 | Working

## Maps & Navigation
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Waze](#waze) | v4.34.1.0 | Working | Just give app time to initially get location.

## Music & Audio
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Google Play Music](#google-play-music) | v8.6.6626-1.Z | Working

## Personalization
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Lawnchair](#lawnchair) | v1.1.01742 | Working

## Photography
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Facetune](#facetune) | v1.1.4 | Working
[Google Photos](#google-photos) | v3.14.0.185628364 | Buggy | Everything works except showing "shared library" from "partner account".

## Productivity
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[ACR](#acr) | v27.5 | Working
[ACR Pro License](#acr-pro-license) | v10.0 | Not Working | Reports that the apps isn't installed from PlayStore and so must be reinstalled from there.
[DAVdroid](#davdroid) | v1.10.1.1-ose | Working | Even syncs Google Contacts along with pictures and other info. But only primary calendar is synced.
[Enpass](#enpass) | v5.6.4 | Working | But needs "Google Device Registration" enabled in microG settings to authenticate full version.
[Google Docs](#google-docs) | v1.18.052.05.35 | Working
[Google Keep](#google-keep) | v4.1.051.04.30 | Working
[MiXplorer](#mixplorer) | v6.25.4 | Working
[Pushbullet](#pushbullet) | v17.7.20 | Working

## Shopping
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Walmart](#walmart) | v18.2.1 | Not Working | Doesn't signin. So no Walmart Pay or online shopping.

## Tools
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Gboard](#gboard) | v6.9.8.183626756 | Working
[SMS Backup+](#sms-backup+) | v1.5.11-beta12 | Working

## Travel & Local
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[Google Maps](#google-maps) | v9.71.0 | Working

## Trivia
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[HQ](#hq) | vv1.1.0 | Working

## Weather
|    Name of App    |  Version  | State | Notes |
  ----------------- | --------- | ----- | -----
[AccuWeather](#accuweather) | v5.2.1-free | Working


---
## Communication
### ConnectBot
<img align="right" width="80" height="80" src="/icons/connectbot.png">[ConnectBot](https://connectbot.org) is a powerful open-source Secure Shell (SSH) client. It can manage simultaneous SSH sessions, create secure tunnels, and copy/paste between other applications. This client allows you to connect to Secure Shell servers that typically run on UNIX-based servers.  
[Github](https://github.com/connectbot/connectbot/) | [Google Play](https://play.google.com/store/apps/details?id=org.connectbot) | [F-Droid](https://f-droid.org/packages/org.connectbot/)
### Firefox
<img align="right" width="80" height="80" src="/icons/firefox.png">Experience a fast, smart and personal Web. [Firefox](https://www.mozilla.org/en-US/firefox/mobile/) is the independent, people-first browser made by Mozilla, voted the Most Trusted Internet Company for Privacy. Upgrade today and join hundreds of millions who depend on Firefox for a more personal browsing experience.  
[Mercurial](https://www.mercurial-scm.org/wiki/Download) | [Google Play](https://play.google.com/store/apps/details?id=org.mozilla.firefox)
### FolderSync Pro
<img align="right" width="80" height="80" src="/icons/foldersync-pro.png">[FolderSync](http://www.tacit.dk)enables simple sync to cloud based storage to and from local folders on the device SD cards. It support a wide range of different cloud providers and file protocols, and support for more platforms are added continuously. Root file access supported on rooted devices.  
[Google Play](https://play.google.com/store/apps/details?id=dk.tacit.android.foldersync.full)
### Gmail
<img align="right" width="80" height="80" src="/icons/gmail.png">[Gmail](https://gmail.com) is an easy to use email app that saves you time and keeps your messages safe. Get your messages instantly via push notifications, read and respond online & offline, and find any message quickly. Gmail also supports both Gmail and non-Gmail addresses (Outlook.com, Yahoo Mail, or any other IMAP/POP email) right from the app.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.gm&hl=en)
### Google Hangouts
<img align="right" width="80" height="80" src="/icons/google-hangouts.png">[Google Hangouts](https://hangouts.google.com) bring conversations to life with photos, emoji, and even group video calls for free. Both voice and video calls are supported. Connect with friends across computers, Android, and Apple devices.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.talk&hl=en)
### Google Voice
<img align="right" width="80" height="80" src="/icons/google-voice.png">[Google Voice](https://www.google.com/googlevoice/about.html) gives you a free phone number for calling, text messaging, and voicemail. It works on smartphones and computers, and syncs across your devices so you can use the app while on the go or at home.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.apps.googlevoice)
### Microsoft Edge
<img align="right" width="80" height="80" src="/icons/microsoft-edge.png">[Microsoft Edge](https://www.microsoft.com/en-us/windows/microsoft-edge), now available on Android, creates one continuous browsing experience for Windows 10 users across their devices. Content and data sync seamlessly in the background, so users can browse across devices, without skipping a beat.  
[Google Play](https://play.google.com/store/apps/details?id=com.microsoft.emmx)
### Telegram
<img align="right" width="80" height="80" src="/icons/telegram.png">[Telegram](https://telegram.org), is a messaging app with a focus on speed and security. It’s super-fast, simple, secure and free. Telegram seamlessly syncs across all of your devices and can be used on desktops, tablets and phones alike. You can send an unlimited amount of messages, photos, videos and files of any type (.doc, .zip, .pdf, etc.).  
[Github](https://github.com/DrKLO/Telegram) | [Google Play](https://play.google.com/store/apps/details?id=org.telegram.messenger) | [F-Droid](https://f-droid.org/packages/org.telegram.messenger/)

## Entertainment
### Atom
<img align="right" width="80" height="80" src="/icons/atom.png">[Atom](https://www.atomtickets.com) is the only mobile movie ticketing app that makes it easier than ever to buy movie tickets, make movie plans with friends and get a VIP experience at the movie theater so you never wait in line. Find all the latest new and upcoming movies, watch movie trailers, read movie ratings and reviews and browse movie showtimes directly from the top-rated Atom app.  
[Google Play](https://play.google.com/store/apps/details?id=org.gamatech.androidclient.app)
### MoviePass
<img align="right" width="80" height="80" src="/icons/moviepass.png">[MoviePass](https://www.moviepass.com) is the nation’s premier theatrical subscription service, allowing you to see a movie a day in over 4000 theaters across the United States for one low subscription fee. See any 2D movie in theaters from its first day of release and available in over 4000 theaters nationwide.  
[Google Play](https://play.google.com/store/apps/details?id=com.moviepass.mobile)
### Stremio Beta
<img align="right" width="80" height="80" src="/icons/stremio-beta.png">[Stremio](https://www.stremio.com) is a video streaming application, that allows you to watch and organize video content from different services, including movies, series, live TV and video channels. The content is aggregated by an add-on system providing streams from services like Netflix, iTunes, HBO, YouTube, Twitch and more.  
[Google Play](https://play.google.com/store/apps/details?id=com.stremio.beta) | [Official Website](https://www.stremio.com/downloads)

## Finance
### Chase Mobile
<img align="right" width="80" height="80" src="/icons/chase.png">Do your Chase(https://www.chase.com) banking right from your Android device. You can manage your accounts, make deposits, find ATMs andmore. Now it’s easy to bank 24/7, right from your Android™ device. Tostart, just enroll in Chase Online(SM).  
[Google Play](https://play.google.com/store/apps/details?id=com.chase.sig.android)
### Bank of America Mobile Banking
<img align="right" width="80" height="80" src="/icons/bofa.png">Bank conveniently and securely with the [Bank of America® Mobile Banking](https://www.bankofamerica.com) app for U.S.-based accounts. Manage Your Bank Accounts and Finances. Please see the Online Banking Service Agreement at bankofamerica.com/serviceagreement for more information on these banking features. Your mobile carrier’s message and data rates may apply.  
[Google Play](https://play.google.com/store/apps/details?id=com.moviepass.mobile)
### Expense Manager Pro
<img align="right" width="80" height="80" src="/icons/expense-manager-pro.png">[Expense Manager](https://sites.google.com/site/expensemgr/) is simple, intuitive, stable and feature-rich app that is just designed for you. Everything you need at your fingertips to manage the expenditures, checkbook and budgets.  
[Google Play](https://play.google.com/store/apps/details?id=com.expensemanager.pro)

## Health & Fitness
### Google Fit
<img align="right" width="80" height="80" src="/icons/fit.png">[Google Fit](https://www.google.com/fit/) tracks steps, time, distance, and calories to help you measure and achieve fitness goals. Aggregates info from other apps to track fitness, nutrition, sleep, and weight. Check your progress from your phone, tablet, computer, or Android Wear watch.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.apps.fitness&hl=en)

## Lifestyle
### Diaro
<img align="right" width="80" height="80" src="/icons/diaro.png">[Diaro](https://diaroapp.com) is the easiest and most secure way to keep a diary. Trusted by millions of users worldwide, download now for free and keep your secret diary or diet, travel or life journal securely. Powerful search is also available to help you find diary entries by any keyword in the title or text and filter results by date, folder, tags or location.  
[Google Play](https://play.google.com/store/apps/details?id=com.pixelcrater.Diaro)

## Maps & Navigation
### Waze
<img align="right" width="80" height="80" src="/icons/waze.png">[Waze](https://www.waze.com) is the world's largest community-based traffic and navigation app. Join other drivers in your area who share real-time traffic and road info, saving everyone time and gas money on their daily commute. Get alerted before you approach police, accidents, road hazards or traffic jams, all shared by other drivers in real-time. It's like a personal heads-up from a few million of your friends on the road.  
[Google Play](https://play.google.com/store/apps/details?id=com.waze)

## Music & Audio
### Google Play Music
<img align="right" width="80" height="80" src="/icons/google-play-music.png">[Google Play Music](https://play.google.com/music/listen) provides free, ad-supported radio for what you’re doing, how you’re feeling, or what you want to hear. Instantly start radio stations based on songs, artists, or albums, or browse by genre, mood, activity, decade, and more.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.music)

## Personalization
### Lawnchair
<img align="right" width="80" height="80" src="/icons/lawnchair.png">[Lawnchair](https://lawnchair.info), bringing Pixel Features to the masses. An open-source project developed by volunteers, Lawnchair has quickly become the de-facto choice for Android enthusiasts everywhere. New features are being added regularly... with the promise that Lawnchair will always be FREE and open-source.  
[Github](https://github.com/LawnchairLauncher/Lawnchair) | [Google Play](https://play.google.com/store/apps/details?id=ch.deletescape.lawnchair.plah) | [F-Droid](https://f-droid.org/packages/ch.deletescape.lawnchair.plah/)

## Photography
### Facetune
<img align="right" width="80" height="80" src="/icons/facetune.png">[Facetune](http://www.facetuneapp.com/index.html) provides easy-to-use, powerful tools (previously reserved only for the pros) to retouch and perfect every photo or selfie, making each one look like it came straight out of a high-fashion magazine.  
[Google Play](https://play.google.com/store/apps/details?id=com.lightricks.facetune)
### Google Photos
<img align="right" width="80" height="80" src="/icons/google-photos.png">[Google Photos](https://www.google.com/photos/about/) is a new photo gallery from Google, made for the way you take photos today. Your photos and videos will be automatically backed up and organized, so you can find and share them faster - and never run out of space on your phone.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.apps.photos)

## Productivity
### ACR
<img align="right" width="80" height="80" src="/icons/acr.png">[ACR](http://nllapps.com/apps/acr/) has been available for over 4 years and used by over 4 million active and 20 million total users. They collectively spend total of 33 years and 105 days, individually 16 minutes on ACR every single day! Right now, there are over 10,000 people have ACR open on their phone.  
[Google Play](https://play.google.com/store/apps/details?id=com.nll.acr)
### ACR Pro License
<img align="right" width="80" height="80" src="/icons/acr-pro-license.png">[ACR Pro License](http://nllapps.com/apps/acr/) is the unlock key for ACR. ACR must be installed on the phone to unlock the Pro features. Pro features include ability to record by contact, ability to start recording in the middle of conversation, cloud integration, auto delete short recordings etc.  
[Google Play](https://play.google.com/store/apps/details?id=com.nll.acr.license`)
### Enpass
<img align="right" width="80" height="80" src="/icons/enpass.png">[Enpass](https://www.enpass.io) offers you freedom from remembering too many passwords and other important credentials. It secures them in one place by your master password and makes them accessible anywhere and everywhere - on your smartphones, tablets, or desktops. Also comes with builtin password and TOTP generators.  
[Google Play](https://play.google.com/store/apps/details?id=io.enpass.app)
### DAVdroid
<img align="right" width="80" height="80" src="/icons/davdroid.png">[DAVdroid](https://www.davdroid.com) is the only all-in-one synchronization solution for your contacts (CardDAV), calendars (CalDAV) and your tasks (based on VTODO). The app is easy to set up and integrates perfectly with your favorite calendar/contacts app (including default apps). It can also be used seperately, if you either have CalDAV, CardDAV or only Tasks.  
[GitLab](https://gitlab.com/bitfireAT/davdroid) | [Google Play](https://play.google.com/store/apps/details?id=at.bitfire.davdroid) | [F-Droid](https://f-droid.org/en/packages/at.bitfire.davdroid/)
### Google Docs
<img align="right" width="80" height="80" src="/icons/google-docs.png">Create, edit and collaborate with others on documents from your Android phone or tablet with the [Google Docs](https://www.google.com/docs/about/) app. Create, share and collaborate on docs on your Google Drive.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.apps.docs.editors.docs)
### Google Keep
<img align="right" width="80" height="80" src="/icons/google-keep.png">Quickly capture what’s on your mind and get a reminder later at the right place or time. Speak a voice memo on the go and have it automatically transcribed. Grab a photo of a poster, receipt or document and easily organize or find it later in search. [Google Keep](https://www.google.com/keep/) makes it easy to capture a thought or list for yourself, and share it with friends and family.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.keep)
### MiXplorer
<img align="right" width="80" height="80" src="/icons/mixplorer.png">[MiXplorer](https://forum.xda-developers.com/showthread.php?t=1523691) mix of explorers (SD, FTP, LAN, Cloud and other storage explorers) is a fast, smooth, beautiful, reliable and fully-featured file manager with a simple and intuitive user interface.  
[XDA Labs](https://labs.xda-developers.com/store/app/com.mixplorer)
### Pushbullet
<img align="right" width="80" height="80" src="/icons/pushbullet.png">[Pushbullet](https://www.pushbullet.com) automatically shows you all of your phone's notifications right on your computer. This means you can see who's calling or read and reply to text messages even if your phone is on silent or in another room.  
[Google Play](https://play.google.com/store/apps/details?id=com.pushbullet.android)

## Shopping
### Walmart
<img align="right" width="80" height="80" src="/icons/walmart.png">[Walmart](https://www.walmart.com)'s own shopping app. Award-winning app designed to save time and money. In addition to making purchases from walmart.com, app can be used to search for items from local Walmart store and make payments using Walmart Pay.  
[Google Play](https://play.google.com/store/apps/details?id=com.walmart.android)

## Tools
### Gboard
<img align="right" width="80" height="80" src="/icons/gboard.png">[Gboard](https://www.google.com/inputtools/try/) has everything you love about Google Keyboard—speed and reliability, Glide Typing, voice typing, and more—plus Google Search built in. No more app switching; just search and share, right from your keyboard.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.inputmethod.latin)
### SMS Backup+
<img align="right" width="80" height="80" src="/icons/sms-backup+.png">[SMS Backup+](https://github.com/jberkel/sms-backup-plus/#readme) can automatically backup SMS, MMS and call log entries using a separate label in Gmail / Google Calendar. It is also possible to restore SMS and call log entries back to the phone (MMS not supported yet).  
[Github](https://github.com/jberkel/sms-backup-plus/#readme) | [Google Play](https://github.com/jberkel/sms-backup-plus/#readme) | [F-Droid](https://f-droid.org/packages/com.zegoggles.smssync/)

## Travel & Local
### Google Maps
<img align="right" width="80" height="80" src="/icons/google-maps.png">[Google Maps](https://google.com/maps) is the official mapping service developed by Google. It offers satellite imagery, street maps, 360° panoramic views of streets, real-time traffic conditions, and route planning for traveling by foot, car, bicycle, or public transportation.  
[Google Play](https://play.google.com/store/apps/details?id=com.google.android.apps.maps)

## Trivia
### HQ
<img align="right" width="80" height="80" src="/icons/hq.png">[HQ](https://twitter.com/hqtrivia) is a live trivia app that you play for real money. The game goes live at 3 p.m. and 9 p.m. EST on weekdays and 9 p.m. EST on weekends. The game is hosted by comedian Scott Rogowsky, though he occasionally has substitutes, including British broadcast personality Sharon Carpenter.  
[Google Play](https://play.google.com/store/apps/details?id=com.intermedia.hq)

## Weather
### AccuWeather
<img align="right" width="80" height="80" src="/icons/accuweather.png">Local weather forecast & real time rain, storm, ice & snow reports: enjoy Superior Accuracy™ wherever you are with AccuWeather[AccuWeather](https://www.accuweather.com). Track severe winter weather with weather radar maps, real time weather alerts & the AccuWeather hurricane tracker feature. Get your holiday weather forecast: plan any journey with precision and confidence. Never get caught in the rain again.  
[Google Play](https://play.google.com/store/apps/details?id=com.accuweather.android)
