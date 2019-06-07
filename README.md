# Hash-Table

## A data structure that created by assigning numerical indices to key-pair values by the use of a hashing function

## Hashing
* Calculation applied to the key to transform it into in index 

* Numeric keys can be divided by the number of available indices or addresses & taking the remainder key % address

* Alphanumeric keys can be divided by the sum of their ASCII codes

Tim: T = 84 i = 105 m = 109 === 298 % addresses 
 ### What happens if our function creates the same index?

 - this is called a collison, there is a few ways we can go about solving this

# Open Addressing
#### The process of moving an item somewhere that is not it's calculated position
## Linear probing

| Search        | Insert          | Delete  |
| ------------- |:-------------:| -----:|
| O(1)      |O(1) | O(1) |
| O(N)      | O(N)      |  O(N)|

