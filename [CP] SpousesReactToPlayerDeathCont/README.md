# SpousesReactToPlayerDeath - Version 1.3.5-beta4
_Forked and updated for Stardew Valley 1.6+ and Content Patcher 2.0+_

### Releases
Available at [NexusMods.com]

### Description
This project creates a Content Patcher mod that adds additional relationship-centric content to player death cutscene.

### Changelog
<details>
  <summary>Version 1.3.5-beta4 - Bugfix again again</summary>
  
  - Fixed scene selection conditions
  - Fixed malformed spouse tokens ...again
  - Adjusted NPC routes in hospital ex scene to terminate at more logical spots
  - Improved troubleshooting process so as to reduce bugs in future public releases
  - Updated roadmap
</details>
<details>
  <summary>Version 1.3.5-beta3 - Bugfix ...again</summary>
  
  - Fixed malformed spouse tokens
</details>
<details>
  <summary>Version 1.3.5-beta2 - Bugfix</summary>
  
  - Fixed mismatched tokens in scene selection logic (again)
</details>
<details>
  <summary>Version 1.3.5-beta1 - Minor change</summary>
  
  - Updated config schema token for slightly better readability
</details>
<details>
  <summary>Version 1.3.4 - Small bugfix</summary>
  
  - Fixed Kataryna's missing token membership for selecting the correct mines scene
  - Added optional dependencies to manifest.json
</details>
<details>
  <summary>Version 1.3.3 - Dialogue + QoL</summary>
  
  - Added dialogue for Kataryna from ES
  - Added pt.json translation file (many thanks to Nexusmods member helens0uzasilva)
  - Fixed conditions check for Krobus
  - Fixed conditions check for Lance from SVE
</details>
<details>
  <summary>Version 1.3.2 - Dialogue QoL</summary>
  
  - Added option to skip all cutscenes
  - Reverted unnecessary change to mines scene selection
</details>
<details>
  <summary>Version 1.3.1 - Dialogue Round 2</summary>

  - Added dialogue for Juliet from ES
  - Fixed (hopefully) the dialogue fetch issue for as-yet un-implemented spouses
  - Added missing dialogue to the default spouse section
</details>
<details>
  <summary>Version 1.3.0 - Dialogue Round 1</summary>
  
  - Added dialogue for Lance from SVE and Aideen from ES
</details>
<details>
  <summary>Version 1.2.5 - i18n Refactor Completion</summary>

  - Finished refactoring all remaining hard-coded strings into i18n entries
</details>
<details>
  <summary>Version 1.2.4 - Embarrassing Housekeeping</summary>

  - Fixed the update key in manifest.json (for realsies this time)
  - Created a nested folder in NexusMods releases for unzipping into users' Mods folders
</details>
<details>
  <summary>Version 1.2.3 - Nesting Issue</summary>

  - Fixed improper nesting issue in ElliottsLetters.json
</details>
<details>
  <summary>Version 1.2.2 - Syntax Correction</summary>

  - Fixed missing comma in content.json
  - Started creating i18n entries for the missing permitted characters (each character is commented out until finished)
</details>
<details>
  <summary>Version 1.2.1 - Mystery of the Missing Keys</summary>

  - Fixed missing nexusmods update key in manifest.json
</details>
<details>
  <summary>Version 1.2.0 - Initial File Refactor</summary>

  - Refactored content.json into easily manageable delegate files (and for future randomization?)
  - Normalized indentation throughout all files
  - Added comments everywhere, both as informal section titles and as TODO reminders
  - Uploaded publicly to NexusMods.com
  - Switched repository from private to public
</details>
<details>
  <summary>Version 1.1.0 - Initial Commit</summary>

  - Uploaded original project before attempts to update/expand
  - Received permission from the East Scarp, Ridgeside Village, and Stardew Valley Expanded authors to include/retain their characters
</details>

### Roadmap
- [x] Refactor content.json to delegate files for ease of modification
- [ ] Add missing SVE characters
  - [x] Lance
  - [ ] Scarlett
- [ ] Add content for the remaining East Scarp characters (Jasper was the original inspiration for this mod, and is already handled in the East Scarp mod?)
  - [x] Aideen
  - [x] Juliet
  - [x] Kataryna
  - [ ] Tristan
- [ ] Add content for the Ridgeside Village characters
  - [ ] Alissa
  - [ ] Blair
  - [ ] Corine
  - [ ] Daia
  - [ ] Flor
  - [ ] Kiarra
  - [ ] Maddie
  - [ ] Ysabelle
  - [ ] Ian
  - [ ] Jeric
  - [ ] June
  - [ ] Kenneth
  - [ ] Philip
  - [ ] Sean
  - [ ] Shiro
- [ ] Follow up on additional characters as time/motivation allows
  - [ ] Rasmodia
  - [ ] Gale - Wizard of Waterdeep
  - [ ] Wilford
  - [ ] Marlon
  - [ ] My Eugene
- [ ] Add additional content for event variants (spouses shouldn't say the same thing every single time, hey?)
- [ ] Investigate handling for individual players in a multiplayer game
- [ ] Investigate compatibility with other mods

~~Investigate refactoring i18n file for ease of modification~~ i18n files cannot be refactored as far as I can tell, sadge

### License
_TBD_ (will talk to CasualInvidia regarding licensing)

### Acknowledgments
- _[CasualInvidia] producer of the original mod_
- _[Lemurkat] producer (+team) of East Scarp_
- _[Rafseazz] producer (+team) of Ridgeside Village_
- _[FlashShifter] producer (+team) of Stardew Valley Expanded_ 


[NexusMods.com]: <https://www.nexusmods.com/stardewvalley/mods/24668/>
[CasualInvidia]: <https://www.nexusmods.com/stardewvalley/users/105860563>
[Lemurkat]: <https://www.nexusmods.com/stardewvalley/users/68088657>
[Rafseazz]: <https://www.nexusmods.com/stardewvalley/users/66167516>
[FlashShifter]: <http://www.nexusmods.com/stardewvalley/users/46021252>
