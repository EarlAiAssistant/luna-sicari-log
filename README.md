# Luna & Sicari Log

A small iPhone Home Screen app for logging the dogs' reactions and training sessions, and sharing a summary with the trainer.

- **Log a reaction:** what you noticed, and how each dog responded (three barks, Calm, or Other). Every tap saves.
- **Log a training session:** dog, homework, minutes, date, and a note.
- **Export:** a trainer message, a spreadsheet file (CSV), or a full backup (JSON) through the iPhone share sheet.
- **Dogs:** add, rename, retire, or delete dogs, and edit each dog's photo and homework list.

All entries are stored on the phone only, in the browser storage of the installed Home Screen app. Nothing is sent to a server. Back up from Export > Backup now and then.

## Install on iPhone

1. Open https://earlaiassistant.github.io/luna-sicari-log/ in Safari.
2. Tap Share, then **Add to Home Screen**, then **Add**.
3. Open it from the Home Screen icon (not from Safari), since the two keep separate data.

## Updating

The site is served by GitHub Pages from the `main` branch. After changing any file, bump `VERSION` in `sw.js` so installed copies pick up the new version on their next launch.
