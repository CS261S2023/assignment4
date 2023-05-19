Assignment #4 


This assignment is intended to be relatively straightforward. Hopefully it
will be easy for you, and boost your assignment grade!!!

#1. (40pts) Write a subroutine to count the number of collisions for a hash table 
that has been filled. You are given a declaration of a function here: 

int hash_table_collisions(struct hash_table* hash_table) {
  /*
   * This function should count the number of collisions in the hash table
   *
   * this would essentially be the total number of elements above 1 for each 
   * "bucket" or hash array index. If there is only one element associated 
   * with a bucket, it would not count as a collision. Two elements would count
   * as one collision, three elements would count as 2 collisions and so on. 
   */
  int num_col = 0;
  
  // code goes here: 

  return num_col;
}

Clearly, nothing is done yet. You are to loop through the array, then 
traverse the linked list, and count the number of collisions. 

#2 (40pts) Write an updated hash function. You are given a second hash function, called
``hash_function2()''. You are to change the code so that it is different from 
the hash_function1(). Initially, they are the same. 

Your code should confirm that the number of collisions, counted by the function you
wrote for part #1, should reduce.

The lowest number of possible collisions for 11 elements, and 8 slots is 3. If you get the collisions down to 3, you will recieve full points. For each collision above that, you will lose 4 points. Be creative with your hash_functions!!! 
