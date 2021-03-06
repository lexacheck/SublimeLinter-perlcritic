SublimeLinter-perlcritic
========================

This linter plugin for
[SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3) provides an
interface to the [perlcritic](https://metacpan.org/pod/perlcritic).
It will be used with files that have the "Perl" syntax.

## Installation
SublimeLinter 3 must be installed in order to use this plugin. If
SublimeLinter 3 is not installed, please follow the instructions
[here](http://www.sublimelinter.com/en/latest/installation.html).

### Linter installation
Before installing this plugin, you must ensure that `perlcritic` is installed
on your system. To install `perlcritic`, type `cpanm perlcritic`.

### Plugin installation
Please use [Package Control](https://sublime.wbond.net/installation) to
install the linter plugin. This will ensure that the plugin will be updated
when new versions are available. If you want to install from source so you can
modify the source code, you probably know what you are doing so we won’t cover
that here.

To install via Package Control, do the following:

1. Within Sublime Text, bring up the [Command
   Palette](http://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html)
   and type `install`. Among the commands you should see `Package Control:
   Install Package`. If that command is not highlighted, use the keyboard or
   mouse to select it. There will be a pause of a few seconds while Package
   Control fetches the list of available plugins.

2. When the plugin list appears, type `perlcritic`. Among the entries you
   should see `SublimeLinter-perlcritic`. If that entry is not highlighted, use
   the keyboard or mouse to select it.

## Settings
For general information on how SublimeLinter works with settings, please see
[Settings](http://www.sublimelinter.com/en/latest/settings.html).
For information on generic linter settings, please see
[Linter Settings](http://www.sublimelinter.com/en/latest/linter_settings.html).

## Contributing
If you would like to contribute enhancements or fixes, please do the
following:

1. Fork the plugin repository.
2. Hack on a separate topic branch created from the latest `master`.
3. Commit and push the topic branch.
4. Make a pull request.
5. Be patient.  ;-)

Please note that modifications should follow these coding guidelines:

- Indent is 4 spaces.
- Code should pass flake8 and pep257 linters.
- Vertical whitespace helps readability, don’t be afraid to use it.

Thank you for helping out!
