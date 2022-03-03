# Theme - Monokai Plus

[Monokai](https://monokai.pro) theme for Sublime Merge 2.

Requires [related color](https://github.com/bitsper2nd/sublime-monokai-scheme) scheme. This implementation of Monokai uses the Sublime Merge Theme as a template with the Monokai color palette.

## Install

Assuming the required color scheme is installed, git clone the project or download it into your Sublime Merge `Packages`
folder as `Monokai Theme`. Edit your merge `Preferences.sublime-settings` file to use the Monokai theme:

```
    "theme": "Monokai Plus.sublime-theme"
```

## Screenshots

Monokai Plus (Machine)

![machine](screenshots/machine.png "Monokai Plus (Machine)")

Monokai Plus (Octagon)

![octagon](screenshots/octagon.png "Monokai Plus (Octagon)")

Monokai Plus (Ristretto)

![ristretto](screenshots/ristretto.png "Monokai Plus (Ristretto)")

Monokai Plus (Spectrum)

![spectrum](screenshots/spectrum.png "Monokai Plus (Spectrum)")

## Extra

Quickly switch between themes on Sublime Merge with the command palette:
- Open a new file
- Paste the following code:
```
// Change Theme
    {
        "caption": "Change Theme: Machine",
        "command": "set_preference",
        "args": {
            "setting": "theme",
            "value": "Monokai Plus (Machine).sublime-theme"
        },
    },
    {
        "caption": "Change Theme: Octagon",
        "command": "set_preference",
        "args": {
            "setting": "theme",
            "value": "Monokai Plus (Octagon).sublime-theme"
        },
    },
    {
        "caption": "Change Theme: Plus",
        "command": "set_preference",
        "args": {
            "setting": "theme",
            "value": "Monokai Plus.sublime-theme"
        },
    },
    {
        "caption": "Change Theme: Ristretto",
        "command": "set_preference",
        "args": {
            "setting": "theme",
            "value": "Monokai Plus (Ristretto).sublime-theme"
        },
    },
    {
        "caption": "Change Theme: Spectrum",
        "command": "set_preference",
        "args": {
            "setting": "theme",
            "value": "Monokai Plus (Spectrum).sublime-theme"
        },
    },
```
- Save the file as `Default.sublime-commands` in `Sublime Merge/Packages/User` folder.
- Open the command palette and type **Change**.
