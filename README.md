## RxJS (Reactive Extensions for JS)

RxJS is a powerful library used in Angular for reactive programming. It allows you to work with asynchronous data streams and handle events in a more flexible and efficient way.

**Key Points about RxJS**

1. **Observable**: RxJS introduces the concept of Observables, which represent a stream of data that can be observed over time. This is useful for handling asynchronous operations like HTTP requests, user inputs, and more.

2. **Operators**: RxJS provides a wide range of operators to transform, filter, and combine data streams. Common operators include `map`, `filter`, `mergeMap`, and `switchMap`.

3. **Subscriptions**: To start receiving data from an Observable, you need to subscribe to it. Subscriptions allow you to define what should happen when new data is emitted, when an error occurs, or when the stream completes.

4. **Subjects**: Subjects are special types of Observables that allow you to multicast to multiple observers. They can act as both an Observable and an Observer, making them useful for scenarios like event emitters.

5. **Integration with Angular**: RxJS is deeply integrated into Angular. It's used in Angular's HTTPClient for handling HTTP requests, in forms for reactive form handling, and in various other parts of the framework to manage asynchronous data flows.
