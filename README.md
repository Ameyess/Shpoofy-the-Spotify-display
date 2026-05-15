# Shpoofy-the-Spotify-display
Shpoofy is a compact, circular display that shows the album art of whatever you're currently listening to on Spotify, in real time. It sits on a custom 3D-printed stand shaped like a vinyl record, powered entirely through a single USB-C cable that routes cleanly through the enclosure. The entire project is self contained and does not show any extra wires. 

## Why I Built This
 
I spend a lot of time at my desk and I wanted a physical, always-on display for whatever I'm listening to without having to glance at my phone. The vinyl record  felt like a natural fit for a music display, and I wanted to design an enclosure that looked intentional rather than just a screen duct-taped to a stand. The display uses a 1.28in round screen with a built-in ESP32 microcontroller. The ESP32 connects to Wi-Fi and polls the Spotify API to fetch the currently playing track's album art, then renders it on the circular display. The code was written in VS Code using the PlatformIO extension, which handles deploying firmware directly to the ESP32.

## Project Images
