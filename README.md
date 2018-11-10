# FrTime
 
FrTime is a Racket language that turns (most of) Racket into a language for Functional Reactive Programming (FRP). 
[Racket](https://racket-lang.org/) is a Scheme-based general-purpose programming language. 
One of the strong selling points of Racket is it's support for easily implementing domain-specific languages (DSL).

In that same vein FrTime provides the `frtime` language, which extends the `racket` language and so supports declarative construction of reactive systems in a syntax very similar to that of Racket.

Demo applications using FrTime can be found within this repository, see [here](https://github.com/racket/frtime/blob/master/demos/README).

Documentation for FrTime can be found [here](http://docs.racket-lang.org/frtime/) on the Racket Documentation page.

## Installation

In order to run FrTime, you first need to [download and install Racket](http://download.racket-lang.org/). 
The Racket installation contains an interactive REPL that can be started from the command line as `racket` 
and it contains the graphical IDE DrRacket, that can be started as `drracket`.

To use FrTime within the REPL, start it as `racket -I frtime`.
To use FrTime within DrRacket, start `drracket` and type `#lang frtime` into the top editing panel, called the definitions window.
To test whether FrTime works as expected, just type `undefined` into the REPL or in the the definitions window, 
the system should reply with `(undefined)`.
