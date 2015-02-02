Code Retreat - Java Template
=============================

Preparation
-----------
Get [gradle](http://gradle.org) if you don't have it already.

Programming
-----------

Main code goes under src/main/java. The main class is, by default,
coderetreat.GameOfLife. If you want to change that, change the value
of mainClassName in gradle. You may run your program with

```
gradle run
```

Tests are written in JUnit4. Put them under src/test/java. To run the
tests, run

```
gradle test
```
