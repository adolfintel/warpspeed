# WarpSpeed.js

WarpSpeed.js is a simple and lightweight library for drawing an animated and customizable starfield to an HTML5 Canvas element, with a good amout of settings that you can tweak. Settings can also be tweaked at run time.

## See it in action
[Play with the configurator](http://fdossena.com/warpspeed/editor.html)

## Compatibility

As far as I know, it works on browsers as old as IE9.
Any browser that supports the Canvas element should be supported.
Remember to include a fallback if you're planning to support older browsers too.

## Basic usage

1. Include warpspeed.min.js into your page.
2. call new WarpSpeed('your canvas id here')

To tweak the settings, you can use `editor.html`, and copy the string at the bottom, then in your page you can call `new WarpSpeed('<your canvas id here>','<string from editor>')`

## Usage with React

1. Copy warpspeed.js in react-integration folder, and paste it in your React file.
2. Add 'import WarpSpeed from "./warpspeed.js"' at the top of your React file.
3. Add 'const x = new WarpSpeed('your canvas id here')' in your componentDidMount() function.

## Files

- __warpspeed.js__		Source code
- __warpspeed.min.js__	Compressed version to include in your pages. USE THIS ONE!
- __editor.html__			Visual settings editor
- __example[1-3].html__		Various usage examples

## Screenshots
![Screenshot](http://fdossena.com/warpspeed/screen1.png)
![Screenshot](http://fdossena.com/warpspeed/screen2.png)
![Screenshot](http://fdossena.com/warpspeed/screen3.png)
![Screenshot](http://fdossena.com/warpspeed/screen4.png)
![Screenshot](http://fdossena.com/warpspeed/screen5.png)

## License
Copyright (C) 2016-2021 Federico Dossena

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/lgpl>.
