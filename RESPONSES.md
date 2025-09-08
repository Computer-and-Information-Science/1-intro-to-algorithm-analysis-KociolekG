# CISC230 - Gage Kociolek

## factorial2.cpp

-  input/parameter impacting number of calls: **The unsigned int n impacts the number of calls.** 

- 3 specific examples of input/parameter and number of calls: **Given that the factorial is put into play, the greater number increases call amount. 0!=1 is called once, 1!=1 is called twice, 2!=2 is called three times.**

- number of recursive calls when input/parameter is *n* : **Formula for calls -> C(n) = n + 1.**

## ireverse2.cpp

- input/parameter impacting number of calls: **The unsigned int n again is the input that impacts the amount of calls but reverses them.**

- 3 specific examples of input/parameter and number of calls: **10->01, 12->21, 13->31**

- number of recursive calls when input/parameter is *n*: **c = calls, n = number of digits, r = reverse, n(r) = c**

## sreverse2.cpp

- input/parameter impacting number of calls: **s for the string carries the amount of characters input, affecting the calls.**

- 3 specific examples of input/parameter and number of calls: **Hello = olleH -> 5 calls, Goodbye = eybdooG -> 7 calls, racecar= racecar -> 7 calls**

- number of recursive calls when input/parameter is *n*: **similar concept to ireverse2.cpp but with letters instead of digits.**

## permute.cpp

- input/parameter impacting number of calls: **s for the string is the value that puts the program through various calls based on input.**

- 3 specific examples of input/parameter and number of calls: **Ton -> ton,tno,ont,otn,nto,not -> 6 calls, Hi -> hi, ih -> 2 calls, Bun ->bun,bnu,unb,ubn,nbu,nub -> 6 calls.**

- number of recursive calls when input/parameter is *n*: **The number of calls can be perceived in the perspective of a factorial where n! = n(n-1) varying on the characters input.**

## tower.cpp

- input/parameter impacting number of calls: **The parameter n increases number of calls varying by user input.**

- 3 specific examples of input/parameter and number of calls: **3 discs entered -> 7 calls, 4 discs entered = 15 calls, 5 disks -> 31 calls**

- number of recursive calls when input/parameter is *n*: **The tower of hanoi which this program is referencing matches the formula of (2^n-1) where n is the number input.**

## fibonacci2.cpp (presented in video lesson)

- input/parameter impacting number of calls: **There is no user input this time, the parameter n is set to 20 for the first 20 fibonacci numbers.**

- 3 specific examples of input/parameter and number of calls: **If someone were to edit how many values to call from N, the calls would match the input 2-> 1 1, 3 -> 1 1 2, 4 -> 1 1 2 3**

- number of recursive calls when input/parameter is *n*: **The value of N meets the number of calls, N = C**