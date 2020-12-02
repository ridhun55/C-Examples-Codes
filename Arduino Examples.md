
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

# Example 4 : Blink LED

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

# Example 5 : Use of #define 

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">define</span> LED 13</span>

<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">setup</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pinMode</span>(LED,<span class="hljs-literal" style="color: rgb(120, 169, 96);">OUTPUT</span>);
}
<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">loop</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(LED,<span class="hljs-literal" style="color: rgb(120, 169, 96);">HIGH</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">delay</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">1000</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(LED,<span class="hljs-literal" style="color: rgb(120, 169, 96);">LOW</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">delay</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">1000</span>);
}</pre>

# Example 6 : Switch interfaceing

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-keyword" style="font-weight: 700;">int</span> s1 = <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">setup</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pinMode</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">8</span>, <span class="hljs-literal" style="color: rgb(120, 169, 96);">INPUT</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pinMode</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">13</span>, <span class="hljs-literal" style="color: rgb(120, 169, 96);">OUTPUT</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">begin</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">9600</span>);
}
<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">loop</span>()
{
  s1 = <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalRead</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">8</span>);

  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">if</span> (s1 == <span class="hljs-literal" style="color: rgb(120, 169, 96);">LOW</span>)
  {
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">13</span>, <span class="hljs-literal" style="color: rgb(120, 169, 96);">LOW</span>);
  }
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">else</span>
  {
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">13</span>, <span class="hljs-literal" style="color: rgb(120, 169, 96);">HIGH</span>);
  }
}</pre>

# Example 7 : IR Sensor Interfaceing

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-keyword" style="font-weight: 700;">int</span> IR = <span class="hljs-number" style="color: rgb(136, 0, 0);">12</span>;
<span class="hljs-keyword" style="font-weight: 700;">int</span> LED = <span class="hljs-number" style="color: rgb(136, 0, 0);">13</span>;

<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">setup</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pinMode</span> (IR, <span class="hljs-literal" style="color: rgb(120, 169, 96);">INPUT</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pinMode</span> (LED, <span class="hljs-literal" style="color: rgb(120, 169, 96);">OUTPUT</span>);
}

<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">loop</span>()
{
  <span class="hljs-keyword" style="font-weight: 700;">int</span> data = <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalRead</span> (IR);

  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">if</span> (data == <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>)
  {
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(LED, <span class="hljs-literal" style="color: rgb(120, 169, 96);">LOW</span>);
  }
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">else</span>
  {
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(LED, <span class="hljs-literal" style="color: rgb(120, 169, 96);">HIGH</span>);
  }
}
</pre>

# Example 8 : Ultrasonic Sensor Interfaceing

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-keyword" style="font-weight: 700;">int</span> trigPin = <span class="hljs-number" style="color: rgb(136, 0, 0);">9</span>;
<span class="hljs-keyword" style="font-weight: 700;">int</span> echoPin = <span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>;
<span class="hljs-keyword" style="font-weight: 700;">long</span> duration, distance;

<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">setup</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">begin</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">9600</span>);

  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pinMode</span>(trigPin, <span class="hljs-literal" style="color: rgb(120, 169, 96);">OUTPUT</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pinMode</span>(echoPin, <span class="hljs-literal" style="color: rgb(120, 169, 96);">INPUT</span>);
}

<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">loop</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(trigPin, <span class="hljs-literal" style="color: rgb(120, 169, 96);">LOW</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">delayMicroseconds</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">2</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">digitalWrite</span>(trigPin, <span class="hljs-literal" style="color: rgb(120, 169, 96);">HIGH</span>);        
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">delayMicroseconds</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>);
  duration = <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pulseIn</span>(echoPin, <span class="hljs-literal" style="color: rgb(120, 169, 96);">HIGH</span>);  
  distance = duration / <span class="hljs-number" style="color: rgb(136, 0, 0);">58.2</span>;         
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">delay</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">println</span>(distance);

}</pre>

# Example 9 : Bluetooth Module Interfaceing

download any moble terminal for bluetooth communication

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;SoftwareSerial.h&gt;</span></span>
<span class="hljs-built_in" style="color: rgb(57, 115, 0);">SoftwareSerial</span> bt(<span class="hljs-number" style="color: rgb(136, 0, 0);">2</span>, <span class="hljs-number" style="color: rgb(136, 0, 0);">3</span>); <span class="hljs-comment" style="color: rgb(136, 136, 136);">/* (Rx,Tx) */</span>

<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">setup</span>()
{
  bt.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">begin</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">9600</span>);
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">begin</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">9600</span>);
}

<span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">loop</span>()
{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">if</span> (bt.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">available</span>())
  {
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">Serial</span>.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">write</span>(bt.<span class="hljs-built_in" style="color: rgb(57, 115, 0);">read</span>());
  }
}</pre>
