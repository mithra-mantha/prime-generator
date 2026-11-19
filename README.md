# prime-generator
This is a repository to store my prime generation programs. I am experimenting with different algorithms and different languages to see which one becomes the fastest.
## Rules
Any language and any algorithm can be used, as long as it satisifies these criteria. It can be scripted, compiled, functional; doesn't matter.
### Execution
* Each program must accept an integer argument in the terminal. It then return a list of all the prime numbers from 1 to that integer. The list may not contain composite numbers, 0, or 1. The program does not necessarily have to print the list to the screen(to stop the terminal rendering speed from bottlenecking execution), but it must exist somewhere in memory.
* Programs may only store the primes 2, 3, and 5 and optimize by eliminating multiples of those primes. No other primes can be used.
* They must be completely self contained and cannot use an external library, or a bridge to another language(like C extensions for Python). However, they can use built in modules, like using the `array` module in Python.
### Timing:
* Timing is measured by the time it takes for the program to execute from the terminal. The program cannot self-time itself because different languages use different timing mechanisms.