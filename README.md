# big-o-notation

Analysis of algorithms is the most important step for software development. A well-written algorithm is not only time-efficient 
but also space-efficient. The complexity of algorithms is measured using asymptotic notations. Using these notations, we can 
determine if an algorithm performs better than the other one. Coding interviews often include questions regarding complexity 
analysis of algorithms, or they might ask you to implement the most efficient algorithms. To answer such questions you 
should be able to calculate the complexity of any algorithm.

General Tips#

- Every time a list or array gets iterated over c×length times, it is most likely in O(n) time.
- When you see a problem where the number of elements in the problem space gets halved each time, 
  it will most probably be in O(log n) runtime.
- Whenever you have a single nested loop, the problem is most likely in quadratic time.