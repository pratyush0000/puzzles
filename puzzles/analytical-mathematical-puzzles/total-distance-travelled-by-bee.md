# Total distance travelled by bee

Two trains are on the same track and are approaching each other.

* The speed of the first train is 50 km/h, and the speed of the second train is 70 km/h.
* A bee starts flying between the trains when the distance between the two trains is 100 km.
* The bee first flies from the first train to second train. Once it reaches the second train, it immediately flies back to the first train … and so on until trains collide.
* Speed of the bee is 80 km/h.&#x20;

Calculate the total distance traveled by the bee.



An easy approach to solve this can be by using the concept of relative velocity:

![](https://media.geeksforgeeks.org/wp-content/uploads/20210730120521/gfg2-660x351.png)

With respect to Train A, train B's velocity is (70+50) = 120 km/hr. Thus, the time taken by Train B to collide with Train A will be

```
 (100 km) / (120 km/hr)  = 5/6 hr = 50 min
```

&#x20;Now, since the velocity of the bee is 80 km/hr, the distance travelled by the bee in this time interval will be

```
 80 km/hr * 5/6 hr = 66.67 km (approx)
```
