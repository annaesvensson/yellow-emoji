<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Emojiawesome 0.8.12

Massor och massor av emoji.

![Skärmdump](emojiawesome-screenshot.jpg?raw=true)

## Hur man lägger till en emoji

Lägg till `:shortcode:` till texten på en sida. Här är en [emoji-fusklapp](https://github.com/ikatyang/emoji-cheat-sheet).

Det är också möjligt att skapa en `[ea]` förkortning eller använda HTML `<i class="ea ea-name" aria-label="name"></i>`. Du kan lägga till en extra stil till namnet, till exempel `ea-lg`, `ea-2x`, `ea-3x`, `ea-4x` och `ea-5x`.

## Exempel

Lägga till emoji:

    :smile: 
    :heart: 
    :coffee:

Lägga till emoji med förkortning, normal storlek:

    [ea ea-smile]
    [ea ea-heart]
    [ea ea-coffee]

Lägga till emoji med förkortning, dubbel storlek:
    
    [ea ea-smile ea-2x]
    [ea ea-heart ea-2x]
    [ea ea-coffee ea-2x]

Lägga till emoji med HTML, normal storlek:

    <i class="ea ea-smile" aria-label="smile"></i>
    <i class="ea ea-heart" aria-label="heart"></i>
    <i class="ea ea-coffee" aria-label="coffee"></i>

Lägga till emoji med HTML, dubbel storlek:

    <i class="ea ea-smile ea-2x" aria-label="smile"></i>
    <i class="ea ea-heart ea-2x" aria-label="heart"></i>
    <i class="ea ea-coffee ea-2x" aria-label="coffee"></i>

## Inställningar

Följande inställningar kan konfigureras i filen `system/extensions/yellow-system.ini`:

`EmojiawesomeToolbarButtons` = verktygsfältknappar för [edit-tilläget](https://github.com/annaesvensson/yellow-edit/tress/main/README-sv.md)  

## Installation

[Ladda ner tillägg](https://github.com/annaesvensson/yellow-emojiawesome/archive/main.zip) och kopiera zip-fil till din `system/extensions` mapp. Högerklicka om du använder Safari.

Detta tilläg använder [Twemoji 13.0.0](https://github.com/twitter/twemoji) av Twitter. 

## Utvecklare

Anna Svensson. [Få hjälp](https://datenstrom.se/sv/yellow/help/).
