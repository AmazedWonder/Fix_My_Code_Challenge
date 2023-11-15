# Fix-my-code-0

Fix my code is a project, where I’ll jump into an existing code base and fix it!

downloaded the repository [0x00-Fix_My_Code_Challenge](https://intranet.alxswe.com/rltoken/GLYjW57NUS-s-JEsfjuNFA) and use it as initial files for all solutions.

## Tasks

| Task | File |
| ---- | ---- |
| 0. FizzBuzz | [0-fizzbuzz.py](./0-fizzbuzz.py) |
| 1. Print square | [1-print_square.js](./1-print_square.js) |
| 2. Sort | [2-sort.rb](./2-sort.rb) |
| 3. User password | [3-user.py](./3-user.py) |
| 4. Double linked list | [4-delete_dnodeint/](./4-delete_dnodeint/) |


### Fix:
0. FizzBuzz
Something is going wrong….

$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$

15 should print FizzBuzz not Fizz

1. Print square

Something is going wrong….

$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
$
./1-print_square.js 10 should print a square of size 10…

2. Sort
Something is going wrong….

$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
$

3. User password

Something is going wrong….

$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
$
My tests should not print any error…

4. Double linked list

Please find here my implementation of a Double linked list in C: [source code](https://intranet.alxswe.com/rltoken/x1hyDpdIwxbkpR_4E9PpOQ)
Something is going wrong….

$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint 
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
0
402
1024
-----------------
1
2
3
4
0
402
1024
-----------------
2
3
4
0
402
1024
-----------------
3
4
0
402
1024
-----------------
4
0
402
1024
-----------------
0
402
1024
-----------------
402
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
$
It doesn’t look right…


