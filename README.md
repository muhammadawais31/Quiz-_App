# Quizly – Interactive Quiz

## Run
1. Unzip the folder.
2. Double-click `index.html` to open it in any modern browser (internet needed once for the Tailwind and jsPDF CDN scripts).

Optional local server: `python3 -m http.server 8000` then open http://localhost:8000

## Customize
- Edit the `BANK` array in `index.html` to add or change questions (`c` is the index of the correct answer).
- Change `TIME` for the per-question countdown (seconds).
- Change `.slice(0,5)` in `start()` to use more or fewer questions per round.
