💖 English for My Love – English Learning App with Lukas 🇹🇭 🇬🇧 🇩🇪
​Eine interaktive Web-App für thailändische Muttersprachlerinnen zum Englischlernen. Die App kombiniert Alltagssätze mit romantischen Beziehungsmomenten und nutzt Spaced Repetition (Karteikarten-Wiederholung) sowie einen freundlichen animierten deutschen Tutor namens Lukas.
🚀 Live-Demo auf GitHub Pages
Sobald der Workflow einmal gelaufen ist, ist die App hier erreichbar:
https://marc499.github.io/Thai_learn_Engl1/

🛠️ Veröffentlichen via GitHub Actions (empfohlen)
Dieses Repository enthält den Workflow `.github/workflows/deploy-pages.yml`.
Er lädt den Repository-Inhalt als statische Seite zu GitHub Pages hoch und
aktiviert Pages dabei automatisch (`actions/configure-pages` mit `enablement: true`).
Es muss also nichts im Settings-Dialog gespeichert werden.

1. Diesen Branch nach `main` mergen.
2. Unter dem Reiter **Actions** läuft „Deploy to GitHub Pages" an
   (alternativ von Hand über **Run workflow** starten).
3. Nach ca. 1–2 Minuten steht die URL oben im Workflow-Job und unter Settings → Pages.

Falls Pages später auf „Deploy from a branch" zurückgestellt wurde: unter
Settings → Pages als **Source** wieder **GitHub Actions** auswählen, dann greift
der Workflow.

🔁 Alternative: Deploy from a branch
Settings → Pages → Source: „Deploy from a branch", Branch `main`, Ordner `/ (root)`, dann Save.
Wichtig: `index.html` muss dafür im Wurzelverzeichnis von `main` liegen — das ist hier der Fall.
​✨ Features der App
​💖 Romantische & Alltags-Kategorien: 30 ausgewählte Sätze für Beziehungs- und Alltagssituationen.
​🔊 Audio-Ausgabe: Automatische Sprachausgabe (Text-to-Speech) für die englische Aussprache per Knopfdruck.
​🇹🇭 Karaoke-Thailändisch: Lautschrift/Phonetikhilfe zur leichten Orientierung beim Lesen.
​🇩🇪 Deutsche Übersetzung: Zur Kontrolle für den Partner.
​🇩🇪 Virtueller Tutor "Lukas": Vektor-animierter deutscher Charakter, der ermutigende Tipps und Sprüche gibt.
​⏱️ Spaced Repetition System (SRS): Wiederholungsintervalle (1 Min, 10 Min, 1 Tag, 3 Tage) wählbar.
​💾 Automatisches Speichern: Der Lernstatus und gelernten Karten werden direkt im Browser (localStorage) gespeichert.
​📱 Nutzung auf dem Smartphone
​Deine Partnerin kann die GitHub-Pages-URL einfach im Safari- oder Chrome-Browser öffnen und die Seite zum Home-Bildschirm ihres Handys hinzufügen ("Zum Home-Bildschirm ("Add to Home Screen")"), sodass sie wie eine normale App funktioniert.
