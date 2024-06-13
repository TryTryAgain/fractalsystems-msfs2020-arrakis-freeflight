# Issues and Workaround/Solutions

## Problem: I am an amateur

- I have no previous flightsim modding experience or game development
- I have limited time to commit

## Solution: I am an amateur

- I will stand on the shoulders of giants and take advantage of all the available tools that can help me; see README.md#CreditsAndThanks

## Problem: Default Discovery Flight Music

- I cannot find a way to remove Discovery background music when in flight :(
  - Current workaround: General Options -> Sound -> Volume Levels ('Music' at the bottom) -> Set to 0
  - Of course other Discovery flights have custom music and I've tried swapping those out to test (ultimately I'd create an empty track)
    - I'd be happy for any solution, I'll continue to try and find one...

## Solution: Default Discovery Flight Music

- BushTripInjector allows for custom Audio/MusicStyle for Discovery flights via Wwise
  - Used a blank quarter-second wav
    - <https://archive.org/details/audio-silent-wavs-one-second-half-second-quarter-second>
  - Wwise AudioKinetic Launcher: SampleProject + SDK/editor; created a blank-track Default_Blank_Soundbank
  - Used the Wwise Packager to create the required Default_Blank_Soundbank.PC.PCK Wwise file
  - I was then able to use that Default_Blank_Soundbank.PC.PCK for the Wwise custom Music setting with BTI (amazing thanks for that!)

## Problem: Inability to add access to Weight and Balance (Fuel customization) panel

- I would be very happy to solve this one, that would be amazing...
  - Current workaround: there's the ability to use Flight Assists to enable infinite fuel; not ideal but may help

## Solution: Custom Discovery SPB opens up All

- Custom xml edits from/for BTI (this basically makes it FreeFlight)
