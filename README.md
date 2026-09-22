Homework-2
Name: Aiden Krasnopolskiy
Language: Java
IDE: VS Code

This is answer to all the questions from the homework.

1. What is the worst-case Big O time complexity of Bubble Sort?
O(n²)

2. Why does Bubble Sort have this time complexity?
Bubble sort has this time complexity because it uses nested loops. It repeatedly compares nearby elements and may swap them. As the number of elements increase, the more comparisons it needs to do as it repeatedly passes through the same array potentially swapping elements.

3. If Bubble Sort processes 10 elements, approximately how many comparisons could be required compared with 1,000 elements?
For 10 elements, the algorithm needs to do approximately 100 comparison, but for 1000 elements, it would take 1000000 comparisons. This is because since the time complexity of bubble sort is 0(n²), the number of operations grows approximately with the square of the number of elements.

4. What is the Big O time complexity of Merge Sort?
O(n log n)

5. Which algorithm generally performs better when the amount of data becomes very large?
Merge Sort generally performs better when the amount of data becomes very large because it has O(n log n) time complexity, while Bubble Sort has O(n²). As the amount of data increases, O(n log n) grows much slower than O(n²).

6.
Bubble Sort = O(n²)

Merge Sort = O(n log n)

7. What is the Big O time complexity of Linear Search?
O(n)

8. What is the Big O time complexity of Binary Search?
O(log n)

9. Why does Binary Search require sorted data?
Binary search requires sorted data because the algorithm decides which side to search based on the value of the middle index. If the value is larger than the middle value, then it only searches right of the middle value and if its less than the middle value, it searches left. It does this on repeat until it finds the value or until it can't and returns the index as -1.

10. Which search would you use if the data were not sorted?
If the data isn't sorted, I would use the linear search because it doesn't require the data to be sorted and would just go through the elements one by one until it finds it.

11. Which search would generally be better for a very large sorted array?
For a large sorted array, binary search is generally better because the time complexity of binary search O(log n) grows slower than linear search O(n). Binary search eliminates half the data for each comparison, while linear only eliminates one, so for a large sorted array, binary search is a lot better.

12. 
Algorithm        Purpose	    Big O
Bubble Sort	     Sorting	    O(n²)
Merge Sort	     Sorting	    O(n log n)
Linear Search	   Searching	  O(n)
Binary Search	   Searching	  O(log n)
