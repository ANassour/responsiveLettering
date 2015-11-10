# responsiveLettering

![Responsive Lettering](responsiveLettering_screen.jpg)

Responsive lettering: scalable, interpolating vector shapes that can make themselves fit in a range of rectangles.
<a href="http://letterror.com/dev/mathshapes/">More examples here.</a>

The python code consists of a couple of scripts to generate the SVG needed for responsive lettering. Somehow these compile into a RoboFontExtension, but that probably needs to be fixed.

The www/ folder contains a working example. As it is loading .js and .json files it might be necessary to serve the files from a real server. When everything works it should look something like <a href="http://letterror.com/dev/public/index.html">this</a>.

The www code depends on jQuery, but probably not a very specific version, and snap.js, a very handy library for manipulating SVG data. All the vector data comes from json, so in theory it might be possible to rewrite all this without snap.js. 

Ideas and code very much in debt to Jeremie Hornus, Nina Stössinger, Andrew Johnson, Onur Yazıcıgil, and Nick Sherman. 

## License

The Respsonve Lettering package is published under the [BSD-3 license](http://opensource.org/licenses/BSD-3-Clause).
