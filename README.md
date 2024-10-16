# Sorting Algorithms

<h1>Sorting Algorithms</h1>

<h2>1. Insertion Sort</h2>
<p>Insertion Sort is a simple sorting algorithm that builds a sorted array one element at a time. It iterates through the list, and for each element, it finds the appropriate position in the sorted part of the list and inserts it there. It is efficient for small data sets and works well with partially sorted arrays.</p>
<h3>Algorithm:</h3>
<ol>
    <li>Start with the second element (index 1) as the key.</li>
    <li>Compare the key with the elements before it.</li>
    <li>If the key is smaller than the compared element, shift the compared element one position up to make space for the key.</li>
    <li>Insert the key into its correct position.</li>
    <li>Repeat steps 2-4 for all elements in the array.</li>
    <li>End.</li>
</ol>
<h3>Time Complexity:</h3>
<p>The average and worst-case time complexity of Insertion Sort is <strong>O(n²)</strong>, where <strong>n</strong> is the number of elements in the array. However, its best-case time complexity is <strong>O(n)</strong> when the array is already sorted.</p>

<h3>Example:</h3>
<pre>
Input: [5, 2, 4, 6, 1, 3]
Output: [1, 2, 3, 4, 5, 6]
</pre>

<h2>2. Bubble Sort</h2>
<p>Bubble Sort is one of the simplest sorting algorithms. It repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process is repeated until no swaps are needed, indicating that the list is sorted. It is known for its simplicity but is inefficient for large lists.</p>
<h3>Algorithm:</h3>
<ol>
    <li>Start at the beginning of the array.</li>
    <li>Compare the first two elements.</li>
    <li>If the first element is greater than the second, swap them.</li>
    <li>Move to the next pair and repeat the process until the end of the array.</li>
    <li>Repeat the entire process for the array until no swaps are needed.</li>
    <li>End.</li>
</ol>
<h3>Time Complexity:</h3>
<p>Bubble Sort has an average and worst-case time complexity of <strong>O(n²)</strong>. Its best case is <strong>O(n)</strong> when the array is already sorted.</p>

<h3>Example:</h3>
<pre>
Input: [64, 34, 25, 12, 22, 11, 90]
Output: [11, 12, 22, 25, 34, 64, 90]
</pre>

<h2>3. Selection Sort</h2>
<p>Selection Sort is a comparison-based sorting algorithm that divides the input list into a sorted and an unsorted region. It repeatedly selects the smallest (or largest) element from the unsorted region and swaps it with the first element of the unsorted region. This method continues until the entire list is sorted. It has a time complexity of O(n²), making it inefficient on large lists.</p>
<h3>Algorithm:</h3>
<ol>
    <li>Divide the array into a sorted and an unsorted region.</li>
    <li>Find the smallest element in the unsorted region.</li>
    <li>Swap it with the first element of the unsorted region.</li>
    <li>Move the boundary between sorted and unsorted regions one position to the right.</li>
    <li>Repeat steps 2-4 until the entire array is sorted.</li>
    <li>End.</li>
</ol>
<h3>Time Complexity:</h3>
<p>Selection Sort has a time complexity of <strong>O(n²)</strong) for all cases (best, average, and worst).</p>

<h3>Example:</h3>
<pre>
Input: [29, 10, 14, 37, 13]
Output: [10, 13, 14, 29, 37]
</pre>

<h2>Conclusion</h2>
<p>While these sorting algorithms are straightforward and easy to implement, they are not suitable for large datasets due to their inefficiencies. For larger datasets, more advanced algorithms like Merge Sort or Quick Sort are typically preferred, as they offer better performance with average time complexities of <strong>O(n log n)</strong>.</p>

</body>
