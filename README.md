# TurboPack — Scratch → HTML

Eine moderne, statische GitHub-Pages-Oberfläche für den [TurboWarp Packager](https://packager.turbowarp.org/).

## Schnellstart

1. Den Inhalt dieses Ordners in ein GitHub-Repository auf den Branch `main` hochladen.
2. In **Settings → Pages** bei **Build and deployment** als Source **GitHub Actions** auswählen.
3. Der Workflow `.github/workflows/pages.yml` veröffentlicht die Seite automatisch.

Kein Node.js, kein Build-Schritt und kein eigenes Backend sind für die Oberfläche erforderlich.

## Architektur

Die Seite bindet den offiziellen TurboWarp Packager unter `https://packager.turbowarp.org/` als eingebettete App ein. Dadurch bleibt die eigentliche Scratch-Verarbeitung bei TurboWarp, während deine GitHub-Pages-Seite leichtgewichtig und statisch bleibt.

TurboWarp Packager: https://github.com/TurboWarp/packager
Lizenz des TurboWarp Packagers: MPL-2.0
