# Sorting

## **THEORY**

A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.

![image](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/029a073c-9f3a-4d3b-8cb2-573f927a729b)

- **Selection Sort**

In selection sorting technique, the smallest element is fetched by comparing itself with the rest of the elements and sorted at the array's first position. The complete array is divided into two halves, the sorted subarray on the left and the unsorted subarray on the right. Once the first element is sorted, the search for the second minimum element begins from the rest of the array and is positioned at second place.

![image](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/37f41260-a272-4616-8e96-a39223730def)
![image](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/6adb5793-3f31-44e8-a317-c2d92bd5f56d)

Similarly, all the elements are positioned on the sorted side of the subarray one after the other, and the complete array becomes a sorted array.

- **Insertion Sort**

In this sorting technique, the elements are sorted by comparing the elements with their previous elements. It starts by comparing the second element with the first element. If the second element is smaller than the first, then we will swap it.

![image](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/4f70a340-1bc8-41e2-99fd-14a8d8e2e82f)

After that, we will compare the third element with all the elements that are before it. Similarly, it goes for the fourth element and so on. Once all the comparisons are made, the elements become sorted. 

- **Bubble Sort**

Bubble sort is one of the most straightforward sorting algorithms. In this sorting technique, we begin by comparing the first two elements of the array and checking if the first element is greater than the second element; if it is, we will swap those elements and move forward to the next element. 

![image](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/69881323-4509-4959-bdc7-0afedb21a639)



If the first element is not greater than the second, then we don’t need to swap it. And this process will keep on repeating till the end of the array.

![image](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/52ac6ac4-03c6-4fdc-83df-e35e963c9b20)

## **ALGORITHM**

Here's the algorithm for the provided C++ program that sorts an array using Selection Sort, Insertion Sort, or Bubble Sort based on user input:

1.Start

2.Declare an integer variable n to store the number of elements in the array.

Output "Enter the number of elements in the array: " to prompt the user for input.

Read the value of n from the user.

3.Declare an integer array arr of size n to store the elements of the array.

Output "Enter n elements of the array: " to prompt the user for the array elements.

Use a loop to read and store the n elements in the arr array.

4.Declare an integer variable choice to store the user's choice of sorting algorithm.

Output "Choose a sorting algorithm:".

Output "1. Selection Sort".

Output "2. Insertion Sort".

Output "3. Bubble Sort".

Output "Enter your choice: " to prompt the user for their choice.

5.Read the value of choice from the user.

6.Use a switch statement to perform the selected sorting algorithm based on the value of choice:

a. If choice is 1, call the selectionSort(arr, n) function to perform Selection Sort.

b. If choice is 2, call the insertionSort(arr, n) function to perform Insertion Sort.

c. If choice is 3, call the bubbleSort(arr, n) function to perform Bubble Sort.

d. If choice is none of the above, output "Invalid choice" and return 1 to exit the program.

Output "Sorted array: " to indicate the sorted array.

7.Use a loop to display the elements of the sorted arr array.

8.End

The program provides the user with a menu to choose a sorting algorithm and then displays the sorted array using the selected sorting technique.

### **OUTPUT**

1. 
![Exp22_1](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/eb5de79e-4cac-4b81-8749-a47226daa84c)

2.
![exp22_2](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/0b85f36e-0942-47a9-8e0d-c728cd43b0ce)

3.
![exp22_3](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/59fe445b-8f40-43ad-ae42-2168ec1b54f0)

4.
![exp22_4](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/ff5b2ec3-afa2-49a8-b962-586a69dbaf16)
![exp22_5](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/9b23413b-f53d-4509-9ac0-44e46a111e45)
![exp22_6](https://github.com/Purvansha022609/Sorting-Algorithm/assets/139473344/0b8be50a-4266-47c0-8b00-8890cb720b64)
