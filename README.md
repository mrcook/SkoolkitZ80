# Skoolkit Z80 Assembly Language Syntax Package

SkoolkitZ80 is a Z80 assembly language syntax highlighting package for [Sublime Text 3](https://www.sublimetext.com/) [dark theme], focusing specifically on the `.skool` files produced and used in the [Skoolkit](http://skoolkit.ca/) ZX Spectrum game disassembly toolkit.

![SkoolkitZ80 Example](images/skoolkitz80-syntax.png?raw=true "Example of SkoolkitZ80 syntax highlighting")


### Installation

##### [Package Control]

Open the SublimeText _Command Palette_ (`Shift-Cmd-P` on OS X, `Shift-Ctrl-P` on Linux/Windows) and select "Package Control: Install Package". Then search for and install SkoolkitZ80.

Note: once installed, _Package Control_ will keep SkoolkitZ80 up-to-date automatically.

##### Manual Installation

First, locate the SublimeText [packages folder](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-packages-directory) on your OS, then clone with git:

    cd /path/to/sublime/packages/folder
    git clone https://github.com/mrcook/SkoolkitZ80.git SkoolkitZ80


### Roadmap

- ~Better colours! The current ones are just a first-pass to get something working, but they're a bit harsh in places.~
- Better Z80 syntax highlighting - currently only handle the simpler opcode's.
- ~Support for HEX address values throughout.~
- Support Skoolkit loops.
- Support more Skoolkit block types.
- Support more Skoolkit ASM directives.
- Support Skoolkit macros.
- Syntax highlighting for Skoolkit CTL files?
- Highlight comment start/end {...} tags?


### Contributing

Pull requests are welcome.


### License

Copyright (c) 2018 Michael R. Cook

```
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```