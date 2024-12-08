# roguesquerie

A Rogue-like game.

## Overview

Everybody should write a Rogue-like at least once, right?

This particular endeavor was inspired by Zed Shaw's ongoing Twitch streams [C++ Programming an Homage to Rogue](https://www.twitch.tv/zedashaw).

And [Matt Colville streaming NetHack](https://www.twitch.tv/matthew_colville)...

And... this blog post recently featured on HackerNews details [The Story of Rogue](https://spillhistorie.no/the-story-of-rogue/)...

### Why Traveller?

Why start with Traveller as a base for the mechanics?

It's a simple system, with an open [System Reference Document](https://www.traveller-srd.com/) provided by Mongoose Publishing.

Also, lifepaths...

See Mark Munson's [Mongoose 2nd Edition Character Generator](https://munsondevelopment.com/) for the potential fun in character building.

Mark Munson also has other [Traveller resources](https://www.munsondev.com/chargen/).

For an actual play example of Traveller in action, see [Voyagers of the Jump](https://www.glasscannonnetwork.com/shows/voyagers-of-the-jump) from Glass Cannon Network.

## Features

See the [specification document](docs/design/specification.md).

## Caveats

This project is not focused on the [2008 Berlin Interpretation](https://en.wikipedia.org/wiki/Roguelike#Key_features) of a Rogue-like.

### Berlin Interpretation Criteria

- Strong consideration
    - Random dungeon creation
    - permadeath
    - turn-based
    - grid-based
    - non-modal
    - emergent gameplay ([TIMTOWTDI](https://wiki.c2.com/?ThereIsMoreThanOneWayToDoIt))
    - resource management
    - hack and slash
    - exploration

- Additional consideration
    - usually single character
    - monsters have same behavioural options as players (re: item acquisition, magic, etc.)
    - tactical play may require repeated experimentation to determine a method for success
    - environment composed of rooms and corridors
    - player status is present on-screen throughout the game

## Screenshots

not yet...

## License

[MIT License](LICENSE)
