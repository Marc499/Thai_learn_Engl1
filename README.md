💖 English for My Love – English Learning App with Lukas 🇹🇭 🇬🇧 🇩🇪
​Eine interaktive Web-App für thailändische Muttersprachlerinnen zum Englischlernen. Die App kombiniert Alltagssätze mit romantischen Beziehungsmomenten und nutzt Spaced Repetition (Karteikarten-Wiederholung) sowie einen freundlichen animierten deutschen Tutor namens Lukas.
🚀 Live-Demo auf GitHub Pages
Die App ist hier erreichbar:
https://marc499.github.io/Thai_learn_Engl1/

🛠️ Veröffentlichen
Das Deployment läuft über GitHub Pages im Branch-Modus — dafür ist kein
eigener Actions-Workflow nötig, da die App aus einer einzelnen statischen
`index.html` besteht.

Einstellung unter Settings → Pages: **Source: „Deploy from a branch"**,
Branch `main`, Ordner `/ (root)`.

Jeder Push auf `main` veröffentlicht die Seite danach automatisch neu; der
Build „pages build and deployment" erscheint unter dem Reiter **Actions**
und braucht ca. 1 Minute.

Wichtig: `index.html` muss im Wurzelverzeichnis von `main` liegen — das ist
hier der Fall. Die leere Datei `.nojekyll` verhindert, dass Jekyll die Seite
umbaut.
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
