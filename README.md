JAX-RS 2.0 has given specification and implementation for asynchronous programming for server and client rest full services.
Jersey api also provided Asynchronous support for rest full services on top JAX-RS 2.0.
What all interfaces should be asynchronous
The implementations of interfaces that perform IO operations or long running computations are good candidates for making asynchronous.

https://dennis-xlc.gitbooks.io/restful-java-with-jax-rs-2-0-en/cn/part1/chapter13/server_asynchronous_response_processing.html
https://allegro.tech/2014/10/async-rest.html
https://praveer09.github.io/technology/2016/07/28/using-asynchrony-to-reduce-response-times/#why-do-we-need-asynchronous-programs
https://dzone.com/articles/jax-rs-20-asynchronous-server-and-client
https://abhirockzz.wordpress.com/2016/04/03/asynchronous-jax-rs-basics-gotchas/

<h2>jersey</h2>
https://jersey.github.io/
https://jersey.github.io/documentation/latest/async.html
http://www.jeejava.com/asynchronous-rest-service-using-jersey-completion-callback/
https://danielkvist.net/wiki/jersey-async-rest

<h2>JAX-RS 2.1 Reactive Client API</h2>
https://blogs.oracle.com/pavelbucek/jax-rs-21-reactive-client-api
Replacing Async() with Rx()
https://blog.dejavu.sk/2015/01/07/reactive-jersey-client-part-2-usage-and-supported-reactive-libraries/
https://blog.dejavu.sk/2015/01/07/reactive-jersey-client-part-3-customization/
https://github.com/jersey/jersey/tree/master/examples/rx-client-webapp
