<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Emojiawesome 0.8.12

Lots and lots of emoji.

![Screenshot](emojiawesome-screenshot.png?raw=true)

## How to add an emoji

Add `:shortcode:` to the text of a page. Here's an [emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet). 

It's also possible to create an `[ea]` shortcut or use HTML `<i class="ea ea-name" aria-label="name"></i>`. You can add an additional style to the name, for example `ea-lg`, `ea-2x`, `ea-3x`, `ea-4x` and `ea-5x`.

## Examples

Adding an emoji:

    :smile: 
    :heart: 
    :coffee:

Adding an emoji with shortcut, normal size:

    [ea ea-smile]
    [ea ea-heart]
    [ea ea-coffee]

Adding an emoji with shortcut, double size:
    
    [ea ea-smile ea-2x]
    [ea ea-heart ea-2x]
    [ea ea-coffee ea-2x]

Adding an emoji with HTML, normal size:

    <i class="ea ea-smile" aria-label="smile"></i>
    <i class="ea ea-heart" aria-label="heart"></i>
    <i class="ea ea-coffee" aria-label="coffee"></i>

Adding an emoji with HTML, double size:

    <i class="ea ea-smile ea-2x" aria-label="smile"></i>
    <i class="ea ea-heart ea-2x" aria-label="heart"></i>
    <i class="ea ea-coffee ea-2x" aria-label="coffee"></i>

## Settings

The following settings can be configured in file `system/extensions/yellow-system.ini`:

`EmojiawesomeToolbarButtons` = toolbar buttons for the [edit extension](https://github.com/annaesvensson/yellow-edit)  

## Installation

[Download extension](https://github.com/annaesvensson/yellow-emojiawesome/archive/main.zip) and copy zip file into your `system/extensions` folder. Right click if you use Safari.

This extension includes [Twemoji 13.0.0](https://github.com/twitter/twemoji) by Twitter. 

## Developer

Anna Svensson. [Get help](https://datenstrom.se/yellow/help/).
