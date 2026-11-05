# RM Support office big screen

Full-screen display for the RM Support office TV: rotating slides, Mazal Tov board, people, QR codes, signs and music stations.

- Live: https://david7578433-bit.github.io/office-big-screen/
- `index.html` is the whole app; `config.json` holds what it shows (slides, people, signs, timing); `logo.jpg` is the logo.

## Run it without Tab

Open it in a browser on the TV computer (full screen with F11). It needs to be served by a web server so `config.json` loads:

    python3 -m http.server 8000     # then open http://localhost:8000

Hosting: GitHub Pages (Settings > Pages > `main` / root), or any static host. No server, database or keys.
