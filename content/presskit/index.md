---
type: page
showTableOfContents: true
---

{{< figure src="images/screenshot-start_1.png" width="1000" >}}

## Factsheet

- **Developer:** Sander Frenken (Amsterdam, Netherlands)

- **Release Date:** Q3 2025

    [Alpha via TestFlight available here](https://testflight.apple.com/join/IsXcGtGR)

- **Platforms:** iOS/ iPadOS

- **Pricing:** TBD

## Description

Battledom is an iOS game that has been in development since October 2022 and is currently in the beta testing stage. 
So far, around 200 people have had the chance to play it.

Battledom is a unique RTS-like game that combines resource management with real-time battle mechanics. Players can engage in large-scale battles on expansive maps, commanding hundreds of soldiers. 

Additionally, the player can deploy and directly control siege weapons to target enemies. The game focuses on either actively attacking and defeating opponents or defending against them for as long as possible. 
Currently, the enemy is controlled by the computer, as multiplayer functionality is not (yet) planned.

The core of Battledom lies in its battle mechanics, but there's much more to explore. The player can design their own soldiers, choosing from over 1,000 different assets, including weapons, armor, and shields, which determine their stats. 

To create equipment like swords, armour, and magic staffs, players must gather resources from various sources such as farmlands, woodlands and mines. These resources can also be traded for other resources or coins, which can be used to upgrade structures within the supply chain, including a blacksmith, a siege workshop, and an university.

Battledom is optimized for mobile and tablet use, allowing players to make progress in short sessions or engage for longer periods. The resource management aspect of the game is based on idle game mechanics, with the option to actively speed up resource gathering. Additionally, players can enjoy an endless defense mode on randomly generated maps to earn resources and achieve high rankings using GKLeaderBoard.

Battledom pays homage to the classic RTS genre while being tailored for mobile gaming. The initial release will feature a campaign mode with 20 different stages, with the storyline presented through in-game scripted visuals that utilize the battle engine for full-scale battles. The endless defense mode offers additional, limitless fun.

The game is fully developed in Swift, utilizing [SpriteKit](https://developer.apple.com/documentation/spritekit/) and [GamePlayKit](https://developer.apple.com/documentation/gameplaykit) for game mechanics and rendering. Some of the tools created for Battledom's development are open-sourced and available [here](https://sanderfrenken.github.io/battledom-site/presskit/#selected-articles).

Using native Apple languages ensures high performance and potential ease of portability to macOS and tvOS.

The development of Battledom is entirely managed by me, Sander Frenken. Freelancers are responsible for creating the artwork and sounds. I am aiming for a release in Q3 2025. At present, my focus is on optimization, balancing, and content creation, as the core of the game is largely complete.

When I'm not working as a part-time iOS engineer at a bank in the Netherlands, I dedicate my time to game development. My most important and fulfilling roles, however, are entertaining my two little ones and spending quality time with my wife.

You can learn more about me and my passion for game development on my [personal blog](https://sanderfrenken.github.io/dev-blog).

## History

I started Battledom development in 2022. It started as an experiment: After the release of [Herodom](https://apps.apple.com/us/app/herodom/id1371997444), a successful Tower defense game for iOS, I was aiming to create a more dynamic battle mechanic. 

Using [GamePlayKit](https://developer.apple.com/documentation/gameplaykit), I was able to create a performant system that enabled me to control larger groups of units. Steering their behavior with different actions, I was enjoying myself guiding my armies through large maps, looking for enemies to defeat.

It was this mechanic that I expanded upon, and led to the foundation of Battledom: a mobile RTS.

For the resource management part I took my inspiration from various idle games, which I fits very well for a mobile RTS: one can easily pick and play for a couple of minutes, gather some resources, and come back later.

Now in Q1 2025 Battledom is nearing completion, at least mechanic wise. Play testing has started in Q4 2024. The current focus is on adding additional content and processing the feedback received.

## Features

- Real time battle mechanics. Command your armies to victory!

- Build your own army using 1000+ different assets

- Controllable siege weapons

- Variety of animal units to surprise your enemies with

- Harvest resources for your empire at the farmlands, mines and woodlands

- Endless mode with random generated maps for endless combat fun!

## Videos

{{< youtube ZecfzsuEKZw >}}

{{< youtube 0y0pernS0Gc >}}

## Images

{{< figure src="images/screenshot-script_2.png" width="800" >}}
{{< figure src="images/screenshot-game-still-combi-1.png" width="800" >}}
{{< figure src="images/screenshot-script_9.png" width="800" >}}
{{< figure src="images/screenshot-game-active-8.png" width="800" >}}
{{< figure src="images/screenshot-script_6.png" width="800" >}}
{{< figure src="images/sceenshot-farmlands_1.png" width="800" >}}
{{< figure src="images/village-stores.png" width="800" >}}
{{< figure src="images/screenshot-game-active-9.png" width="800" >}}
{{< figure src="images/screenshot-game-active-15.png" width="800" >}}
{{< figure src="images/screenshot-village_overview_2.png" width="800" >}}
{{< figure src="images/screenshot-script_combi.png" width="800" >}}
{{< figure src="images/sceenshot-farmlands_2.png" width="800" >}}
{{< figure src="images/character-create.png" width="800" >}}
{{< figure src="images/village-menus.png" width="800" >}}
{{< figure src="images/screenshot-game-active-2.png" width="800" >}}
{{< figure src="images/screenshot-game-active-4.png" width="800" >}}
{{< figure src="images/screenshot-woodlands-combi.png" width="800" >}}
{{< figure src="images/screenshot-game-still-combi-4.png" width="800" >}}
{{< figure src="images/screenshot-start_2.png" width="800" >}}

## Logo

{{< figure src="images/icon.png" width="400" >}}

## Downloads

Download all images from zips here:

[part 1 here](images/presskit_part_1.zip)

[part 2 here](images/presskit_part_2.zip)

[part 3 here](images/presskit_part_3.zip)

[PDF](images/screenshots_battledom.pdf)

## Awards & Recognition

N/A

## Selected Articles

N/A

## Additional Links

- **Opensourced character generator:** All character artwork for Battledom is available [here](https://liberatedpixelcup.github.io/Universal-LPC-Spritesheet-Character-Generator/#?body=Body_color_light&head=Human_male_light) to experiment with. Sources are available [here](https://github.com/LiberatedPixelCup/Universal-LPC-Spritesheet-Character-Generator).

- **Opensourced SpriteKit components:** Making games is time consuming. I open sourced some of the components for Battledom. Addional SpriteKit components can be found [here](https://github.com/sanderfrenken/MoreSpriteKit). 

- **Opensourced Tiled map to SpriteKit converter:** I also developed a package that offers the capability to turn [Tiled](https://www.mapeditor.org) maps into [SKTileMapNode](https://developer.apple.com/documentation/spritekit/sktilemapnode) and related objects. It also offers additional functionality like pathfinding on the tilemap.

- **Liberated Pixel Cup:** All artwork for Battledom is part of the [Liberated Pixel Cup initiative](https://lpc.opengameart.org/).

- **Commissioned work:** For Battledom I work with a couple of very talented artists, and the art we contribute back to the community on [opengameart.org](https://opengameart.org/content/lpc-commissioned).

## About me

I am a part-time game developer when I don't work my other job as an iOS engineer at a bank in the Netherlands.

Most important, what also keeps me busy is trying to entertain my two little ones: Oliver and Elisa. And spending time with my lovely wife, Fabienne.

You can find me more about me and my drives [here on my personal blog space](https://sanderfrenken.github.io/dev-blog).

## Contact

- [**Reddit**](https://www.reddit.com/user/sanderfrenken/)

- [**Mail**](mailto:rednasgamesinfo@gmail.com)

- [**Discord**](https://discord.com/users/478807114752589825)

- [**LinkedIn**](https://www.linkedin.com/in/sander-frenken-071a2157/)