General Idea:
  Circles is a simple svg game for the purposes of testing the capabilities of SVG.
The idea behind it, is to make it using only vanilla javascript no external libraries and also keep it as lean as possible.
The maximum size of the should not go over 40 kb minified. Also everything should be contained in a single file.

Future features:
  Make a background of blurred circles traveling behind to create the illusion of depth.
  Make overlaping circles merge into one shape.
  Create sound effects and music.
  Create a leaderboard using online service. Allow players to select name and registration.
  
Known issues:
  There is some jitter in the animation, probably caused because drawing a single frame takes more than 16ms. Investigate further.
  
Optimizations:
  Better algo for collision detection. Cut the scene into smaller pieces and detec collisions only inside there.
  Dont clear the whole svg on every frame. Remmember shape possitions and clear squares around them.
