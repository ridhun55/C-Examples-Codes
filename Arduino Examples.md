
# Arduino Examples Documentation
# RIDHUN DEV

Arduino Examples Codes Run In Arduino IDE </br>
Download Arduino IDE Software : https://www.arduino.cc/en/software

# Example 1 : Hello World (Serial monitor)
Print "Hello World" on Serial monitor

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(67, 79, 84);"><span class="hljs-keyword" style="color: rgb(0, 151, 157);">void</span> <span class="hljs-built_in" style="color: rgb(211, 84, 0);">setup</span>() {
  <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">begin</span>(<span class="hljs-number" style="color: rgb(138, 123, 82);">9600</span>);
}

<span class="hljs-keyword" style="color: rgb(0, 151, 157);">void</span> <span class="hljs-built_in" style="color: rgb(211, 84, 0);">loop</span>() {
  <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">println</span>(<span class="hljs-string" style="color: rgb(0, 92, 95);">"hello world"</span>);
}</pre>

# Example 2 : Read data from Serial monitor
<h3> Methord 1 : Read data from Serial monitor & Print on Serial monitor (char)</h3>

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(67, 79, 84);"><span class="hljs-keyword" style="color: rgb(0, 151, 157);">void</span> <span class="hljs-built_in" style="color: rgb(211, 84, 0);">setup</span>() {
  <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">begin</span>(<span class="hljs-number" style="color: rgb(138, 123, 82);">9600</span>);
}

<span class="hljs-keyword" style="color: rgb(0, 151, 157);">void</span> <span class="hljs-built_in" style="color: rgb(211, 84, 0);">loop</span>() {
  <span class="hljs-built_in" style="color: rgb(211, 84, 0);">while</span>( <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">available</span>())  
  {  
   <span class="hljs-keyword" style="color: rgb(0, 151, 157);">char</span> data = <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">read</span>();
   <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">println</span>(data);
  }
}</pre


<h3> Methord 2 : Read data from Serial monitor & Print on Serial monitor (string) </h3>


<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(255, 255, 255) none repeat scroll 0% 0%; color: rgb(67, 79, 84);"><span class="hljs-keyword" style="color: rgb(0, 151, 157);">void</span> <span class="hljs-built_in" style="color: rgb(211, 84, 0);">setup</span>()
{
  <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">begin</span>(<span class="hljs-number" style="color: rgb(138, 123, 82);">9600</span>);
}
<span class="hljs-keyword" style="color: rgb(0, 151, 157);">void</span> <span class="hljs-built_in" style="color: rgb(211, 84, 0);">loop</span>()
{
  <span class="hljs-built_in" style="color: rgb(211, 84, 0);">while</span> ( <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">available</span>())
  {
    <span class="hljs-keyword" style="color: rgb(0, 151, 157);">String</span> data = <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">readString</span>();
    <span class="hljs-built_in" style="color: rgb(211, 84, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(211, 84, 0);">println</span>(data);
  }
}</pre>
