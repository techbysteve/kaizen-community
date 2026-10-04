# Kaizen

Kaizen is a desktop read-later app and RSS reader. Save articles and feeds as clean Markdown, from the app or your
browser, highlight the passages that matter, and let Claude or ChatGPT search everything you've read. Your library
lives on your computer, encrypted, and nowhere else.

This repository holds Kaizen's releases and is the place to report bugs and ask for features. Learn more at
[kaizenhq.net](https://kaizenhq.net).

## Download

Get the latest version from [Releases](https://github.com/techbysteve/kaizen-community/releases/latest).

| System | Download |
| --- | --- |
| macOS (Apple Silicon) | `.dmg` |
| Windows (x64) | `-setup.exe`, or the `.msi` |
| Linux (x64) | `.AppImage`, `.deb` or `.rpm` |

- **macOS:** open the `.dmg` and drag Kaizen to Applications. Run it from there, not from the disk image, so updates
  and the Claude Desktop extension keep working.
- **Windows:** Kaizen isn't code-signed on Windows yet, so SmartScreen may warn the first time you run the installer.
  Choose **More info → Run anyway**.
- **Linux:** make the AppImage executable (`chmod +x Kaizen_*.AppImage`) and run it, or install the `.deb` or `.rpm`
  with your package manager. Kaizen keeps its encryption key in the Secret Service, so it needs one running, such as
  GNOME Keyring or KWallet.

Kaizen comes with a 14-day trial. See [pricing](https://kaizenhq.net/#pricing) for a license.

## Updates

Kaizen checks for a new version when it starts and every six hours while it's open. You can also check from
**Settings → About**, which shows what's new in each update. Each copy updates from the format it was installed from;
updating a `.deb` or `.rpm` install asks for your administrator password.

## Feedback and support

- **Bugs and feature requests:** [open an issue](https://github.com/techbysteve/kaizen-community/issues/new). For a bug,
  include your Kaizen version (Settings → About), your operating system, and the steps that cause it.
- **Questions and help:** email [support@kaizenhq.net](mailto:support@kaizenhq.net) or join the
  [Discord](https://discord.gg/mdJQ2jwWP).

Please don't post license keys or anything from your library in an issue; issues here are public.
