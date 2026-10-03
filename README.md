# Neph – Releases

Hier liegen die Installationspakete und Update-Manifeste des Browsers **Neph**. Der Quelltext von Neph selbst ist nicht Teil dieses Repositorys.

**Download:** https://github.com/Casp3r1918/neph-releases/releases/latest/download/NephSetup.exe

Das Setup installiert ohne Administratorrechte nach `%LOCALAPPDATA%\Programs\Neph`. Installierte Kopien prüfen beim Start und alle sechs Stunden das `manifest.json` des neuesten Releases, laden nur geänderte Dateien und übernehmen sie beim nächsten Neustart; startet eine neue Version nicht, kehrt Neph zur vorigen zurück.

Neph baut auf dem Chromium Embedded Framework auf (BSD-3-Clause). Das darin enthaltene ffmpeg steht unter der LGPL 2.1; das Quelltextangebot dazu liegt jedem Release als `Neph-<Version>-Quellen.md` bei und im Repository `neph-chromium`.
