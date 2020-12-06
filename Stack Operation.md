# Stack Operation C++ Example 

1. PUSH
2. POP
3. Display

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">stack</span>[<span class="hljs-number" style="color: rgb(136, 0, 0);">20</span>],top=<span class="hljs-number" style="color: rgb(136, 0, 0);">-1</span>; <span class="hljs-comment" style="color: rgb(136, 136, 136);">//global declaration</span>

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">push</span><span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">if</span>(top&gt;<span class="hljs-number" style="color: rgb(136, 0, 0);">9</span>)
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nStack Overflow"</span>;
  <span class="hljs-keyword" style="font-weight: 700;">else</span>
  {   top=top+<span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnter a value : "</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">stack</span>[top];
  }
}

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">pop</span><span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">if</span>(top==<span class="hljs-number" style="color: rgb(136, 0, 0);">-1</span>)
   <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n [ Stack Overflow. ] No Elements to pop\n\n"</span>;
  <span class="hljs-keyword" style="font-weight: 700;">else</span>
  {
  	  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n\n"</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">stack</span>[top]&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" is deleted..\n\n"</span>;
      top--;
  }
}

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">display</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">int</span> i;
    <span class="hljs-keyword" style="font-weight: 700;">if</span>(top==<span class="hljs-number" style="color: rgb(136, 0, 0);">-1</span>)
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n [ Stack underflow. ] No elements to display..\n\n"</span>;
    <span class="hljs-keyword" style="font-weight: 700;">else</span>
    {
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nThe stack elements are : "</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;i&lt;=top;i++)
    {
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\t"</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">stack</span>[i];
    }
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n"</span>;

    }
}


<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{ 
  <span class="hljs-keyword" style="font-weight: 700;">int</span> ch;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Program for Stack Operations\n\n"</span>;
  <span class="hljs-keyword" style="font-weight: 700;">do</span>
  {   <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n1.Push"</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n2.Pop"</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n3.Display"</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n4.Exit"</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnter your choice : "</span>;
      <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;ch;
      <span class="hljs-keyword" style="font-weight: 700;">if</span>(ch==<span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>)
    push();
      <span class="hljs-keyword" style="font-weight: 700;">else</span> <span class="hljs-keyword" style="font-weight: 700;">if</span>(ch==<span class="hljs-number" style="color: rgb(136, 0, 0);">2</span>)
    pop();
      <span class="hljs-keyword" style="font-weight: 700;">else</span> <span class="hljs-keyword" style="font-weight: 700;">if</span>(ch==<span class="hljs-number" style="color: rgb(136, 0, 0);">3</span>)
    display();
      <span class="hljs-keyword" style="font-weight: 700;">else</span> <span class="hljs-keyword" style="font-weight: 700;">if</span>(ch==<span class="hljs-number" style="color: rgb(136, 0, 0);">4</span>)
       <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnd Of program"</span>;
  }<span class="hljs-keyword" style="font-weight: 700;">while</span>(ch!=<span class="hljs-number" style="color: rgb(136, 0, 0);">4</span>);
}
</pre>
