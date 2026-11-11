---
title: Forge — Privacy Policy
---

# Forge — Privacy Policy

Effective date: 2026-11-11

Forge is an iPhone app for logging workouts, weigh-ins and food. Forge is published by an
individual developer — the developer named as the seller on Forge's App Store page — not a
company. That developer ("we", "us") is responsible for Forge and for this policy.

## Summary

- Forge has **no account, no login and no server**. We do not receive, see or store the data you
  enter in Forge. (If you contact us, we receive what you send. Apple may give us anonymous crash
  and usage reports if you allow that in iOS; see "Apple".)
- Forge contains **no analytics, no crash-reporting, no advertising and no tracking** software.
- Everything you enter is stored in an encrypted database on your iPhone. Like your other apps'
  data, it is included in your iPhone's iCloud Backup or computer backup if you use one.
- Forge itself goes online for one optional feature only: looking up an unknown food barcode with
  Open Food Facts. That feature is **off until you turn it on**.

## What Forge stores on your iPhone

- Workouts: routines, exercises, sets (weight and reps), personal records, cardio entries, notes.
- Your profile: sex, date of birth, height, activity level, goal weight and any targets you set.
  These are used only for calculations on the phone, such as calorie targets, the "Burned today"
  estimate and body-composition estimates.
- Weigh-ins and body measurements, including readings from a Bluetooth scale (weight and
  impedance) and the body-composition estimates calculated from them.
- Food log, water log, your own foods and saved meals.
- Data from a paired fitness band: steps and activity, heart rate, sleep, blood oxygen, heart rate
  variability, stress, skin temperature, and the alerts Forge works out from those readings.
- Progress photos you take or pick. Copies are kept inside Forge's own storage; they are not added
  to your photo library.
- App settings, and a short error log (Settings → Health & data → Advanced → Diagnostics).
  Figures, quoted text and identifiers are masked in its messages. It leaves the phone only if you
  copy it yourself.

The database is encrypted with SQLCipher. Its key is generated on the phone and kept in the iOS
Keychain.

## Apple Health

Forge works with Apple Health only if you allow it. You choose each data type in the iOS
permission screen.

**Forge can read from Apple Health:**

- Steps and bodyweight, shown next to your workouts and weigh-ins.
- Height, biological sex and date of birth, to fill in your profile.
- Only if you turn on "Show workouts from other apps": workouts and active energy that other apps
  or devices saved, shown on the Today screen.

**Forge can write to Apple Health:**

- Finished workouts (as strength training) with the estimated calories burned.
- Your weigh-ins (bodyweight).
- Only if you turn each one on in Settings: water you log; food you log (calories, protein,
  carbohydrates, fat); and your fitness band's steps, walking and running distance, heart rate,
  resting heart rate, blood oxygen and sleep.

Data read from Apple Health is stored in Forge's database on your iPhone. Forge never uses Health
data for advertising, marketing or data mining, never sells it, and never sends it to us or to any
third party. Health data that Forge stores leaves your iPhone only in ways you control: in your
iPhone's own device backup (see "Backups and exports"), and in files you export and share
yourself.

You can change or withdraw Forge's access at any time in the Health app (your profile picture →
Apps → Forge) or in the iPhone's Settings app. Data Forge already wrote stays in Apple Health
until you delete it there.

## Bluetooth devices

If you turn on a smart scale or a fitness band in Settings → Devices:

- **Scale:** Forge listens for the weight and impedance the scale broadcasts while you stand on
  it. It does not connect to or pair with the scale.
- **Fitness band:** Forge connects to the band to read its stored data and live heart rate, and
  sends it commands, for example setting its clock, starting or ending its workout mode, or making
  it buzz during a workout. Each buzz comes with a short text shown on the band: "Set 3 done" when
  a set is logged, the seconds left (for example "5 s") in a rest's countdown, and "Rest over"
  when a rest ends. Forge can also stay connected to the band in the background to sync it; you
  can switch this off in Settings → Devices → Your band → Keep band connected. The data still goes
  only to Forge on your iPhone.

Forge talks to these devices directly over Bluetooth and sends nothing from them over the
internet. Their readings are stored like the rest of your data (see "Backups and exports" and
"Apple Health"). To stop using a band and remove what it recorded: Settings → Devices →
Your band → Forget band → Delete data.

## Camera and photos

The camera is used to scan a food barcode and to take progress photos. The photo library is used
only when you pick a progress photo. Forge keeps your progress photos inside its own storage on
your iPhone and never uploads them anywhere itself. They are part of your iPhone's device backup,
and they go into an encrypted export only if you turn on "Include photos in backups".

## Optional online barcode lookup (Open Food Facts)

Forge has an offline food list and remembers foods you save. When you scan a barcode Forge does
not know, it can look the product up in Open Food Facts, a free, collaborative food database.

- The lookup is **off by default**. You can turn it on or off at any time in Settings → Food →
  Online barcode lookup. While it is off, Forge asks you each time you scan a barcode it doesn't
  know; "Not now" sends nothing.
- When it is on and you scan an unknown barcode, Forge sends a request over an encrypted (HTTPS)
  connection to `world.openfoodfacts.org`. Forge sends that barcode number, a fixed list of the
  fields it wants back (name, nutrition, serving size) and a fixed app name ("Forge - offline
  fitness app"). It sends no account, name, profile, health data or device identifier. Like any
  internet request, it comes from your phone's internet (IP) address, so Open Food Facts can see
  that a product was looked up from that address.
- The product's name and nutrition values are saved on your iPhone, so the next scan of that
  product works offline.
- Open Food Facts, an association under French law, decides for itself how it handles requests.
  Its privacy policy (https://world.openfoodfacts.org/privacy) says it keeps visitors' IP
  addresses and server logs for up to 3 years for security, technical analysis and popularity
  statistics. We have no agreement with Open Food Facts and receive nothing from it about your
  lookups.

Food data from Open Food Facts is © Open Food Facts contributors and is available under the Open
Database License (ODbL): https://openfoodfacts.org.

## Notifications, widgets and Live Activities

Rest-timer alerts and reminders (training day, weigh-in, water) are **local notifications**
scheduled on your iPhone. They are off until you turn them on. Forge never registers for push
notifications and has no server to send them.

Widgets and the workout Live Activity show your workout, bodyweight and food figures on your Home
Screen or Lock Screen, if you add them. During a workout with a paired band, the Live Activity also
shows your current heart rate. Anyone who can see your Lock Screen can see what they
show.

## App lock

You can lock Forge with Face ID (or your passcode) in Settings → Health & data → App lock. Face ID
is handled by iOS; Forge never sees your face data.

## Backups and exports

- **iPhone backup:** Forge's database, its encryption key and your progress photos are part of
  your iPhone's iCloud Backup and computer backups, so a new or restored iPhone gets your data
  back. The backup is made, stored and protected by Apple under your Apple Account. With Advanced
  Data Protection on, it is end-to-end encrypted; without it, Apple holds the backup's keys. We
  cannot access it. You control iCloud Backup in Settings → [your name] → iCloud → iCloud Backup.
  Forge does not use iCloud Drive, CloudKit or any other iCloud storage of its own.
- **Encrypted export (.dfit):** Settings → Health & data → Advanced → Export a copy creates a file
  encrypted with a passphrase you choose. The file goes wherever you send it from the share sheet.
  Forge's internal database key is never put in the file. Photos are included only if you turn on
  "Include photos in backups".
- **CSV export:** Settings → Health & data → Advanced → Export CSV creates plain, **unencrypted**
  spreadsheet files of your workouts, weigh-ins and food log. Anyone with those files can read
  them.
- **Shared routines:** "Share" in the routine editor creates a file containing only that
  routine's plan (names, exercises and targets), no logged data.

Forge itself sends data off your iPhone only in the optional barcode lookup described above. Your
data can also leave your iPhone in ways you control: your iPhone's device backup, files you
export and share, an error log you copy, and data you allow Forge to write to Apple Health, which
Apple handles under your Health and iCloud settings.

You are responsible for keeping your own backups. An encrypted export can only be opened with the
passphrase you chose; nobody, including us, can recover a lost passphrase or the data in that
file. Encryption protects your data, but no software can promise perfect security: keep your
iPhone protected with a passcode, and remember that widgets and Live Activities show figures on
your Lock Screen.

## No accounts, no analytics, no tracking

Forge has no sign-up or login. It contains no analytics, crash-reporting, advertising or
attribution software, and it does not track you across apps or websites. Forge does not use the
advertising identifier.

## Apple

Forge is distributed through Apple's App Store, and Apple processes data about your download and
device under Apple's own privacy policy. If you allow "Share With App Developers" in iOS Settings
→ Privacy & Security → Analytics & Improvements, Apple may give us crash reports and usage
statistics about Forge, which do not identify you to us. We use them only to fix problems.

## Links and this page

Forge contains links (this policy, Open Food Facts) that open in your browser. Those websites
have their own privacy policies. This page is hosted by GitHub, which processes visitors' data
under its own privacy statement.

## Keeping and deleting your data

Your data stays on your iPhone until you delete it:

- **Delete your data in the app:** Settings → Health & data → Advanced → **Reset & re-seed
  program** permanently deletes your workouts, records, routines, profile, weigh-ins and
  measurements, food and water logs, your own foods and saved meals, progress photos, cardio and
  band data, then loads the starter program again. App settings (such as targets, reminders and
  favourites) and the on-phone error log are kept. It does not delete data in Apple Health, in
  older iPhone backups, or in files you exported. Smaller options there clear only weigh-ins or
  this week's workouts.
- **Band data only:** Settings → Devices → Your band → Forget band → Delete data.
- **Delete the app:** deleting Forge removes its database, photos, widgets' data and error log
  from your iPhone. iOS may keep a small amount of Forge's settings and its database key in the
  iPhone's Keychain after the app is deleted; they contain no workout, food or health records.
- **iCloud Backup:** older iCloud Backups that contain Forge are kept by Apple until you delete
  them in the iOS Settings app (your name → iCloud → Manage Account Storage → Backups).
- **Apple Health:** data Forge wrote to Apple Health is kept by Apple Health. Delete it in the
  Health app (your profile picture → Apps → Forge).
- **Exported files** are wherever you saved them; delete them there.

## Your rights

Forge sends us nothing, so apart from messages you choose to send us, we hold no personal data
about you and there is nothing for us to give you, correct or delete; you can view, export and
delete your data in the app yourself (see above). If you think data protection law applies to how
Forge works, you can contact us (see Contact), and where that law gives you the right, you can
complain to your data protection authority. The optional
barcode lookup happens only when you turn it on and is processed by Open Food Facts as an
independent organisation.

## Children

Forge is not intended for children. It collects no personal information from anyone, including
children.

## Changes to this policy

If a new version of Forge changes what happens to your data, this page will be updated and the
effective date changed.

## Health notice

Forge is not a medical device and does not diagnose, treat or prevent any condition. Calorie
figures and targets (including "Burned today"), body fat and other body-composition values, and
the heart rate, blood oxygen, heart rate variability, stress, sleep and skin-temperature figures
from a fitness band are estimates from consumer devices and formulas. They can be wrong, and body
composition from a foot-to-foot scale is especially rough; use them to follow trends, not as
measurements. Forge's suggestions (calorie, protein and water targets, deload weeks) are general
guidance, not medical advice. Talk to a doctor or other qualified professional before starting a
training or diet programme, and before making any decision about your health.

Forge is provided free of charge under Apple's standard licence agreement for App Store apps.

## Contact

For questions about this policy or Forge, open an issue at
https://github.com/elrato964/forge-privacy/issues (this needs a free GitHub account; issues are
public, so please don't include personal or health details).
