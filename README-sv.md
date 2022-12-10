<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Emoji 0.8.14

Massor och massor av emoji.

![Skärmdump](emoji-screenshot.png?raw=true)

## Hur man installerar ett tillägg

[Ladda ner ZIP-filen](https://github.com/annaesvensson/yellow-emoji/archive/main.zip) och kopiera den till din `system/extensions` mapp. [Läs mer om tillägg](https://github.com/annaesvensson/yellow-update/tree/main/README-sv.md).

## Hur man lägger till en emoji

Lägg till `:shortcode:` till texten på en sida. Här är en [emoji-fusklapp](https://github.com/ikatyang/emoji-cheat-sheet).

Det är också möjligt att skapa en `[emoji]` förkortning eller använda HTML. Du kan valfritt lägga till en stil, till exempel `emoji-2x`, `emoji-3x`, `emoji-4x` och `emoji-5x`.

## Exempel

Lägga till emoji:

    :smile: 
    :heart: 
    :coffee:

Lägga till emoji med förkortning, olika storlek:

    [emoji emoji-smile]
    [emoji emoji-heart emoji-2x]
    [emoji emoji-coffee emoji-3x]

Lägga till emoji med HTML, olika storlek:

    <i class="emoji emoji-smile" aria-label="leende"></i>
    <i class="emoji emoji-heart emoji-2x" aria-label="hjärta"></i>
    <i class="emoji emoji-coffee emoji-3x" aria-label="kaffe"></i>

Smileys & känslor:

    :grinning:           :smile:              :angry:
    :frowning:           :wink:               :heart_eyes:
    :kissing_heart:      :stuck_out_tongue_winking_eye:
    :joy:                :mask:               :blush:
    :sleeping:

## Inställningar

Följande inställningar kan konfigureras i filen `system/extensions/yellow-system.ini`:

`EmojiToolbarButtons` = verktygsfältknappar för [edit-tilläget](https://github.com/annaesvensson/yellow-edit/tress/main/README-sv.md)  

## Tack

Detta tilläg innehåller [Twemoji 13.0.0](https://github.com/twitter/twemoji) av Twitter. Tack för de vackra emoji.

## Utvecklare

Anna Svensson. [Få hjälp](https://datenstrom.se/sv/yellow/help/).
