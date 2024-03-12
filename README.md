# DHH Ruby Snippets for Sublime Text 4

## Installation
Clone this repo into you Sublime Text Packages directory and be able to use DHH
Ruby snippets from TextMate 2 in Sublime Text 4.

## Additional Key Bindings
Add those two commands to your User Key Bindings:

    {
      "keys": [
        "ctrl+p"
      ],
      "command": "insert_snippet",
      "args": {
        "name": "Packages/User/dhhruby-sublime/params.sublime-snippet"
      },
      "context": [
        {
          "key": "selector",
          "operator": "equal",
          "operand": "source.ruby"
        }
      ]
    },
    {
      "keys": [
        "super+enter"
      ],
      "command": "insert_snippet",
      "args": {
        "name": "Packages/User/dhhruby-sublime/defmethod.sublime-snippet"
      },
      "context": [
        {
          "key": "selector",
          "operator": "equal",
          "operand": "source.ruby"
        }
      ]
    }

## Attributions
Converted from:
https://github.com/dhh/textmate-rails-bundle

## License
MIT