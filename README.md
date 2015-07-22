How to use google-code-prettify Github & websites
===

---
## To read this document compare the following:

[SOURCE CODE](https://raw.githubusercontent.com/un5t0ppab13/prettyprint/master/README.md)
to
[RENDERED CODE](https://github.com/un5t0ppab13/prettyprint/blob/master/README.md)

---

### EASIEST: Github has color syntax you can use with markdown (i.e. README.md), 
### The easiest this way is shown below:
    
<pre class="prettyprint lang-html">

  &lt;div id="code-example"&gt;
    &lt;h1&gt;My First Heading&lt;/h1&gt;
    &lt;p&gt;My first paragraph&lt;/p&gt;
  &lt;/div&gt;
  
</pre>

##### Notice you do not need any link or script, it is provided by Github (hint you must be looking at the md for this section):


---

##### AVOID: You can of course attempt to reference link and script tags, but they will not render if not inside the pre tag

<link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/un5t0ppab13/prettyprint/master/monokai_for_google_prettyprint.css">
    
<script src="https://google-code-prettify.googlecode.com/svn/loader/run_prettify.js"></script>

<pre class="prettyprint lang-html">

  &lt;div id="code-example"&gt;
    &lt;h1&gt;My First Heading&lt;/h1&gt;
    &lt;p&gt;My first paragraph&lt;/p&gt;
  &lt;/div&gt;
  
</pre>

---


##### AVOID: Unless you use \&lt; and \&gt; for them as well, but still no color syntax

&lt;link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/un5t0ppab13/prettyprint/master/monokai_for_google_prettyprint.css"&gt;
    
&lt;script src="https://google-code-prettify.googlecode.com/svn/loader/run_prettify.js"&gt;&lt;/script&gt;

<pre class="prettyprint lang-html">

  &lt;div id="code-example"&gt;
    &lt;h1&gt;My First Heading&lt;/h1&gt;
    &lt;p&gt;My first paragraph&lt;/p&gt;
  &lt;/div&gt;
  
</pre>

---

##### OK: If you move them inside the \<pre> tag you can see them too, which makes sense:
<pre class="prettyprint lang-html">

&lt;link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/un5t0ppab13/prettyprint/master/monokai_for_google_prettyprint.css"&gt;
    
&lt;script src="https://google-code-prettify.googlecode.com/svn/loader/run_prettify.js"&gt;&lt;/script&gt;


  &lt;div id="code-example"&gt;
    &lt;h1&gt;My First Heading&lt;/h1&gt;
    &lt;p&gt;My first paragraph&lt;/p&gt;
  &lt;/div&gt;
  
</pre>

---

##### AVOID: And you still need \&lt; or \&gt; or they won't show:

<pre class="prettyprint lang-html">

<link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/un5t0ppab13/prettyprint/master/monokai_for_google_prettyprint.css">
    
<script src="https://google-code-prettify.googlecode.com/svn/loader/run_prettify.js"></script>


  &lt;div id="code-example"&gt;
    &lt;h1&gt;My First Heading&lt;/h1&gt;
    &lt;p&gt;My first paragraph&lt;/p&gt;
  &lt;/div&gt;
  
</pre>


___


### Summation: to show code with color syntax, just use the first example

---


## RENDERING CODE: on Github is easy and useful ( using markdown )
#### Simply don't use any \&lt; or \&gt;

<pre class="prettyprint lang-html">

  <div id="code-example">
    <h1>My First Heading</h1>
    <p>My first paragraph</p>
  </div>
  
</pre>

---

##### AVOID: If you use 4 spaces however you will just see the code without color syntax

    <link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/un5t0ppab13/prettyprint/master/monokai_for_google_prettyprint.css">
    
    <script src="https://google-code-prettify.googlecode.com/svn/loader/run_prettify.js"></script>

    <pre class="prettyprint lang-html">

      <div id="code-example">
        <h1>My First Heading</h1>
        <p>My first paragraph</p>
      </div>
  
    </pre>

---


##### AVOID: If you use 4 spaces on all code including the \<pre>, even with \&lt; AND \&gt; you will just see the code without color syntax:

    <pre class="prettyprint lang-html">

      &lt;div id="code-example"&gt;
        &lt;h1&gt;My First Heading&lt;/h1&gt;
        &lt;p&gt;My first paragraph&lt;/p&gt;
      &lt;/div&gt;
  
    </pre>





##### AVOID: you cannot use \&lt; AND \&gt; on \<pre> tags, if you want to render code with color syntax

    &lt;pre class="prettyprint lang-html"&gt;

      &lt;div id="code-example"&gt;  
        &lt;h1&gt;My First Heading&lt;/h1&gt;
        &lt;p&gt;My first paragraph&lt;/p&gt;    
      &lt;/div&gt;
  
    &lt;/pre&gt;

---


##### AVOID: Notice if you don't use \&lt; instead of < and \&gt; instead of > AND indent all code by 4 spaces you will no longer render the html but, you still will not see code color syntax:

    <link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/un5t0ppab13/prettyprint/master/monokai_for_google_prettyprint.css">
    
    <script src="https://google-code-prettify.googlecode.com/svn/loader/run_prettify.js"></script>

    <pre class="prettyprint lang-html">

        <div id="code-example">
          <h1>My First Heading</h1>
          <p>My first paragraph</p>
        </div>
  
    </pre>

---


##### AVOID: using \&lt; instead of < and \&gt; instead of > for everything is not useful:

&lt;link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/un5t0ppab13/prettyprint/master/monokai_for_google_prettyprint.css"&gt;
    
&lt;script src="https://google-code-prettify.googlecode.com/svn/loader/run_prettify.js"&gt;&lt;/script&gt;

&lt;pre class="prettyprint lang-html"&gt;

  &lt;div id="code-example"&gt;  
    &lt;h1&gt;My First Heading&lt;/h1&gt;
    &lt;p&gt;My first paragraph&lt;/p&gt;    
  &lt;/div&gt;
  
&lt;/pre&gt;


---


##### AVOID: But if you do that but skip the pre tags, It 'works', just don't, bc any code following it is stuck, notice that everything after is using githubs code 'blocks': 

&lt;link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/un5t0ppab13/prettyprint/master/monokai_for_google_prettyprint.css"&gt;
    
&lt;script src="https://google-code-prettify.googlecode.com/svn/loader/run_prettify.js"&gt;&lt;/script&gt;

<pre class="prettyprint lang-html">

  &lt;div id="code-example"&gt;  
    &lt;h1&gt;My First Heading&lt;/h1&gt;
    &lt;p&gt;My first paragraph&lt;/p&gt;    
  &lt;/div&gt;
  
<pre>



### SUMMATION: Don't use \&lt; or \&gt; for \<pre> tags


---


##### If you would like an example of using google-code-prettify on websites (aka html instead of md), then fork this repo and render the html (They use the Monokai color syntax theme)



![alt tag](https://github.com/un5t0ppab13/prettyprint/blob/master/docs/prettyprint.png)


![alt tag](docs/prettyprint.png)

---

[google-code-prettify](https://code.google.com/p/google-code-prettify/wiki/GettingStarted#Serving_your_own_JS_&_CSS)

---

## License

All rights reserved
Copyright (C) 2015 Un5t0ppab13

[Check out my profile page page](http://github.com/un5t0ppab13).