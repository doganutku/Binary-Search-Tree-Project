[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Write the Binary Search Tree steps for given array.
--

    Start with the first element of this array. root equals to 7.
    After that we need to check every element with the root and put in a correct place.


                [7]           -- 0. level 
               /   \          
            [5]     [8]       -- 1. level
           /       /  \      
        [1]      [6]  [9]     -- 2. level
        /  \                 
      [0]   [3]               -- 3. level
      /  \
    [2]  [4]                  -- 4. level


    For a more balanced Binary Search Tree, firstly we can sort that array in a consecutive manner.
    We get [0,1,2,3,4,5,6,7,8,9] array. Binary Search Tree which contains 3 level height looks like:


             [5]           -- 0. level 
            /   \          
         [3]     [7]       -- 1. level
         / \     /  \      
      [1]  [4]  [6]  [8]   -- 2. level
      /  \             \  
    [0]   [2]          [9] -- 3. level
