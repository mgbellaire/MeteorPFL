# Meteor Prepare For Launch

JSCS and JSHint configuration for Meteor Style Guide rules

## Setup

1. Install [JSCS][jscs]: `npm install -g jscs`
2. Install [JSHint][jshint]: `npm install -g jshint`
3. Copy jscsrc to your home directory: `cp ~/stylejs/jscsrc ~/.jscsrc`
4. Copy jshintrc toyour home directory: `cp ~/stylejs/jshintrc ~/.jshintrc`

## How to use

There are many JSCS integrations for [Sublime Text][subl-jscs], [Vim][vim-jscs] and [PHPStorm][pstorm-jscs]. There are also many integrations for JSHint on those same applications ([Sublime Text][subl-jshint], [Vim][vim-jshint] and [PHPStorm][pstorm-jshint]).

The alternative to these integrations is to run the binaries yourself on the command line:
* `jscs $PATH` will do recursive checks in a directory or check a specific path. The .jscsrc rules are applied automatically.
* `jshint $PATH` will acts the same as JSCS.

[jshint]: http://jshint.com
[jscs]: http://jscs.info
[subl-jscs]: https://packagecontrol.io/packages/SublimeLinter-jscs
[vim-jscs]: https://github.com/scrooloose/syntastic
[pstorm-jscs]: http://plugins.jetbrains.com/plugin/7554
[subl-jshint]: https://github.com/victorporof/Sublime-JSHint
[vim-jshint]: https://github.com/scrooloose/syntastic
[pstorm-jshint]: https://www.jetbrains.com/phpstorm/help/jshint.html
