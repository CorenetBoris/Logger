

# logger

all credits to songho
http://www.songho.ca/misc/logger/logger.html

Debugging JavaScript programs is somewhat difficult compared to other programming languages because JavaScript does not provide a console to print out debugging messages. You may frequently use alert() function to print out a message or numeric data if your program performs properly or not. But, sometimes, alert() method is not appropriate, for example, calling alert() method inside a loop. Plus, you must close this modal dialog window manually in order to continue to run your JavaScript program.


This JavaScript Logger class provides a simple but very handy logging feature to print debugging messages on a separate console window at the bottom of the web browser. (This page already enabled Logger. You will see the log console at the bottom of this page.)

In order to use this logger, you only need include Logger.js in your html page. Logger class will automatically create a console for you at the bottom of the browser window when it is first time invoked.
