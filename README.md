# Shpoofy-the-Spotify-display
Shpoofy is a compact, circular display that shows the album art of whatever you're currently listening to on Spotify, in real time. It sits on a custom 3D-printed stand shaped like a vinyl record, powered entirely through a single USB-C cable that routes cleanly through the enclosure. The entire project is self contained and does not show any extra wires. 

## Why I Built This
 
I spend a lot of time at my desk and I wanted a physical, always-on display for whatever I'm listening to without having to glance at my phone. The vinyl record  felt like a natural fit for a music display, and I wanted to design an enclosure that looked intentional rather than just a screen duct-taped to a stand. The display uses a 1.28in round screen with a built-in ESP32 microcontroller. The ESP32 connects to Wi-Fi and polls the Spotify API to fetch the currently playing track's album art, then renders it on the circular display. The code was written in VS Code using the PlatformIO extension, which handles deploying firmware directly to the ESP32.

## Project Images

### Final Assembly
<img width="738" height="814" alt="image" src="https://github.com/user-attachments/assets/b8e55510-1f3a-4d64-9020-43f0612e3918" />

### Vinyl Assembly
<img width="1243" height="779" alt="image" src="https://github.com/user-attachments/assets/80fdfab7-7054-47a3-809d-dddc6334174e" />

### Stand & Enclosure
The stand features a cutout to house the power bank and cable routing channels to keep everything clean.
<img width="778" height="823" alt="image" src="https://github.com/user-attachments/assets/c36091ce-8065-4337-9405-6b5b3571b80b" />
<img width="735" height="760" alt="image" src="https://github.com/user-attachments/assets/503b4aac-23de-4460-a595-6573a69df876" />


## Wiring Diagram
![Wiring Diagram](https://stasis.hackclub-assets.com/images/1778348669043-0pixxb.png)

The wiring is about as simple as it gets. The 1.28in round display has a built-in ESP32, so there's no separate microcontroller or soldering involved. A single USB-C cable powers the whole thing, it routes through a dedicated cutout in the enclosure and plugs into either a power bank (housed in the stand) or a wall plug.

<img width="820" height="789" alt="image" src="https://github.com/user-attachments/assets/76ca1b29-539e-4b39-8aba-ca921fbac6ab" />

Wiring Channels in Vinyl assembly
<img width="1914" height="964" alt="image" src="https://github.com/user-attachments/assets/d72e2a13-6eed-4fb6-8ee5-ba300f52ade0" />

## Bill of Materials

| # | Name | Purpose | Qty | Total Cost (USD) | Distributor |
|---|------|---------|-----|-----------------|-------------|
| 1 | [Heat Set Inserts](https://www.aliexpress.com/item/1005006302728370.html) | Joining 3D printed parts to the ESP32 board during assembly | 1 | $1.50 | AliExpress |
| 2 | [1.28in Round Display (w/ built-in ESP32)](https://www.aliexpress.com/item/1005012049323480.html) | Displaying the Spotify album art | 1 | $15.14 | AliExpress |
 


