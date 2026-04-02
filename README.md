# Atom Engine

Atom Engine is a browser‑based atomic simulation built with Python and packaged for the web using pygbag.  
It runs entirely in the browser with no installation required.

##  Live Web App
You can run the simulator directly here:

https://Koda64.github.io/atom-engine/

##  Features
- Interactive atomic model visualization  
- Electron shells and particle layout  
- Runs fully in WebAssembly Python  
- Installable as a PWA (Add to Home Screen)  
- Works on desktop and mobile browsers  

##  Project Structure
This repository contains the exported `web` build from pygbag:

- `index.html` — main entry point  
- `favicon.png` — browser tab icon  
- `icon-192.png` — PWA app icon  
- `icon-512.png` — high‑resolution PWA icon  
- `.wasm`, `.data`, `.js` — WebAssembly runtime files  
- `atomengine.tar.gz` — packaged game assets  

##  Install as an App
On Chrome (Android):

1. Open the live link  
2. Tap the menu (⋮)  
3. Select **Add to Home Screen**  
4. Launch Atom Engine like a native app  

##  Built With
- Python 3.12  
- pygbag 0.9.3  
- WebAssembly  

##  License
This project uses the default pygbag template license.
