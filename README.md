# fractalsystems-msfs2020-arrakis-freeflight

🛩️ Microsoft Flight Simulator 2020 custom content
🛩️

    🚨🚁 THIS IS PROVIDED AS IS WITHOUT ANY WARRANTY OR GUARANTEE 🚁🚨
    🚨🚁   THE AUTHOR IS NOT LIABLE FOR ANY DAMAGES OR LOSSES.    🚁🚨

🌎🛫🌍✈️🌍🛬🌏

A community addon that introduces a kind of working FreeFlight mode...hacked together Discovery flights without limitations, more so a "Dune Challenges without Challenges" via Custom Activity Content - "DNE: DUNE CHALLENGES WITHOUT CHALLENGES" Discovery Flights, enabling mostly unrestricted flight around the Dune world (Arrakis) scenery in the Ornithopter. When using the supplied Missions you will see familiar scenery from the Dune Challenges, if you fly/teleport to anywhere else (ICAO/coordinates) you may find something interesting hidden around the buried/bulging planet Earth that is Dune!

💡🌟🥹🪄😵‍💫💫🎆

Inspired by the fact that we have an amazing Ornithopter in the game and a pretty fun/unique planet texture of Arrakis to fly in but we're stuck doing that from within the constraints of the predefined challenges and no other way...and frustrated to find limitations with existing workarounds (lacking ability to manage custom weather/time of day on-the-fly/in-flight, same with Assistance options/crash damage etc. and needing to rely on dev mode/teleport instead of being able to drop right in ready to fly if that's what you want vs. fumbling away at FLT files and/or enabling dev mode).

🗺️🌐🧭⏱️🧭🌐🗺️

Enjoy a pseudo-FreeFlight mode on the planet Dune/Arrakis scenery in the Ornithopter via custom Discovery Flights. Packaged for a more enjoyable experience... Train for the Challenges without all the restarts 😜😏 ... get that awesome screenshot, play around with replay, etc. in the fun Dune scenery and/or explore the buried/bulging planet Earth wrapped in dunes if you feel like it.

## Credits and Thanks

🛩️ Thanks for all the great inspiration and examples! 🛩️

❤️🧑‍✈️🧳🚁📦💺🕹️

Pieced together by Michael Lawler aka FractalSystems @ <https://github.com/TryTryAgain/fractalsystems-msfs2020-arrakis-freeflight> (This project)

### Send me some love

💸🧑‍✈️🧳🚁📦💺🕹️

<https://paypal.me/FractalSystems> or <https://www.buymeacoffee.com/FractalSystems>

### Tools Referenced/Used

🧰🏗️👷📐🧑‍💻🍻🎉

<https://forums.flightsimulator.com/t/add-free-flight-option-to-the-arrakis-scenery-in-the-dune-expansion/630504/3>, "kromeboyit" who I believe made the original `MenuHierarchy=DNE` discovery allowing for the scenery via Missions/FLT files.

<https://forums.flightsimulator.com/t/guide-mission-creation-for-msfs/564333> a great introduction to mission building, extremely helpful and detailed as well as the SimpleMission sample project: <https://flightsim.to/file/23934/mission-creation-resources> and similarly the great example(s) shared here <https://github.com/geehalel/msfsmissions> and by Don Done here <https://flightsim.to/file/9805/mission-tutorial>, great material to learn from.

<https://www.fsdeveloper.com/wiki/index.php/Mission_Creation_for_MSFS>, <https://www.fsdeveloper.com/wiki/index.php/SimpleMission_(MSFS)>, <https://www.fsdeveloper.com/wiki/index.php/MSFS_Mission_Script_-_Flow_states>

<https://docs.flightsimulator.com>, the SDK, and the game itself. As well as their YouTube channel <https://www.youtube.com/@MicrosoftFlightSimulator>

<https://flightsim.to/file/3681/bushmissiongen>, <https://github.com/DoNotBeOnFire/msfs2020-weather-presets/tree/master/packaging-weather-presets-tutorial> and <https://www.bushtripinjector.de/downloads/> super helpful and critical to my success. As well as <https://www.bushtripinjector.de/mission-changer/> (in case you want to edit what I've provided in a potentially more accessible way; NOTE: UNTESTED)

<https://albar965.github.io/littlenavmap.html> couldn't live without it, love it, use it all the time.

## Features

🛩️ I've created this for myself but thought others would enjoy 🛩️

🚀🪂🛸🚀🤩💖✨

- Flying the Ornithopter on Dune in a sort of customizable-Discovery/pseudo-FreeFlight mode
  - Dune Challenges' starting off points as Discovery flights
  - The Challenges objectives/TaG points included as POIs
  - Discovery Flights for each of the following
    - Desert Run
    - Race to Arrakis
    - Mountain Dive
    - Hole-in-the-Rock
    - Canyon Rush
    - Coriolis Storm Escape
- The ability to customize time of day and weather presets while in flight/landed to your hearts content without limitations
  - Custom Coriolis sandstorm weather included (static, not animated), any other custom weather presets you have will work too
- The ability to turn off Crash/Damage/Stress so you don't have to restart and reload again and again
- The ability to land and takeoff wherever you want without any time constraints or world/settings limitations
- The ability to teleport anywhere on the buried/bulging Earth planet called Dune :D
- The ability to coexist with multiplayer traffic from the real world :D

## Installation

🛩️ Add it to your Community folder, find it in Custom Content 🛩️

🤞📜📢🙌🥁🖳👏

- The Dune Expansion DLC is required for this to work
- Download, extract, and add everything from within `fractalsystems-arrakis-freeflight` to your community folder
  - You can copy all or be selective, whatever you want, but don't copy only the root folder with everything inside...that won't work, it must be the 
- If you have path length or any other issues extracting I would recommend using 7-Zip -> Extract to "fractalsystems-arrakis-freeflight\"
  - Then you can move into your community folder or symlinked through and addon linker
- Find the Missions under Custom Content sections named:
  - "DNE: DUNE CHALLENGES WITHOUT CHALLENGES"

### Suggested addons

🛩️ Make your experience more enjoyable 🛩️

🎚️📡🔮🍀🎰🪩🎛️

- If you do want to explore the buried/bulging planet Earth with the Dune scenery (places outside of the intended Arrakis scenery)
  - FS Pilot (teleport anywhere in the world from your Android phone)
    - <https://flightsim.to/file/10573/fs-pilot-world-map-and-flight-planner>
  - msfs2020-go VFRmap (teleport anywhere in the world from your browser)
    - Direct: <https://github.com/lian/msfs2020-go/releases>
    - Writeup: <https://www.msfsaddons.org/freeware/plugin-vfrmap>
- If you don't like addons, you can always use the Developer Tools teleport window to transplant your plane to any ICAO or coordinates
  - To Enable/Use the Developer tools teleport window:
    - Enable Developer tools: Options -> General Options -> Developers -> Turn Developer Mode 'On'
    - Open the teleport window: Tools -> Teleport Window (enter in ICAO or coordinates and click go to)
    - To exit: DevMode -> Exit DevMode

## Potential Future Additions

🛩️ One day there may be some AGI that will make all my ideas and dreams come true, GAI has been helpful along the way though 🛩️

🧐❤️‍🔥⌚😤🔥🥵🌡️

- Adding custom weather presets, learn how to animate/move the Coriolis sandstorm - using `fractalsystems-weather-arrakispresets` as a kind of placeholder
- Actually making the source code so that it's a proper Mission pack that can be built via a build pipeline vs. depending on hacking it together via BTI/xml/flt changes
- Adding some more mission objectives and/or race timers between POIs that can be reset by triggers; could be useful for training (would be useful for me learning the SDK if nothing else)
  - Maybe even something like teleporting based on entering a wormhole or something to visit interesting buried/bulging Earth sites :P
- Add cold/dark start options in addition to the supplied hot/already-in-flight mode that mimic the challenges
- Adding other predetermined starting points (ideas/suggested coordinates are more than welcomed)
- Solve some of the Known Limitations/Issues (some tracked already in #ISSUES.md)

### Contributions Welcome

✏️📃📝⛓️📋📈🔑

- You can open issues, fork, pull/merge request, whatever. All contributions welcomed and appreciated! I understand I am a complete amateur and most of my choices were beyond unconventional or supported/standard methods for achieving what was done...I apologize for the cringeworthy decisions made in advance.  I'd be happy to change course if anyone has better ideas.

### Known Limitations/Issues

🚧🛑🧱🛠️⚙️🤖😬

Potential Animation Glitches - It seems even the official Dune Challenges themselves have this same issue:

- Depending on where you fly on the map you may temporarily lose animations/movements of the Ornithopter; wings appear to freeze, although you continue to fly, toggling gear continues to work but without visual animations or representation of current state...
- Glitches in terrain/scenery is to be expected
  - This is even more true if you travel outside of the intended scenery...although sometimes that may be what you want to do...

Not really a Discovery Flight or a FreeFlight

- This is likely due to the fact that I smashed something together vs. wrote from the ground up.
- Occasionally if left idle on the ground, with wings flapping, you may lift off again.
  - Turn off your engine or fold the wings.

### Other Bugs/Issues

🪲🐞🐝🪰🪳🐜🐛

Really appreciate your feedback. Feel free to share any suggestions or report any issues!
