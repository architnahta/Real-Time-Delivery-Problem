# Real-Time-Delivery-Problem
Delivery Problem and its Solution Using Greedy Algorithm.
Real time delivery problem comes with the problem of cost efficiency. Manually, we can find the shortest path between a maximum of 8-10 locations. But electronic computation is required for more, say for 100 addresses , we have 100! ways to travel all the addresses.

One of the main goals of this project is to improve the performance of our existing TSP algorithm. Generally, the best approach for improving the performance is improvising time to reach any node in computation. The new strategy is to use a greedy method for edge selection, rather than trying all possible path permutations.

---
### Comparison : 
|S No.|	Number of Addresses	|Queue Cost	|This Method’s Cost|
|-------|-----------------|--------|----------|
|1	|1	|0	|0
|2	|10	|13.4867	|12.274157|
|3	|25	|161.116	|102.276726|
|4	|50	|280.677	|124.393112|
|5	|75	|581.483	|284.161163|
|6	|100	|500.201	|124.585869|
|7	|150	|803.706	|372.977966|
|8	|200	|1921.47	|474.072662|

---
### Time Complexity :
The other ways to find the optimal solution are Branch and Bound, Dynamic Programming etc.
Our method has an advantage over them because of its lesser time complexity. That is O(n2)
Since,Finding the minimum cost in from one location to another takes a complexity of O(n).
Finding the minimum cost for locations from n location to another n locations takes O(n*n) unit of time.
Whereas,  **Branch & Bound has a time complexity of O( (n-1)! ).
          Dynamic Programming has a time complexity of O(n2* 2n).**
---
### Concepts Used : 
**Language :**  C/C++
**Functions:** To be called for the different cost calculations and path determination.
**Array:**  Used to store path details and cost matrix.
**Control Flow:** Manipulations of seek positions every time to go to desired position. 

