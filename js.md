# Introduction to Programming

> A supplementary course introducing programming for media/culture technologies, based on the [JavaScript](http://en.wikipedia.org/wiki/JavaScript) language

KAIST [Graduate School of Culture Technology](http://ct.kaist.ac.kr), Spring 2014   
Hours: TBD   
Professor: [Dr. Graham Wakefield](http://www.grahamwakefield.net)   
TA: Seungwha Jang      
Language: English   
Web: [https://github.com/grrrwaaa/gct501/blob/master/js.md](https://github.com/grrrwaaa/gct501/blob/master/js.md)

## Why JavaScript?

JavaScript (JS) is a language of growing importance at the intersection of media/culture technology. 

> Note: Despite the similarity of name, JavaScript has no particular relation to Java. JavaScript is however also known as [ECMAScript](http://en.wikipedia.org/wiki/ECMAScript), JScript, and ActionScript.

### JS is everywhere:

- It has become the de facto 'language of the web', having evolved from lightweight scripting roots to a full-fledged application language with powerful capabilities in HTML5. 
- Not only is it used pervasively in client browser-based applications, it is also used for high-performance server applications, particularly using the [node.js](http://nodejs.org/) system. 
- JS has also been used as an embedded scripting language for desktop applications by Google, Adobe, OpenOffice, Apple, MicroSoft, Qt, GNOME, etc., including many media-oriented applications such as Max/MSP/Jitter, [Processing](http://en.wikipedia.org/wiki/Processing.js), Logic Pro, Unity, DX Studio, Maxwell Render, Flash, etc., and many games/game engines.

### For media/culture technology purposes:

- A browser-based JS application will run on Windows, OSX, Linux, Android, iOS etc., so long as browser applications are up to date. In recent years this has meant that even low-level audio signal processing and 3D OpenGL are available for use. 
- Browser and server-based applications open up easy possibilities to reach out to vast audiences and connect to social and other media networks, to explore collaborative interfaces, to interact with the increasing number of devices supporting websocket APIs, etc.

### Flexible, fast, well-supported:

- JS is a primarily imperative, procedural language (just like C, Java, Python, etc.), however it also supports functional programming features such as first-class functions. It is dynamically-typed and object-based, but uses a more flexible, dynamic [prototype-based](http://en.wikipedia.org/wiki/Prototype-based_programming) rather than static class-based inheritance. 

- Although it is a dynamic language, JS virtual machines such as [Google's V8](http://en.wikipedia.org/wiki/V8_(JavaScript_engine)) can achieve remarkably high performance through implicit Just-In-Time compilation to machine code.  

- The JS community is vast, and the available libraries, modules, frameworks, extensions, etc. are correspondingly huge. For example [npm](https://www.npmjs.org/) lists almost 60,000 (at time of writing) libraries for node.js desktop/server-side applications. 

- JS has become the language of choice for several Introduction to Computer Science (CS101) courses, including at [Stanford University](http://www.stanford.edu/class/cs101/) (also [here](https://www.coursera.org/course/cs101)). The Khan Academy also offers [a free, online course](https://www.khanacademy.org/cs).

## Syllabus

The syllabus contains three parallel tracks. The first track builds up understanding in the programming **language** itself, and principles of program construction in general. The second track applies these capabilities in a **browser-based** environment, beginning with basic HTML5 and gradually introducing commonly-used libraries/frameworks for media and culture technology, including audio synthesis, 2D, and 3D graphics. The third track explores the use of JS in **server and desktop** scenarios via Node.js, including commonly-used design patterns, libraries and frameworks, and deployment systems. 

The combination of the three tracks should enable students to construct complex, powerful and efficient applications with rich real-time audiovisual media, dynamic interaction, available for small- or large-scale networks of users, connected to the cloud, supporting data collection, visualization and exploration, the develompent of multi-user online games (even for the Oculus Rift), new concepts of social-technological communication, and more. 

- Language 
	- Weeks 1-4: Basic language capability
		- The distinction between language, run-time, developement environment, and libraries
		- Expressions and variables
		- Statements, control flow and functions
		- Strings and regular expressions
		- Objects and arrays, JSON (stringify/parse)
	- Weeks 5-8: Deeper understanding
		- Scope, closures, upvalues
		- OOP: Constructors, new and this, prototype-inheritance
		- Algorithms & data-structures
	
- Browser-based JS & HTML5 (weeks 1-12)
	- Weeks 1-4: Essentials
		- Development: [Chrome console](https://developers.google.com/chrome-developer-tools/docs/console), [jsfiddle](http://jsfiddle.net/), etc.
		- [HTML](http://www.w3schools.com/html/) & [CSS](http://www.w3schools.com/css/default.asp)
	- Weeks 2-6: Rendering
		- [DOM](http://www.w3schools.com/js/js_htmldom.asp), events and [jQuery](http://jquery.com/)
		- Canvas and [Easel.js](http://www.createjs.com/#!/EaselJS)/[processing.js](http://processingjs.org/articles/jsQuickStart.html) etc
	- Weeks 7-14: More libraries, frameworks and APIs
		- Data-viz and [D3.js](http://d3js.org/)
		- WebGL and [Three.js](http://threejs.org/)
		- WebAudio and [Gibberish.js](http://www.charlie-roberts.com/gibberish/)
		- Social APIs
		- etc.

- Desktop/server-side JS with [node.js](http://nodejs.org/) (weeks 8-14)
	- Weeks 8-14: Server-side applications
		- Development: local (terminal) or online using e.g. [Cloud 9](https://c9.io/)
		- Asynchronous, "evented"
		- [modules via NPM](https://www.npmjs.org/)
		- A simple file server, a flexible server application; using e.g. [express](http://expressjs.com/)
		- Continuous interaction via websockets and [socket.io](http://socket.io/)
		- Databases (SQL or noSQL)
		- Deployment on [Nodejitsu](https://www.nodejitsu.com/)/[Heroku](https://www.heroku.com/)/[Cloudno.de](http://cloudno.de/)/[AppFog](https://www.appfog.com/)/[Modulus.io](https://modulus.io/) [etc](https://github.com/joyent/node/wiki/node-hosting)
	- Weeks 12-14: Desktop and embedded
		- Node controlling subprocesses
		- Node + browser -> [node-webkit](https://github.com/rogerwang/node-webkit/wiki)
		- JS Embedded in other applications: [Max/MSP](http://www.cycling74.com/docs/max5/tutorials/max-tut/javascriptchapter01.html), Adobe, etc.

## Additional learning resources:

- [Eloquent JavaScript](http://eloquentjavascript.net/contents.html)
- [W3C JavaScript Guide](http://www.w3schools.com/js/)
- [Mozilla JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [Codecadamy](http://www.codecademy.com/tracks/javascript)
- [Khan Academy](https://www.khanacademy.org/cs/programming)
- [Stanford CS101](https://www.coursera.org/course/cs101)
- [The Node handbook](http://www.nodebeginner.org/)
- [How to Node](http://howtonode.org/)

