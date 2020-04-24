As I'm not amongst experts but what according to me this article is about, will try my best to give a brief look.

# Summary of an article!
In the given article "Thomas Heartman" is creating a super simple application that fetches(to go and get) some Pokemon data and prints it to the console.
Before he got into his objective, he introduced some basic concept of Async Rust, Future, executor.<br/>
<br/>
Async according to him, In Rust, running code concurrently or to run multiple computations on the same OS thread. Concuurent programming(asynchronous programming) is better for multi tasking when the task spends a lot of time waiting i.e., for a response from a server. These tasks are called I/O-bound.
.await is used when we need the result of async. computation and the values which are on waiting, called 'futures'.<br/>
<br/>
Multithreading is perfect for CPU intensive tasks that can be use across different, multiple cores.<br/>
<br/>

Then he explained an example of execution of async fn!<br/>

Future needs to be run on an executor,so that a task may be done.Other ececuters are Join, block_on etc.
<br/>

 We need to reach out to external library to do asynchronous programmming in Rust The standard library does not come with an executor, so we need to reach out to an external crate.<br/>
 
 The executor takes care of executing the futures, polling them and returnig their results when they're done.<br/>
 Here, in four steps he created an application:<br/>
	
 1) Making a new directory,
 2) Adding dependies,
 3) Fetching data from a url,
 4) Extend it!

