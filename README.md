# Skoolkit Z80 Assembly Language Syntax Package

SkoolkitZ80 is a Z80 assembly language syntax highlighting package [dark theme] for [Sublime Text 3](https://www.sublimetext.com/), focusing specifically on the `.skool` files produced and used in the [Skoolkit](http://skoolkit.ca/) ZX Spectrum game disassembly toolkit.

![SkoolkitZ80 Example](images/skoolkitz80-syntax.png?raw=true "Example of SkoolkitZ80 syntax highlighting")


### Installation

##### [Package Control]

Open the SublimeText _Command Palette_ (`Shift-Cmd-P` on OS X, `Shift-Ctrl-P` on Linux/Windows) and select "Package Control: Install Package". Then search for and install SkoolkitZ80.

Note: once installed, _Package Control_ will keep SkoolkitZ80 up-to-date automatically.

##### Manual Installation

First, locate the SublimeText [packages folder](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-packages-directory) on your OS, then clone with git:

    $ cd /path/to/sublime/packages/folder
    $ git clone https://github.com/mrcook/SkoolkitZ80.git SkoolkitZ80


### Roadmap

- Theme: add a _light theme_, or support any currently installed theme.
- Improve handling of more complex Z80 opcodes.
- Support Skoolkit loops.
- Improve Skoolkit macro support.
- Syntax highlighting for Skoolkit CTL files?
- Highlight comment start/end {...} tags?


### Contributing

Pull requests are welcome.


### License

Copyright (c) 2018-2019 Michael R. Cook

```
This work is licensed under the terms of the MIT license.
For a copy, see <https://opensource.org/licenses/MIT>.
```