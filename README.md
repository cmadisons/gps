# 🛰️ GPS V.2

### ▶️ **[Open the app](https://cmadisons.github.io/gps/)**

Where you are, how fast you're going, and how far to anywhere you've marked.

Best on a phone, outside.

## What it does

| | |
|---|---|
| 🏠 Your address | The actual street you're standing on, not just numbers |
| 📍 Where you are | Your exact spot, and how accurate the fix is |
| 🏃 Speed | How fast you're moving, in mph or km/h |
| 🧭 Heading | Which way you're pointed |
| ⛰️ Altitude | How high up you are |
| 📌 Mark this spot | Save where you're standing and name it |
| ⭐ Your places | Every place you've marked, nearest first, with distance and direction |
|  🗺️ Live map | A real OpenStreetMap that moves with you, with pins for your places |
| 🗺️ Open in Maps | Hands a place off to your maps app for directions |
| 🚶 Trip | How far you've walked, how long, top speed and average |
| 🔎 Find a place | Search any address, town or landmark and jump the map there |
| 🚗 Directions | Real routes along real roads to anywhere you pick |
| 🛣️ Every way there | All the options drawn in blue — tap any to take it |
| ❤️ The best way | The fastest one drawn in red |
| 📍 More than one stop | Add several places and it plans the whole run |
| ✏️ Name places | `364 Waterloo Road ::: home` — your name, address underneath |
| ⏱️ How long you stay | Learns your usual stay at each place (not home) |
| 🕐 The plan | When you'll reach each stop, and whether it'll still be open |
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

**Closing times are yours to set.** Tap 🕐 on a place and type when it
shuts, like `17:30`. The plan then tells you whether you'll make it, and
warns you when it'll be tight.

**Addresses, routes and the map need internet.** Street names and directions come
from OpenStreetMap's free services. Without a connection you still get your
position, distances and the trip — just no address and no map picture.

**Indoors is fuzzy.** Inside a building your device guesses from wifi, which
can be off by a lot. Outside with a clear view of the sky it's within a few
metres. The app tells you how accurate the current fix is.

## Want to add more?

There are comments in [index.html](index.html) showing where to add a new
number to the readout or a new button on a place.
