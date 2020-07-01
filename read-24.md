# read-24
### 19 june 2020
# [table of contents](https://h-griffin.github.io/reading-notes-401/)

###  Resources
- Read [Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)

hash tables take advantage of an arrays **O(1) look up time**, when given a key:value pair, it converts the key string into a hash number, and sotres that key as an index, this allowes the hash table to to skip itterating through the entire array to check if the key:value pair is the one that was searched for, each hash code is unique. searching through an array with a for loop has an **O(N) look up time** becuse the length of the list/array is unkown. while each key is uniwu, the hash code is created only from the input, not random, the same input receives the same hash code. 

to create a hash code, set a length to an array, such as 1024. then add or multiply all the ASCII values togehter and multiply it by a prime number. then use modulo to to get the remainder after dividing my the length of the array, this give what index it will be stored at. 

a collision is when different keys link to the same 'bucket' the string 'JB' and 'BJ' will have the same hash code. the hash table stores the value with the key by appending to the end of a linked list, and searches for the node with the value to ensure the correct value is returned with the hash code.

- Watch [what is a hash table?](https://www.youtube.com/watch?v=MfhjkfocRR0)
- Read [basics of hash tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
- Skim [hash table wiki](https://en.wikipedia.org/wiki/Hash_table)

