# Table of Contents

- [Linked Lists](#Linked-Lists)
- [General Top Interview Questions](#General-Top-Interview-Questions)
- [Google Interview Questions](#Google-Interview-Questions)


-----
- ## Linked Lists
    * What is it?
        - linked list is a data structure
    - ### Implementation
        - [Linked List Practice on My Personal Codepen](https://codepen.io/thomastaeChoi/pen/bGpjjRE?editors=0010)
        - [ ] Singly-linked List (with tail w/o tail)
            * basic property & methods
                - [ ] get(index) - returns the value of the nth item (starting at 0 for first)
                - [ ] addAtHead(value) - adds an item to the head of the list
                - [ ] deleteAtHead() - removes an item from head of the list
                - [ ] addAtTail(value) - adds an item at the tail of the list
                - [ ] deleteAtTail() - removes an item at the tail of the list
                - [ ] addAtIndex(index, val) - adds value at the n-th index of the list
                - [ ] deleteAtIndex(index) - removes an item at the n-th index of the list
                - [ ] size() - returns number of data elements in list
            
            * special methods
                - [ ] valueNFromEnd(n) - returns the value of the node at nth position from the end of the list
                - [ ] reverse() - reverses the list
                - [ ] removeValue(value) - removes the first item in the list with this value
        - [ ] Doubly-linked List
            - [Description (video)](https://www.coursera.org/lecture/data-structures/doubly-linked-lists-jpGKD)
            - No need to implement but understand what's going on
    - ### Two pointer technique
        * looking for a cycle
        * 2 pointers catching up to another
        * Time O(?) - how many times loop execute
        * Space O(1)
        * think of the speed of the 2 pointers
            * 1 fast or 1 slow
            * 2 traversing different list sizes
        
        - practice
            - [ ] [Linked List Cycle](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1212/)
            - [ ] [Linked List Cycle II](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1214/)
            - [ ] [Intersection of Two Linked Lists](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1215/)
            - [ ] [Remove Nth Node From End of List](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1296/)

    - ### Classic Linked List Problems
        * Reverse Linked List
            * 2 different ways from leetcode
            - [ ] [Reverse Linked List](https://leetcode.com/explore/learn/card/linked-list/219/classic-problems/1205/)
        * Remove Linked List Elements
            * use dummy/sentinel node technique
            - [ ] [Remove Linked List Elements](https://leetcode.com/explore/learn/card/linked-list/219/classic-problems/1207/)
        * Odd Even Linked List
            * 2 pointer technique is useful here
            - [ ] [Odd Even Linked List](https://leetcode.com/explore/learn/card/linked-list/219/classic-problems/1208/)
        * Palindrome Linked List
            * multiple ways to solve this
            - [ ] [Palindrome Linked List](https://leetcode.com/explore/learn/card/linked-list/219/classic-problems/1209/)

-----

- ## General Algo Interview Questions
    - ### Easy
    - #### Array
        - [ ] [Remove Duplicates from Sorted Array](https://leetcode.com/explore/featured/card/top-interview-questions-easy/92/array/727/)
        - [ ] [Remove Duplicates from Sorted Array II](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/)
        - [ ] [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
        - [ ] [Best Time to Buy and Sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/)
        - [ ] [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)
        - [ ] [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/)
        - [ ] [Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/)
        - [ ] [Single Number](https://leetcode.com/problems/single-number/)
        - [ ] [Plus One](https://leetcode.com/problems/plus-one/)
        - [ ] [Move Zeroes](https://leetcode.com/problems/move-zeroes/)
        - [ ] [Two Sum](https://leetcode.com/problems/two-sum/)
        - [ ] [Flatten Array]()
        
    - #### String
        - [ ] [Reverse String](https://leetcode.com/problems/reverse-string/)

    - #### Linked Lists
        - [ ] [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)
        - [ ] [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)

    - #### Binary Search
        

-----
- ## Google Interview Questions
    - ### Online Phone Screening
        - [ ] [Unique Email Addresses](https://leetcode.com/explore/interview/card/google/67/sql-2/3044/)
        - [ ] [License Key Formatting](https://leetcode.com/explore/interview/card/google/67/sql-2/472/)
        - [ ] [Fruit Into Baskets](https://leetcode.com/explore/interview/card/google/67/sql-2/3046/)
    
    - ### Arrays and Strings
        - [ ] [Longest Substrings Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
        - [ ] [Container With Most Water](https://leetcode.com/explore/interview/card/google/59/array-and-strings/3048/)
        - [ ] [3 Sum](https://leetcode.com/explore/featured/card/google/59/array-and-strings/3049/)
        - [ ] [Plus One](https://leetcode.com/explore/featured/card/google/59/array-and-strings/339/)
        - [ ] [Valid Parentheses](https://leetcode.com/explore/featured/card/google/59/array-and-strings/467/)
        - [ ] [K Closest Points to Origin](https://leetcode.com/explore/interview/card/google/59/array-and-strings/3062/)

    - ### Linked Lists
        - [ ] [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)