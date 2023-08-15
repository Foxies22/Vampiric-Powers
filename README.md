# Vampiric-Powers

DIO knows that the Stardust Crusaders have determined his location and will be coming to fight him. To foil their plans he decides to send out some Stand users to fight them. Initially, he summoned n
 Stand users with him, the i
-th one having a strength of ai
. Using his vampiric powers, he can do the following as many times as he wishes:

Let the current number of Stand users be m
.
DIO chooses an index i
 (1≤i≤m
).
Then he summons a new Stand user, with index m+1
 and strength given by:
am+1=ai⊕ai+1⊕…⊕am,
where the operator ⊕
 denotes the bitwise XOR operation.

Now, the number of Stand users becomes m+1
.
Unfortunately for DIO, by using Hermit Purple's divination powers, the Crusaders know that he is plotting this, and they also know the strengths of the original Stand users. Help the Crusaders find the maximum possible strength of a Stand user among all possible ways that DIO can summon.

Input
Each test contains multiple test cases. The first line contains the number of test cases t
 (1≤t≤10000
). The description of the test cases follows.

The first line of each test case contains a single integer n
 (1≤n≤105
)  – the number of Stand users initially summoned.

The second line of each test case contains n
 integers a1,a2,…,an
 (0≤ai<28
)  – the strength of each Stand user.

It is guaranteed that the sum of n
 over all test cases does not exceed 105
.

Output
For each test case, output a single integer, maximum strength of a Stand user among all possible ways that DIO can summon.
