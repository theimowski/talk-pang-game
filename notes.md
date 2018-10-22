# Notes for Pang talk

## TODO

Left time: 25p

10-20

+ Fix "too many scores in client" bug 1p
+ Buttons for controlling 2p

10-21

+ "Play again" instead of refresh page 1p
+ Code refactor 5p
  + Azure blobs (Server)
  + Physics module
  + Client
+ Plan stages 2p
+ Practice live coding 2p

10-22

* Final amends 2p
* Slides 2p

10-23 - 10-24

* Practice live coding 8p

## Extra if time allows

* Gestures instead of dumb clicking
* Better page layout
* Nicer prompt for high score name
* Lock-free append only blobs in Azure

## Stages

* Initial (yellow player on board with no balls)
  * dotnet new
  * trim down dependencies
  * add matter.js, mainloop
  * add canvas, physics modules
  * skeleton for main functions to draw player
* Buttons + moving player
* Ball on the board
* Button + Shooting harpoon
* Shooting balls and splitting
* Counting score
* Game over
* Reset game after game over
* High scores
* Deploy

## Change for initial

+ extract onTick
+ renderShape, renderCircle etc as library to use
+ comment out html, then add incrementally
+ Physics.moveBody for player moving
+ snippet: `let checkIn`
+ snippet: point class etc for harpoon
+ snippet: ball collisions
+ Some snippets for server and shared and client proxy or even have it already ready!
+ snippet for renderHighScores
+ Active pattern for IPair collision
