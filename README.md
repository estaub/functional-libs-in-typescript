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

* more than one contributor
* written in typescript
* supported typescript before API locked in
* Supports iterator chaining if relevant
* Supports left-to-right function chaining (pipe vs. compose) if relevant

Areas supported

* Collections
* Either/Option
* Try

Candidates

* [collectable](https://github.com/frptools/collectable)
* [fp-ts](https://gcanti.github.io/fp-ts/)
* [funfix](https://github.com/funfix/funfix)  
* [immer](https://immerjs.github.io/immer/docs/typescript)
* [monet](https://github.com/monet/monet.js)
* [pratica](https://github.com/rametta/pratica)
* [prelude.ts](https://github.com/emmanueltouzery/prelude.ts)
* [purify](https://github.com/gigobyte/purify)
* [tifi](https://github.com/mobily/tifi)


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
* [ramda](https://github.com/types/npm-ramda/)

The elimination of ramda needs explanation, since it's the dominant JS FP utility lib.  The authors of the package have shown no interest in supporting TS













