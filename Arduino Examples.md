
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

# Example 2 : Read data from Serial monitor & Print on Serial monitor (char)

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">setup</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">begin</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">9600</span>);
}
<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">loop</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">if</span>(<span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">available</span>()&gt;<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>)
  {
    <span class="hljs-keyword" style="font-weight: 700;">char</span> data = <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">read</span>();
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">println</span>(data);
  }
}</pre>

# Example 3 : Read data from Serial monitor & Print on Serial monitor (string)

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">setup</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">begin</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">9600</span>);
}
<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">loop</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">while</span> (<span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">available</span>())
  {
    <span class="hljs-keyword" style="font-weight: 700;">String</span> data = <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">readString</span>();
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">println</span>(data);
  }
}</pre>

Example 4 : Blink LED

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">setup</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pinMode</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">13</span>,<span class="hljs-literal" style="color: rgb(120, 169, 96);">OUTPUT</span>);
}
<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">loop</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">13</span>,<span class="hljs-literal" style="color: rgb(120, 169, 96);">HIGH</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">delay</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">1000</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">13</span>,<span class="hljs-literal" style="color: rgb(120, 169, 96);">LOW</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">delay</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">1000</span>);
}</pre>
