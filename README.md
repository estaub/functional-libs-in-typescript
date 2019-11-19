# functional-libs-in-typescript
Survey of functional programming libs usable in Typescript


Because of their generic nature, using Javascript utility libraries with Typescript has often been tedious.  Libraries need to be designed to support type interencing of parameters and return values.

This is a cursory survey of FP libraries that claim Typescript support.  Many are Typescript-centric.  I have not tried these; this is just an aid to help narrow down the set of libraries to evaluate.

Some libraries were not studied because they didn't meet these support criteria:

* has well-supported types (even if only in DefinitelyTyped)
* doesn't demonstrate indifference toward typescript support
* has commits in the last year
* has documentation
* has been published to npm, with at least one additional release
* more than just one function
* general-purpose

Criteria reviewed

* number of contributors
* is written in typescript
* number of outstanding typing-related issues
* supports iterator chaining if relevant
* supports left-to-right function chaining (pipe vs. compose) if relevant

Areas supported

* Collections
* Either
* Option / Maybe
* Try
* Immutables
* Pipe
* Async


Candidates

* [collectable](https://github.com/frptools/collectable) - high-performance, persistent, immutable, functional data structures, a la Scala
* [fp-ts](https://gcanti.github.io/fp-ts/) - a coherent collection of abstract datatypes and type classes, grounded in category theory, a la Scala.
* [funfix](https://github.com/funfix/funfix) - complete implementations of Option, Either, and Try, a la Scala. 
* [immer](https://immerjs.github.io/immer/docs/typescript) - typically used for React state management; supports semi-immutable objects that are only mutable within a well-defined scope
* [iter-tools](https://github.com/iter-tools/iter-tools) - a rich toolset for working with iterables, both sync and async
* [monet](https://github.com/monet/monet.js) - Scala-derived Either, Maybe, immutable List, and a few more.
* [pratica](https://github.com/rametta/pratica) - Maybe, Result.  
* [prelude.ts](https://github.com/emmanueltouzery/prelude.ts)
* [purify](https://github.com/gigobyte/purify)
* [ramda](https://github.com/types/npm-ramda/)
* [remeda](https://remedajs.com/)
* [sanctuary](https://sanctuary.js.org/)
* [tifi](https://github.com/mobily/tifi)


The inclusion of ramda is questionable, done largely because it's the dominant JS FP utility lib.  Typescript friendliness was never a consideration in its API design.  There are two type libraries for it: one in [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/ramda), with many authors and recent PR's and a second, referenced in the [Ramda documentation](https://ramdajs.com/), in github.com/types/npm-ramda, which has not been updated in over a year.


Not studied

* [1-liners](https://github.com/1-liners/1-liners)
* [101](https://github.com/tjmehta/101)
* [barely-functional](https://github.com/cullophid/barely-functional)
* [creed](http://blog.briancavalier.com/creed/)
* [crocks](https://github.com/evilsoft/crocks/)
* [ferrum](https://github.com/adobe/ferrum)
* [folktale](https://folktale.origamitower.com) (TS-centric 3.0 release ETA mid-2020)
* [fpEs](https://github.com/TeaEntityLab/fpEs/)
* [pareto.js](https://github.com/concretesolutions/pareto.js/)
* [pico-lambda](https://github.com/trainyard/pico-lambda)
* [prelude-js](https://github.com/alanrsoares/prelude-js)
* [prelude-ls](http://www.preludels.com/#)













