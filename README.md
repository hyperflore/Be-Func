# Be Func

Be Func is the Be Themer build for people who want the plugins without the theme.
It keeps every function plugin, including **Meow** (voice call recorder) and **Owlie** (screen recorder).
It leaves out the theme effects, the splash screen and custom CSS.

Be Themer's theme engine and its theme-effect plugins are in [Be Styler](https://github.com/hyperflore/Be-Styler).

## Install

Download `Be-Func.exe` from the [latest release](https://github.com/hyperflore/Be-Func/releases/latest), run it and press Install.
A command-line installer (`Be-Func-Cli.exe`) is included too.

Check the download against `SHA256SUMS.txt` (see the release page) before you run it:

```powershell
Get-FileHash .\Be-Func.exe -Algorithm SHA256
```

Be Func installs into your own user folder, so it needs no administrator rights.
Only one Be Themer build can be installed at a time: installing a different build replaces this one.

## What's included

- 48 plugins: Meow, Owlie, Lazy (browser), Spotify, YouTube, Twitch, Kick, Message Logger, Calculate and more.
- No theme engine, no wallpaper or glass effects, no splash screen, no custom CSS.

## Build from source

```powershell
npm run build              # renderer, main process and plugins into dist/
npm run build:installer    # installers and checksums into release/ (Windows, .NET Framework 4)
npm test
```

## Sponsor

If Be Func is useful to you, you can support its developer [70nee](https://github.com/70nee) through GitHub Sponsors:
<https://github.com/sponsors/70nee>

## Disclaimer

Be Func is open source under the MIT License (see [LICENSE](LICENSE)).
It is not affiliated with or endorsed by Discord. Client mods can break Discord's Terms of Service, so use it at your own risk.
