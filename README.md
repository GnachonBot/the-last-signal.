# The Last Signal — The Sanctuary

A standalone, seven-stage fictional GTA RP experience featuring Tiffy and Rick. No server, packages, accounts or external assets required to play.

## Open or publish
Open `index.html` in a browser. To publish on GitHub Pages, create a public repository (e.g. `sanctuary-last-signal`), upload `index.html` to the root of `main`, and select Settings > Pages > Deploy from a branch > main > /(root) > Save. Open the published link and test before sharing. Official guide: https://docs.github.com/en/pages/quickstart

## Customise before sending
Edit the `const CONFIG` section near the start of the script in `index.html`:
- `city`: defaults to `Another city` so the destination stays unnamed.
- `rendezvous`: optional in-character meeting details.
- `inviteUrl`: optional approved public HTTPS server invitation (leave empty to hide).
- `audioUrl`: optional relative file path (e.g. `transmission.mp3`); upload that recording with the HTML. The transcript is already included. No voice recording is supplied.
- `frequency`: defaults to 87.6 MHz; use one decimal between 85.0 and 90.0.
- `phrase`: defaults to `cows and chickens here`; edit the matching visible clues and letter/replies in the HTML if changing it.
- `storageKey`: change the version to start all visitors on a fresh chapter.

## Game master walkthrough (spoilers)
1. Tune radio to 87.6 MHz (use the tuning note if needed) and lock on.
2. Acknowledge the transmission from Tiffy and Rick.
3. Open field notes about the mysterious signal.
4. Choose Fragment B in the Cortex dossier (return route compromised).
5. Enter `Cows and chickens here` (case and punctuation ignored).
6. Read the personal letter to The Sanctuary.
7. Reveal the next contact instructions and choose one of three optional copyable replies.

Progress is saved in browser local storage where available. Reset Experience clears the local progress. Sound defaults to enabled (browser autoplay restrictions may require a click or key press); use the soundtrack button to mute or resume the original 16-bar cinematic soundtrack in `last-signal-score.wav` (approximately 44 seconds, looping). It features an original melody, piano-like keys, strings, bass and percussion. Distinct browser-generated interaction effects are provided for tuning, signal acquisition, unlocking, wrong answers, Cortex, personal packets, hints, the final reveal and replies. Separate music and SFX volume sliders and a master mute are available. No third-party recordings or tracks are used. Music/SFX preferences are saved on the device.

The deployed page checks its own HTML for changes every 30 seconds, on returning to the tab, and on reconnecting. When it sees a newer version, it reloads automatically and attempts to restore the open file, puzzle inputs, reply, packet states and music position. Increment the relay-version meta tag with each release; the HTML fingerprint also detects changes after the initial successful check. Browser background throttling or offline mode can delay checks. The CHECK NOW button triggers a manual check. Six individually addressed family packets are available in file 06. Replies are not sent automatically. No analytics or backend are included.

## Story / privacy
The unexplained signal and intercepted fragments are fictional creative additions. Cortex's intentions are not established. The exact city is deliberately unnamed; the site has no real destination or server invite unless you add one. Keep all details fictional or approved for public sharing: GitHub Pages source is public and puzzle locks are not security. Do not put real private data or secrets in it. Participation is optional; use only within your group's agreed RP and server rules. The site is not yet deployed.