# -codealpha_tasks

The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones. It typically starts with 0 and 1, and continues infinitely.

Here's the sequence:

0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, ...

The Logic Behind It

The core principle of the Fibonacci sequence is its recursive nature. To find the next number in the sequence, you simply add the two previous numbers.

Mathematically, it can be expressed as:

F(n) = F(n-1) + F(n-2)

Where:
    F(n) is the nth term in the sequence
    F(n-1) is the previous term
    F(n-2) is the term before that
    
For example:

  To find the 5th term:
        F(5) = F(4) + F(3)
        F(5) = 3 + 2
        F(5) = 5
