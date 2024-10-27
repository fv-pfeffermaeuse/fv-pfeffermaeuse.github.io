# Website des Förderverein Kneipp-Kita Pfeffermäuse e.V.

Um diese Seite zu bearbeiten, muss ein Account auf  [https://github.com/](https://github.com/) angelegt werden. 
Sobald das getan ist, bitte den Account-Namen an den Förderverein senden, damit der Account zur Benutzergruppe hinzugefügt werden kann. 
Anschließend können die Dateien bearbeitet werden.

# Inhalte
Die Inhalte befinden sich unter [fv-pfeffermaeuse.github.io/tree/main/content](https://github.com/fv-pfeffermaeuse/fv-pfeffermaeuse.github.io/tree/main/content)
Wenn eine neue Seite hinzugefügt werden soll, muss hier ein neuer Ordner angelegt werden.

## Neuen Beitrag erstellen

Wenn ein neuer Beitrag für die Hauptseite geschrieben werden soll, muss im Ordner [content/posts](https://github.com/fv-pfeffermaeuse/fv-pfeffermaeuse.github.io/tree/main/content/posts) ein neuer Unterordner angelegt werden.

In diesem Ordner müssen sich zwei Dateien befinden:
- `index.md` (am einfachsten aus einem der anderen Beiträge kopieren und anpassen)
- Ein Bild, das mit dem Namen `feature-` beginnt. Dieses wird als Cover-Bild benutzt

In der `index.md`-Datei werden im oberen Bereich (abgetrennt durch `---`-Zeichen) die Informationen des Beitrags eingetragen. 
Darunter kann Text geschrieben werden.
Die Informationen sind:
- `title: "Nächstes Vereinstreffen: 12.12.2024"` - Der Titel, der auf der Übersichtseite angezeigt wird. Sollte für einen neuen Beitrag angepasst werden.
- `date: 2024-09-10T00:00:00+01:00` - Der Tag, an dem der Beitrag erscheint. Wird ein Tag in der Zukunft eingetragen, wird der Beitrag erst sichtbar, wenn dieser Zeitpunkt erreicht ist. 
- `categories: ["Post","Blog"]` - Muss nicht angepasst werden
- `draft: false` - Bitte nicht anpassen. Wird dieser Wert auf `true` gesetzt, wird der Beitrag als Entwurf behandelt und nicht angezeigt

## Kontaktformulare verwalten

Die Website ist reines HTML, es gibt keinen Server-Part. 
Das bedeutet auch, dass wir nicht selbst Emails versenden können.
Um trotzdem Kontaktformulare anzubieten (z.B. für die Mitgliederanmeldung) wird der Dienst [FormSpark](https://dashboard.formspark.io/) verwendet. 

Um neue Formulare zu erstellen, bestehende Formulare zu verwalten oder sonstige Änderungen vorzunehmen, müsst ihr euch auf https://dashboard.formspark.io/ mit dem Konto `Mitgliederverwaltung.FVpfeffermaeuse@outlook.de` einloggen. 
Das sendet eine Bestätigungsemail an `Mitgliederverwaltung.FVpfeffermaeuse@outlook.de`, mit der ihr Zugriff auf den Verwaltunsgbereich bekommt.

### ReCaptcha

Um Spam zu verhindern, wurde in alle Formulare [Google ReCaptcha v2](https://developers.google.com/recaptcha/docs/invisible?hl=de) [hinzugefügt](https://github.com/fv-pfeffermaeuse/fv-pfeffermaeuse.github.io/commit/2db6bb99b434c4a3baef1f0ae384814b99d98baa).
Die Prüfung erfolgt gegen ein privates Konto - Wenn das irgendwann nicht mehr funktioniert, muss ein neuer Check erstellt werden. Dafür muss in der Website in jedem Forumlar der Wert für `data-sitekey` mit dem Website-Schlüssel (verfügbar auf `https://www.google.com/recaptcha/admin/site/` wenn ein neues ReCaptcha erstellt wurde) ersetzt werden.

Außerdem muss in Formspark bei jedem Formular der geheime Sicherheitsschlüssel ersetzt werden.