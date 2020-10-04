# Stack Overflow learnings and answers

Interesting things I've learnt while answering Stack Overflow questions.

*[Stack Overflow Profile](https://stackoverflow.com/users/9632621/andrei-g%c4%83tej?tab=profile).*

- [Answers and Learnings from Stack Overflow](#answers-and-learnings-from-stack-overflow)
  - [Angular](#angular)
  - [RxJS](#rxjs)
  - [NgRx](#ngrx)

## Angular

* [startWith is returning old value](https://stackoverflow.com/a/57607344/9632621)
* [call method on component through @ViewChild in views into a QueryList](https://stackoverflow.com/a/57516972/9632621)
* [How can I get an ng-content select filter to work with projected template content?](https://stackoverflow.com/a/57822471/9632621)
* [When should I use “ngProjectAs” attribute?](https://stackoverflow.com/a/58574420/9632621)
* [How to dynamically render any number of ng-template](https://stackoverflow.com/a/58866130/9632621)
* [What is ViewChild](https://stackoverflow.com/a/58859787/9632621)
* [Create dynamic components with different location in logical component tree](https://stackoverflow.com/a/58688619/9632621)
* [ControlValueAccessor ngModel not being updated](https://stackoverflow.com/a/59717930/9632621)
* [What may happen if you don't unsubscribe from an Observable in canActivate of a guard?](https://stackoverflow.com/a/59610864/9632621)
* [Angular Template Reference : Bind height of one div to height of another](https://stackoverflow.com/a/59600020/9632621)
* [What method does angular reactive forms use to register a form control name](https://stackoverflow.com/a/59334476/9632621)
* [Better way to declare multiple depth routes in angular](https://stackoverflow.com/a/59009478/9632621) (custom `urlMatcher`)
* [Get value of input radio buttons and separate label values as an object?](https://stackoverflow.com/a/59850077/9632621)
* [Unit testing for service with multiple API calls in parallel using Karma and Jasmine / Angular 8](https://stackoverflow.com/a/59928722/9632621)
* [Angular 8: How to use a Multi-Content-Projection / Multiple-Transclusion slot twice?](https://stackoverflow.com/a/60906231/9632621)
* [Set Validators on Nested FormControl objects with Angular 8](https://stackoverflow.com/a/59974885/9632621)
* [Router event with switchMap duplicated output](https://stackoverflow.com/a/61257762/9632621)
* [Angular Rxjs: Observable does not display on view](https://stackoverflow.com/a/61772025/9632621)
* [Angular/RXJS Data issues with quickly repeated HTTP calls](https://stackoverflow.com/a/61771265/9632621)
* [Angular resolver observable completes too early](https://stackoverflow.com/a/62118446/9632621)
* [Angular: configure default QueryParamsHandling](https://stackoverflow.com/a/62087769/9632621)
* [Will using Angular Reactive Forms .get() method in template cause unnecessary method calls like a component method?](https://stackoverflow.com/a/62038649/9632621)
* [Why I can't access to @ViewChild reference of a div defined in another component (not a subcomponent) in this example?](https://stackoverflow.com/a/61897182/9632621)
* [Which observables do Angular complete automatically?](https://stackoverflow.com/a/62166851/9632621)
* [Angular observables never come to completion handler](https://stackoverflow.com/a/62259184/9632621) (+ the magic behind `ActivatedRoute`)
* [Why RouterLink adds the input to the end of current URL in bracket](https://stackoverflow.com/a/62607924/9632621) (+ how `RouterLink` works)
* [Angular lazy loaded module with child component default route](https://stackoverflow.com/a/62739986/9632621) (+ diff between relative and absolute redirects)
* [Angular 8 Jasmine/Karma spyOn behavior questions](https://stackoverflow.com/a/62811473/9632621) (+ how spies work when working with custom decorators)
* [How to best handle multiple subscriptions to the same observable on the template?](https://stackoverflow.com/a/62829161/9632621) (+ how `ConnectableObservable` works, `share()`)
* [Custom Angular FormField emitting event when configured not to](https://stackoverflow.com/a/62770069/9632621) (+ internals of `FormControl.setValue` & `CVA`)
* [Nested Routing in Angular](https://stackoverflow.com/a/62854244/9632621) (+ an explanation of `pathMatch: 'full'` option)
* [Using formcontrol.setError() to propagate error to a custom control component](https://stackoverflow.com/questions/63078764/using-formcontrol-seterror-to-propagate-error-to-a-custom-control-component/63079391?noredirect=1#comment111589469_63079391)
* [Handling errors for replaying, long-living Observables](https://stackoverflow.com/a/63308687/9632621)
* [NgModuleFactoryLoader.load() is not able to find the module](https://stackoverflow.com/a/63409187/9632621) (+ details about `RouterLinkWithRef`'s implementation)

---

## RxJS

* [Rxjs throw timeout error from pipe to observable error section](https://stackoverflow.com/a/57717689/9632621)
* [RxJS operators execution order](https://stackoverflow.com/a/58635055/9632621)
* [Angular RXJS Polling from within nested observables](https://stackoverflow.com/a/59811302/9632621)
* [How does observable and promise work in Angular?](https://stackoverflow.com/a/59542933/9632621)
* [File upload progress not being updated in the observable or completed before the observable is ready](https://stackoverflow.com/a/60967053/9632621)
* [How do I throw an exception after exhausting RxJs retryWhen operator attempts?](https://stackoverflow.com/a/60907538/9632621)
* [how to cancel one of the pending http request from many angular 8](https://stackoverflow.com/a/60894517/9632621)
* [Merge main Observable stream with updates](https://stackoverflow.com/a/60782310/9632621)
* [How to make rxjs pause / resume?](https://stackoverflow.com/a/60327351/9632621)
* [Is there a more functional implementation of this Writable Stream using RxJS that waits for a promise to resolve before processing?](https://stackoverflow.com/a/59876783/9632621)
* [How make an observable buffer data till an event happen and stop buffering?](https://stackoverflow.com/a/61640336/9632621)
* [RxJS: Check token validity before calling S3 List, and wait for the token in case it is invalid](https://stackoverflow.com/a/61610470/9632621)
* [Rxjs How to wait for all observables from dynamic components to complete in smart component](https://stackoverflow.com/a/61590410/9632621)
* [RxJS: Difference between auditTime and sampleTime?](https://stackoverflow.com/a/61569731/9632621)
* [Emit on cancel / complete of an inner observable](https://stackoverflow.com/a/61424614/9632621)
* [Typescript Function Overload Incompatibility](https://stackoverflow.com/a/61475316/9632621)
* [RXJS bufferedAmount / accumulate value / reduce with reset](https://stackoverflow.com/a/61468051/9632621)
* [RxJS Operator to compose observables into state?](https://stackoverflow.com/a/61437980/9632621)
* [RXJS subscribe only if previous value is not that great and I really need a better one](https://stackoverflow.com/a/61325784/9632621)
* [How to limit mergeMap inner subscriptions to the N latest or a sliding window queue](https://stackoverflow.com/a/61341294/9632621)
* [How RXJS type inference work when multiple pipe is used typescript](https://stackoverflow.com/a/61205100/9632621)
* [Is it necessary to unsubscribe/complete in a backend service to prevent side effects?](https://stackoverflow.com/a/61126488/9632621)
* [Combine rxjs streams, detect changes and return one value](https://stackoverflow.com/a/61082842/9632621)
* [Catching distinct errors in RxJS](https://stackoverflow.com/a/60997776/9632621)
* [Angular RxJs Observable stream merge data](https://stackoverflow.com/a/61824856/9632621)
* [How to finish an active debounceTime in OnDestroy](https://stackoverflow.com/a/61814654/9632621)
* [Unit testing NestJS Observable Http Retry](https://stackoverflow.com/a/61790455/9632621)
* [How to emit an event after 5 minutes have elapsed for each item (relative to items timestamp)?](https://stackoverflow.com/a/61797217/9632621)
* [Nest.js handling errors for HttpService](https://stackoverflow.com/a/61744692/9632621)
* [RxJs test for multiple values from the stream](https://stackoverflow.com/a/61733372/9632621)
* [Rxjs bindNodeCallback is not working properly with swithmap and flatmap](https://stackoverflow.com/a/61728226/9632621)
* [¿How exactly does the mergeMap operator work and in which cases is it used?](https://stackoverflow.com/a/61656247/9632621)
* [RxJS: conditional throttling](https://stackoverflow.com/a/61837535/9632621)
* [An interesting story about type inference with RxJs and typescript](https://stackoverflow.com/a/62059027/9632621)
* [RxJS unsubscribe hook](https://stackoverflow.com/a/62052529/9632621)
* [How to combine multiple observables on first observable complete and return as new observable in method](https://stackoverflow.com/a/62037510/9632621)
* [Using rxjs to throttle a callback](https://stackoverflow.com/a/62037167/9632621)
* [Subscription triggered only once after error](https://stackoverflow.com/a/62036694/9632621)
* [How do I buffer until last stream in RxJs](https://stackoverflow.com/a/61970971/9632621)
* [Unit testing a BehaviorSubject in a service](https://stackoverflow.com/a/61958692/9632621)
* [Rxjs - cancel debounce in the specific case](https://stackoverflow.com/a/61940464/9632621)
* [How to bring errors back into the normal events flow?](https://stackoverflow.com/a/61940305/9632621)
* [How to merge multiple subjects into observable and emit on subscribe](https://stackoverflow.com/a/61918602/9632621)
* [RxJS: Even if used `shareReplay()` on source observable, `throwError()` gets executed separately for each observable](https://stackoverflow.com/a/61889323/9632621)
* [RxJS countdown clock not displaying](https://stackoverflow.com/a/61865134/9632621)
* [Subscribing to valueChanges with combineLatest](https://stackoverflow.com/a/61874922/9632621)
* [How to emit only last request in subscribe method](https://stackoverflow.com/a/62158099/9632621)
* [Cache Http requests using only RxJS operators](https://stackoverflow.com/a/62167779/9632621)
* [Shuffling values returned from an Observable](https://stackoverflow.com/a/62178274/9632621)
* [rxjs share with interval causes issue when waiting for next interval iteration](https://stackoverflow.com/a/62243470/9632621)
* [Reinitialize Service when authenticating](https://stackoverflow.com/a/62345337/9632621)
* [Immediate observable not firing through Observable.defer](https://stackoverflow.com/a/62422444/9632621) (+ `publishReplay`, `ConnectableObservable`)
* [rxjs: why the stream emit twice when another stream use take(1)](https://stackoverflow.com/a/62657611/9632621) (+ `shareReplay` vs `publishReplay`, `ConnectableObservable`)
* [Do i need to unsubscribe from a Promise that has been converted to an Observable with Observable.from()?](https://stackoverflow.com/a/62684636/9632621)
* [Detect when a Subject has no more subscriptions](https://stackoverflow.com/a/62580184/9632621)
* [RxJS cache and refresh with shareReplay](https://stackoverflow.com/a/62636142/9632621)
* [With RXJS, how can I get an observable of keys pressed from the first press until the end of a time window?](https://stackoverflow.com/questions/63090683/with-rxjs-how-can-i-get-an-observable-of-keys-pressed-from-the-first-press-unti/63091173#63091173) (`share` and `buffer` use case)
* [NestJS interceptor - handle error inside .pipe()](https://stackoverflow.com/questions/63038134/nestjs-interceptor-handle-error-inside-pipe/63042489#63042489)
* [Obsevables and async iterators](https://stackoverflow.com/a/62313389/9632621)
* [Handling errors for replaying, long-living Observables](https://stackoverflow.com/a/63308687/9632621)
* [Do subscriptions to rxjs Subjects cause memory leaks if not unsubscribed when the subject goes out of scope?](https://stackoverflow.com/a/63258734/9632621)
* [Non-strict sequences with redux-observable and RxJS](https://stackoverflow.com/a/63513016/9632621) (+ an interesting case for `windowWhen`)
* [RxJs Marble testing concatMap with withLatestFrom](https://stackoverflow.com/a/63545403/9632621)
* [How can I chain RxJS observable in a redux-observable epic?](https://stackoverflow.com/a/64059464/9632621) (+ a nice mix of `startWith` and `endWith`)
* [rxjs retry with delay and multicast](https://stackoverflow.com/a/64097996/9632621)
* [Under the hood of `Observable.pipe`, `Observable.subscribe` and how `Subject.observers` array gets populated](https://stackoverflow.com/a/64120874/9632621)
* [Pausable behavior with `multicast`](https://stackoverflow.com/a/64195208/9632621)

---

## NgRx

* [NgRx reach action's payload inside flatMap's function](https://stackoverflow.com/a/59659407/9632621)
* [NGRX: http retry interceptor causing failure action not to be fired](https://stackoverflow.com/a/60913999/9632621)
* [NgRx Testing - Subscribe callback not updating during test](https://stackoverflow.com/a/61687625/9632621)
* [Is it possible to unite Reducer's ActionCreators?](https://stackoverflow.com/a/61403038/9632621)
* [Potential race condition using ngrx nested switchMaps](https://stackoverflow.com/a/61275072/9632621)
* [NgRx - Multiple actions are being dispatch during the router transition](https://stackoverflow.com/a/61246909/9632621)
* [Testing fail action - marble - ngrx Effects](https://stackoverflow.com/a/61663899/9632621) (+ how **TestScheduler** works)
* [How to use NgRx MockStore setState?](https://stackoverflow.com/a/61699758/9632621)
* [Ngrx after reseting the store, component dispatching an action](https://stackoverflow.com/a/61696539/9632621)
* [canLoad in children routes using NgRx](https://stackoverflow.com/a/61849336/9632621) (+ `pathMatch: 'full'`)
* [What is the correct way to read from NgRx store using selector in an angular service and use the value to call another function?](https://stackoverflow.com/a/62228750/9632621)
* [Angular NgRx Effect errors in Marble Testing: Expected $.length = 0 to equal 2. / Expected $[0] = undefined to equal Object](https://stackoverflow.com/a/62308683/9632621)
