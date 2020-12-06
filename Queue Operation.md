Queue Operation C++ Example 

1. Insertion
2. Deletion
3. Displaying


<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">queue</span>[<span class="hljs-number" style="color: rgb(136, 0, 0);">100</span>], n = <span class="hljs-number" style="color: rgb(136, 0, 0);">4</span>, front = - <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>, rear = - <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">Insert</span><span class="hljs-params">()</span> </span>{
   <span class="hljs-keyword" style="font-weight: 700;">int</span> val;
   <span class="hljs-keyword" style="font-weight: 700;">if</span> (rear == n - <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>)
   <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n\nQueue Overflow"</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
   <span class="hljs-keyword" style="font-weight: 700;">else</span> {
      <span class="hljs-keyword" style="font-weight: 700;">if</span> (front == - <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>)
      front = <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n\nInsert the element in queue : "</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;val;
      rear++;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">queue</span>[rear] = val;
   }
}

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">Delete</span><span class="hljs-params">()</span> </span>{
   <span class="hljs-keyword" style="font-weight: 700;">if</span> (front == - <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span> || front &gt; rear) {
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n Queue Underflow "</span>;
      <span class="hljs-keyword" style="font-weight: 700;">return</span> ;
   } <span class="hljs-keyword" style="font-weight: 700;">else</span> {
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n\nElement deleted from queue is : "</span>&lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">queue</span>[front] &lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
      front++;;
   }
}

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">Display</span><span class="hljs-params">()</span> </span>{
   <span class="hljs-keyword" style="font-weight: 700;">if</span> (front == - <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>)
   <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n\nQueue is empty"</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
   <span class="hljs-keyword" style="font-weight: 700;">else</span> {
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n\nQueue elements are : "</span>;
      <span class="hljs-keyword" style="font-weight: 700;">for</span> (<span class="hljs-keyword" style="font-weight: 700;">int</span> i = front; i &lt;= rear; i++)
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">queue</span>[i]&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" "</span>;
         <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
   }
}

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> </span>{
   <span class="hljs-keyword" style="font-weight: 700;">int</span> ch;
   
   <span class="hljs-keyword" style="font-weight: 700;">do</span> {
   	  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n\n =========================================="</span>;
   	  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n1) Insert element to queue"</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"2) Delete element from queue"</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
   	  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"3) Display all the elements of queue"</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
   	  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"4) Exit"</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnter your choice : "</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;ch;
      
	  <span class="hljs-keyword" style="font-weight: 700;">switch</span> (ch) 
	  {
         <span class="hljs-keyword" style="font-weight: 700;">case</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>: Insert();        <span class="hljs-keyword" style="font-weight: 700;">break</span>;
         <span class="hljs-keyword" style="font-weight: 700;">case</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">2</span>: Delete();  	  <span class="hljs-keyword" style="font-weight: 700;">break</span>;
         <span class="hljs-keyword" style="font-weight: 700;">case</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">3</span>: Display();       <span class="hljs-keyword" style="font-weight: 700;">break</span>;
         <span class="hljs-keyword" style="font-weight: 700;">case</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">4</span>: <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Exit \n"</span>; <span class="hljs-keyword" style="font-weight: 700;">break</span>;
         <span class="hljs-keyword" style="font-weight: 700;">default</span>: <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Invalid choice \n"</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
      }
   } <span class="hljs-keyword" style="font-weight: 700;">while</span>(ch!=<span class="hljs-number" style="color: rgb(136, 0, 0);">4</span>);
   <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
}</pre>
