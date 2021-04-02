# Trijam 114 submission

This is my [Trijam 114](https://itch.io/jam/trijam-114) submission!

11:57pm Thursday night for me, voting ends in ~2 hours. Looks like the theme is gonna be...

## Smoke without fire

Ideas if it is:
- A game where you have to try and start a fire but it's impossible.
- Lighting cigarettes with a stove element.
- Rubbing sticks together but only to a certain point, if you rub too quickly it starts a fire and you get game over.
- A "smokethrower" where you have to make smokescreens.
- Character is leaf man and you have to prevent him catching fire.

If I go with rubbing sticks together to generate smoke, but not fire, I could probably do something cool with Matter physics. Watch friction values, or something, and add particle emitters at intercetions between "sticks" (just long rectangles, rounded if possible). Or possibly two custom polygons w/ branches.

The particle emitters could correspond to how much friction is being calculated between the two bodies. Or if I don't have access to that data, just go with how long they've been touching.

The name could be `"Counter-Combust"`.

12:17am Friday morning, the controls on computer could be to drag the mouse around, moving a branch. On mobile, the same but touching the screen.

Could use this example, and modify it so it starts as contrailing smoke, but the longer you move the "hotter" it gets, and the smoke eventually turns to fire.

Could show a bar at the top, that is the "igniation quota".