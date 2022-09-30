<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Emojiawesome 0.8.12

Jede Menge Emoji.

![Bildschirmfoto](emojiawesome-screenshot.jpg?raw=true)

## Wie man ein Emoji hinzufügt

Füge `:shortcode:` zum Text einer Seite hinzu. Hier ist ein [Emoji-Spickzettel](https://github.com/ikatyang/emoji-cheat-sheet). 

Es ist auch möglich eine `[ea]`-Abkürzung zu erstellen oder HTML `<i class="ea ea-name" aria-label="name"></i>` zu benutzen. Du kannst weitere Stile an den Namen anhängen, beispielsweise `ea-lg`, `ea-2x`, `ea-3x`, `ea-4x` und `ea-5x`.

## Beispiele

Emoji hinzufügen:

    :smile: 
    :heart: 
    :coffee:

Emoji mit Abkürzung hinzufügen, normale Größe:

    [ea ea-smile]
    [ea ea-heart]
    [ea ea-coffee]

Emoji mit Abkürzung hinzufügen, doppelte Größe:
    
    [ea ea-smile ea-2x]
    [ea ea-heart ea-2x]
    [ea ea-coffee ea-2x]

Emoji mit HTML hinzufügen, normale Größe:

    <i class="ea ea-smile" aria-label="Lächeln"></i>
    <i class="ea ea-heart" aria-label="Herz"></i>
    <i class="ea ea-coffee" aria-label="Kaffee"></i>

Emoji mit HTML hinzufügen, doppelte Größe:

    <i class="ea ea-smile ea-2x" aria-label="Lächeln"></i>
    <i class="ea ea-heart ea-2x" aria-label="Herz"></i>
    <i class="ea ea-coffee ea-2x" aria-label="Kaffee"></i>

## Einstellungen

Die folgenden Einstellungen können in der Datei `system/extensions/yellow-system.ini` vorgenommen werden:

`EmojiawesomeToolbarButtons` = Symbolleistenschaltflächen für die [Edit-Erweiterung](https://github.com/datenstrom/yellow-extensions/tree/master/source/edit/README-de.md)  

## Installation

[Erweiterung herunterladen](https://github.com/datenstrom/yellow-extensions/raw/master/downloads/emojiawesome.zip) und die Zip-Datei in dein `system/extensions`-Verzeichnis kopieren. Rechtsklick bei Safari.

Diese Erweiterung benutzt [Twemoji 13.0.0](https://github.com/twitter/twemoji) von Twitter.

## Entwickler

Datenstrom. [Hilfe finden](https://datenstrom.se/de/yellow/help/).
