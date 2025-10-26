# NetHack-RTK (Heisig's Remembering the Kanji version)

## Description

This is for historical preservation purposes only. This is a modification of Nethack's battle code in C with insertions to ask random questions on Japanese kanji in order for attacks to harm enemies, intended as a way to study Heisig's Remembering the Kanji while playing a game. Only Windows binary included as the source code was lost two decades ago. Depending on your region settings, kanji in the game may not display properly. See Readme_First_NetHackRTK.txt for directions on how to set up your specific mnemonics for the game battles.

## Features

- **Study While Playing**: Combine Japanese kanji study with classic NetHack gameplay
- **Remembering the Kanji Integration**: Pre-loaded with kanji and keywords from RTK1 (Remembering The Kanji 1)
- **Customizable Kanji List**: Edit kanji.csv to match your study progress
- **Personal Mnemonics**: Add your own memory stories to reinforce learning
- **Historical Preservation**: A unique artifact from the early 2000s combining gaming and language learning

## Installation

### Prerequisites
- Windows (binary included)
- Display with proper Unicode support (kanji may not display correctly on all region settings)

### Setup

1. Extract the archive anywhere on your system
2. Run `NetHackW.exe` from the `NetHackRTK` directory

## Usage

### Starting the Game

Simply launch `NetHackW.exe` and play NetHack as normal. When you encounter enemies and attempt attacks, you'll be asked questions about Japanese kanji.

### Customizing Your Kanji

1. Open `kanji.csv` in a text editor
2. The file format is: `NUMBER, KEYWORD, KANJI, MNEMONIC,`
   - **NUMBER**: Kanji number in RTK1
   - **KEYWORD**: RTK1 keyword for the kanji
   - **KANJI**: The actual kanji character
   - **MNEMONIC**: Your personal story to remember the kanji

3. Example entries:
   ```
   990,use,使,a PERSON who's an OFFICER gets "USED" for his abilities
   991,convenience,便,as it GROWS LATE a PERSON can only satisfy cravings at a "CONVENIENCE" store
   ```

4. Remove kanji entries for chapters you haven't studied yet (make a backup first!)

### Game Help

- Refer to `Guidebook.txt` in the NetHackRTK folder for gameplay information
- Use in-game help for additional information on how to play

## Project Structure

```
NetHack-RTK/
├── README.md                       # This file
├── Readme_First_NetHackRTK.txt    # Original release notes
├── NetHackRTK/
│   ├── NetHackW.exe               # Main Windows executable
│   ├── kanji.csv                  # Kanji database (customize this)
│   ├── defaults.nh                # Game configuration
│   ├── nhdat                       # Game data file
│   ├── tiles32.bmp                # Game graphics
│   ├── *.dll                       # Required libraries
│   ├── Guidebook.txt              # Game manual
│   ├── NetHack.txt                # Additional documentation
│   └── [other game files]         # Supporting files
└── .gitignore                      # Git ignore rules
```

## Notes

- **Source Code Not Available**: The original C source code modifications were lost approximately two decades ago. This repository preserves the Windows binary version.
- **Kanji Display**: Depending on your Windows region settings, kanji characters may not display correctly. Adjust your system locale if needed.
- **RTK3 Support**: While the game can theoretically handle RTK3 kanji, no pre-made RTK3 dataset is included.
- **Original License**: See the `license` file in the NetHackRTK directory for the original NetHack license terms.

## Historical Context

This project is a unique fusion of:
- **NetHack**: A classic roguelike dungeon crawling game
- **Remembering the Kanji (RTK)**: A popular kanji learning methodology by James Heisig
- **Early 2000s Language Learning**: An innovative approach to combining gaming with serious study

## Support

For questions about the original game mechanics, refer to `Guidebook.txt`. For kanji-specific questions, consult RTK learning communities online.

## License

NetHack license applies to the base game. See the `license` file in the NetHackRTK directory for full details.

---

*Preserved for historical purposes - A unique artifact of early 2000s educational gaming.*
