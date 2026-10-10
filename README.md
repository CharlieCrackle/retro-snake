# Retro Snake

Retro Snake: a VIC-20-styled Snake game where you play a rat.

- **index.html** is the whole game in one file. There's no framework and nothing to install. Open it in any browser, or play it online through GitHub Pages.
  - Steer with the arrow keys or WASD. Space pauses, Enter restarts and M turns the music on or off.
  - The world is a 40×40 grid. The screen shows a 20×20 window, drawn on an HTML canvas, that follows the rat. Red lines mark the outer walls when they're on screen.
  - There are three pieces of cheese in the world at a time.
  - Eat cheese to score. Dodge the black cats, which move slowly toward you. You start with two, and another joins every 10 points, up to four.
  - The radar shows the whole 40×40 world: you in turquoise, the cheese in white and the cats as purple crosses. A box shows the part that's on screen.
  - The **A / AUTO 1 MIN** button makes the game play itself for one minute, with a countdown on the button. If the rat crashes, auto mode starts a new rat. When the minute is up, the game pauses so you can take over. Pressing a steering key takes over at any time, and clicking the button again stops auto mode.
  - BYTES FREE shows 3583 minus the rat's length.
  - The music is the full "Three Blind Mice" nursery rhyme, looping on VIC-style square waves with a soft bass and a light tick on each beat. It starts on your first key press, because browsers block sound until you interact with the page.
  - Settings such as speed are at the top of the script.
