# Java-Programming

Prime - Threads Program
-->In this program, Thread class (can be a Thread subclass or Runnable interface implementer) which will be responsible in
fining the number of prime numbers in a given range. Program 1 will require you to write a class which will receive a range of value and it will count the number of primes in that range. It should also return the amount of time it took to calculate the count. Time can be measured as the difference to two calls to System.nanoTime static method. The exact number of threads in your program should be variable
between one to many. The number of threads can be a constant parameter t in your program. The program should then be able to allocate the proper ranges to the threads. The range for prime calculation should be from 3 to n. If n = 5,000,000 and t = 2, then thread 1 gets [3-2,500,000] and thread 2 gets [2,500,001-5,000,000]. If n = 5,000,000 and t = 3, then thread 1 gets [3-1,666,666] and thread 2 gets [1,666,667-3,333,333] and thread3 gets [3,333,334-5,000,000], etc.
