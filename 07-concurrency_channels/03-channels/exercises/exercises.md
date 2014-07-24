# Channels - Concurrency and Channels

### Code Review

[Unbuffered channels - Tennis game](../example1/example1.go)

[Unbuffered channels - Relay race](../example2/example2.go)

[Buffered channels - Control concurrency](../example3/example3.go)

(Advanced) [Timers](../advanced/timer)

(Advanced) [Semaphores](../advanced/semaphore)

(Advanced) [Pooling](../advanced/pool)

### Exercise 1
Review the provided program that will be used for future exercises. Program uses a function type, closures and creates goroutines to calculate Fibonacci numbers. This program is goroutine safe thanks to the sync package.
[Starter Program](exercise.go)

### Exercise 2
From exercise 1, use channels instead of the sync package.
[Simple Solution](final/final.go)

___
[![GoingGo Training](../../../00-slides/images/ggt_logo.png)](http://www.goinggotraining.net)
[![Ardan Studios](../../../00-slides/images/ardan_logo.png)](http://www.ardanstudios.com)
[![GoingGo Blog](../../../00-slides/images/ggb_logo.png)](http://www.goinggo.net)