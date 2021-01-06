# Table of Contents

- [Linked Lists](#Linked-Lists)
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
                - [ ] removeAtHead() - removes an item from head of the list
                - [ ] addAtTail(value) - adds an item at the tail of the list
                - [ ] removeAtTail() - removes an item at the tail of the list
                - [ ] addAtIndex(index, val) - adds value at the n-th index of the list      
                - [ ] removeAtIndex(index) - removes an item at the n-th index of the list            
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
            - [x] [Linked List Cycle](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1212/)
            - [x] [Linked List Cycle II](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1214/)
            - [x] [Intersection of Two Linked Lists](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1215/)
            - [x] [Remove Nth Node From End of List](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1296/)

    - ### Classic Linked List Problems
        * Reverse Linked List
            * 2 different ways from leetcode
            - [x] [Reverse Linked List](https://leetcode.com/explore/learn/card/linked-list/219/classic-problems/1205/)
        * Remove Linked List Elements
            * use dummy/sentinel node technique
            - [x] [Remove Linked List Elements](https://leetcode.com/explore/learn/card/linked-list/219/classic-problems/1207/)
        * Odd Even Linked List
            * 2 pointer technique is useful here
            - [x] [Odd Even Linked List](https://leetcode.com/explore/learn/card/linked-list/219/classic-problems/1208/)
        * Palindrome Linked List
            * multiple ways to solve this
            - [x] [Palindrome Linked List](https://leetcode.com/explore/learn/card/linked-list/219/classic-problems/1209/)

-----
- ## Google Interview Questions
    - ### Online Phone Screening
        - [x] [Unique Email Addresses](https://leetcode.com/explore/interview/card/google/67/sql-2/3044/)
        - [x] [License Key Formatting](https://leetcode.com/explore/interview/card/google/67/sql-2/472/)