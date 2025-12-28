# Awesome FP JS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a curated list of awesome 🌎 [functional programming](en.wikipedia.org/wiki/Functional_programming) code and learning resources for JavaScript. As a multi-paradigm programming language, JavaScript can be written in many styles. With these resources we want to help you to make better use of JavaScript’s support for writing programs in a _functional_ way.

Functional programming is a 🌎 [style of programming](wiki.haskell.org/Functional_programming) which models computations as the evaluation of expressions. Contrast this  with imperative programming where programs are composed of statements which change global state when executed. Functional programming typically avoids using mutable state and favors _side-effect free_ functions and _immutable_ data instead. This encourages writing composable and declarative programs that are easy to reason about.

##### Table of Contents

* [Libraries](#libraries)
  * [Data Structures](#data-structures)
  * [Algebraic Data Types](#algebraic-data-types)
  * [Lenses](#lenses)
* [Functional Languages that Compile to JavaScript](#functional-languages-that-compile-to-javascript)
* [Programming Tools](#programming-tools)
* [Resources](#resources)
  * [Books](#books)
  * [Articles](#articles)
  * [Videos](#videos)
  * [Examples and Exercises](#examples-and-exercises)
* [Community](#community)
* [Contribution](#contribution)

##### Tags
These may be appended to entries.  Each should be preceded by a "+" or "-" to indicate presence or absence of the tag's meaning.  "-" tags should only be included when they are likely to help someone filter libraries for their needs.  For instance, `-TS` tags are probably useful for Typescript users screening for types, but `-CT` tags would be less likely to be helpful to anyone.

* __CT__.  Category Theory.  This library appears to be inspired by Haskell, Scala, or another functional language's library with a grounding in Category Theory.
* __TS__.  Typescript.  This library has typescript types.

## Libraries

* <b><code>&nbsp;24100⭐</code></b> <b><code>&nbsp;&nbsp;1432🍴</code></b> [Ramda](https://github.com/ramda/ramda)) – A practical functional library for JavaScript that is designed specifically for a functional programming style. A style that makes it easy to create functional pipelines and never mutates user data. +TS.
* <b><code>&nbsp;&nbsp;&nbsp;686⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [Ramda Adjunct](https://github.com/char0n/ramda-adjunct)) is a community-maintained extension of Ramda.
* <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Ramda-extension](https://github.com/tommmyy/ramda-extension)) is set of utility point-free functions composed only from Ramda functions.
* <b><code>&nbsp;&nbsp;1752⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [Rambda](https://github.com/selfrefactor/rambda)) - A faster alternative to Ramda in under 10kB.
* <b><code>&nbsp;&nbsp;&nbsp;223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Rambdax](https://github.com/selfrefactor/rambdax)) - Extended version of Rambda
* [Folktale](http://folktale.origamitower.com/) – A standard library for functional programming in JavaScript. Typescript support expected mid-2020.  -TS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [lodash/fp](https://github.com/lodash/lodash/wiki/FP-Guide)) – An instance of <b><code>&nbsp;61504⭐</code></b> <b><code>&nbsp;&nbsp;7112🍴</code></b> [Lodash](https://github.com/lodash/lodash)) with its methods wrapped to produce immutable, auto-curried, iteratee-first, data-last methods. +TS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [iterflow](https://github.com/gv-sh/iterflow)) - Powerful iterator utilities for TypeScript with statistical operations, windowing, and lazy evaluation. +TS
* <b><code>&nbsp;&nbsp;&nbsp;223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [functional.js](https://github.com/functionaljs/functional-js)) – A lightweight functional JavaScript library that facilitates currying and point-free / tacit programming.
* <b><code>&nbsp;&nbsp;1547⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [101](https://github.com/tjmehta/101)) – A modern and modular JavaScript utility library made to work well with vanilla JavaScript methods.  -TS
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [fnuc](https://github.com/algesten/fnuc)) – A functional library for CoffeeScript (and JavaScript) to facilitate functional composition and higher order functions.
* <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [barely-functional](https://github.com/cullophid/barely-functional)) – A tiny (2.7kb) functional programming library using native ES5/6 operations. -TS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [bluebird-promisell](https://github.com/zhangchiqing/bluebird-promisell)) - A practical functional programming library for promises.
* [prelude.ls](http://gkz.github.io/prelude-ls/) – A functionally oriented utility library somewhat based off of Haskell's Prelude module. -TS.
* <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [preludejs](https://github.com/alanrsoares/prelude-js)) - Hardcore Functional Programming for JavaScript. -TS.
* <b><code>&nbsp;&nbsp;&nbsp;798⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [1-liners](https://github.com/1-liners/1-liners)) – Functional tools that couldn’t be simpler. A dead simple functional utility belt, hand-crafted with love and attention.  -TS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [fn-curry](https://github.com/thunklife/fn-curry)) – A simple function to curry a function.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [curry](https://github.com/thisables/curry)) – Curry your functions using function bind syntax.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [compose-function](https://github.com/stoeffel/compose-function)) – Compose a new function from smaller functions.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [functionize](https://github.com/paldepind/functionize)) – A collection of functions which aid in making non-functional libraries functional.
* <b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [lambdajs](https://github.com/loop-recur/lambdajs)) – The full ECMAScript API done a functional way.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [fp-dom](https://github.com/fp-dom/)) – Making the DOM functional.
* <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [react-on-lambda](https://github.com/sultan99/react-on-lambda)) - Replace JSX in React with functions (currying, compositions and etc). 
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [trifl](https://github.com/algesten/trifl)) – A functional user interface library with unidirectional dataflow and a virtual dom.
* <b><code>&nbsp;&nbsp;&nbsp;248⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [funcy](https://github.com/bramstein/funcy)) – An experiment in adding functional pattern matching to JavaScript. _Experimental_  :triangular_flag_on_post:
* <b><code>&nbsp;&nbsp;&nbsp;119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [date-fp](https://github.com/cullophid/date-fp)) – A functional utility library for working with JavaScript dates. All functions in date-fp are pure, autocurried and will not mutate the date objects they are applied to.
* <b><code>&nbsp;&nbsp;1654⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;126🍴</code></b> [js-joda](https://github.com/js-joda/js-joda)) – An immutable date and time library that provides a simple, domain-driven and clean API based on the ISO8601 calendar.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [\_part\_](https://github.com/AutoSponge/_part_)) – A micro library that encourages functional programming by making native methods available as partially applied functions.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [claire](https://github.com/robotlolita/claire)) – A property-based testing library for clearly specifying code invariants and behaviour.
* <b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [FPO.js](https://github.com/getify/fpo)) – FP library for JavaScript by Kyle Simpson (aka getify). Supports named-argument style methods.
* <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Javascript Parser Combinator](https://github.com/d-plaindoux/parsec)) – Javascript parser combinator implementation inspired by the Haskell's Parsec
* <b><code>&nbsp;&nbsp;&nbsp;373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [fun-task](https://github.com/rpominov/fun-task)) – An abstraction for managing asynchronous code in JS. Tasks are similar to Promises with the key difference that Tasks can represent a computation while Promises can represent only the results of a computation. Ships with Flow type definitions.
* <b><code>&nbsp;&nbsp;3496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [most](https://github.com/cujojs/most)) – Ultra-high performance reactive programming to help you compose asynchronous operations on streams of values and events without many of the hazards of side effects and mutable shared state.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [zen-signals](https://github.com/joaomilho/zen-signals)) – ☯ The simplest signal library possible
* <b><code>&nbsp;&nbsp;&nbsp;632⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [funfix](https://github.com/funfix/funfix)) – Funfix is a library of type classes and data types for Functional Programming in JavaScript, TypeScript and Flow.  +CT, +TS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [pico-lambda](https://github.com/trainyard/pico-lambda)) - Arrays, Strings and things the functional way. A 640b functional library based on native methods. -TS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pareto-js](https://github.com/concretesolutions/pareto.js/)) - An extremely small, intuitive and fast functional utility library for JavaScript -TS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [fpEs](https://github.com/TeaEntityLab/fpEs/)) - A small library provides simple usages of basic FP & pattern-matching/sumtype & MonadIO/Rx & Optional for Javascript. -TS.
* [Creed](http://blog.briancavalier.com/creed/) – Sophisticated and functionally-minded async with advanced features: coroutines, promises, ES2015 iterables, fantasy-land. -TS.
* <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [TGrid](https://github.com/samchon/tgrid)) - Grid Computing Framework, Network & Thread extension of <b><code>&nbsp;&nbsp;&nbsp;627⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [TSTL](https://github.com/samchon/tstl)), supporting RFC (Remote Function Call). +TS.
* <b><code>&nbsp;&nbsp;&nbsp;531⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Ferrum](https://github.com/adobe/ferrum)) – Iterator library with support for objects as iterables, lazy evaulation and`pipe()`; implements Traits (from Rust)/Type Classes (from Haskell) in JS. -TS.
* 🌎 [fp-ts](gcanti.github.io/fp-ts/) - Typed functional programming in TypeScript. +CT, +TS.
* <b><code>&nbsp;&nbsp;&nbsp;182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [iter-tools](https://github.com/iter-tools/iter-tools)) - a rich toolset for working with iterables, both sync and async. +TS.
* 🌎 [remeda](remedajs.com/) A function library roughly subsetting Ramda, but written in Typescript and thus more type-friendly. +TS.
* <b><code>&nbsp;&nbsp;1045⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [futil-js](https://github.com/smartprocure/futil-js)) - A collection of functional utilities that could conceivably be part of a library like lodash/fp, but for some reason or other are not.
* <b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [rubico](https://github.com/a-synchronous/rubico)) - 🏞 [a]synchronous functional syntax
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [rocket-pipes](https://github.com/darky/rocket-pipes)) - Powerful pipes, that chain Promise and ADT like Maybe or Either from popular FP libraries. +TS
* <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [omg-curry](https://github.com/Debdut/omg-curry)) - Comprehensive Curry Library with Operator Curry, Curry from functions, Decurry and Infifnite Curries.
* <b><code>&nbsp;&nbsp;&nbsp;349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [lfi](https://github.com/TomerAberbach/lfi)) - A Lazy Functional Iteration Library Supporting Sync, Async, and Concurrent Iteration.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [ts-multimethod](https://github.com/darky/ts-multimethod)) - TypeScript multimethods inspired by Clojure multimethods. +TS
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [ts-fp-di](https://github.com/darky/ts-fp-di)) - Tiny TypeScript functional dependency injection, based on Node.js AsyncLocalStorage. +TS
* <b><code>&nbsp;12433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;476🍴</code></b> [effect-ts](https://github.com/Effect-TS/core)) – A Fully-fledged functional effect system for typescript with a rich standard library. +TS
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [qio](https://github.com/tusharmath/qio)) – A type-safe, functional, performant, lawful, composable data structure that solves practical problems of effect-full code in node and browser. +TS
* <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Ditox.js](https://github.com/mnasyrov/ditox)) - Powerful dependency injection container for building modular apps. +TS
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [RxEffects](https://github.com/mnasyrov/rx-effects)) - Reactive state and effect management with RxJS. +TS
* <b><code>&nbsp;&nbsp;1149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [fxts](https://github.com/marpple/FxTS)) - Lazy evaluation and concurrency. +TS
* 🌎 [ts-belt](mobily.github.io/ts-belt/) - Fast, modern, and practical utility library for FP in TypeScript. (Uses a data-first approach like remeda, but is 🌎 [faster](mobily.github.io/ts-belt/benchmarks/v3.7.0/macbook-air-2020) than remeda, ramda, rambda, and lodash/fp.)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [fp-multik](https://github.com/lulldev/fp-multik)) - JS/TS lightweight value-multimethod util
* <b><code>&nbsp;&nbsp;1292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [true-myth](https://github.com/true-myth/true-myth)) A library for safe, idiomatic null and error handling in TypeScript, with `Maybe` and `Result` types, supporting both a functional style and a more traditional method-call style
* <b><code>&nbsp;14603⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [ts-pattern](https://github.com/gvergnaud/ts-pattern)) - The exhaustive Pattern Matching library for TypeScript, with smart type inference. Pattern Matching is a code-branching technique coming from FP languages.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [hyogwa](https://github.com/ENvironmentSet/hyogwa)) - Natural 🌿 effect system that fits TypeScript; Write codes as you write **plain typescript code**.
* <b><code>&nbsp;&nbsp;&nbsp;299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Verticalize](https://github.com/laurentpayot/verticalize)) - Super lightweight function that looks and behaves like a pipe operator.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [PureEval](https://github.com/PureEval/PureEval)) - A powerful JavaScript functional programming toolset, including utility functions and abstract data structures.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [context-fp](https://github.com/darky/context-fp)) - Microscopic functional programming context aka dependency injection. +TS
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [klubok](https://github.com/darky/klubok)) - Pipes with easy mocking, intended for huge amount of unit tests. +TS
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [fp-filters](https://github.com/Oaxoa/fp-filters)) - A curated collection of 130+ common-use filter functions. 
  Written in a functional programming style. Lightweight direct imports. Supports ES modules and CommonJS. 100% Unit 
  tested. +TS

### Data Structures

Write performant functional code by using the right data structures for the task.

* <b><code>&nbsp;&nbsp;&nbsp;424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Icepick](https://github.com/aearly/icepick)) Utilities for treating frozen JavaScript objects as persistent immutable collections
* <b><code>&nbsp;33099⭐</code></b> <b><code>&nbsp;&nbsp;1774🍴</code></b> [Immutable.js](https://github.com/facebook/immutable-js)) – Immutable persistent data collections.
* <b><code>&nbsp;28789⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;866🍴</code></b> [Immer](https://github.com/mweststrate/immer)) – Immer is a tiny package for immutable state based on copy-on-write mechanism. +TS.
* <b><code>&nbsp;&nbsp;3378⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Mori](https://github.com/swannodette/mori)) – ClojureScript’s persistent data structures and supporting API from the comfort of vanilla JavaScript.
* <b><code>&nbsp;&nbsp;3165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Baobab](https://github.com/Yomguithereal/baobab)) – persistent and optionally immutable data tree with cursors.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [immutable-sequence.js](https://github.com/qiao/immutable-sequence.js)) –  High performance implementation of Immutable Sequence in JavaScript, based on <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Finger Trees](https://github.com/qiao/fingertree.js)).
* [Timm](http://guigrpa.github.io/timm/) – Immutability helpers with fast reads and acceptable writes.
* <b><code>&nbsp;&nbsp;5986⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;263🍴</code></b> [Lazy.js](https://github.com/dtao/lazy.js)) – A utility library with a lazy engine under the hood that strives to do as little work as possible while being as flexible as possible.
* <b><code>&nbsp;&nbsp;&nbsp;518⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [DerivableJS](https://github.com/ds300/derivablejs)) – Functional Reactive State for JavaScript and TypeScript. DerivableJS enables you to make elegant declarative statements about how your bits of state are related. +TS.
* <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [imlazy](https://github.com/benji6/imlazy)) – Library for creating and manipulating lazy iterables using the ES2015 iteration protocols.
* <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [collectable](https://github.com/frptools/collectable)) – Super high-performance immutable data structures for modern JavaScript and TypeScript applications. +TS.
* <b><code>&nbsp;&nbsp;1659⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [List](https://github.com/funkia/list)) - An extremely fast immutable list with a comprehensive functional API. Designed to <b><code>&nbsp;&nbsp;1659⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [seamlessly integrate with Ramda](https://github.com/funkia/list#seamless-ramda-integration)).
* <b><code>&nbsp;&nbsp;&nbsp;383⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [prelude.ts](https://github.com/emmanueltouzery/prelude.ts)) - Immutable persistent collections, functional constructs such as Option and Either, and combinators. Implemented in Typescript but supports javascript too.  +CT, +TS.
* <b><code>&nbsp;&nbsp;&nbsp;627⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [TSTL](https://github.com/samchon/tstl)) - C++ STL (Standard Template Library) is implemented in TypeScript. STL Containers, iterators, algorithms and functors, that following functional programming rule, are provided. +TS.

### Algebraic Data Types

Use the laws of math instead of always reinventing your own thing. Algebraic!

* <b><code>&nbsp;10228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;378🍴</code></b> [Fantasy Land](https://github.com/fantasyland/fantasy-land)) – Not a library, but a specification of the Monad laws for libraries to follow.
* <b><code>&nbsp;&nbsp;&nbsp;775⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Static Land](https://github.com/rpominov/static-land)) – Specification similar to Fantasy Land but based on static methods rather than instance methods.
* <b><code>&nbsp;&nbsp;&nbsp;489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [immutable-ext](https://github.com/DrBoolean/immutable-ext)) – FantasyLand extensions for <b><code>&nbsp;33099⭐</code></b> <b><code>&nbsp;&nbsp;1774🍴</code></b> [Immutable.js](https://github.com/facebook/immutable-js)).
* <b><code>&nbsp;&nbsp;&nbsp;705⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [daggy](https://github.com/puffnfresh/daggy)) – Library for creating tagged constructors.
* <b><code>&nbsp;&nbsp;3056⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [Sanctuary](https://github.com/plaid/sanctuary)) – Sanctuary makes it possible to write safe code without null checks.  +CT, +TS.
* [monet.js](http://cwmyers.github.io/monet.js/) – A library that assists functional programming by providing a rich set of Monads and other useful functions.  +CT, +TS.
* <b><code>&nbsp;&nbsp;&nbsp;479⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [union-type](https://github.com/paldepind/union-type)) – A small JavaScript library for defining and using union types.
* <b><code>&nbsp;&nbsp;&nbsp;176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [freeky](https://github.com/DrBoolean/freeky)) – A collection of Free monads.
* <b><code>&nbsp;&nbsp;2495⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Fluture](https://github.com/Avaq/Fluture)) – A Future library with included control utilities, high performance and great error messages.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [fantasy-combinators](https://github.com/fantasyland/fantasy-combinators)) – Common combinators.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [fantasy-birds](https://github.com/fantasyland/fantasy-birds)) – Port of the Haskell package Data.Aviary.Birds. Everything for your combinatory needs.
* <b><code>&nbsp;&nbsp;1601⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [crocks](https://github.com/evilsoft/crocks)) – A collection of popular Algebraic Data Types with the main goal to curate and provide not only a common interface between each type, but also all of the helper functions needed to hit the ground running. -TS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [kudo-js](https://github.com/blitzritz/kudojs)) - A small utility library with a set of Algebraic Data Types and Helper functions to help you write code in a functional programming style in Javascript
* <b><code>&nbsp;&nbsp;1588⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [purify](https://github.com/gigobyte/purify)) - Functional programming library for TypeScript focusing on ADTs.  +CT, +TS.
* <b><code>&nbsp;&nbsp;&nbsp;147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [MojiScript](https://github.com/joelnet/MojiScript))- an async-first, opinionated, and functional language designed to have 100% compatibility with JavaScript engines
* <b><code>&nbsp;&nbsp;&nbsp;487⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Pratica](https://github.com/rametta/pratica)) - Small, simple, easy FP data types for pragmatic and productive developers who need to ship reliable code fast.  +CT, +TS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Tifi](https://github.com/mobily/tifi)) - Tifi is a library for functional programming in TypeScript. It solves a problem of the existence of both `undefined` and `null`. Tifi is inspired by the OCaml/Reason utilities for the option data type. +CT, +TS.
* <b><code>&nbsp;&nbsp;&nbsp;355⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [sweet-monads](https://github.com/JSMonk/sweet-monads)) - A collection of popular monads (such as `Either` and `Maybe`) and the lazy iterator.
* <b><code>&nbsp;&nbsp;6930⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [NeverThrow](https://github.com/supermacro/neverthrow)) - This package contains a `Result` type that represents either success (`Ok`) or failure (`Err`).

### Lenses

* <b><code>&nbsp;&nbsp;&nbsp;216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [lenses](https://github.com/DrBoolean/lenses)) – Composable <b><code>&nbsp;&nbsp;2074⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;272🍴</code></b> [kmett](https://github.com/ekmett/lens)) style lenses.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [optics](https://github.com/flunc/optics)) – Profunctor optics (Lens, Prism, iso).
* <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [ramda-lens](https://github.com/ramda/ramda-lens)) – :ram: :mag_right: Lens library built on Ramda.
* <b><code>&nbsp;&nbsp;&nbsp;109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [fantasy-lenses](https://github.com/fantasyland/fantasy-lenses)) – Composable, immutable getters and setters. (Profunctor lenses WIP)
* <b><code>&nbsp;&nbsp;&nbsp;177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [nanoscope](https://github.com/5outh/nanoscope)) – Lenses with dotty support.
* <b><code>&nbsp;&nbsp;&nbsp;921⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [partial.lenses](https://github.com/calmm-js/partial.lenses)) – Partial lenses is a comprehensive, high-performance optics library for JavaScript.
* <b><code>&nbsp;&nbsp;&nbsp;419⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [shades](https://github.com/jamesmcnamara/shades)) – A lodash-inspired lens-like library for Javascript.

## Functional Languages that Compile to JavaScript

* <b><code>&nbsp;&nbsp;9359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;791🍴</code></b> [ClojureScript](https://github.com/clojure/clojurescript)) – Compiles [Clojure](http://clojure.org/), a hosted Lisp with immutable persistent data structures, to JavaScript.
* [Elm](http://elm-lang.org/) – A type-safe functional programming language for declaratively creating web browser-based graphical user interfaces. Implemented in Haskell.
* [Fable](http://fable.io/) - Compiles [F#](http://fsharp.org) to readable JavaScript.
* [PureScript](http://www.purescript.org/) – A small strongly typed programming language that compiles to JavaScript.
* [Idris](http://www.idris-lang.org/) – A general purpose pure functional programming language with dependent types.
* <b><code>&nbsp;&nbsp;2619⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [GHCJS](https://github.com/ghcjs/ghcjs)) – 🌎 [Haskell](www.haskell.org/) to JavaScript compiler, based on GHC.
* <b><code>&nbsp;&nbsp;1567⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [ElixirScript](https://github.com/bryanjos/elixirscript)) – Compiles a subset of [Elixir](http://elixir-lang.org/), a dynamic, functional language designed for building scalable and maintainable applications, to JavaScript.
* [Js\_of\_ocaml](http://ocsigen.org/js_of_ocaml/) – Compiles [OCaml](http://ocaml.org/) bytecode to JavaScript, making it possible to run OCaml programs in the browser.
* 🌎 [Reason](reasonml.github.io) – Reason is a new interface to OCaml, a highly expressive dialect of the ML language featuring type inference and static type checking.
* 🌎 [ReScript](rescript-lang.org/) – (previously known as 🌎 [Bucklescript](rescript-lang.org/bucklescript-rebranding)) ReScript is a type-safe language that compiles to the highest quality of clean, readable and performant JavaScript code.
* [Scala.js](http://www.scala-js.org/) – Compiles [Scala](http://www.scala-lang.org/) to JavaScript.
* [LiveScript](http://gkz.github.io/LiveScript/) – LiveScript has a straightforward mapping to JavaScript and allows you to write expressive code devoid of repetitive boilerplate.
* <b><code>&nbsp;&nbsp;&nbsp;326⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Quack](https://github.com/quack/quack)) - A multi-paradigm programming language with gradual and duck typing that targets PHP and JS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [ion](https://github.com/ion-lang/ion)) - no BS JS
* <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [RamdaScript](https://github.com/yosbelms/ramdascript)) - A Lisp that compiles to opinionated JavaScript on top of RamdaJS
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [RacketScript](https://github.com/vishesh/racketscript)) – RacketScript aims to leverage both JavaScript and Racket's ecosystem, and make interoperability between them clean and smooth.
* 🌎 [Koka](www.microsoft.com/en-us/research/project/koka/) – Koka is a function-oriented programming language that seperates pure values from side-effecting computations with a familiar JavaScript like syntax.
* 🌎 [TypeScript](www.typescriptlang.org/) - TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.
* 🌎 [Gleam](gleam.run) - Gleam is a typed, functional language that compiles to Erlang and JavaScript.

## Programming Tools

* <b><code>&nbsp;&nbsp;&nbsp;972⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [eslint-plugin-fp](https://github.com/jfmengels/eslint-plugin-fp)) - ESLint rules for functional programming
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [4.5](https://github.com/TylorS/4.5)) – A functional assertions library. If you prefer functional style APIs and practices in JavaScript, this library aims to solve this with functionally-oriented assertions that are lazy and monadic.
* <b><code>&nbsp;&nbsp;&nbsp;202⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [hm-def](https://github.com/xodio/hm-def)) – Runtime type checking for JS with Hindley Milner signatures.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [ftor](https://github.com/kongware/ftor)) - A pluggable runtime type checker and functional debugging tool that supports parametric and row polymorphism, implicit rank-2 types and algebraic data types via Scott Encoding.

## Resources

### Books

* <b><code>&nbsp;23811⭐</code></b> <b><code>&nbsp;&nbsp;1902🍴</code></b> [Professor Frisby’s Mostly Adequate Guide to Functional Programming](https://github.com/MostlyAdequate/mostly-adequate-guide)) – This is a book on the functional paradigm in general using the world’s most popular functional programming language: JavaScript. It’s a practical introduction that builds up intuition through real-world examples. Strongly recommended. By 🌎 [Brian Lonsdorf](twitter.com/drboolean) (2016)
* <b><code>&nbsp;16800⭐</code></b> <b><code>&nbsp;&nbsp;1952🍴</code></b> [Functional-Light JavaScript](https://github.com/getify/functional-light-js)) – This book explores the core principles of functional programming (FP) that can be applied to JavaScript. But what makes this book different is that it approaches these principles without all the heavy terminology.
* 🌎 [JavaScript Allongé](leanpub.com/javascriptallongesix), the “Six” edition. Starts with as little as possible about functions – but no less! – and builds up towards powerful combinators and decorators. A foundational book. By [Reginald  Braithwaite](https://github.com/raganwald) (2016)
* 🌎 [Functional Programming in JavaScript](www.manning.com/books/functional-programming-in-javascript) teaches JavaScript developers functional techniques that will improve extensibility, modularity, reusability, testability, and performance. Through concrete examples and jargon-free explanations, this book teaches you how to apply functional programming to real-life development tasks. By Luis Atencio (2016)
* [Eloquent JavaScript](http://eloquentjavascript.net/). A modern introduction to programming using JavaScript. By Marijn Haverbeke (2014)
* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) teaches how to create code that’s beautiful, safe, and simple to understand and test by using JavaScript’s functional programming support. By [Michael Fogus](https://github.com/fogus) (2013)
* 🌎 [Grokking Simplicity](www.manning.com/books/grokking-simplicity) teaches functional programming from first principles. It uses JavaScript for all code examples and it uses real-world scenarios. By [Eric Normand](https://github.com/ericnormand) (2019)
* <b><code>&nbsp;&nbsp;&nbsp;382⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [scriptum](https://github.com/kongware/scriptum/blob/master/README.md)) - a no-frills functional programming library and a online course based on it

### Articles

* 🌎 [FP Concepts in JavaScript](medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-b0650773139c) – An introduction to Functional Programming Concepts in JavaScript. Uses the Ramda library to teach the concepts of composition, pointfree style, and functors through the simplest of examples.
* [Functional programming with JavaScript](http://stephen-young.me.uk/2013/01/20/functional-programming-with-javascript.html) – Another introduction to Functional Programming in JavaScript with a focus on three key themes: computation as the application of functions, statelessness, avoiding side effects.
* [A gentle introduction to functional JavaScript](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/) – A four-part series introduction functional programming in JavaScript that gets you up to speed what all the hype about functional programming is all about.
* 🌎 [Functors from first principle - explained with JS](dev.to/snird/functors-from-first-principle-37lh) - Explaining functors concept using JavaScript.
* 🌎 [Why Curry Helps](hughfdjackson.com/javascript/why-curry-helps/) – A short overview of how to write reusable and declarative code using currying.
* [Favoring Curry](http://fr.umio.us/favoring-curry/) - Practical applications of currying using Ramda.
* [Functional Mumbo Jumbo – ADTs](http://blog.jenkster.com/2016/06/functional-mumbo-jumbo-adts.html) – A beginner-friendly introduction to Algebraic Data Types.
* 🌎 [JavaScript and Type Thinking](medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d) – Learn to reason about your JavaScript code with _type thinking_. Algebraic Data Types are introduced as a conceptual basis to reason about program entities.
* 🌎 [Lazy, composable, and modular JavaScript](codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript) – Use four new features of ES6 – iterables, generators, fat arrows, and for-of – in conjunction with higher-order functions, function composition, and lazy evaluation, to write cleaner and more modular JavaScript.
* [Why Ramda](http://fr.umio.us/why-ramda/) – To those not used to functional programming, Ramda seems to serve no purpose whatsoever. However, it does offer a different style of coding, a style that’s taken for granted in purely functional programming languages: Ramda makes it simple for you to build complex logic through functional composition.
* 🌎 [Monads in JavaScript](curiosity-driven.org/monads-in-javascript) – An introduction to the Monad design pattern in JavaScript.
* 🌎 [A Monad in Practicality: First-Class Failures](web.archive.org/web/20241118045403/https://robotlolita.me/articles/2013/a-monad-in-practicality-first-class-failures/) – A walk through some practical use cases for specific monadic structures in JavaScript: use the `Maybe` monad to handle simple failure cases and model more complex scenarios with the `Either` monad or the `Validation` applicative functor.
* 🌎 [Functional programming](glebbahmutov.com/blog/tags/functional/) – Many articles on various aspects of functional programming in JavaScript by Gleb Bahmutov.
* <b><code>&nbsp;18663⭐</code></b> <b><code>&nbsp;&nbsp;1014🍴</code></b> [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon)) – Jargon from the functional programming world explained in JavaScript.
* [Data Structures in JavaScript](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/) – A series of blog posts that reimplements various data structures in JavaScript to better understand their benefits and downsides.
* 🌎 [So You Want to be a Functional Programmer](medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536) - Easy to understand, with some examples, introduction to Functional Programming in Javascript and Elm.
* 🌎 [Functional Programming for JavaScript People](medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504) - A complete introduction to functional programming patterns by Chet Corcos with a lot of javascript examples.
* 🌎 [Introduction to Immutable.js and Functional Programming Concepts](auth0.com/blog/intro-to-immutable-js/) - Learn about functional data structures and their uses in this overview of Facebook's popular library for JavaScript: Immutable.js.
* 🌎 [Master the JavaScript Interview: What is Functional Programming?](medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0) - A simple introduction by @ericelliott to functional principles and vocabulary.
* 🌎 [Composing Software](medium.com/javascript-scene/the-rise-and-fall-and-rise-of-functional-programming-composable-software-c2d91b424c8c) - A series of articles on learning functional programming and compositional software techniques in JavaScript ES6+ from the ground up by @ericelliott.
* 🌎 [Anonymous Recursion in JavaScript](dev.to/simov/anonymous-recursion-in-javascript) - Short and easy to understand article about implementing anonymous recursion in JavaScript.
* 🌎 [Functional Composition in Javascript](joecortopassi.com/articles/functional-composition-in-javascript/) – Step by step explanation of how to compose functions in javascript.
* 🌎 [Functional Programming Principles in Javascript](medium.freecodecamp.org/functional-programming-principles-in-javascript-1b8fc6c3563f) - Practical code examples to learn functional programming concepts like pure function, immutability, first-class entities, and higher order functions
* 🌎 [Basic Monads in Javascript](dev.to/rametta/basic-monads-in-javascript-3el3) - Introduction to 2 easy monads in Javascript, Maybe & Either.
* 🌎 [F# for JavaScript Devs](dev.to/rametta/f-for-js-devs-2b88) - Showcasing the similarities between F# and JavaScript
* 🌎 [A practical guide to writing more functional Javascript](medium.com/@nadeesha/a-practical-guide-to-writing-more-functional-javascript-db49409f71) - A step by step guide to convert imperative JavaScript to more declarative, functional JavaScript.
* <b><code>&nbsp;&nbsp;1168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [You don't (may not) need loops ➿](https://github.com/you-dont-need/You-Dont-Need-Loops)) - Loops are one of the first constructs that junior programmers learn, but they can pose many potential issues in the software development process, and could be avoided in many cases.

### Videos

* 🌎 [Classroom Coding with Prof. Frisby](www.youtube.com/watch?v=h_tkIpwbsxY&list=PLK_hdtAJ4KqX0JOs_KMAmUNTNMRYhWEaC) – A series that builds a “practical” web application with React and functional programming in JavaScript.
* 🌎 [Hey Underscore, You're Doing It Wrong!](www.youtube.com/watch?v=m3svKOdZijA) – Underscore.js claims to be a functional programming library, but is it really?
* 🌎 [Functional programming patterns for the non-mathematician](www.youtube.com/watch?v=AvgwKjTPMmM) – Learn about practical use cases for functors, applicatives, and monads.
* 🌎 [Pure JavaScript](vimeo.com/49384334) – Christian Johansen will show you how you can significantly up your game by leaving loops behind and embracing functions as the primary unit of abstraction.
* 🌎 [Functional programming in JavaScript](www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) - A series by Mattias Petter Johansson, from the youtube channel FunFunFunction, that is specifically about popularization of functional programming in JavaScript.
* 🌎 [Functional Programming in TypeScript](www.youtube.com/playlist?list=PLuPevXgCPUIMbCxBEnc1dNwboH6e2ImQo) - Discover functional programming with Typescript and create a library like fp-ts alongside Sahand Javid in this beginner-friendly YouTube playlist.
* 🌎 [Anjana Vakil: Learning Functional Programming with JavaScript - JSUnconf 2016](www.youtube.com/watch?v=e-5obm1G_FY) - A simple and understandable introduction of functional proramming in javascript.
* 🌎 [Functional Programming Basics In ES6](www.youtube.com/watch?v=FYXpOjwYzcs) - A complete introduction to functional programming in javascript made it easy by ES6.
* 🌎 [JavaScript Programmers Should Learn Algebraic Data Types -- May 2018 -- UtahJS Lehi](www.youtube.com/watch?v=B0VoyujJWIE) - Seth House explains how ADTs (Algebraic Data Types) can be useful to JavaScript developers.

### Examples and Exercises

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [FPJS-Class](https://github.com/loop-recur/FPJS-Class)) – Functional Programming learned through JavaScript.
* <b><code>&nbsp;&nbsp;2046⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;433🍴</code></b> [functional-javascript-workshop](https://github.com/timoxley/functional-javascript-workshop)) – The goal of this workshop is to create realistic problems that can be solved using terse, vanilla, idiomatic JavaScript to teach fundamental functional programming features of JavaScript.
* <b><code>&nbsp;&nbsp;1444⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [functional-frontend-architecture](https://github.com/paldepind/functional-frontend-architecture)) – A functional frontend framework. Based on Ramda + union-type-js + Flyd + Snabbdom
* <b><code>&nbsp;&nbsp;2029⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [cube-composer](https://github.com/sharkdp/cube-composer)) – A puzzle game inspired by functional programming.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [FP Youtube Search](https://github.com/jaysoo/example-fp-youtube-search)) – YouTube search app with ReactJS, Redux, and FP concepts
* 🌎 [Hardcore Functional Programming in JavaScript](frontendmasters.com/courses/functional-javascript/) – Learn to apply techniques from the forefront of computer science research to solve practical problems in Javascript. Discover functional programming and see it demonstrated step-by-step with how to build an example web app using abstract interfaces like Monads, Functors, Monoids and Applicatives. (_commercial_)
* <b><code>&nbsp;&nbsp;&nbsp;256⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Escape from Callback Mountain](https://github.com/justsml/escape-from-callback-mountain)) - Design & refactoring tips for Promise-based Functional JavaScript. Key benefits include better readability, testability, and reusability. MIT.
* [Learn Rx](http://reactivex.io/learnrx/) – A series of interactive exercises introducing five basic ingredients of functional (reactive) programming: the `map`, `filter`, `concatAll`, `reduce`, and `zip` functions.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Holdem Evaluator](https://github.com/laberin/holdem-eval)) - Yet another Holdem Evaluator with Ramda functional style

## Community

### Related Lists

* <b><code>&nbsp;&nbsp;&nbsp;289⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Awesome FRP JS](https://github.com/stoeffel/awesome-frp-js)) – A curated list of awesome (functional) reactive programming stuff in JavaScript.
* <b><code>&nbsp;&nbsp;&nbsp;996⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [lucasviola/Awesome Functional Programming](https://github.com/lucasviola/awesome-functional-programming)) – Awesome resources on functional programming theory and learning materials.
* <b><code>&nbsp;&nbsp;3519⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;304🍴</code></b> [xgrommx/Awesome Functional Programming](https://github.com/xgrommx/awesome-functional-programming)) – A ton of articles on functional programming, as well as a huge list of functional libraries for many programming languages.
* <b><code>&nbsp;&nbsp;&nbsp;305⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Functional Programming Resources In JavaScript](https://github.com/busypeoples/functional-programming-javascript))
* <b><code>&nbsp;&nbsp;1035⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [tk-learning-center/Functional Programming Learning Path](https://github.com/tk-learning-center/functional-programming-learning-path)) - A Learning Path for Functional Programming

### Talk

* 🌎 [Functional Programming Slack channel](fpslack.com/) – Community with a friendly channel for JavaScript as well as many other channels about functional programming in general.


## Contribution

:star: Suggestions and PRs are welcome! :star:

Please read the [contribution guidelines](./contributing.md) to get started.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christoph Hermann](http://stoeffel.github.io/) has waived all copyright and related or neighboring rights to this work.

## Source
<b><code>&nbsp;&nbsp;6032⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;396🍴</code></b> [stoeffel/awesome-fp-js](https://github.com/stoeffel/awesome-fp-js))