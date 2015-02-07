## Node.js

Node.js® is a platform built on [Chrome's JavaScript runtime](http://code.google.com/p/v8/) for easily building fast, scalable network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.

Node is a single-threaded, single-process system which enforces shared-nothing design with OS process boundaries. It has rather good libraries for networking. I believe this to be a basis for designing very large distributed programs. The “nodes” need to be organized: given a communication protocol, told how to connect to each other. In the next couple months we are working on libraries for Node that allow these networks.

Ryan Dahl set out to build his JavaScript platform atop Mozilla's SpiderMonkey, the engine at the heart of Firefox. But after about two days, he switched to Google's V8, and that's where he stayed. "V8 is just a nice, clean library," Dahl says. "It's compact and extracted away from Chrome. It's distributed as its own package, and it's easy to build and it's got a nice header file with nice documentation. It's kind of constrained. It doesn't have dependancies on other things. It seemed much more modern than the Mozilla stuff."

Google isn't officially involved in the project, but according to Dahl and other Node developers, the company has been helpful when the project requires V8 bug-fixes or additional insight. "It's an exciting project. I was at the jsconf.eu conference in Berlin last year, and there was a lot of buzz around Node," Google V8 team member Erik Corry tells The Reg. "It's a very cool use of V8 and shows what you can do when you combine open source software in new ways, not necessarily anticipated by the original authors."

Originally, Dahl called his project web.js. It was merely a webserver, an alternative to Apache and other "blocking" servers. But the project soon grew beyond his initial webserver library, expanding into a framework that could be used to build, well, almost anything. So he rechristened it node.js.

He released an early incarnation of the platform in June 2009, but few noticed until he gave a demo at that year's jsconf. His 45-minute talk was met with a standing ovation, and the project was off and running, not just among application developers but at big-name cloud outfits as well.

reference:

> [discussion on stackoverflow](http://stackoverflow.com/questions/5621812/why-is-node-js-named-node-js) 
> [Ryan Dahl talks about node.js](http://www.theregister.co.uk/2011/03/01/the_rise_and_rise_of_node_dot_js?page=4)