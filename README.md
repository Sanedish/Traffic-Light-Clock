# Traffic Light Clock

A massive, wall-mounted 7-segment digital clock where each segment is constructed from genuine, full-sized American traffic lights. This repository will house the firmware, schematics, and 3D modeling/mounting files needed to bring this oversized display to life.

## Project Overview

Traditional 7-segment displays use simple LEDs, but this clock supersedes them in scale. Each of the 7 segments in standard 4-digit or 6-digit layouts will be represented by an individual traffic light (e.g., using the green, yellow, and red lenses, together, as the actual display segments). 

## Planned Features

* **Real Time Clock (RTC):** Precise timekeeping using an RTC module (e.g., DS3231).
* **GPS Time Sync:** Using an inexpensive GPS module to collect the current time and dare from GPS/GLONASS.
* **Segment Switching:** Custom relay or solid-state drivers to safely handle the mains voltage of the traffic lights.
* **Web UI / Bluetooth Control:** Modifying clock settings, cycling animations, or changing color combinations via a local network connection (planned with an ESP32).
* **Audio output:** Clock may have the ability to output audio. This feature is undecided.

## Work in Progress (WIP)

This project is currently in the **planning and component-sourcing phase**. 
* Acquire traffic lights - Done
* Plan the rest of the project - In progress

## Tech Stack & Hardware

* **Microcontroller:** TBD (likely ESP32 for Wi-Fi/Bluetooth capabilities)
* **Driver:** Relays or custom MOSFETs for traffic light voltage switching
* **Time Module:** DS3231 RTC (not set in stone yet)
* **GPS Module:** TBD
* **Audio Output:** TBD

## Contributing
Since this is a massive WIP, ideas and contributions are highly encouraged! Feel free to open issues to discuss mounting ideas, wiring configurations, or driver designs.

Planning discussions happen in the #bodens-clock channel of the Chris Boden community discord. Invite here: https://discord.gg/aDsF6qCkbN

*Stay tuned for schematics and code updates!*