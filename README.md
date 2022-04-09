# Sorting Algorithms Visualizer

## Application Function: Implemented to visualize various sorting algorithms

<hr/>

### What is an Algorithm?

An algorithm is basically a process of set rules to be followed in calculations or other problem-solving operations. Algorithms define how a work is to be executed upon in order to get the expected result. In this application, it visualizes data being executed via 7 different types of algorithms:

1. Bubble Sort
2. Insertion Sort
3. Merge Sort
4. Quick Sort
5. Heap Sort
6. Counting Sort

<hr/>

### Bubble Sort:

Also known as the `sinking sort`, is a simplified algorithm that runs through the list repeatedly and compares adjacent elements and swaps them if they are out of order. The process of traversing the list is repeated until the list is sorted. The comparison sort algorithm is named after smaller or larger elements "bubble" at the top of the list.

The bubble sort algorithm has a worst-case time complexity of: O(n2). The bubble sort has a space complexity of O(1). The number of swaps in the bubble sort equals the number of inversion pairs in the given array. When the array elements are few and the array is nearly sorted, the bubble sort is effective and efficient.

Bubble sorting is accomplished via recursively comparing adjacent elements and sifting them in ascending or descending order.

<hr/>

### Insertion Sort:

The Insertion Sort algorithm is slightly a better alternative algorithm than to using bubble sort and selection sort for sorting a small data set. The algorithm is mostly used when the list is partially sorted. We assume the 1st element is sorted. Then we check adjacent index for smaller or greater value. If the value is smaller, we insert it in the left side of index[0] which means now smaller value is at index[0] and if it's greater than the original value of index[0] then we get a sorted list of 2 elements. We implement same approach to adjacent elements. Then compare it to previous elements to create a sorted list. So basically - you'll end up with sorted list on the left side of the array and unsorted on the right at one stage. Remember we go back and check if the array is sorted - we do not go forward unless the array behind the concerned element (incl. concerned element) is completely sorted.

<hr/>



<!-- <table>
  <tr>
    <td><img  src="img/ss1.png"></td>
    <td><img  src="img/ss2.png"></td>
    <td><img  src="img/ss3.png"></td>
  </tr>
</table> -->
<p align='center'><img src="img/ss1.png"></p>

## Implemented Algorithms:

* Bubble Sort
* Insertion Sort
* Selection Sort
* Merge Sort
* Quick Sort
* Heap Sort
* Counting Sort

## Built With:
* Python 3.10.4
* Tkinter 8.6.12

<!-- ## Screenshots: -->
<!-- <p align="center"><img height="500" src="img/ss1.png"></p>
<p align="center"><img height="500" src="img/ss2.png"></p>
<p align="center"><img height="500" src="img/ss3.png"></p> -->

## Run It (Python >= 3.10):
- Clone the repository
```bash
$ git clone https://github.com/mandres2/sortingAlgorithm.git
```
- Run ```main.py``` from root
```bash
$ py -3 main.py
```
