# Quiet Launcher privacy policy

Last updated: 8 October 2026.

Quiet Launcher is a home screen for Android, published by **Coders Secret**. It has no account,
no server of its own, and no analytics.

**Nothing Quiet reads on your phone, such as your apps, your notifications or your searches, is
sent anywhere by Quiet.**

The only things that ever leave Quiet are things you choose, at that moment, to hand to another
app on your phone: a reply you type to a notification goes to the app that posted it, and a web
search goes to your browser. The one other exception is Quiet Plus, the optional subscription:
it is bought and checked through Google Play, and Google's billing library, which is part of
Quiet, talks to Google Play and sends its own usage logs to Google. Quiet's own code sends
nothing else, and purchases are checked on your phone, with no server of Coders Secret's in
between. All of these are described below. The rest of this policy explains what Quiet reads on
your device, why, and how to stop it.

## What stays on your device

These are stored in Quiet's own private storage, which no other app can read:

- Your settings: the layout, grid size, theme, clock, notification, focus and search choices.
- The apps you chose for your home screen, any folders you made on the home screen or in the
  app drawer and the names you gave those folders, and the widgets you placed.
- Your last five searches, so the search screen can offer them back to you. A search is saved
  only when you open one of its results. **Clear recent searches**, shown above the search field
  when it is empty, removes them immediately.
- If, and only if, you turn on **Keep what you missed**: a record of the last 50 notifications
  Quiet saw. See below for exactly what a record holds and how to delete it.
- If, and only if, you buy Quiet Plus: Google Play's signed receipt for it, in a file of its
  own. See **Quiet Plus and purchases** below.

When you make or rename a folder, Quiet can suggest a name from the category each app declares
to Android, such as Games or Social. It reads those categories on your phone when it reads the
list of your apps, keeps them in memory only, and never stores or sends them.

Quiet's backup is switched off, and both routes out are closed explicitly: cloud backup and
device-to-device transfer. Turning backup off alone is not enough, because on Android 12 and
above, on devices from some manufacturers, it stops the Google Drive copy while leaving the
transfer to a new phone working. So none of this is copied to Google Drive and none of it is
carried to a new phone. That is deliberate: a launcher that says your choices stay on your device
should not have them arrive on the next one by themselves. The cost is that a new phone starts
fresh, unless you carry your settings over yourself.

You can: **Export to a file** in Settings, under Back up settings, writes your settings to a file
you choose in the system's file picker, and **Import from a file** reads one back. Quiet does
nothing with that file but write it or read it at the moment you ask, and sends it nowhere; where
it goes from there, such as a cloud folder, is your choice and that service's policy. The file
holds your settings, your chosen apps and your folders, from the home screen and the app
drawer. It does not hold your widgets, your recent searches, the record of what you missed, any
notification, or your Quiet Plus receipt.

Uninstalling Quiet deletes all of it. Quiet keeps no copy of any of it anywhere else, so there is
nothing of it to request and nothing of it to delete on request. A Quiet Plus purchase is the one
record kept elsewhere: Google Play keeps the purchase, and gives Coders Secret the order details
described under **Quiet Plus and purchases** below, which you can ask about.

## Notifications

Quiet can show what is waiting on your home screen. This is **off by default** and needs two
separate steps from you, in this order:

1. Granting notification access in your device's system settings, which only you can do. In
   Quiet's Settings, under **Notifications on Home**, **Grant notification access** opens that
   system screen.
2. Turning on **Show notifications**, under **Notifications on Home** in Settings. It stays
   unavailable until access is granted.

With both done, Quiet reads **which app posted a notification and when**. It does not read
message content unless you also turn on **Show message content**, which is a separate setting
and also off by default.

What Quiet reads is held in memory only, for as long as the notification is on your device.
Turning **Show notifications** off stops the reading at once and drops what was held, and
turning **Show message content** off does the same for message content. Revoking notification
access in system settings stops the reading and drops what was held as well.

### Replying and actions

A notification can carry its own buttons, such as Reply or Mark as read. Quiet shows them on
Home so you can use them without opening the app. With **Show message content** off, only Reply
is shown, because other buttons can repeat the message in their labels.

Nothing is sent unless you tap it. When you tap **Send**, the text you typed is handed to the app
that posted the notification, which is what sends it on, exactly as if you had replied from the
notification shade. Quiet keeps no copy of what you typed.

Clearing a notification on Home, by swiping it away or with the **Clear notifications** button,
clears it from your notification shade as well, so the two never disagree about what is waiting.

### Keep what you missed

There is one exception to "in memory only", and it happens only if you ask for it. **Keep what
you missed** is a third setting, off by default, alongside the two above. With it on, Quiet
writes down each notification it sees so you can read what arrived after it has gone from the
shade.

- It keeps the **last 50** and no more. The fifty-first pushes the oldest out.
- Each record holds the app, the time, and the message title and text **only if you have Show
  message content on**. With that off, nothing of the message is extracted, so there is nothing
  of it to write down: the record is an app name and a time.
- It is a file in Quiet's own private storage, which no other app can read, and it is not backed
  up.
- **Clear the record** on the "What you missed" screen deletes it, and it stays deleted:
  notifications still sitting in your shade are not filed again afterwards. Turning the setting
  off deletes it too, rather than merely stopping it growing.
- Turning **Show message content** off deletes the titles and message text already in the record,
  not only the ones still to come. The app and the time stay; those are not what that switch is
  about. Turning **Show notifications** off does not delete anything, because that switch says
  nothing about deleting and a control that quietly destroys what you kept is worse than the
  thing it was guarding against.
- It is never transmitted. Quiet's own code has nowhere to send it, and Google's billing
  library and the Google libraries that come with it, the only parts of Quiet that use the
  network, are never given it.

Quiet never reads notifications in order to collect, profile, or sell anything, and nothing it
reads from them leaves your phone.

## App shortcuts in search

While Quiet is your default home app, Android lets it see the shortcuts other apps offer, such as
"New tab" in a browser or a recent conversation in a messaging app. Search can offer these so
you can go straight to them. Some apps name their shortcuts after people, so a shortcut can
include a contact's name.

Quiet reads the shortcut names only to match them against what you type. They are held in memory
only, never written to storage and never sent anywhere. Turning **App shortcuts in search** off
in Settings stops the reading and drops what was held. When Quiet is not your default home app,
Android does not show it other apps' shortcuts at all.

## Double tap to lock

Double tap to lock is part of Quiet Plus, on Android 9 and later. With it on, a double tap on an
empty part of your home screen turns the screen off and locks your phone. It is **off by
default** and needs two steps from you:

1. Turning on **Double tap to lock** in Quiet's Settings, under Home screen. Quiet first explains
   what it needs, and goes on only if you choose **Agree**. **Not now** saves nothing.
2. Switching on Quiet Launcher in Android's accessibility settings, which Quiet opens next and
   only you can change.

Android lets an app turn the screen off and lock the phone only through an accessibility
service, so Quiet includes one whose only job is that, and uses it for nothing else. It is set up
to receive no accessibility events and cannot see what is on your screen. It does nothing until
you double tap an empty part of the home screen, and then asks Android to lock the phone. It
collects nothing, stores nothing and sends nothing.

When you switch the service on, Android shows its own warning about what an accessibility service
could do in general. Depending on the Android version it asks whether to use Quiet Launcher, or
whether to allow it full control of your device. That warning is the same for every accessibility
service, not a description of this one. Android may
also remind you later, with a notification of its own, that the service is on, and you can review
or switch it off from there.

Turning **Double tap to lock** off in Quiet's Settings stops it and switches the service off. If
Quiet cannot switch it off, Quiet opens Android's accessibility settings so you can switch it off
there, and Settings says the service is still on and offers **Open accessibility settings**, which
Settings shows whenever the service is on, with Quiet Plus or without. You can also switch Quiet Launcher off in Android's accessibility settings at any time.
Uninstalling Quiet removes the service entirely.

Your choice is saved with your other settings and is part of **Export to a file**. The
accessibility service is not: you switch it on on each phone, so on a phone where it is off, the
setting reads off and a double tap does nothing but say why.

## Quiet Plus and purchases

Quiet is free to use. Quiet Plus is an optional subscription, bought through Google Play, that
adds extra features. Apart from the short daily check described below, nothing in this section
happens until you open the Quiet Plus screen.

- **Google Play takes the payment.** Google Play processes every purchase, under Google's own
  terms and [Google's privacy policy](https://policies.google.com/privacy). Coders Secret never
  sees your card or any other payment details. Like every seller on Google Play, Coders Secret
  receives from Google Play, in its Play Console reports, the details of each order: the order
  number, the plan bought and its price, the buyer's approximate location (country, state or
  region, city and postal code, which Google Play takes from the payment profile) and the model
  of the device it was bought on. Coders Secret uses them only for its accounts, for tax and to
  look up an order if you ask for help. Questions or requests about them can be sent to the
  address under **Contact** below.
- **Checked on your phone.** Quiet checks each purchase on your phone, against the signature
  Google Play puts on it. There is no server of Coders Secret's in between, and Quiet sends
  nothing about your purchase to Coders Secret.
- **The receipt.** If you buy Quiet Plus: Google Play's signed receipt for it (order number,
  product, purchase time, purchase token, and whether it renews and has been confirmed), kept so
  Plus works offline. Quiet sends it only back to Google Play, through Google's billing library,
  to confirm and check the purchase. It is not backed up, and uninstalling deletes it. It is kept
  in a private file of its own, apart from your settings, and is not part of **Export to a
  file**.
- **Google's billing library.** To sell and check Quiet Plus, Quiet includes Google Play's
  billing library, made by Google. It talks to Google Play to show the plans and their prices,
  to make a purchase, to confirm it, and to check whether Plus is still active. Google also has
  the library send its own usage logs to Google, which Google describes as records of how the
  library is used, such as whether a request worked, and of connection problems; Google does not
  list exactly what they hold. They are handled under Google's privacy policy. Quiet's own code
  adds nothing to them and sends nothing else.
- **When it connects.** The library connects to Google Play when you open the Quiet Plus screen,
  buy or restore, and at most once a day for a short check when one of Quiet's screens comes to
  the front, so that Quiet notices a renewal, a cancellation or a refund. That check never runs
  as your phone starts or in the first minute after Quiet starts, and Home never waits for it.
- **Cancelling.** Uninstalling Quiet does not cancel Quiet Plus. Manage or cancel it in Google
  Play. Your purchase history stays with Google Play, under Google's privacy policy.
- **Review codes.** A review code entered on the Quiet Plus screen, such as the ones Coders
  Secret gives to Google Play's app reviewers, is checked on your phone and kept only on your
  phone, in a private file of its own that is not backed up, is not part of **Export to a file**
  and is deleted after the code expires or when Quiet is uninstalled.

## Permissions

Quiet requests as little as it can:

- **Set wallpaper** (`SET_WALLPAPER`), to set a wallpaper you chose. Quiet cannot read your
  existing wallpaper, and does not ask for the permission that would allow it.
- **Expand the notification shade** (`EXPAND_STATUS_BAR`), for the swipe-down gesture. It grants
  no ability to read anything.
- **Request an uninstall** (`REQUEST_DELETE_PACKAGES`), for Uninstall in an app's options. It
  only lets Quiet ask: Android shows its own confirmation, and nothing is removed unless you
  agree there.
- **Notification access**, described above, only if you grant it.
- **An accessibility service**, described under **Double tap to lock** above, only if you switch
  it on yourself in Android's accessibility settings. Quiet takes you there only after you agree
  to its explanation. It is used for nothing but locking the phone.
- **Google Play billing service** (`com.android.vending.BILLING`), which Google's billing
  library adds, so Quiet can offer Quiet Plus through Google Play. It lets Quiet ask Google Play
  to show its purchase screen and to say whether you have Plus. It gives Quiet no access to your
  payment details.
- **Full network access** (`INTERNET`) and **View network connections**
  (`ACCESS_NETWORK_STATE`), which the Google libraries that come with the billing library add, so
  that the billing library can send its usage logs to Google, as described under **Quiet Plus
  and purchases**. Quiet's own code does not use them.

Quiet does not request contacts, calendar, location, storage, microphone, camera, phone, SMS or
app usage statistics. It does not request permission to see every app installed on your device;
it asks the system only about the specific kinds of app it needs to launch.

Photos you choose as a wallpaper come through the Android photo picker, which shows Quiet the
one image you picked and nothing else in your library.

## Other apps

Widgets you add to your home screen are provided by other apps and drawn by Android. What a
widget shows and does is that app's business and is covered by that app's own privacy policy,
not this one. Quiet decides only how much room a widget gets.

Opening an app, a shortcut or a search result from Quiet hands you to that app, which is likewise
covered by its own policy. **Open in browser** in search hands the words you typed to your
browser or search app, which then searches for them under its own policy. Quiet itself sends
them nowhere.

## Children

Quiet has no accounts, no content feed and no advertising, and it does not communicate with
anyone itself: a reply you type is handed to the app that posted the notification. Quiet's own
code collects no data from anybody, of any age. Quiet Plus is bought through Google Play, whose
own rules and settings decide who can make a purchase on a Google account.

## Security

Everything Quiet keeps is in its own private app storage, which Android keeps from other apps.
Quiet's own code sends nothing it holds anywhere. Quiet's network permissions come with Google's
billing library, which uses them only for Quiet Plus and its own usage logs, as described under
**Quiet Plus and purchases**.

## Changes

Any change to this policy will be published on this page, with the date at the top updated.

## Contact

Coders Secret, the developer of Quiet Launcher. Questions about this policy or about your data
can be sent to <coderssecretofficial@gmail.com>.
