# C++ Examples Codes
# RIDHUN DEV

C++ Examples Codes Run In Dav C++ IDE
Download Dev C++ Software : https://sourceforge.net/projects/orwelldevcpp/

# Example 1 : Hello World 

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span><span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"Hello World!"</span>;
}</pre>

# Example 2 : Input / Output Functions

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span><span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> x;
	
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"Enter a number"</span>;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cin</span>&gt;&gt; x ;
	
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x = "</span> &lt;&lt; x ;
}</pre>

# Example 3 : Datatypes  declaration (print error values)

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span><span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">char</span> p ;
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> q ;
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">float</span> r ;
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">double</span> s ;
	
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"p = "</span> &lt;&lt; p ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"q = "</span> &lt;&lt; q ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"r = "</span> &lt;&lt; r ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"s = "</span> &lt;&lt; s ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;

}</pre>

# Example 4 : Datatypes  declaration & initialization 

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span><span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">char</span> p =<span class="hljs-string" style="color: rgb(196, 26, 22);">'x'</span> ;
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> q = <span class="hljs-number" style="color: rgb(28, 0, 207);">10</span> ;
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">float</span> r = <span class="hljs-number" style="color: rgb(28, 0, 207);">3.14</span>;
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">double</span> s = <span class="hljs-number" style="color: rgb(28, 0, 207);">10030.556</span> ;
	
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"p = "</span> &lt;&lt; p ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"q = "</span> &lt;&lt; q ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"r = "</span> &lt;&lt; r ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"s = "</span> &lt;&lt; s ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;

}</pre>

# Example 5 : Arithmetic operators

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span><span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> x = <span class="hljs-number" style="color: rgb(28, 0, 207);">10</span> ;
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> y = <span class="hljs-number" style="color: rgb(28, 0, 207);">5</span> ;
	
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x + y = "</span> &lt;&lt; x + y ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x - y = "</span> &lt;&lt; x - y ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x * y = "</span> &lt;&lt; x * y ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x / y = "</span> &lt;&lt; x / y ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x % y = "</span> &lt;&lt; x % y ;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;

}</pre>

# Example 6 : Assignment operators

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span><span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> x = <span class="hljs-number" style="color: rgb(28, 0, 207);">10</span> ;
	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> y = <span class="hljs-number" style="color: rgb(28, 0, 207);">5</span> ;
	
	x = y ;	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x = "</span> &lt;&lt; x;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	
	x += y ;	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x = "</span> &lt;&lt; x;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	x -= y ;	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x = "</span> &lt;&lt; x;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	x /= y ;	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x = "</span> &lt;&lt; x;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	x *= y ;	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x = "</span> &lt;&lt; x;  	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span> ;
	
}</pre>

# Example 7 : Logical operators

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">bool</span> x = <span class="hljs-literal" style="color: rgb(170, 13, 145);">true</span>;
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">bool</span> y = <span class="hljs-literal" style="color: rgb(170, 13, 145);">false</span>;
   
   <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x &amp;&amp; y = "</span>;    <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; (x &amp;&amp; y)	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(92, 38, 153);">endl</span>;
   <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x || y = "</span>;    <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; (x || y)	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(92, 38, 153);">endl</span>;
   <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"!x = "</span>;        <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; !(x);

}</pre>



# Controll Satements ( Decision Making Statements )

# Example 8 : If Statements

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> x = <span class="hljs-number" style="color: rgb(28, 0, 207);">5</span>;
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> y = <span class="hljs-number" style="color: rgb(28, 0, 207);">5</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> data = <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> (x == y) 
   {
      <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x and y are equal"</span>;
   }
   
   <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> (x == y) 
   {
     data = x + y;
     <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; data;
   }

}</pre>

# Example 9 : If else Statements

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> x = <span class="hljs-number" style="color: rgb(28, 0, 207);">5</span>;
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> y = <span class="hljs-number" style="color: rgb(28, 0, 207);">6</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> data = <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> (x == y) 
   {
      <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x and y are equal"</span>;
   }
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">else</span>
   {
   		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x and y are not equal"</span>;
   }
   
   <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> (x == y) 
   {
     data = x + y;
   }
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">else</span> 
   {
   	data = <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span>;
   }

<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; data;
}</pre>

# Example 10 : Else if ladder 

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> x = <span class="hljs-number" style="color: rgb(28, 0, 207);">10</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> (x == <span class="hljs-number" style="color: rgb(28, 0, 207);">1</span>) 
   {
      <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"ONE"</span>;
   }
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">else</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> (x == <span class="hljs-number" style="color: rgb(28, 0, 207);">2</span>) 
   {
   		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"TWO"</span>;
   }
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">else</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> (x == <span class="hljs-number" style="color: rgb(28, 0, 207);">3</span>) 
   {
   		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"THREE"</span>;
   }
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">else</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> (x == <span class="hljs-number" style="color: rgb(28, 0, 207);">4</span>) 
   {
   		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"FOUR"</span>;
   }
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">else</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> (x == <span class="hljs-number" style="color: rgb(28, 0, 207);">5</span>) 
   {
   		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"FIVE"</span>;
   }
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">else</span>
   {
   		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"Invalid"</span>;
   }
}</pre>

# Example 11 : Switch Statement 

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> x = <span class="hljs-number" style="color: rgb(28, 0, 207);">5</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">switch</span>(x)
   {
   	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">case</span> <span class="hljs-number" style="color: rgb(28, 0, 207);">1</span> : <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"ONE"</span>; 	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">break</span>;
   	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">case</span> <span class="hljs-number" style="color: rgb(28, 0, 207);">2</span> : <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"TWO"</span>; 	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">break</span>;
   	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">case</span> <span class="hljs-number" style="color: rgb(28, 0, 207);">3</span> : <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"THREE"</span>; <span class="hljs-keyword" style="color: rgb(170, 13, 145);">break</span>;
   	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">case</span> <span class="hljs-number" style="color: rgb(28, 0, 207);">4</span> : <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"FOUR"</span>; 	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">break</span>;
   	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">case</span> <span class="hljs-number" style="color: rgb(28, 0, 207);">5</span> : <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"FIVE"</span>; 	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">break</span>;
   	<span class="hljs-keyword" style="color: rgb(170, 13, 145);">default</span> : <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"INVALID"</span>; 
   }
}</pre>

# Example 12 : Nested If Satament 

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> x = <span class="hljs-number" style="color: rgb(28, 0, 207);">4</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> ( x &gt; <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span> )
   {
   		<span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span> ( x != <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span> )
   		{
   			<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"x is +ve number"</span>;
		}
   }

}</pre>


# Controll Satements ( Looping Statements )

# Example 13 : while loop

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> i = <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span>;
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">while</span> ( i &lt; <span class="hljs-number" style="color: rgb(28, 0, 207);">10</span> )
   {
   		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; i ;    <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span>;
   		i = i + <span class="hljs-number" style="color: rgb(28, 0, 207);">1</span>;
   }

}</pre>

# Example 14 : For loop

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">for</span>( <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> i = <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span>; i &lt; <span class="hljs-number" style="color: rgb(28, 0, 207);">10</span>; i++ )
   {
   		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; i ;    <span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span>;
   }

}</pre>

# Example 15 : Do While loop

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> i = <span class="hljs-number" style="color: rgb(28, 0, 207);">5</span>;
   
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">do</span>
   {
   		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; i ;		<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span>;
   		i = i + <span class="hljs-number" style="color: rgb(28, 0, 207);">1</span>;
   		
   }<span class="hljs-keyword" style="color: rgb(170, 13, 145);">while</span> ( i &lt;= <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span> );

}</pre>

# Controll Satements ( Jump Statements )

# Example 16 : goto

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> i = <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span>;
   
   lable : <span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span>( i &lt; <span class="hljs-number" style="color: rgb(28, 0, 207);">10</span> )
   			{
				<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; i ;	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span>;
				i++ ;  	
   			}
   			<span class="hljs-keyword" style="color: rgb(170, 13, 145);">goto</span> lable;

}</pre>

# Example 17 : break

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">for</span> (<span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> i = <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span>; i &lt; <span class="hljs-number" style="color: rgb(28, 0, 207);">10</span>; i++ )
   {
   	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; i;	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span>;
   	
   		<span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span>( i == <span class="hljs-number" style="color: rgb(28, 0, 207);">3</span> )
   		{
   			<span class="hljs-keyword" style="color: rgb(170, 13, 145);">break</span>;
	   	}
   }

}</pre>

# Example 18 : continue

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(0, 0, 0);"><span class="hljs-meta" style="color: rgb(28, 0, 207);">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="color: rgb(170, 13, 145);">using</span> <span class="hljs-keyword" style="color: rgb(170, 13, 145);">namespace</span> <span class="hljs-built_in" style="color: rgb(92, 38, 153);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> <span class="hljs-title" style="color: rgb(28, 0, 207);">main</span><span class="hljs-params" style="color: rgb(92, 38, 153);">()</span>
</span>{
   
   <span class="hljs-keyword" style="color: rgb(170, 13, 145);">for</span> (<span class="hljs-keyword" style="color: rgb(170, 13, 145);">int</span> i = <span class="hljs-number" style="color: rgb(28, 0, 207);">0</span>; i &lt; <span class="hljs-number" style="color: rgb(28, 0, 207);">10</span>; i++ )
   {
   		<span class="hljs-keyword" style="color: rgb(170, 13, 145);">if</span>( i == <span class="hljs-number" style="color: rgb(28, 0, 207);">3</span> )
   		{
   			<span class="hljs-keyword" style="color: rgb(170, 13, 145);">continue</span>;
	   	}
	
	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt; i;	<span class="hljs-built_in" style="color: rgb(92, 38, 153);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(196, 26, 22);">"\n"</span>;
   }

}</pre>
