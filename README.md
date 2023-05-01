Download Link: https://assignmentchef.com/product/solved-cecs328-lab4
<br>
<strong>Programming assignment 4. </strong>

Implement a function to find the <strong><em>K </em></strong>elements of a given array that are <u>closet to the median</u>. (<strong><em><u>Hint</u></em></strong>: You could use Quick_Select to find the answer!)

<ol>

 <li>Request the user to enter a positive integer, and call it <strong><em>n</em></strong>.</li>

 <li>Generate <strong><em>n</em></strong> random integers between <em><u>-100</u></em> to <em><u>100</u></em> and save them in <strong><em>a</em></strong>.</li>

 <li>Print the generated array.</li>

 <li>Request the user to enter a number between 1 to n, and call it <strong><em>K</em></strong>.</li>

 <li>Find the median of the array. (<strong><em><u>Hint</u></em></strong><strong><u>:</u></strong> The time complexity in this step is <em>O(n)</em>.)</li>

 <li>Save the differences from the median (a[i]-median) in a new array and call it <strong><em>diff</em></strong>. (<strong><em><u>Question</u></em></strong>: What is the time complexity in this stage?</li>

 <li>Use <strong><em>diff</em></strong> to find the K closest numbers.</li>

</ol>

(<strong><em><u>Hint </u></em></strong><strong><u>Important</u></strong>:

The <strong><em>K</em></strong> closet elements have the K smallest absolute difference from the median.

Could you modify in your <strong>if/while statements</strong> of your partitioning step in your

QuickSelect? Maybe using <u>absolute values</u>? What is the time complexity in this step?) <em> </em>

<ol start="8">

 <li>Shift the found K numbers back to their original value (+median). (<strong><em><u>Question</u></em></strong>: What is the time complexity in this step?)</li>

 <li>Print the answer  <em> </em></li>

 <li>Calculate the total time complexity of your algorithm and present your answer when demoing.</li>

</ol>




<u>Example 1</u>: <u>Input</u>: a = [10, 4, 2, 15, 18], K = 2

<u>Output</u>: 4, 15

<u>Example 2</u>: <u>Input</u>: a = [25, 3, 1, 8, 7, 2, 32], K = 4

<u>Output</u>: 1, 2, 3, 8