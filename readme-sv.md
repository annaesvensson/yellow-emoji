# Emoji 0.9.4

Massor och massor av emoji. Utvecklad av Anna Svensson.

<p align="center"><img src="screenshot.png" alt="Skärmdump" /></p>

## Hur man installerar ett tillägg

[Ladda ner ZIP-filen](https://github.com/annaesvensson/yellow-emoji/archive/refs/heads/main.zip) och kopiera den till din `system/extensions` mapp. [Läs mer om tillägg](https://github.com/annaesvensson/yellow-update/tree/main/readme-sv.md).

## Hur man lägger till en emoji

Lägg till `:smile:` eller `[emoji emoji-smile]` till texten på en sida. Här är en [emoji-fusklapp](https://github.com/ikatyang/emoji-cheat-sheet).

## Hur man lägger till en ikon i en layoutfil

Använd HTML-format, till exempel `<i class="emoji emoji-smile" aria-label="leende"></i>`.

## Exempel

Innehållsfil med emoji:

    ---
    Title: Exempelsida
    ---
    Detta är en exempelsida med emoji.

    :smile: :grinning: :angry: :heart: :coffee: :thumbsup:

Lägga till emoji efter namn:

    :smile: 
    :heart: 
    :coffee:

Lägga till emoji med förkortning:

    [emoji emoji-smile]
    [emoji emoji-heart]
    [emoji emoji-coffee]

Lägga till emoji med HTML:

    <i class="emoji emoji-smile" aria-label="leende"></i>
    <i class="emoji emoji-heart" aria-label="hjärta"></i>
    <i class="emoji emoji-coffee" aria-label="kaffe"></i>

Smileys & känslor:

    :grinning:           :smile:              :angry:
    :frowning:           :wink:               :heart_eyes:
    :kissing_heart:      :stuck_out_tongue_winking_eye:
    :joy:                :mask:               :blush:
    :sleeping:

## Inställningar

Följande inställningar kan konfigureras i filen `system/extensions/yellow-system.ini`:

`EmojiToolbarButtons` = verktygsfältknappar för [edit-tillägget](https://github.com/annaesvensson/yellow-edit/tress/main/readme-sv.md)  

## Tack

Detta tillägg innehåller [Twemoji 13.0.0](https://github.com/twitter/twemoji) av Twitter. Tack för de vackra emoji.

Har du några frågor? [Få hjälp](https://datenstrom.se/sv/yellow/help/).
