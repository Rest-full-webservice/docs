JAX-RS 2.0 has given specification and implementation for asynchronous programming for server and client rest full services.
Jersey api also provided Asynchronous support for rest full services on top JAX-RS 2.0.
What all interfaces should be asynchronous
The implementations of interfaces that perform IO operations or long running computations are good candidates for making asynchronous.

Asynchronous programming is a means of writing non-blocking code by running a task on a separate thread than the main application thread and notifying the main thread about its progress, completion or failure.

This way, your main thread does not block/wait for the completion of the task and it can execute other tasks in parallel.

Having this kind of parallelism greatly improves the performance of your programs.


https://dennis-xlc.gitbooks.io/restful-java-with-jax-rs-2-0-en/cn/part1/chapter13/server_asynchronous_response_processing.html</br>
https://allegro.tech/2014/10/async-rest.html</br>
https://praveer09.github.io/technology/2016/07/28/using-asynchrony-to-reduce-response-times/#why-do-we-need-asynchronous-programs</br>
https://dzone.com/articles/jax-rs-20-asynchronous-server-and-client</br>
https://abhirockzz.wordpress.com/2016/04/03/asynchronous-jax-rs-basics-gotchas/</br>
http://niels.nu/blog/2016/spring-async-rest.html</br>
https://howtodevelopit.wordpress.com/2016/03/15/how-to-make-asynchronous-calls-for-a-restful-web-service-using-spring/</br>
http://www.baeldung.com/spring-async</br>
http://www.baeldung.com/spring-mvc-async-security</br>
https://www.slideshare.net/delabassee/jaxrs-21-reloaded</br>
https://www.leveluplunch.com/java/tutorials/026-asynchronous-native-java-method-calls-spring/</br>
https://www.callicoder.com/java-8-completablefuture-tutorial/</br>
https://dzone.com/articles/spring-and-threads-async</br>
https://spring.io/guides/gs/async-method/</br>
https://memorynotfound.com/asynchronous-service-with-spring-async-and-java-future/</br>
http://carlmartensen.com/completablefuture-deferredresult-async</br>

<h2>jersey</h2>
https://jersey.github.io/</br>
https://jersey.github.io/documentation/latest/async.html</br>
http://www.jeejava.com/asynchronous-rest-service-using-jersey-completion-callback/</br>
https://danielkvist.net/wiki/jersey-async-rest</br>
https://www.ivankrizsan.se/2016/12/29/rest-with-asynchronous-jersey-and-rxjava-part-4/</br>
https://www.ivankrizsan.se/2016/12/17/rest-with-asynchronous-jersey-and-rxjava-part-3/</br>
https://www.ivankrizsan.se/2016/11/19/rest-with-asynchronous-jersey-and-rxjava-part-1/</br>

<h2>JAX-RS 2.1 Reactive Client API</h2>
https://blogs.oracle.com/pavelbucek/jax-rs-21-reactive-client-api
Replacing Async() with Rx()</br>
https://blog.dejavu.sk/2015/01/07/reactive-jersey-client-part-2-usage-and-supported-reactive-libraries/</br>
https://blog.dejavu.sk/2015/01/07/reactive-jersey-client-part-3-customization/</br>
https://github.com/jersey/jersey/tree/master/examples/rx-client-webapp</br>
