# Civ V Voices for Unciv

Adds Civ V's Technology and Wonder quotes, along with Leader dialog voices, in [Unciv](https://github.com/yairm210/Unciv).

![Preview](preview.png)

## Features

- Technology Quotes
- Wonder Quotes
- Leader Dialog
- Nation Intro Quotes
- Covers Vanilla, Gods & Kings, [Brave New World](https://github.com/RobLoach/Civ-V-Brave-New-World)
- Add your ideas in the [issue queue](https://github.com/RobLoach/Civ-V-Voices/issues)

## Installation

1. Open Unciv
2. Open the Mods menu
3. Click Sort and Filter
4. Search for "Voices", or "Civ V Voices"
5. Download and install
6. Enable "Permanent audiovisual mod"

## See Also

- [Civ V Music Pack](https://github.com/Kurwizimi/Civ-V-Music-Pack)

## Development

### Sources

- SteamLibrary/steamapps/common/Sid Meier's Civilization V/steamassets/assets/sounds/speech/english
- SteamLibrary/steamapps/common/Sid Meier's Civilization V/steamassets/assets/dlc/expansion/sounds/speech/english
- SteamLibrary/steamapps/common/Sid Meier's Civilization V/steamassets/assets/dlc/expansion2/sounds/speech/english

### Naming

- Wonders `WonderName - Wonder.mp3`
- Technologies `TechName - Researched.mp3`
- Voices
  - `assets/sounds/speech/shared/elizabeth`
  - `intro.mp3` > `Nation.introduction.mp3`
  - `defeated.mp3` > `Nation.defeated.mp3`
  - `attacked.mp3` > `Nation.attacked.mp3`
  - `neutralhello.mp3` > `Nation.neutralHello.mp3`
  - `hatehello.mp3` > `Nation.hateHello.mp3`
  - `request.mp3` > `Nation.tradeRequest.mp3`
  - `declarewar.mp3` > `Nation.declaringWar.mp3`
- Use `src/process.sh` to normalize the audio for the mp3 files
