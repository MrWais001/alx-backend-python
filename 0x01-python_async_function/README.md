Async
This project contains tasks for learning to use asynchronous code in Python 3.

Tasks To Complete
 0. The basics of async
0-basic_async_syntax.py contains an asynchronous coroutine that takes in an integer argument (max_delay, with a default value of 10) named wait_random that waits for a random delay between 0 and max_delay (included and float value) seconds and eventually returns it. The random module should be used.

 1. Let's execute multiple coroutines at the same time with async
1-concurrent_coroutines.py contains a script that meets the following requirements:

Import wait_random from the previous python file that you’ve written and write an async routine called wait_n that takes in 2 int arguments (in this order): n and max_delay. You will spawn wait_random n times with the specified max_delay.
wait_n should return the list of all the delays (float values). The list of the delays should be in ascending order without using sort() because of concurrency.

