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
- `categories: ["Post","Blog",]` - Muss nicht angepasst werden
- `draft: false` - Bitte nicht anpassen. Wird dieser Wert auf `true` gesetzt, wird der Beitrag als Entwurf behandelt und nicht angezeigt