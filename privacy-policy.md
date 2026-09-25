# Quiet Launcher privacy policy

Last updated: 25 September 2026.

Quiet Launcher is a home screen for Android, published by **Coders Secret**. It has no account,
no server, and no analytics.

**Quiet collects nothing. Nothing it reads is sent anywhere by Quiet.**

The only things that ever leave Quiet are things you choose, at that moment, to hand to another
app on your phone: a reply you type to a notification goes to the app that posted it, and a web
search goes to your browser. Both are described below. The rest of this policy explains what
Quiet reads on your device, why, and how to stop it.

## What stays on your device

These are stored in Quiet's own private storage, which no other app can read:

- Your settings: the layout, grid size, theme, clock, notification, focus and search choices.
- The apps you chose for your home screen, and the widgets you placed.
- Your last five searches, so the search screen can offer them back to you. A search is saved
  only when you open one of its results. **Clear recent searches**, shown above the search field
  when it is empty, removes them immediately.
- If, and only if, you turn on **Keep what you missed**: a record of the last 50 notifications
  Quiet saw. See below for exactly what a record holds and how to delete it.

Quiet's backup is switched off, and both routes out are closed explicitly: cloud backup and
device-to-device transfer. Turning backup off alone is not enough, because on Android 12 and
above, on devices from some manufacturers, it stops the Google Drive copy while leaving the
transfer to a new phone working. So none of this is copied to Google Drive and none of it is
carried to a new phone. That is deliberate: a launcher that says your choices stay on your device
should not have them arrive on the next one by themselves. The cost is that a new phone starts
fresh, unless you carry your settings over yourself.

You can: **Export to a file** in Customize, under Back up settings, writes your settings to a file
you choose in the system's file picker, and **Import from a file** reads one back. Quiet does
nothing with that file but write it or read it at the moment you ask, and sends it nowhere; where
it goes from there, such as a cloud folder, is your choice and that service's policy. The file
holds your settings and your chosen apps. It does not hold your widgets, your recent searches,
the record of what you missed, or any notification, and double tap to lock is never switched on
by an import.

Uninstalling Quiet deletes all of it. Quiet has no copy anywhere else, so there is nothing to
request and nothing to delete on request.

## Notifications

Quiet can show what is waiting on your home screen. This is **off by default** and needs two
separate steps from you:

1. Turning **Notifications on Home** on in Customize.
2. Granting notification access in your device's system settings, which only you can do.

With both done, Quiet reads **which app posted a notification and when**. It does not read
message content unless you also turn on **Show message content**, which is a separate setting
and also off by default.

What Quiet reads is held in memory only, for as long as the notification is on your device.
Turning either setting off stops the reading at once and drops what was held. Revoking
notification access in system settings does the same.

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
  about. Turning the notification panel off does not delete anything, because that switch says
  nothing about deleting and a control that quietly destroys what you kept is worse than the
  thing it was guarding against.
- It is never transmitted, because Quiet has no network permission and nowhere to send it.

Quiet never reads notifications in order to collect, profile, or sell anything, because it does
not collect anything at all.

## App shortcuts in search

While Quiet is your default home app, Android lets it see the shortcuts other apps offer, such as
"New tab" in a browser or a recent conversation in a messaging app. Search can offer these so
you can go straight to them. Some apps name their shortcuts after people, so a shortcut can
include a contact's name.

Quiet reads the shortcut names only to match them against what you type. They are held in memory
only, never written to storage and never sent anywhere. Turning **App shortcuts in search** off
in Customize stops the reading and drops what was held. When Quiet is not your default home app,
Android does not show it other apps' shortcuts at all.

## Double tap to lock

Quiet can lock your phone when you double tap an empty part of Home. This is off by default, is
offered only on Android 9 and later, and needs two separate steps from you: turning **Double tap
to lock** on in Customize, where Quiet first explains what it needs and asks you to agree, and
then switching on Quiet's accessibility service in your phone's system settings, which only you
can do.

Android lets an app lock the screen only through an accessibility service, so Quiet includes one
whose only job is that. It is set up to receive no accessibility events and cannot see what is
on your screen. It does nothing until you double tap Home, and then asks Android to lock the
phone. It reads nothing, stores nothing, and sends nothing.

When you switch the service on, Android shows its own warning about what an accessibility
service could do in general, and asks whether to allow Quiet full control of your device. That
warning is the same for every accessibility service, not a description of this one. Android may
also remind you later that Quiet can view and control your screen, and you can review or switch
off the service from that reminder.

Turning **Double tap to lock** off in Customize switches the service off as well. Where Android
does not let Quiet do that, Customize says the service is still on and takes you to the system
settings where you can switch it off. Uninstalling Quiet removes it entirely.

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
- **An accessibility service**, described above, only if you turn on Double tap to lock and
  switch the service on yourself. It is used for nothing but locking the screen.

Quiet does not request internet access, contacts, calendar, location, storage, microphone,
camera, phone, SMS, or app usage statistics. It does not request permission to see every app
installed on your device; it asks the system only about the specific kinds of app it needs to
launch.

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
anyone itself: a reply you type is handed to the app that posted the notification. Quiet collects
no data from anybody, of any age.

## Security

Everything Quiet keeps is in its own private app storage, which Android keeps from other apps.
Quiet has no network permission, so nothing it holds can be transmitted by it.

## Changes

Any change to this policy will be published on this page, with the date at the top updated.

## Contact

Coders Secret, the developer of Quiet Launcher. Questions about this policy or about your data
can be sent to <coderssecretofficial@gmail.com>.
