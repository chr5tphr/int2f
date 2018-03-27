# int2f: A tiny script to convert (large) integers in ASCII to their byte-representation 

Originally inspired by [Illegal primes](https://en.wikipedia.org/wiki/Illegal_prime)

Execute using
```bash
./int2f $INTEGER $FILE
```
where $INTEGER is the integer to be converted and $FILE is the target output.

For example:
```bash
./int2f 22366696896197155182646936609 /dev/stdout
```
will print 'HELLO WORLD!' to stdout.

