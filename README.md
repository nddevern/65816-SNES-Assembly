TODO: Publish this as an actual extension

Forked from https://github.com/vicerust/65816-SNES-Assembly

See [here](https://marketplace.visualstudio.com/items?itemName=joshneta.65816-assembly&ssr=false) for instructions on how to set up colors for your instance of VSCode using user settings. Mine is here:

To set this up/use this I followed the instructions in the developer notes of this otherwise unrelated extension [here](https://marketplace.visualstudio.com/items?itemName=dagenbrock.vscode-merlin-assembler)

{
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "keyword.xkas.command.concatenate",
                "settings": {
                    "foreground": "#848484"
                }
            },
            {
                "scope": "keyword.xkas.mnemonic",
                "settings": {
                    "foreground": "#b69cff"
                }
            },
            {
                "scope": "keyword.xkas.asm",
                "settings": {
                    "foreground": "#828cff"
                }
            },
            {
                "scope": "keyword.xkas.define",
                "settings": {
                    "foreground": "#8bdfe8"
                }
            },
            {
                "scope": "constant.xkas.numeric.hexvalue",
                "settings": {
                    "foreground": "#d6ce58"
                }
            },
            {
                "scope": "constant.xkas.numeric.decvalue",
                "settings": {
                    "foreground": "#c7c7c7"
                }
            },
            {
                "scope": "constant.xkas.numeric.binvalue",
                "settings": {
                    "foreground": "#ed93e0"
                }
            },
            {
                "scope": "constant.xkas.numeric.address",
                "settings": {
                    "foreground": "#ed828d"
                }
            },
            {
                "scope": "label.xkas.sublabel.reference",
                "settings": {
                    "foreground": "#e3c39d",
                    "fontStyle": "italic"
                }
            },
            {
                "scope": "label.xkas.sublabel",
                "settings": {
                    "foreground": "#e3c39d",
                    "fontStyle": "bold"
                }
            },
            {
                "scope": "label.xkas.macrolabel.reference",
                "settings": {
                    "foreground": "#bae6cf",
                    "fontStyle": "italic"
                }
            },
            {
                "scope": "label.xkas.macrolabel",
                "settings": {
                    "foreground": "#bae6cf",
                    "fontStyle": "bold"
                }
            },
            {
                "scope": "label.xkas.label.reference",
                "settings": {
                    "foreground": "#fab969",
                    "fontStyle": "italic"
                }
            },
            {
                "scope": "label.xkas.label",
                "settings": {
                    "foreground": "#fab969",
                    "fontStyle": "bold"
                }
            },
            {
                "scope": "label.xkas.macrodefinition",
                "settings": {
                    "foreground": "#97fcc8",
                    "fontStyle": "bold"
                }
            },
            {
                "scope": "label.xkas.macroreference",
                "settings": {
                    "foreground": "#97fcc8",
                    "fontStyle": "italic"
                }
            }
        ]
    }
}
