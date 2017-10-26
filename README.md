# semicolon-shortcuts

## Branch of pimartin/trailing-semicolon, with option added for moving cursor to end of line after adding semicolon.

## Description
Add (or remove) a semicolon (or a comma) at the end of the line.

## Features
* Key bindings (default to `ctrl-;` and `ctrl-,`)
* Context menu in the editor (`Trailing...`)
* Multiple cursors, multiple lines
* Ignore empty lines (optional)
* Move to end of line after inserting semicolon (optional)
* Start a new line (optional with default commands, always with `trailing-semicolon:semicolon-newline` and `trailing-semicolon:comma-newline`)

## How to use
Press  `ctrl-;` or `ctrl-,` to add/remove a semicolon at the end of the selected lines. The context menu can also be used in the editor, see the `"Trailing..."` sub-menu.

Bind separate keys for these options if desired:
`trailing-semicolon:semicolon-newline`
`trailing-semicolon:comma-newline`
`trailing-semicolon:semicolon-eol`

## Known issues

