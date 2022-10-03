## Merge Sort Task (Project 2) :

#### 1 - Write the stages of sorting the array [16,21,11,8,12,22] with using Merge Sort Algorithm.
#### Splitting Processes ;
  1.1 - [16, 21, 11] - [8, 12, 22]\
  1.2 - [16, 21] - [11] - [8, 12] - [22]\
  1.3 - [16] - [21] - [11] - [8] - [12] - [22]
  
#### Combining Processes ;
    
  1.4 - [16, 21] - [11] - [8, 12] - [22]\
  1.5 - [11, 16, 21] - [8, 12, 22]\
  1.6 - [8, 11, 12, 16, 21, 22]
  
  The sorted array is [8, 11, 12, 16, 21, 22] with 6 steps using Merge Sort Algorithm.
  
  -------------------------------------------------------------------------------------
  
  #### 2 - Write the Big O Notation of Merge Sort Algorithm.
  **O(n.log(n))**
