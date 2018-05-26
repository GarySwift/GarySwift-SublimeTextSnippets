# SublimeTextSnippets & Packages
This a repo to keep my sublime text snippets and packages in sync across machines.

## Installed Packages

These are all of the packaages listed in _Package Control.sublime-settings_. These packages will be automatically installed by Sublime Text.

* A File Icon
* ApacheConf
* AutoFileName
* BracketHighlighter
* Case Conversion
* ColorPicker
* Console Wrap
* CSS3
* DA UI
* DocBlockr
* Emmet
* Emmet Css Snippets
* GitGutter
* Gutter Color
* Hayaku - tools for writing CSS faster
* HighlightWords
* HTML5
* JSONLint
* MarkdownEditing
* Maybs Quit
* Monokai Extended
* Package Control
* PHPSnippets
* Pretty JSON
* Random Everything
* Sass
* SCSS Snippets
* SideBarEnhancements
* SublimeGit
* SublimeLinter
* SublimeLinter-csslint
* SublimeLinter-jshint
* SublimeLinter-php
* Terminal
* Toggle the View Read-Only
* WordPress Completions

## Packages Not Under Version Control

[Open-Include](https://github.com/titoBouzout/Open-Include) by titoBouzout. This will open file paths found under the cursor with `Alt + D`. This was removed from [Package Control](https://packagecontrol.io/packages/Open-Include).

## Package Notes
This a quick guide to the installed packages.

### Console Wrap
This plugin helps you easily create (comment, remove, show all) log statements (console.log, print etc.)

Select a variable (or put cursor on it) and press `ctrl+shift+q`. The log line will appear on the next line. Press "ctrl+shift+q" again to change wrapping (info,warn etc.)

You can Also remove, comment or remove commented log statements from your selsection or from all document you can find that functionality in context menu (right click).

### DocBlockr
DocBlockr is a package for writing comment blocks.

#### Usage:
Pressing enter or tab after `/**` yields a new line and closes the comment.

Single-asterisk `/*` comment blocks behave similarly.

### Random Everything
Plugin for sublime text to generate random, ints, floats, strings and words

#### Usage
This plugin can only be accessed through the Cmd+Shift+P command.

Type random and you get the following choices:

* Random:Int - requires a range from a-b separated with a: -. Default: 1-100
* Random:Float - requires a range from a-b separated with a: -. Default: 1-100
* Random:Letters - generatates a random string of lower and upper -case letters with a length between 3 and 17
* Random:Letters and numbers - generatates a random string of lower and upper -case letters and numbers with a lengthbetween 3 and 17
* Random:Country - picks a random country
* Random:Word - picks a random word from /usr/share/dict/words
* Random:Text - picks 24 random words from /usr/share/dict/words
* Random:Date - picks a random ISO-8601 Date
* Random:First name - picks a random first name from the built-in datafile
* Random:Last name - picks a random last name from the built-in datafile
* Random:Full name - picks a random full name from the built-in datafiles
* Random:E-mail - picks a random E-mail address
* Random:Url - generates a URL using random words from /usr/share/dict/words

Case Conversion is a plugin for Sublime Text. It converts the current word/token between pascal, camel, snake, screaming snake, dot, dash (hyphen), forward slash /, backslash \ cases, and separated words.

### Case Conversion
Case Conversion is a plugin for Sublime Text. It converts the current word/token between pascal, camel, snake, screaming snake, dot, dash (hyphen), forward slash /, backslash \ cases, and separated words.

#### Keybindings
* To snake_case: “ctrl+alt+c”, “ctrl+alt+s”
* To SCREAMING_SNAKE_CASE: “ctrl+alt+c”, “ctrl+alt+shift+s”
* To camelCase: “ctrl+alt+c”, “ctrl+alt+c”
* To PascalCase: “ctrl+alt+c”, “ctrl+alt+p”
* To dot.case: “ctrl+alt+c”, “ctrl+alt+d”
* To dash-case: “ctrl+alt+c”, “ctrl+alt+h”
* To separate words: “ctrl+alt+c”, “ctrl+alt+w”
* To separate with forward slashes: “ctrl+alt+c”, “ctrl+alt+/”
* To separate with backslashes: “ctrl+alt+c”, “ctrl+alt+b”
* To toggle between snake_case, camelCase and PascalCase: “ctrl+shift+-”

### Sublime Terminal
Open Terminal at File Press `cmd+shift+t`

Open Terminal at Project `cmd+alt+shift+t`

### Toggle the View Read-Only
Right click tab, select `Toggle Readonly`

