# Our topic is about Hashing and Hashtable

![hashtable](https://miro.medium.com/max/640/1*edQtyrc1W64rWgQbMMMscw.png)

## First what is Hashing or Hash?

- A hash is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.

## What is Hashtable ?

- Hashtables are a data structure that utilize key value pairs.

## So what is the Benefit of using Hashtables?

- Take advantage of an array’s O(1) read accessv

## How Hashing is implemented ?

- In two steps:

 - An element is converted into an integer by using a hash function. 

 - The element is stored in the hash table where it can be quickly retrieved using hashed key.

## So how hash is being created in more details?

- Here is a possible suggestion:

    + Add or multiply all the ASCII values of the key together.
    + Multiply it by a prime number such as 599.
    + Use modulo to get the remainder of the result, when divided by the total size of the array.
    + Insert into the array at that index.


## So one key should be resolved to one specific index .

## What would happen if two different keys resolved to be the same index of the array? 

- A collision would happen.

## So how to handle this ?

- Collisions are solved by changing the initial state of the buckets. Instead of starting them all as null we can initialize a LinkedList in each one.

- This way is called **Separate chaining (open hashing)**

## other Collision resolution techniques

- Linear probing (open addressing or closed hashing)

- Quadratic Probing

- Double hashing

## So let's talk about buckets and buckets sizes

- **Buckets** : A bucket is what is contained in each index of the array of the hashtable. 

- Each index is a bucket. 

- An index could potentially contain multiple key/value pairs if a collision occurs

- Hash Maps can have any number of buckets.

- If a hash map has only a few buckets it will be densely full and have many collisions.

- But if a hash map has more buckets it will be more sparsely populated, there will be less collisions, but there may be a lot of extra empty space.

#### So what the solution for this ?

- It’s possible to compute the “load factor” of a hash table.
- The load factor tells us something about how full the hash table is.
- So a hash table can start with only a few buckets and then grow and add more buckets to itself according to the load factor.

## Some internal Methods that we use with the hashtables and hashing:

- **Add()** method :takes in a key, gets the Hash, and goes to the index location specified. Then it check if something exists at that index already, if it doesn’t, add it with the key/value pair.If something does exist, add the new key/value pair to the data structure within that bucket.


- **Find()** method: takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.


- **Contains()** method: will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.

- **GetHash()** method : will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

