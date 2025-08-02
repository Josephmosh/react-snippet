# React Setup Snippet

A snippet for Visual Studio Code which provides boilerplate for a React Component.

## Instructions

1. Press <kbd>Cmd</kbd> + <kbd>P</kbd> on Mac, or <kbd>Ctrl</kbd> + <kbd>P</kbd> on Windows to open the VSCode command pallette.
2. Type `>Snippets: Configure Snippets` into the search bar at the top of the screen.
3. Click `New Global Snippets file...`
4. Paste the following code into the new file, in between the curly brackets:

```
"React Setup": {
    "prefix": "r~",
    "body": [
        "import React from 'react';\n\nconst $1 = () => {\n\n    return (\n        <>\n\n        </>\n    );\n\n};\n\nexport default $1;"
    ]
}
```

## Usage

When creating a new React component, type `r~` at the top of your file. Finally, type in the name you want your component to be.

It's as simple as that! Hope you enjoy!
