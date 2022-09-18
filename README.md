# Problem 

Given a list of patients which contains Blood Glucose details. Create a Hashing data structure that is used to store a large amount of data, which can be accessed in O(1) time by operations such as search, insert and delete.

**Write the following declarations and implementations:**</br>
1. display_hash(hashtable) method displays the hashtable.
2. insert(Hashtable, keyvalue, value) method that inserts a value onto a Hashtable, where Hashtable is a list of lists and keyvlaue is used to find the hash function using Hashing(keyvalue) method.

# Constraints
The data of every patient details is a list of integer and string.

## Sample Input - 1
```
3
[150, 'Tom'], [150, 'Jerry'], [131, 'Mickey'], [122, 'Donald'], [123, 'Ben'], [130, 'Scooby'].
```
## Sample Output - 1
```
0 --> 'Tom' --> 'Jerry' --> 'Ben' 
1 --> 'Scooby' 
2 --> 'Mickey' --> 'Donald'
```
## Sample Input - 2
```
10
[80, 'John'], [79, 'Shiney'], [101, 'Jincy'], [91, 'Sunitha'], [95, 'Binu'], [122, 'Betty'], [123, 'Yogi'], [94, 'Motu'], [96, 'Patlu'], [97, 'Nicky'], [98, 'Ricky'], [99, 'Aidan'].
```
## Sample Output - 2
```
0 --> 'John' 
1 --> 'Jincy' --> 'Sunitha' 
2 --> 'Betty' 
3 --> 'Yogi' 
4 --> 'Motu' 
5 --> 'Binu' 
6 --> 'Patlu' 
7 --> 'Nicky' 
8 --> 'Ricky' 
9 --> 'Shiney' --> 'Aidan'
```
