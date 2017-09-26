## My Portfolio @ https://oukaire.github.io
#  Compiling GUIDE and underlying Data structure and abstractions
-------------------------------------------------------------------------
Author:         Onyinyechi Ukaire
Date:           September 25, 2016
Course:         Web Programming 
Description:    Here, I implement my course website
-------------------------------------------------------------------------
Purpose: 

        This program is designed to implement three standard sorting 
        algorithms: bubble sort, merge sort and radix sort.
        There three above sorts were chosen for their space and time
        efficiency when compared to other sorts. 
        ----------
        Bubble sort - on average, it has a complexity of O(n^2) because
        for every n elements in the array, it has perform n operations.
        However, it has a worst case space complexity of O(1), which
        is significantly better than any of the other sorts. it only
        uses the exact amount of space required to contain the integers      

Design & Algorithm: contains classes described below

    Struct:

        "QueueContainer"
        - This struct holds ten Queues
        - The Queues are mimics of standard Queues: FIFO data structure
        - Each Queue is used to represent the bins for the radix sort
          algorithm

    Classes:

        "IntVector"
        - IntVector is a replacement for regular arrays, that allows  
          definition of a dynamic array (a growable list)
        - it's abstract data type is represented by a dynamic array 
          with size, capacity, and a pointer ints to the list
        - repetitions are allowed in IntVector.
        - Contains definition for the assignment operator as well as
          '[]' operator, so list can be used like regular arrays

Technical details--

    List of all files associated with this program:
        - ReadMe.md
          unveils hw5's underlying Data stucture & Design, & how to 
          compile also lists classes and describes their underlying 
          data abstraction and algorithm

        - sortnums.cpp
          a simple program that uses "IntVector" class and 
          "QueueContainer" struct to sort any list of numbers

-------------------------------------------------------------------------
    What does not work (use included Makefile): 
          make

    To run:
          ./hw5
-------------------------------------------------------------------------