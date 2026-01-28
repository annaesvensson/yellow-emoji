# Emoji 0.9.4

Jede Menge Emoji. Entwickelt von Anna Svensson.

![Bildschirmfoto](screenshot.png)

## Wie man eine Erweiterung installiert

[ZIP-Datei herunterladen](https://github.com/annaesvensson/yellow-emoji/archive/refs/heads/main.zip) und in dein `system/extensions`-Verzeichnis kopieren. [Weitere Informationen zu Erweiterungen](https://github.com/annaesvensson/yellow-update/tree/main/readme-de.md).

## Wie man ein Emoji hinzufügt

Füge `:smile:` oder `[emoji emoji-smile]` zum Text einer Seite hinzu. Hier ist ein [Emoji-Spickzettel](https://github.com/ikatyang/emoji-cheat-sheet). 

## Wie man ein Emoji zu einer Layoutdatei hinzufügt

Benutze das HTML-Format, zum Beispiel `<i class="emoji emoji-smile" aria-label="Lächeln"></i>`.

## Beispiele

Inhaltsdatei mit Emoji:

    ---
    Title: Beispielseite
    ---
    Das ist eine Beispielseite mit Emoji.

    :smile: :grinning: :angry: :heart: :coffee: :thumbsup:

Emoji nach Namen hinzufügen:

    :smile: 
    :heart: 
    :coffee:

Emoji mit Abkürzung hinzufügen:

    [emoji emoji-smile]
    [emoji emoji-heart]
    [emoji emoji-coffee]

Emoji mit HTML hinzufügen:

    <i class="emoji emoji-smile" aria-label="Lächeln"></i>
    <i class="emoji emoji-heart" aria-label="Herz"></i>
    <i class="emoji emoji-coffee" aria-label="Kaffee"></i>

Smileys & Gefühle:

    :grinning:           :smile:              :angry:
    :frowning:           :wink:               :heart_eyes:
    :kissing_heart:      :stuck_out_tongue_winking_eye:
    :joy:                :mask:               :blush:
    :sleeping:

## Einstellungen

Die folgenden Einstellungen können in der Datei `system/extensions/yellow-system.ini` vorgenommen werden:

`EmojiToolbarButtons` = Symbolleistenschaltflächen für die [Edit-Erweiterung](https://github.com/annaesvensson/yellow-edit/tree/main/readme-de.md)  

## Danksagung

Diese Erweiterung enthält [Twemoji 13.0.0](https://github.com/twitter/twemoji) von Twitter. Danke für die schönen Emoji.

Hast du Fragen? [Hilfe finden](https://datenstrom.se/de/yellow/help/).
