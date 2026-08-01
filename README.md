# 🛰️ GPS V.2

### ▶️ **[Open the app](https://cmadisons.github.io/gps/)**

Where you are, how fast you're going, and how far to anywhere you've marked.

Best on a phone, outside.

## What it does

| | |
|---|---|
| 📍 Where you are | Your exact spot, and how accurate the fix is |
| 🏃 Speed | How fast you're moving, in mph or km/h |
| 🧭 Heading | Which way you're pointed |
| ⛰️ Altitude | How high up you are |
| 📌 Mark this spot | Save where you're standing and name it |
| ⭐ Your places | Every place you've marked, nearest first, with distance and direction |
|  🗺️ Live map | A real OpenStreetMap that moves with you, with pins for your places |
| 🗺️ Open in Maps | Hands a place off to your maps app for directions |
| 🚶 Trip | How far you've walked, how long, top speed and average |
| 📏 Miles or kilometres | Switch any time |

Your location **never leaves the page**. There's no server to send it to —
everything is worked out on your own device and saved there.

## See the code

📄 **[index.html](index.html)** — the whole app, all in one file

## Run it on your own computer

```bash
git clone https://github.com/cmadisons/gps.git
open gps/index.html
```

## Good to know

**Use the web link, not the file.** Browsers only allow GPS on a real web
address, so opening `index.html` straight off your computer may refuse to
find you. The [online version](https://cmadisons.github.io/gps/) always works.

**Your browser will ask permission** the first time. It has to — no web page
can read your location without you saying yes.

**Indoors is fuzzy.** Inside a building your device guesses from wifi, which
can be off by a lot. Outside with a clear view of the sky it's within a few
metres. The app tells you how accurate the current fix is.

## Want to add more?

There are comments in [index.html](index.html) showing where to add a new
number to the readout or a new button on a place.
