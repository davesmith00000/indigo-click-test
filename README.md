# QA Test: Mouse Clicks!!

I'd like to know if the mouse clicks on the map and the buttons feel responsive to you.

This was a little proof of concept demo of isometric maps.

## What to look for

Do mouse actions feel snappy?
Do you feel like mouse events are getting lost?

## To run the demo

You'll need a static http server, the easiest way (inside this directory, on your command line, assuming linux/mac):

```
$ npm install http-server
http-server -c-1
```

Then open your browser at the address shown, usually [http://127.0.0.1:8080/](http://127.0.0.1:8080/).

If you're on Windows I'm not sure what your best best is - IIS or maybe Python's simple static http server?

## Controls

Everything can be driven from the mouse. The arrow controls allow map navigation, and you can hover over the grid, click on the grid, and multiselect the grid squares.

You can also use your keyboard (but.. please try the mouse for me!): W,A,S, and D to move around and Q and E to rotate.

***Thanks!!***

If you see problems, please can you let me know what platform you were running on, and what kind of mouse input device you were using.
