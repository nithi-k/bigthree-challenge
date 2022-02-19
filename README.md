<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="BigThree_0"></a>BigThree</h1>
<p class="has-line-data" data-line-start="1" data-line-end="3">A non-empty zero-indexed array T consisting of N integers is given.<br>
The product of triplet (A, B, C) equates T[A] x T[B] x T[C] (0 ≤ A &lt; B &lt; C &lt; N)</p>
<p class="has-line-data" data-line-start="4" data-line-end="11">For example, array T such that:<br>
T[0] = -6<br>
T[1] = 2<br>
T[2] = 4<br>
T[3] = -5<br>
T[4] = 10<br>
T[5] = 12</p>
<p class="has-line-data" data-line-start="12" data-line-end="13">The maximal product of the triplet is  (2,4,5) value is 4 * 10 * 12 = 480</p>
<p class="has-line-data" data-line-start="14" data-line-end="16"><strong>Your goal is to write a function to find the maximal product of any triplet.</strong><br>
From the example above the function should return 480</p>
<p class="has-line-data" data-line-start="17" data-line-end="20"><strong>Assumption</strong><br>
N is an integer within the range [3…100,000]<br>
each element of array T is an integer within the range [−1,000…1,000]</p>
<p class="has-line-data" data-line-start="21" data-line-end="23"><strong>Complexity</strong><br>
expected worst-case time complexity is O(N*log(N));</p>
