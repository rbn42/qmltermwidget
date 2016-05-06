<<<<<<< HEAD
#QMLTermWidget

##Description
This project is a QML port of qtermwidget. It is written to be as close as possible to the upstream project in order to make cooperation possible.

At the moment this plugin is powering cool-retro-term and the ubuntu-terminal-app.

This package also contains a simple test application.

To build it:

qmake && make

To test it:

qmlscene -I . test-app/test-app.qml
=======
# QTermWidget

A terminal emulator widget for Qt 5.

QTermWidget is an opensource project originally based on KDE4 Konsole application,
but it took its own direction later.
The main goal of this project is to provide unicode-enabled, embeddable
Qt widget for using as a built-in console (or terminal emulation widget).

# Installation

Requirements:
 * Qt >= 5.4
 * cmake >= 3.0

Supported platforms:
 * Linux
 * BSD
 * OS X

Building

 1. `mkdir -p build && cd build`
 2. `cmake `<path/to/source>`
 3. make

Run `make install` to install.

# License

This project is licensed under the terms of the
[GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html) or any later version.

See the LICENSE file for the full text of the license.
>>>>>>> 3bfdfe86be5dd7699ffa4b0dc8977b5483d3eeba
