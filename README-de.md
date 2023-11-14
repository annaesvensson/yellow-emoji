<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Emoji 0.8.14

Jede Menge Emoji.

![Bildschirmfoto](emoji-screenshot.png?raw=true)

## Wie man eine Erweiterung installiert

[ZIP-Datei herunterladen](https://github.com/annaesvensson/yellow-emoji/archive/refs/heads/main.zip) und in dein `system/extensions`-Verzeichnis kopieren. [Weitere Informationen zu Erweiterungen](https://github.com/annaesvensson/yellow-update/tree/main/README-de.md).

## Wie man ein Emoji hinzufügt

Füge `:shortcode:` zum Text einer Seite hinzu. Hier ist ein [Emoji-Spickzettel](https://github.com/ikatyang/emoji-cheat-sheet). 

Es ist auch möglich eine `[emoji]`-Abkürzung zu erstellen oder HTML zu benutzen. Du kannst wahlweise einen Stil angeben, beispielsweise `emoji-2x`, `emoji-3x`, `emoji-4x` und `emoji-5x`.

## Beispiele

Emoji hinzufügen:

    :smile: 
    :heart: 
    :coffee:

Emoji mit Abkürzung hinzufügen, verschiedene Größen:

    [emoji emoji-smile]
    [emoji emoji-heart emoji-2x]
    [emoji emoji-coffee emoji-3x]

Emoji mit HTML hinzufügen, verschiedene Größen:

    <i class="emoji emoji-smile" aria-label="Lächeln"></i>
    <i class="emoji emoji-heart emoji-2x" aria-label="Herz"></i>
    <i class="emoji emoji-coffee emoji-3x" aria-label="Kaffee"></i>

Smileys & Gefühle:

    :grinning:           :smile:              :angry:
    :frowning:           :wink:               :heart_eyes:
    :kissing_heart:      :stuck_out_tongue_winking_eye:
    :joy:                :mask:               :blush:
    :sleeping:

## Einstellungen

Die folgenden Einstellungen können in der Datei `system/extensions/yellow-system.ini` vorgenommen werden:

`EmojiToolbarButtons` = Symbolleistenschaltflächen für die [Edit-Erweiterung](https://github.com/annaesvensson/yellow-edit/tree/main/README-de.md)  

## Danksagung

Diese Erweiterung enthält [Twemoji 13.0.0](https://github.com/twitter/twemoji) von Twitter. Danke für die schönen Emoji.

## Entwickler

Anna Svensson. [Hilfe finden](https://datenstrom.se/de/yellow/help/).
