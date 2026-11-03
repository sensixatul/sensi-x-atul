SENSI X ATUL — Termux Starter Project

WHAT IT IS
A mobile-friendly installable PWA (website that can be added to the phone home screen).
It does not modify Free Fire, read game files, or provide cheats. Values are illustrative starter presets,
not official or guaranteed settings. Adjust them in training/practice and save your own setup.

RUN IN TERMUX
1. Install Termux from a trusted source.
2. Open Termux and run:
   pkg update -y
   pkg install python unzip -y
3. Extract this ZIP into a folder named sensi_x_atul.
4. Enter the folder:
   cd sensi_x_atul
5. Start local server:
   python -m http.server 8080
6. Open Chrome on your phone:
   http://127.0.0.1:8080
7. In Chrome menu, choose "Add to Home screen" or "Install app" if offered.

PUBLISH
Upload index.html, manifest.json, sw.js, and logo.svg to a static HTTPS host such as GitHub Pages.
After publishing, open the HTTPS website on Android Chrome and choose Install/Add to Home screen.
A public HTTPS URL is required for normal PWA installation and service-worker support.

CUSTOMIZATION
- Gun list and device brands are in index.html.
- Presets are generated in the generate() function.
- All saved setups are stored locally in the browser on that device.

IMPORTANT
This is an unofficial fan-made utility and is not affiliated with Garena.
Free Fire and related marks belong to their respective owners.
