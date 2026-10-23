# Dark Souls III Launcher

Public Windows downloads for the independent DS3 Launcher. This repository
contains release downloads and their checksums; source is maintained separately.

**[Download the latest release](https://github.com/itsMohammedAli/ds3-launcher-releases/releases/latest)**

## Install

Download the release ZIP and extract its top-level `Launcher` folder into
`DARK SOULS III/Game`, beside `DarkSoulsIII.exe`. Run
`Launcher/ds3_launcher.exe`. Keep the whole folder together.

Choose Original Game, Seamless Co-op, or OnlineFix Co-op from the Play page.
Settings include close after launch and shortcuts to the game and save folders.
The launcher has its own sword/bonfire/play icon so it is distinct from the game.

## Seamless Co-op

Install the mod separately from [Yui's DS3 Nexus page](https://www.nexusmods.com/darksouls3/mods/1895?tab=files).
Place `ds3sc_launcher.exe` in `Game`, with the `SeamlessCoop` folder beside it.
The mod itself is not included in the launcher ZIP.

The launcher detects the installed DS3 mod version and checks GitHub/Nexus for
the latest version. The Seamless Co-op tab edits the local INI while preserving
comments, encoding, and unchanged settings. Game save files are never edited.

## Updates and integrity

Numbered public builds check this repository for launcher updates without
credentials. Updates verify the GitHub SHA-256 asset digest before installation.
Each release also includes a `.sha256` file for manual verification.

The archive contains the launcher runtime, the supplied original/OnlineFix file
sets, and installation helpers. The two supplied `steam_api64.dll` files are
currently identical. Supply your verified original DLL in
`Launcher/bundles/original` if you need Original Game to restore a clean Steam
configuration. Unrelated game files and save data are preserved.

There is no GlitchTip or Sentry integration.
