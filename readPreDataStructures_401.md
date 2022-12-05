### 401 Pre-Work - Data Structures & Algorithms

* [Basic Recursion -Video](https://www.youtube.com/watch?v=vPEJSJMg4jY)
  - _use `Ctrl + C` to break and escape an infitely looping function_ 
  - _(to paraphrase) every recursive function should have a base case (in the "if" statement to end the loop) and a recursive case (in the "else" statement which keeps calling itself until the base case applies)

* [Data Structures in 15 Minutes -Video](https://www.youtube.com/watch?v=sVxBVvlnJsM)
  - _`linked list` 1st node is "head", last node is "tail"; "pointers" after every node except the tail; not good at searching or retrieving_

  - _`array` "a continuous block of cells in memory"; great for retrieving but not great for adding; []_
  - _`hash table` good at retrieving and adding; "collisions" (when the hashing function assigns two keys to the same location) make it not ideal in some situations; works via a hashing function that will spit out the info by memory location when fed "keys"_
  - _`stack` last in first out (LIFO); add = "push"; retrieve = "pop"; built on top of arrays; Depths First Search (DFS)_
  - _`queue` first in first out (FIFO); add = "enqueue"; retrieve = "dequeue" (removes from front - like people in a deli line); built on top of arrays_
  - _`graphs & trees` relevant vocab: "edges" and "weights"; graph theory is a subset of computer science all on its own_ 

* [Big O Explained -Video](https://www.youtube.com/watch?v=v4cd1O4zkGw)
  - _"How the runtime scales with respect to input variables."_
  - _only order of magnitude as determined by input variables matters so scalars, duplicates, and lesser orders within a single process are disregarded_
  - _it is recommended to find some example problems online to solve to make sure this calculation is understood properly_

* [Basic Data Structures -Article](https://towardsdatascience.com/8-common-data-structures-every-programmer-must-know-171acf6a1a42)
  - _backs up the previously watched video with more detail_

* [Why Big O -Article](https://triplebyte.com/blog/why-you-should-learn-big-o-and-stop-hacking-your-way-through-algorithms)
  - _provides a less mathematical overview of the Big O concept -I think the two complement each other nicely._

`What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?`

_At this point in my limited but ongoing understanding of data structures I think that knowing how many data points are being manipulated by the software is what will determine the order of magnitude and thereby inform the engineer's decision as to which would be the most efficient data structure to employ for optimal (runtime) performance._

`How can we ensure that we’ll avoid an infinite recursive call stack?`

_Ensuring that the recursive function has a properly implemented base case in the "if" portion of the function should help avoid accidental inclusion of an infinite loop._

`Things I want to know more about`

_Honestly all of it but I think spending more deliberate practice on implementing solutions would be most helpful at this point._
