# Codechef

1. ### Find sum of all numbers whose largest factor/divisor is k
   https://www.codechef.com/START139D/problems/COUNTN

   Soultion :
   
   find all prime number upto 10^6 using sieve.
   find sum of prime number upto n using prefix sum.
   if even then only one ans(2*n) which has largest divisor x.
   otherwise for odd there are two case:-
   i. if the number is prime then ans is n*(sum of all prime no upto n).
   ii. if non-prime then ans is n*(sum of all prime no upto smallest prime factor of n).
---
2. Maximum length of subsequence that is divisible by number of distinct elements in that subsequence
   https://www.codechef.com/problems/LARGESTK?tab=statement

   Solution:
   int length = (curr/d)*d;
   Note : (4/3)*3 is not 4 but 3. This code can be used to traverse all possibilities of maximum length that is divisible by freq of dist elements.
---

