# FRP

[EricPonto.com](https://www.ericponto.com/)

## Functional programming

* pure funcs
* immutable data
* "containers" e.g. Array, jQuery
* functor: a generic mappable container

## Reactive programming

* react to changing data
* React: unidirectional data flow. Angular 1: dirty checking.
* General Theory of Reactivity (matrix)
* plural + temporal = Observable

## FRP

* RxJS `scan()` is like `Array.reduce()`
* Everything can be represented as Observable
* `Observable.of(val)`, `from(array)`, `fromPromise(promise)`
* Use with Ajax calls, events, animations, web sockets, web workers
* `mergeMap()` to flatten and map
* `startWith()` to init val
* `combineLatest()` to combine streams and use the latest value
* `App = Actions.map(Model).map(View)`
* Some gotchas -- use Cycle framework if you want Observables everywhere
