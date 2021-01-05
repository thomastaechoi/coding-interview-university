- # Linked Lists
    - ### Implementation
        - [ ] Singly-linked List (with tail w/o tail)
            - [ ] size() - returns number of data elements in list
            - [ ] empty() - bool returns true if empty
            - [ ] value_at(index) - returns the value of the nth item (starting at 0 for first)
            - [ ] push_front(value) - adds an item to the front of the list
            - [ ] pop_front() - remove front item and return its value
            - [ ] push_back(value) - adds an item at the end
            - [ ] pop_back() - removes end item and returns its value
            - [ ] front() - get value of front item
            - [ ] back() - get value of end item
            - [ ] insert(index, value) - insert value at index, so current item at that index is pointed to by new item at index
            - [ ] erase(index) - removes node at given index
            - [ ] value_n_from_end(n) - returns the value of the node at nth position from the end of the list
            - [ ] reverse() - reverses the list
            - [ ] remove_value(value) - removes the first item in the list with this value
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
            - [X] [Linked List Cycle](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1212/)
            - [X] [Linked List Cycle II](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1214/)
            - [X] [Intersection of Two Linked Lists](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1215/)
            - [X] [Remove Nth Node From End of List](https://leetcode.com/explore/learn/card/linked-list/214/two-pointer-technique/1296/)

    - ### Classic Linked List Problems
        * reverse linked list
            * 2 different ways from leetcode
            - [] [Reverse Linked List](https://leetcode.com/explore/learn/card/linked-list/219/classic-problems/1205/)