# Field & Veld — installing the beta

Download the file for your device from the
[Releases page](https://github.com/tatendachitima/field-and-veld/releases), then
follow the steps below.

This is a farm record book for Windows and Android. It keeps records of your
fields, crops, plantings, spraying and weeding, scouting reports, harvests,
sales, costs and crew.

It works with **no internet connection**. Nothing about your farm is sent
anywhere. There is no account to sign up for and nothing to pay.

---

## What you need

**On Windows**

- A Windows 10 or Windows 11 computer, 64-bit
- About 350 MB of free space (the installer file itself is 213 MB)
- **No internet connection** — not to install it, not to use it

You do not need to be the computer's administrator. It installs for you only.

**On Android**

- Android 7 or newer, 64-bit (any phone from the last several years)
- About 120 MB of free space (the file itself is 40 MB)

Both files are large because everything they need is packed inside, including
the web components used to draw the app. Nothing is fetched while installing,
so they work the same on a farm with no signal as in town. Copy one over on a
flash drive or by cable.

---

## Installing it on Windows

1. Copy `Field-Veld-0.9.1-x64-setup.exe` onto the computer — from a flash
   drive, or however it reached you.
2. Double-click it.
3. **Windows will try to stop you.** See below. This is expected.
4. Follow the installer. It takes a minute or two.
5. Open **Field & Veld** from the Start menu.

### Windows will warn you — this is normal

You will see a blue box saying **"Windows protected your PC"** and
*"Microsoft Defender SmartScreen prevented an unrecognised app from starting."*

This does not mean anything is wrong with the file. Windows shows this for any
program that has not been through Microsoft's paid signing process, which this
beta has not. To continue:

1. Click **More info**
2. Click **Run anyway**

If you would rather not, that is a fair decision — email
**chitima.tatenda@gmail.com** and wait for a signed version.

---

## Installing it on Android

1. Get `field-and-veld-0.9.1-arm64.apk` onto the phone — downloaded directly,
   sent over, or copied by cable.
2. Open it, usually from **Files** or your browser's downloads.
3. **Android will ask permission first.** Because this did not come from the
   Play Store, Android asks you to allow "install unknown apps" for whichever
   app you opened the file with (Files, Chrome, WhatsApp). Tap through to the
   setting, switch it on, then come back and tap Install.
4. Open **Field & Veld** and set a password.

The app asks for two permissions as you go. Both are refusable and it keeps
working without them:

- **Notifications** — so a sync request from another device can reach you when
  the app is not on screen.
- **Microphone** — only if you record a voice note.

### Updating it later

Install the newer file straight over the old one. Your records are untouched.
If Android refuses with a message about signatures, that means the new file was
signed with a different key than the one you have — say so in an email rather
than uninstalling, because uninstalling *does* delete your records.

### What is not finished on Android yet

- **Voice notes are recorded but not written out to text** on the phone. The
  recording is kept and plays back; the typed-out version only happens on
  Windows for now.
- **Backing up and exporting to a file** is not wired to Android's file picker
  yet. Use the Windows app for backups until it is.

Everything else — records, reports, the worker portal, syncing between
devices — works on both.

---

## The first time you open it

### 1. You choose a password

Your records are locked with it. That is what makes the computer or phone being
stolen, or a backup being lost, not a disaster.

> **Write your password down and keep it somewhere safe, away from the
> device.**
>
> There is no way to reset it. Not by us, not by anyone. The password is not
> checked against a stored answer — it is the key that unscrambles your
> records. Without it nobody can read them, including you.
>
> This is the one part of the app where being careless costs you everything
> on it.

### 2. A short tour runs

Ten screens explaining what to record and in what order. You can skip it and
bring it back later from **Settings → Help → Replay the tour**.

### 3. Have a look around first, if you like

The last card of the tour offers to **load the sample farm** for you — fields,
plantings at different stages, activities and harvests — so you can see what a
season looks like before typing your own. Take it. Prodding a farm that is not
yours is the fastest way to learn where everything lives.

It is also there later under **Settings → Data & sync → Load sample data**, and
**Clear all data** in the same place empties it again when you are ready to
start properly.

---

## Where to start with your own farm

In this order:

1. **Fields** — your blocks of land, with hectares
2. **Crops** — what you grow (there are ready-made Zimbabwean crop templates)
3. **Plantings** — a crop, in a field, on a date

Plantings are the important one. Activities, scouting, harvests and costs all
hang off them. If you only ever record one thing, record your plantings.

Everything else is explained in **Settings → Help**.

---

## Two things worth doing early

### Back up every week

Your records are on this computer and nowhere else. No cloud copy — which is
why it works with no connection — but it also means a dead hard drive takes
everything.

**Settings → Export database**, save it to a flash drive, keep the flash drive
somewhere else. Friday afternoon is a good habit.

The exported copy is locked with your password too, so a lost flash drive is
not a lost farm.

### Put your crew on their phones

**Settings → Worker portal** turns this computer into a small website that
phones on the same wifi can open. No app to install on the phone, no airtime.

Give each worker a PIN under **Labour**. They tap their own name, enter their
PIN, and can log scouting reports and harvests, see their jobs, and ask you a
question. The forms use pictures rather than words, so a worker who cannot read
can still file a proper report.

This only works while this computer is switched on and on the same wifi.

---

## The one thing that does need internet, once

**Voice messages** — recording a spoken reply that gets written out as text —
needs a one-time download of the speech model (75–466 MB) from
**Settings → Voice messages**. Do that where there is decent wifi. After it has
downloaded, it works offline like everything else.

Transcription is **English only** at the moment. Speaking Shona will produce a
poor transcript rather than an error, so record in English if you want the text
to be readable.

---

## If something goes wrong

This is a beta. Things will be rough in places, and finding them is the point.

When something breaks, note:

- what you were doing
- what you expected
- what happened instead
- the date and time

Send that to **chitima.tatenda@gmail.com**. A photo of the screen is worth a lot.

**Your records are not sent with a bug report.** Nothing leaves the computer
unless you export it and hand it over yourself.

---

## Uninstalling

*Settings → Apps → Installed apps → Field & Veld → Uninstall*, the normal
Windows way.

**Your records are not deleted with it.** They stay on the computer, so
reinstalling picks up where you left off. To remove them as well, use
**Settings → Clear all data** inside the app *before* uninstalling.
