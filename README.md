# mini-apps

Kleine private Web-Apps, getrennt vom antjoy-Projekt. Jede App liegt in einem eigenen Ordner mit `index.html`.

Adresse: https://antjoyapp.github.io/mini-apps/

| App | Ordner |
|---|---|
| Training | `training/` |

Neue App: Ordner anlegen, `index.html` hinein, Link in der Start-`index.html` ergänzen, committen und pushen. GitHub Pages veröffentlicht nach etwa einer Minute.

Hinweise:
- Das Repo ist öffentlich (GitHub Pages im Gratis-Tarif). Keine privaten Daten oder Schlüssel ablegen.
- Jede App speichert im Browser unter einem eigenen `localStorage`-Schlüssel, weil alle Apps dieselbe Adresse teilen.
- Lokal testen: `python3 -m http.server 8000` in diesem Ordner, dann `http://localhost:8000/`.
