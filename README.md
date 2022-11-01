# Homework: stable-marriage


## Stable marriage
Given $n$ men and $n$ women, where each person has ranked all members of the opposite sex in order of preference, marry the men and women together such that there are no two people of opposite sex who would both rather have each other than their current partners. (When there are no such pairs, the matching is stable.)

The input is the name of a file defining an instance as in the following example. The output should be a list of pairs (2-el arrays) Husband-Wife.

Try the following instance which is given in `stable-marriage-instance.pi` 
* A:YZX,   
* B:ZYX,   
* C:XZY,  
* X:BAC,   
* Y:CBA,   
* Z:ACB

The output of `picat stable-marriage.pi stable-marriage-instance.pi` should be `[{1,3},{2,1},{3,2}]` (meaning that the 1st Man, i.e., A, is married to the third woman, i.e. Z, etc.)