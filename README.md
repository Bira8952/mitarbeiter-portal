# Team-Portal

Infos und Anleitungen für das Team – auf dem Handy und am Computer.
Die ganze App ist eine einzige Datei: `index.html`. Die Daten liegen in Firebase.

**Adresse, sobald GitHub Pages eingeschaltet ist:**
https://bira8952.github.io/mitarbeiter-portal/

## 1. Online stellen mit GitHub Pages (einmalig, kostenlos)

1. Oben in diesem Repository auf **Settings** tippen, dann links auf **Pages**.
2. Unter **Build and deployment** → **Source**: **Deploy from a branch** wählen.
3. Bei **Branch**: `main` und daneben `/ (root)` wählen → **Save**.
4. 1–2 Minuten warten. Oben auf der Seite erscheint dann «Your site is live at …».

## 2. Firebase einstellen (einmalig)

1. [Firebase-Konsole](https://console.firebase.google.com) → Projekt öffnen → **Authentication** → **Settings** (Einstellungen) → **Authorized domains** (Autorisierte Domains) → **Add domain** → `bira8952.github.io` eintragen → **Add**.
2. Das Portal unter der neuen Adresse **einmal als Leitung öffnen**. Dabei werden ältere Beiträge für die neuen Regeln vorbereitet.
3. Erst danach: **Firestore Database** → **Rules** (Regeln) → den ganzen Inhalt der Datei `firestore.rules` einfügen → **Publish** (Veröffentlichen).

Wichtig ist die Reihenfolge bei Schritt 2 und 3: Werden die Regeln vorher veröffentlicht, sieht das Team die älteren Beiträge erst, nachdem eine Leitungsperson das Portal geöffnet hat.

## 3. Aufs Handy

Adresse im Browser öffnen → **Teilen** → **Zum Home-Bildschirm**. Dann startet das Portal wie eine App, mit eurem Logo als Symbol.

## Neue Version hochladen

1. In diesem Repository **Add file** → **Upload files**.
2. Die neue `index.html` hineinziehen → **Commit changes**.
3. Nach 1–2 Minuten ist sie online. Die Seite neu laden.

Ändert sich auch `firestore.rules`, den neuen Inhalt wie in Schritt 2.3 in Firebase einfügen.
