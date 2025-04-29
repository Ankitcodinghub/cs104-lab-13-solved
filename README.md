# cs104-lab-13-solved
**TO GET THIS SOLUTION VISIT:** [CS104 Lab 13 Solved](https://www.ankitcodinghub.com/product/cs-104-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109350&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS104 Lab 13 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1. In Bubble sort, you repeatedly swap the adjacent elements that are not in correct order until there are no possible swaps. (if there are no possible swaps, it means that the list is sorted.) Create a random array of size 10 and fill it with integers between 1-100.

Write a method called bubbleSort to sort the array you have created. Call the method and print your array after the method call to check whether you have successfully sorted the array.

2. Counting sort is a sorting technique that can be applied to an array holding integers from a certain range. Suppose that you are given an array of 10 integers and those integers are from the range 0-9. Instead of sorting those numbers directly, you count the frequency of each number and create a frequency array. Then you should use the frequency array to print the numbers in ascending order.

Input array: {1, 4, 1, 2, 7, 5, 2, 3, 9, 8}

Frequency array: {0, 2, 2, 1, 1, 1, 0, 1, 1, 1}

Then looking at the frequencies in frequency array, you should print the numbers in the original array in ascending order. Two 1’s: Print 1 1

Two 2’s: Print 2 2

One 3: Print 3 One 4: Print 4

…

1 1 2 2 3 4 …

Write a method called printSorted which takes an integer array and range where range is the range of the numbers inside the array. Your method should print the numbers inside the array in ascending order.

3. Implement recursive and iterative binary search methods.

4. Implement recursive version of insertion sort. Remember its definition from the lectures. Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part. To sort an array of size n in ascending order:

1: Iterate from arr[1] to arr[n] over the array.

2: Compare the current element (key) to its predecessor.

3: If the key element is smaller than its predecessor, compare it to the elements before. Move the greater elements one position up to make space for the swapped element.

Recursion idea:

1: Base Case: If array size is 1 or smaller, return.

2: Recursively sort first n-1 elements.

3: Insert last element at its correct position in sorted array.

5. Write a Python program to sort a list of elements using Bogosort. We will implement its randomized version. See details below.
