## Gameplay

You play as a character escaping from a CIA prison cell, in each level the player is tasked with getting to the exit point without dying. The game is in a fixed top down view showing the locations of various enemies so the player can plan their moves. Each level can be completed using various levels of stealth to give the game some re-playability.

## Code

At the start of the project my aim was to create a game with multiple levels so I spent time developing a level generation tool to help with this. The tool allowed me to generate level meshes from data in the Unity editor complete with lightmaps. This avoided the alternative of creating levels in a 3D modeling program or constructing them from kit parts which would have lead to imperfections and lost time spent creating assets. The level textures were stored as scriptable objects so that changes to the style of the game could be quickly applied to all game levels.

I also tried to do this for my AI system. Rather than manually scripting AI behavior I decided to implement a behavior tree system so that code could be better reused and modularised. I attempted to create a data driven system for defining behavior trees in Unity however I fell foul of the serialisation system and realised a full solution would take up a large part of the game jam time so I abandoned this project.

## Result

Feedback from judges was mostly positive

> ***"Big points for the visual/interactive tutorial, shows a lot of thought went into the game and just comes off as really polished"***
<!-- -->
> ***"Gameplay was pretty well implemented, no notable bugs were encountered during the playthrough. Game rules were clear and easy to interact with and some advanced concepts were used and generally well executed."***
<!-- -->

The most notable problem encountered was bugs with the UI including scaling to multiple resolutions (this has been fixed in an update)

> ***"I recommend making the UI/menus scale for different resolutions. I selected 720p from the drop down menu and I wasn't able to play as buttons were off screen. I had to opt for the highest resolution to resolve it."***

 Full feedback from judges can be found on the game jam page on Itch.io. I was really happy with the level of polish on the final product, there were only a few bugs in the game and I was pleased that most of the judges didn't seem to find them! Many other entries had much more complexity and visual finesse and this is something I'd like to work on in the future.

<iframe frameborder="0" src="https://itch.io/embed/330180?linkback=true" width="208" height="167"></iframe>

## Links
* [Itch.io Game Page @fa-external-link ](https://nick-pearson.itch.io/escape-from-the-cia)
* [Itch.io Game Jam Page @fa-external-link ](https://itch.io/jam/search-for-a-star-game-dev-challenge-2019/rate/330180)
