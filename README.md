# My projects

Hi, I am Jiří Prokop currently enrolled in 3rd year of bachelor's degree at University of technology - Faculty of Information technology(also known as VUT FIT).

Here are some of the projects I worked on:

## Interpret
The goal was to create an interpret for the assigned language. First it's parsed with [parser.php](interpret/parse.php) into a xml structure. 
[interpret.py](interpret/interpret.py) then loads it and starts the execution.

## IJC - du1

Our assignment was to create a program which would could within short period of time find up 3 milion prime numbers and then efficiently store them in bitfield. 

- bitset: functions for manipulation with bits(using inline functions or macros to ensure speed)
- error: functions for easier error handling
- primes: implementing the Sieve of Eratosthenes
       
Functionality is then tested with steg-decode, where a secret message is hidden in prime possitions of pixels in picture of ppm format.

## My Malloc
This program implements my own malloc with arena allocation technique.

## IPS - du2
Basic program for playing with threads. Mostly C code with C++ mutexes.
