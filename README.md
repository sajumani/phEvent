# Reactive Event Library

Functional Reactive Programming library in PHP.

The basic functionality is to take a value or event and send the value to observers. This observers are composable.

## Upgrade Policy

Library uses [semantic versioning](http://semver.org), so that you should be able to upgrade supporting version 1. Version 2 will probably support different ways of function composition, using generators, coroutines and other available language constructs. Also, it will take lessons learned from using this library and apply better API. Later major versions will drop support for PHP5.3. The only reason PHP5.3 is supported, is that all of the code will run on PHP5.3 and to widen the amount of users that can develop using the library.

Library supports PHP5.3. Other versions of PHP are supported allowing for features in other versions.

## Installation

You may install this library using composer.

**TODO: Need to add composer configuration.**

## Inspirations

This library will have many inspirations which will be listed here. The references will include all sources that were looked at for planning and deciding the best API function list and implementation.

## References

In no way is this list meant to be exhaustive list of all libraries or tutorials. Only a bare minimum set to reference for future planning and development. The attempt is to learn from current implementations and attempt to create something that is simple and still implement all of the features from existing libraries.

 * [Bacon.js](http://baconjs.github.io/)
 * [HaskellWiki Functional Reactive Programming](http://www.haskell.org/haskellwiki/Functional_Reactive_Programming)
 * [Functional Reactive Animation Paper](http://conal.net/papers/icfp97/)
 * [Sodium Haskell library](http://hackage.haskell.org/package/sodium)
 * [Reactive Banana](http://www.haskell.org/haskellwiki/Reactive-banana)
 * [RxJava](https://github.com/ReactiveX/RxJava)
 * [Paper on FRP in Java](http://haskell.cs.yale.edu/?post_type=publication&p=198)
 * [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)
 * [Kefir JS FRP library](https://github.com/pozadi/kefir)
 * [GoFlow](https://github.com/trustmaster/goflow) - Reactive programming for Go
 * [Wikipedia Article](http://en.wikipedia.org/wiki/Functional_reactive_programming) on Functional Reactive Programming
 * [StackOverflow answer](http://stackoverflow.com/questions/1028250/what-is-functional-reactive-programming) on what Functional Reactive Programming should be
 * [Reactive Programming Explained](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)

## Library Dependency

This library is not to have dependencies.

# User Guide


# Behaviours and Events

Behaviours are events to set up.
