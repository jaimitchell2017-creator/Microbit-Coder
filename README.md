# Micro:bit Simulator and Web Flasher

This is a complete static web client that allows users to test, write, compile, and upload code straight into a micro:bit directly from a browser without needing any desktop software installations.

## Features
1. **Interactive Virtual Simulator**: Full 5x5 LED array renderer and functional Button interfaces embedded with custom Web Audio API syntax engines to emulate sounds and note tones natively.
2. **Text Editor**: Write code inside the online interpreter module instantly.
3. **Hex Exporter & Importer**: Generates flashable `.hex` system binaries for real devices instantly.
4. **WebUSB Hardware Flasher**: Implements Chrome / Chromium WebUSB bindings to access physical hardware and flash the micro:bit straight from the web browser without native applications.

## How to Deploy on GitHub Pages
1. Push this workspace code structure into a new repository on your GitHub account.
2. Go to your repository settings -> **Pages**.
3. Under Build and deployment, set Source to **Deploy from a branch** and select your `main` or `master` branch.
4. Click **Save**. Within a few minutes, your online interactive testing dashboard link will go live!
