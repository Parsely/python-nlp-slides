# python-nlp-slides

"Just Enough NLP with Python" is a little seminar I gave to the Parse.ly team about doing NLP with Python/NLTK and some of the problems with entity idenitfication in particular.

## View the slides online

Slides can be viewed in compiled form at:

http://pixelmonkey.org/pub/python-nlp/

Note that the slides can be controlled as follows:

 * Advance forward / back with the forward and back keys, or left click / right click of the mouse
 * Press `c` to get the "controls", which also allows you to skip slides and switch to outline mode
 * Outline mode includes some notes not included in the slidedeck, and also allows you to easily copy/paste examples into your own interpreter

I suggest you run through the slides in slide mode, and then review them in outline mode, doing examples from your own interpreter. That's how I tended to do things when I physically gave the presentation. Of course, you can also contact me on Twitter at [@amontalenti](http://twitter.com/amontalenti) if you want to see if I might be giving the talk nearby you sometime soon :-)

## How this was built

Using Python, of course. It's turtles all the way down.

I wrote the slides using [reST](http://docutils.sourceforge.net/rst.html), and specifically Docutils [support for S5 export](http://docutils.sourceforge.net/docs/user/slide-shows.html). Scripts are included to compile the presentation from the index.rst file and also to allow development of new slides with live recompilation using pyinotify (Linux systems only). See `build.sh` and `monitor.sh` for more information.
