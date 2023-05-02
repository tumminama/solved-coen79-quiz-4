Download Link: https://assignmentchef.com/product/solved-coen79-quiz-4
<br>
<ol>

 <li>Write the <em>pseudo-code</em> of an algorithm which evaluates a <em>fully parenthesized mathematical expression</em> using <em>stack</em> data structure. (calculator).</li>

</ol>




















































<ol start="2">

 <li>For the queue class given in Appendix 1 (cf. end of this assignment), implement the <em>copy constructor</em>.</li>

</ol>

Note that the class uses a dynamic array. Also please note that you should not use the copy function (copy only the <em>valid entries</em> of one array to the new array).







<ol>

 <li>template &lt;<strong>class</strong> Item&gt;</li>

 <li>queue&lt;Item&gt;::queue (<strong>const</strong> queue &lt;Item&gt;&amp; source)</li>

</ol>




<ol start="3">

 <li>queue class given in Appendix 1 (cf. end of this assignment), implement the following function, which increases the size of the dynamic array used to store items. Please note that you should not use the copy function (copy only the valid entries of one array to the new array).</li>

</ol>

























<ol start="4">

 <li>deque class given in Appendix 2 (cf. end of this assignment), implement the following constructor. The constructor allocates an array of block pointers and initializes all of its entries with NULL. The initial size of the array is init_bp_array_size.</li>

</ol>




<ol>

 <li>template &lt; <strong>class</strong> Item &gt;</li>

 <li>deque&lt;Item&gt;::deque( <strong>int</strong> init_bp_array_size, <strong>int</strong> init_block_size )</li>

 <li>{</li>

 <li>bp_array_size = init_bp_array_size;</li>

 <li>block_size = init_block_size;</li>

</ol>




<ol start="5">

 <li>deque class given in Appendix 2 (cf. end of this assignment), write the full implementation of the following function.</li>

</ol>







<ol>

 <li>template &lt;<strong>class</strong> Item&gt;</li>

 <li><strong>void</strong> deque &lt;Item&gt;::pop_front()</li>

 <li>// Precondition: There is at least one entry in the deque</li>

 <li>// Postcondition: Removes an item from the front of the deque</li>

 <li>{</li>

 <li>assert(!isEmpty());</li>

</ol>




<ol start="6">

 <li>What are the outputs of the following programs?</li>

</ol>







<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>




<table width="653">

 <tbody>

  <tr>

   <td width="653">1.  #include &lt; iostream &gt;2.  using namespace std;3.</td>

  </tr>

  <tr>

   <td width="653">4. <strong>class</strong> Base {</td>

  </tr>

  <tr>

   <td width="653">5.            <strong>private</strong>:6.            <strong>int</strong> i, j;</td>

  </tr>

  <tr>

   <td width="653">7.            <strong>public</strong>:8.            Base (<strong>int</strong> _i = 0, <strong>int</strong> _j = 0): i(_i), j(_j) {}</td>

  </tr>

  <tr>

   <td width="653">9. };   10.</td>

  </tr>

  <tr>

   <td width="653">11. <strong>class</strong> Derived: <strong>public</strong> Base {</td>

  </tr>

  <tr>

   <td width="653">12.           <strong>public</strong>:13.           <strong>void</strong> show() { cout &lt;&lt; ” i = ” &lt;&lt; i &lt;&lt; ”  j = ” &lt;&lt; j;   }</td>

  </tr>

  <tr>

   <td width="653">14. };   15.</td>

  </tr>

  <tr>

   <td width="653">16. <strong>int</strong> main(<strong>void</strong>) {</td>

  </tr>

  <tr>

   <td width="653">17.     Derived d;</td>

  </tr>

  <tr>

   <td width="653">18.     d.show();</td>

  </tr>

  <tr>

   <td width="653">19.     <strong>return</strong> 0;</td>

  </tr>

  <tr>

   <td width="653">20. }</td>

  </tr>

 </tbody>

</table>







<table width="653">

 <tbody>

  <tr>

   <td width="653">1.       #include &lt; iostream &gt;2.       using namespace std;   3.</td>

  </tr>

  <tr>

   <td width="653">4. <strong>class</strong> P {</td>

  </tr>

  <tr>

   <td width="653">5.            <strong>public</strong>:6.            <strong>void</strong> print()  {</td>

  </tr>

  <tr>

   <td width="653">7.         cout &lt;&lt; ” Inside P”;</td>

  </tr>

  <tr>

   <td width="653">8.     }</td>

  </tr>

  <tr>

   <td width="653">9. };     10.</td>

  </tr>

  <tr>

   <td width="653">11. <strong>class</strong> Q: <strong>public</strong> P {</td>

  </tr>

  <tr>

   <td width="653">12.           <strong>public</strong>:13.           <strong>void</strong> print() {</td>

  </tr>

  <tr>

   <td width="653">14.         cout &lt;&lt; ” Inside Q”;</td>

  </tr>

  <tr>

   <td width="653">15.     }</td>

  </tr>

  <tr>

   <td width="653">16. };     17.</td>

  </tr>

  <tr>

   <td width="653">18. <strong>class</strong> R: <strong>public</strong> Q {};     19.</td>

  </tr>

  <tr>

   <td width="653">20. <strong>int</strong> main(<strong>void</strong>) {</td>

  </tr>

  <tr>

   <td width="653">21.     R r;</td>

  </tr>

  <tr>

   <td width="653">22.     r.print();</td>

  </tr>

  <tr>

   <td width="653">23.     <strong>return</strong> 0;</td>

  </tr>

  <tr>

   <td width="653">24. }</td>

  </tr>

 </tbody>

</table>






















<table width="653">

 <tbody>

  <tr>

   <td width="653">1.       #include &lt; iostream &gt;2.       using namespace std;    3.</td>

  </tr>

  <tr>

   <td width="653">4. <strong>class</strong> Base {};    5.</td>

  </tr>

  <tr>

   <td width="653">6. <strong>class</strong> Derived: <strong>public</strong> Base {};    7.</td>

  </tr>

  <tr>

   <td width="653">8. <strong>int</strong> main() {</td>

  </tr>

  <tr>

   <td width="653">9.     Base * bp = <strong>new</strong> Derived;</td>

  </tr>

  <tr>

   <td width="653">10.     Derived * dp = <strong>new</strong> Base;</td>

  </tr>

  <tr>

   <td width="653">11. }</td>

  </tr>

 </tbody>

</table>

























<strong>Appendix 1: </strong>queue class declaration:




<ol>

 <li>template &lt; <strong>class</strong> Item &gt;</li>

</ol>













<strong>Appendix 2: </strong>deque class declaration:




<ol>

 <li>template &lt; <strong>class</strong> Item &gt; 2. <strong>class</strong> deque {</li>

 <li><strong>public</strong>:</li>

 <li>// TYPEDEF</li>

 <li><strong>static</strong> <strong>const</strong> size_t BLOCK_SIZE = 5; // Number of data items per block</li>

 <li>// Number of entries in the block of array pointers. The minimum acceptable value is 2 8. <strong>static</strong> <strong>const</strong> size_t BLOCKPOINTER_ARRAY_SIZE = 5;  9.</li>

 <li>typedef std::size_t size_type;  11.     typedef Item value_type;</li>

 <li></li>

 <li>deque(<strong>int</strong> init_bp_array_size = BLOCKPOINTER_ARRAY_SIZE,</li>

 <li><strong>int</strong> initi_block_size = BLOCK_SIZE);</li>

 <li></li>

 <li>deque(<strong>const</strong> deque &amp; source);  17.     ~deque();</li>

 <li></li>

 <li>// CONST MEMBER FUNCTIONS</li>

 <li>bool isEmpty();</li>

 <li>value_type front();       value_type back();</li>

 <li></li>

 <li>// MODIFICATION MEMBER FUNCTIONS</li>

 <li><strong>void</strong> operator = (<strong>const</strong> deque &amp; source);</li>

 <li><strong>void</strong> clear();</li>

 <li><strong>void</strong> reserve();</li>

 <li><strong>void</strong> push_front(<strong>const</strong> value_type &amp; data);</li>

 <li><strong>void</strong> push_back(<strong>const</strong> value_type &amp; data);</li>

 <li><strong>void</strong> pop_back();       <strong>void</strong> pop_front();</li>

 <li></li>

 <li><strong>private</strong>:</li>

 <li>// A pointer to the dynamic array of block pointers     value_type** block_pointers;</li>

 <li></li>

 <li>// A pointer to the final entry in the array of block pointers  38.     value_type** block_pointers_end;</li>

 <li></li>

 <li>// A pointer to the first block pointer that’s now being used  41.     value_type** first_bp;</li>

 <li></li>

 <li>// A pointer to the last block pointer that’s now being used  44.     value_type** last_bp;</li>

 <li></li>

 <li>value_type* front_ptr; // A pointer to the front element of the whole deque  47.     value_type* back_ptr; // A pointer to the back element of the whole deque</li>

 <li></li>

 <li>size_type bp_array_size; // Number of entries in the array of block pointers  50.     size_type block_size; // Number of entries in each block of items</li>

 <li>};</li>

</ol>


