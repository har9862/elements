<p align="center">
  <img src="https://cdn.rawgit.com/eudaldgr/elements/master/data/icons/128/com.github.eudaldgr.elements.svg" alt="Icon" />
</p>

# Elements
Periodic table

UNDER CONSTRUCTION

<p align="center">
    <img
    src="https://raw.githubusercontent.com/eudaldgr/elements/master/Screenshot1.png" />
</p>

<p align="center">
    <img
    src="https://raw.githubusercontent.com/eudaldgr/elements/master/Screenshot2.png" />
</p>

<p align="center">
    <img
    src="https://raw.githubusercontent.com/eudaldgr/elements/master/Screenshot3.png" />
</p>

<p align="center">
    <img
    src="https://raw.githubusercontent.com/eudaldgr/elements/master/ScreenshotA.png" />
</p>

### elements for elementary OS

A periodic table to learn about elements.

## Installation

### Dependencies

These dependencies must be present before building
 - `valac`
 - `meson`
 - `gtk+-3.0`
 - `granite`
 - `glib2.0`

 You can install these on a Ubuntu-based system by executing this command:
 
 `sudo apt install valac libgtk-3-dev libglib2.0-dev libgranite-dev meson`

### Building

```
git clone https://github.com/eudaldgr/elements.git
meson build && cd build
meson configure -Dprefix=/usr
ninja
sudo ninja install
com.github.eudaldgr.elements
```

### Deconstruct

```
sudo ninja uninstall
```
