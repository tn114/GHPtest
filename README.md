# Kaffee-Umfrage – GitHub Pages Test

Kleine Beispiel-Umfrage als einzelne statische Seite (`index.html`, ohne Build-Schritt).

## Veröffentlichen auf GitHub Pages

1. Auf GitHub ein neues **öffentliches** Repository anlegen, z. B. `GHPtest` (ohne README).
2. Lokal pushen:
   ```bash
   git remote add origin https://github.com/<DEIN-NAME>/GHPtest.git
   git push -u origin main
   ```
3. Im Repo: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**, Ordner **/ (root)** → **Save**
4. Nach ca. 1 Minute ist die Seite erreichbar unter
   `https://<DEIN-NAME>.github.io/GHPtest/`

## Hinweis zu den Antworten

GitHub Pages hostet nur statische Dateien – es gibt keinen Server, der Antworten speichert.
Die Ergebnisse werden deshalb nur im jeweiligen Browser (localStorage) gespeichert.
Für echte, gesammelte Antworten müsste das Formular an einen externen Dienst
(z. B. Formspree, Google Forms, Supabase) senden.
