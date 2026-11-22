# Rayan Rehou | Interactive Portfolio

One-page portfolio laid out like an engineering datasheet. Every project has something visitors can operate:

- **Fig. 1 System map**: click a layer (Device, Network, Server, Data, Interface) to see which projects touch it.
- **Football Analytics Explorer**: the original 56-second walkthrough video, plus links to the live dashboard and repo.
- **4-Bit Digital Logic System**: a working 4-bit ALU (8 of the 16 ops) with Z/C/V/N flags, plus a modulo-60 BCD counter.
- **Smart Temperature Monitor**: simulated DHT22 readings, adjustable alert threshold, serial-monitor log.
- **Circuit Analysis**: RC low-pass filter with live Bode plot and cutoff frequency.
- **Hand-Gesture Controller**: the 21 MediaPipe landmarks, with the planned palm and pinch gestures.
- **Airline Reservation Simulator**: demo video of the 2024 beginner project (in French).
- **Button-Controlled Traffic Light**: demo video plus a clickable simulation that follows the real ESP32 code and timing.
- **Wi-Fi LED Controller**: demo video of the real test, plus a recreation of the ESP32's control page (Turn on / Flash / Turn off, network ESP32-Light, 192.168.4.1) driving a simulated LED.
- An About section with relevant courses, how I work, and what I'm learning now.
- A working terminal (`help`, `projects`, `open alu`, `contact`…), EN/FR toggle, light/dark theme.

All files sit at the top level next to `index.html` (no subfolders), so they can be uploaded to GitHub in one go. No build step.

## Run locally
Open `index.html` in a browser, or run `python -m http.server 8000` and visit http://localhost:8000.

## Publish on GitHub Pages
1. Create a repo named `rayan-rehou.github.io`.
2. Upload every file in this folder (select all, then drag them onto GitHub's upload page).
3. Settings → Pages → Deploy from a branch → `main` / root.

## Edit content
All text lives in the `T`, `P`, `SKILLS`, `REV` and `AWARDS` objects near the top of the `<script>` in `index.html`, in English and French.
