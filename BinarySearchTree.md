 ## Binary Search Tree Task (Project 3)
 
#### 1 - Write the stages of Binary Search Tree with the array [7, 5, 1, 8, 3, 6, 0, 9, 4, 2].

   When we locate the elements into the binary search tree, Previously we will look at the root for it.

 1.1 - The first element of the array 7 is root.\
 ![1](https://user-images.githubusercontent.com/70758836/193569045-433b14ec-9d4b-4e93-a38d-c3affa0ef4d1.png)
 
 1.2 - 5 is less than the root 7 so the number 5 is written to **the left of the root 7**.\
 ![2](https://user-images.githubusercontent.com/70758836/193569191-5c4e374c-7d54-46f2-85f4-f9acdc6ff3b2.png)
 
 1.3 - 1 is less than 7 and then less than 5 so the number 1 is written to **the left of the node 5**.\
![3](https://user-images.githubusercontent.com/70758836/193569329-925d8f38-1e4a-4abc-8797-0c0b66b86d6d.png)

 1.4 - 8 is greater than the root 7 and the right side of the root is empty so 8 is written to **the right side of the root 7**.\
![4](https://user-images.githubusercontent.com/70758836/193569720-4c071c1d-7b8e-4f2f-a2bb-b4c97c3ff7c6.png)

 1.5 - 3 is less than the root 7, less than 5 but greater than 1 so the number 3 is written to **the right of the node 1**.\
![5](https://user-images.githubusercontent.com/70758836/193569739-e53da2bf-1f48-4797-8980-26e2fcf0a095.png)

 1.6 - 6 is less than the root 7 but greater than 5. So the number 6 is written to **the right of the node 5**.\
![6](https://user-images.githubusercontent.com/70758836/193569759-dd6aecea-197e-4b06-b099-268d226561ee.png)

 1.7 - 0 is less than the root 7, and the number 5 and 1 so the number 0 is written to the left side of **the last node 1 of the left side**. \
![7](https://user-images.githubusercontent.com/70758836/193569782-8803bc43-fe17-48bf-827b-6b716c66ce8b.png)

 1.8 - 9 is greater than the root 7 and the number 8 so the number 9 is written to **the right of the node 8**.\
![8](https://user-images.githubusercontent.com/70758836/193569789-0c2cfee8-1a30-4924-ab77-d151b582c72c.png)

 1.9 - 4 is less than the root 7 and the number 5 but greater than 3 so the number 4 is written to **the right of the node 3**.\
![9](https://user-images.githubusercontent.com/70758836/193569809-ae94c909-b417-4369-8988-70268c7b091e.png)

 1.10 - 2 is less than the root 7 and the number 5 but greater than 1. When looking to the right of the number 1, the right node of the number 1 is 3. Due to 
 the number 2 is less than 3. The number 2 is written to **the left of the node 3**.\
![10](https://user-images.githubusercontent.com/70758836/193569838-8aa0f86a-374f-4d10-a5f1-d9f071f5bce5.png)
