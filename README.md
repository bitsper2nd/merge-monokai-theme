# Theme - Monokai Plus

[Monokai](https://monokai.pro) theme for Sublime Merge 2.

This implementation of Monokai uses the Sublime Merge Theme as a template with the Monokai color palette.

## Install

Assuming the required color scheme is installed, git clone the project or download it into your Sublime Merge `Packages`
folder as `Monokai Theme`. Edit your merge `Preferences.sublime-settings` file to use the Monokai theme:

```
    "theme": "Monokai Plus.sublime-theme"
```

For the square tabs version of this theme:

```
    "theme": "Monokai Plus SQ.sublime-theme"
```

## Screenshots

Monokai Plus (Cognition)

![cognition](https://github.com/user-attachments/assets/f1e57a8b-1c09-4382-a6a9-1649dadcb0b9 "Monokai Plus (Cognition)")

Monokai Plus (Machine)

![machine](https://github.com/user-attachments/assets/2ef6fbc9-6498-4952-9ab2-b2b6e7d141d6 "Monokai Plus (Machine)")

Monokai Plus (Octagon)

![octagon](https://github.com/user-attachments/assets/b2893ef4-b92c-4a65-8c6b-270c804d7a91 "Monokai Plus (Octagon)")

Monokai Plus

![plus](https://github.com/user-attachments/assets/f203c40b-9433-4bd9-9d63-c886c9ce8fbd "Monokai Plus")

Monokai Plus (Ristretto)

![ristretto](https://github.com/user-attachments/assets/185935b6-e114-4e1c-880d-5fdb5a6c8b9d "Monokai Plus (Ristretto)")

Monokai Plus (Spectrum)

![spectrum](https://github.com/user-attachments/assets/ad41089c-b749-43e8-a2d8-1d0cca0600ec "Monokai Plus (Spectrum)")

## Quick tip

Quickly switch between themes on Sublime Merge with the command palette:

- Open a new file
- Paste the following code:

```
// Change Theme
    [
        {
            "caption": "Change Theme: Cognition",
            "command": "set_preference",
            "args": {
                "setting": "theme",
                "value": "Monokai Plus (Cognition).sublime-theme"
            },
        },
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
            "caption": "Change Theme: Monokai",
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
    ]
```

- Save the file as `Default.sublime-commands` in `Sublime Merge/Packages/User` folder.
- Open the command palette and type **Change**.

## Extra

Here is the repo of the [color scheme](https://github.com/bitsper2nd/sublime-monokai-scheme) for Sublime Text. Also checkout my [other theme](https://github.com/bitsper2nd/merge-mariana-theme) based on the Mariana color palette.
