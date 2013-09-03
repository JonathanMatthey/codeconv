CodeConv
=====

Case
----

***camelCase*** for functions and variables

---- function DoStuff(){}

++++ function soStuff(){}

***TitleCase*** for classes

---- var car = function(){}

++++ var Car = function(){}

***_prefix*** stands for global variables

---- var _document;

++++ var Document;


Layout
----

Multiple definitions of variable should be one lined at the top of a module

---- var test;
---- var test = 1;
---- var test = 2;

++++ var test, test = 1, test =2;


Vertical align multiple variable assignments

---- var whatAboutThisShit = yes,
----  hasPlayed = 1,
----  movedOn = 2;

++++ var whatAboutThisShit = yes,
++++     hasPlayed         = 1,
++++     movedOn           = 2;


Don't leave trailing comas in json objects

---- var obj = { asd, 
----     qwe, 
----     qwe,
----   }


++++ var obj = { asd, 
++++ qwe, 
++++ qwe
++++ }


