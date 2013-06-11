# _Tetris24_

![screenshot of tetris24](http://tetris-comikaze24.rhcloud.com/screenshot.png)

_tetris24 is an HTML5 tetris clone written in 24 hours during Comikaze24._

You can play the game at [http://tetris-comikaze24.rhcloud.com/](http://tetris-comikaze24.rhcloud.com/ "24 Hour Tetris"). 

Within the limitations of the coding time, this is basically my personal take on Tetris. At its heart it clones the Game Boy version, with a few minor rule changes that better fit my aesthetic.

## Features

- 40hz game control
- self-adjusting display framerate with framerate independent logic
- 20 progress levels of difficulty/speed
- level-dependent scoring
- level-dependent [lock delay](http://harddrop.com/wiki/Lock_delay "Lock delay - Hard Drop - Tetris Wiki")
- *proper* Game Boy [naive gravity](http://harddrop.com/wiki/Line_clear#Line_clear_gravity "Line clear - Hard Drop - Tetris Wiki")
- level-dependent [soft drop](http://harddrop.com/wiki/Drop#Soft_drop "Drop - Hard Drop - Tetris Wiki")

## Platforms

Tested on the latest (10/06/2013):

- Chrome 27
- Firefox 21
- IE 10 
- Safari 

The game has been confirmed to work on the latest Chrome, Firefox, and Safari as well as IE10. It *might* work on IE8 or IE7.

## How to Play

You can play the game at [http://tetris-comikaze24.rhcloud.com/](http://tetris-comikaze24.rhcloud.com/ "24 Hour Tetris"). 

Paraphrasing [Wikipedia](http://en.wikipedia.org/wiki/Tetris "Tetris - Wikipedia, the free encyclopedia"):

>Tetriminos are game pieces shaped like tetrominoes, geometric shapes composed of four square blocks each. A random sequence of Tetriminos fall down the playing field (a rectangular vertical shaft, called the "well" or "matrix"). The objective of the game is to manipulate these Tetriminos, by moving each one sideways and rotating it by 90 degree units, with the aim of creating a horizontal line of ten blocks without gaps. When such a line is created, it disappears, and any block above the deleted line will fall. When a certain number of lines are cleared, the game enters a new level. 

Points are awarded for clearing lines. Clearing multiple lines at once (up to four) results in greater point values.

Use the `w`,`a`,`s`,`d` keys to maneuver the falling terominos. The `j` and `k` keys rotate. On many platforms, the `spacebar` as well as the on-screen checkbox will pause and unpause the game.

Gameplay begins immediately on page load. Restart the game at any time by refreshing the page.

## Known Issues

### Static Resolution

Due to time constraints, the game does not have an adjustable resolution or size. The game is ideally played on a 1366x768 screen on Chrome or Safari. Bigger will---of course---work. Firefox is playable on 1366x768 screens or larger, though you may have to adjust your scrolling to see the whole playfield. Metro IE10 is preferred over the desktop variant, due to less UI chrome.

### Difficulty Curve

I based my difficulty curve on the table from the original Game Boy rom at <a href="http://harddrop.com/wiki/Tetris_(Game_Boy)">Hard Drop</a>. However, it didn't feel as aggressive in the early levels as I remember. My resulting adjustments have likely made the game inhumanly hard at the higher difficulty levels.

## Installation

To serve the game from a webserver yourself, simply copy `144.png`, `72.png`, and `index.html` to an empty directory and serve that.

## Thanks

Thanks to [Ace Comics & Games](http://acecomics.com.au/annerley.html "Ace Comics & Games") in Annerley for hosting the event and to everyone at [Pulp Faction](http://pulpfaction.net/ "Pulp Faction") for organizing it.

Special thanks to [all the artist](https://vimeo.com/68030029 "24 hour comic challenge Brisbane timelapse") who made the event so much fun. *Extra* special thanks to [Dan Gilmore](http://www.2inchesofwater.com/ "2 Inches of Water") of [2 Inches of Water](http://www.2inchesofwater.com/ "2 Inches of Water") for helping select the tetrimino colors.

## License

tetris24 was authored by Trevor Jay and is licensed to you under the [Creative Commons Attribution 3.0 Australia License](http://creativecommons.org/licenses/by/3.0/au/deed.en_GB "Creative Commons - Attribution 3.0 Australia - CC BY 3.0 AU"). 

All rights to Tetris and all related copyrights and trademarks are retained by their original owners.
