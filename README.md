Download Link: https://assignmentchef.com/product/solved-ch231a-assignment3-asymptotic-analysis
<br>
Considering the following pairs of functions <em>f </em>and <em>g</em>, show for each pair whether or not it belongs to each of the relations <em>f </em>∈ Θ(<em>g</em>), <em>f </em>∈ <em>O</em>(<em>g</em>), <em>f </em>∈ <em>o</em>(<em>g</em>), <em>f </em>∈ Ω(<em>g</em>), <em>f </em>∈ <em>ω</em>(<em>g</em>), <em>g </em>∈ Θ(<em>f</em>), <em>g </em>∈ <em>O</em>(<em>f</em>), <em>g</em>∈<em>o</em>(<em>f</em>), <em>g</em>∈ Ω(<em>f</em>), or <em>g</em>∈<em>ω</em>(<em>f</em>).

<ul>

 <li>(2 points) <em>f</em>(<em>n</em>) = 9<em>n </em>and <em>g</em>(<em>n</em>) = 5<em>n</em><sup>3</sup>,</li>

</ul>

√

<ul>

 <li>(2 points) <em>f</em>(<em>n</em>) = 9<em>n</em><sup>0<em>.</em>8 </sup>+ 2<em>n</em><sup>0<em>.</em>3 </sup>+ 14log<em>n </em>and <em>g</em>(<em>n</em>) = <em>n</em>,</li>

 <li>(2 points) <em>f</em>(<em>n</em>) = <em>n</em><sup>2</sup><em>/</em>log<em>n </em>and <em>g</em>(<em>n</em>) = <em>n</em>log<em>n</em>,</li>

 <li>(2 points) <em>f</em>(<em>n</em>) = (log(3<em>n</em>))<sup>3 </sup>and <em>g</em>(<em>n</em>) = 9log<em>n</em>.</li>

 <li><strong style="font-size: 2em;">Problem 3.2 </strong><span style="font-size: 2em;">Selection Sort                                                                          </span></li>

</ul>

Insertion Sort was discussed during the lecture. Selection Sort is similar to Insertion Sort and works as follows. Given an array of elements, you always take the current element and exchange it with the smallest element that can be found on the right hand side of the current element. In doing so, you will gradually build up a sorted sequence on the left side (like in Insertion Sort), and in each iteration ”attach” the smallest element from the remaining unsorted right side to it.

<ul>

 <li>(2 points) Implement Selection Sort.</li>

 <li>(3 points) Show that Selection Sort is correct (Hint: consider the loop invariant).</li>

 <li>(3 points) Generate random input sequences of length <em>n </em>as well as sequences of length <em>n </em>that represent <strong>Case </strong><em>A </em>and <strong>Case </strong><em>B </em>for the Selection Sort algorithm. <strong>Case </strong><em>A</em>: the case which involves the most swaps (Hint: it is not a decreasingly ordered array). <strong>Case </strong><em>B</em>: the case with the least swaps. Briefly describe how you generated the sequences (e.g., with a random sequence generator using your chosen language).</li>

 <li>(4 points) Run the algorithm on the sequences from (c) with length <em>n </em>for increasing values of <em>n </em>and measure the computation times. Plot curves that show the computation time of the algorithm in <strong>Case </strong><em>A</em>, <strong>Case </strong><em>B</em>, and <strong>average case </strong>for an increasing input length <em>n</em>. Note that in order to compute reliable measurements for the <strong>average case</strong>, you have to run the algorithm multiple times for each entry in your plot. You can use a plotting tool/software of your choice (Gnuplot, R, Matlab, Excel, etc.).</li>

</ul>

(1 point) Interpret the plots from (d) with respect to asymptotic behavior and constants