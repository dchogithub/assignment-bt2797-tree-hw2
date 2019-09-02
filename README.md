# Homework #2 Solution
**Student Name**: David Cho

**NetID**: bt2797

<ul id="toc">
<li><a href="#Q1">Question 1.</a></li>
    <ul>
      <li><a href="#Q1a">1(a)</a></li>
      <li><a href="#Q1b">1(b)</a></li>
	  <li><a href="#Q1c">1(c)</a></li>
	  <li><a href="#Q1d">1(d)</a></li>
    </ul>
	<li><a href="#Q2">Question 2.</a></li>
    <ul>
      <li><a href="#Q2a">2(a)</a></li>
      <li><a href="#Q2b">2(b)</a></li>
    </ul>
	<li><a href="#Q3">Question 3.</a></li>
    <ul>
      <li><a href="#Q3a">3(a)</a></li>
      <li><a href="#Q3b">3(b)</a></li>
	  <li><a href="#Q3c">3(c)</a></li>
	  <li><a href="#Q3d">3(d)</a></li>
    </ul>
	<li><a href="#Q4">Question 4.</a></li>
    <ul>
      <li><a href="#Q4a">4(a)</a></li>
      <li><a href="#Q4b">4(b)</a></li>
	  <li><a href="#Q4c">4(c)</a></li>
	  <li><a href="#Q4d">4(d)</a></li>
	  <li><a href="#Q4e">4(e)</a></li>
    </ul>
	<li><a href="#Q5">Question 5.</a></li>
    <ul>
      <li><a href="#Q5a">5(a)</a></li>
      <li><a href="#Q5b">5(b)</a></li>
	  <li><a href="#Q5c">5(c)</a></li>
	  <li><a href="#Q5d">5(d)</a></li>
    </ul>
</ul>


<h2 id="Q1">Question 1</h2>
<h3 id="Q1a">Question 1 (a)</h3>
<section class="answer">
	<p>Tags: nav, a, img</p>
	<p>Attributes: class, href, alt, src, style</p>
</section>
<h3 id="Q1b">Question 1 (b)</h3>
<section class="answer">
		<p>Can you use the same id attribute on more than one element in an HTML document?Does the fact that we use id attributes as targets for links within a page influence this? Can you use the same class on multiple elements in a document? Why or why wouldn’t this be helpful for styling?</p>
		<p>No, I can not use same id for more than one element.</p>
		<p>Yes, of course. Multiple elements with same id cause for ambigous transaction. Of course, browser tries to fix this problem and go to the first element with corresponding id, but of course, it is terrible: using multiple elements for same id.</p>
		<p>Yes, I can use same class for different elements.</p>
		<p>It is helpful for styling since allows to apply same style to different elements (for example, different buttons with same style).</p>
</section>
<h3 id="Q1c">Question 1 (c)</h3>

<h3 id="Q1d">Question 1 (d)</h3>

<h2 id="Q2">Question 2</h2>
<h3 id="Q2a">Question 2 (a)</h3>
<section class="answer">
	<p>Selector: body; type: simple selector (by type); properties: padding-bottom with value 50px<p>
	<p>Selector: #RelatedItems nav; type: descendant selector (by id and type); properties: max-height with value: 50vh; overflow-y with value auto<p>
	<p>Selector: .graphDrawing; type: simple selector (by class); properties: border with value dashed thin #808080; border-radius with value 5px; width with value 90%; margin with value 0; margin-bottom with value 25px<p>
</section>
<h3 id="Q2b">Question 2 (b)</h3>
<section class="answer">
	<p>Composite selector article figcaption allows to select all items with type figcaption inside the selector with type article</p>
	<p>Composite selector a.navbar-brand img allows to select all items with type img inside the selectors with type a which have class navbar-brand</p>
</section>

<h2 id="Q3">Question 3</h2>
<h3 id="Q3a">Question 3 (a)</h3>
<section class="answer">
	<p>parseInt('hello'); // (i) Why? and What is a NaN? NaN means 'not-a-number'. This answer was caused fact that word hello is not number</p>
	<p>parseInt('12hello'); // (ii) Answer 12 since parseInt try to parse number while we have digit in the string. After first not-digit, function stops converting and return received number</p>
	<p>parseInt('1010', 2); // (iii) What does this do?	This command convert binary number to decimal, result be 10 since 2^3+2^1=10</p>
	<p>parseInt('hi5'); // (iii) Is this the same as (ii)? No, since first character is not digit, therefore we could not parse numer</p>
	<p>![3A](img/pic_q3a.png)</p>
</section>

<h3 id="Q3b">Question 3 (b)</h3>
<section class="answer">
	<p>pi = Math.PI;</p>
	<p>h = 6.62607004e-34;</p>
	<p>mpg = 343/11.8;</p>
	<p>mpg.toString(); // Example, gives full "precision"</p>
	<p>pi.toFixed(5);// (i) Use toFixed to get a string of the first 5 digits of pi </p>
	<p>h.toPrecision(3);// (ii) Use toPrecision to get h (planck's constant) to 3 sig figs</p>
	<p>mpg.toFixed(1);// (iii) Use toFixed to get the mpg to a tenth of a gallon</p>
	<p>![3b](img/pic_q3b.png)</p>
</section>

<h3 id="Q3c">Question 3 (c)</h3>
<section class="answer">
	<p>```javascript</p>
	<p>a = "DavidCho"; // double quote string</p>
	<p>b = 'DavidCho'; // single quote string</p>
	<p>console.log(a === b); // Check if these are equal</p>
	<p>// Why bother with two string delimiters? It is usefull if we need additional quote for using quote in message,output etc.</p>
	<p>test = "It's a pain to always escape quotes"; // (i) does this work? Yes</p>
	<p>console.log(test);</p>
	<p>// test = 'It's a pain to always escape quotes'; // (ii) why not this? Since we string was closed after symbol t in word it</p>
	<p>// console.log(test2);</p>
	<p>test3 = 'It\'s a pain to always escape quotes'; // (iii) What is going on here? We have blocks ' by using character backslash</p>
	<p>console.log(test3);</p>
	<p>```</p>
	<p>![3c](img/pic_q3c.png)</p>
</section>


<h3 id="Q3d">Question 3 (d)</h3>
<section class="answer">
	
	<p>name = "David Cho";</p>
	<p>uname = name.toUpperCase(); // (i) What? Convert string to upper case</p>
	<p>console.log(uname);</p>
	<p>lname = name.toLowerCase(); // (ii) What? Convert string (name) to lower case</p>
	<p>console.log(lname);</p>
	<p>// Explain what the following two lines do and show a screenshot</p>
	<p>// of the results. Next 2 lines check, is name in upper case contains A, and is name in lower case contains i</p>
	<p>console.log("Your name includes an 'a': " + uname.includes('A'));</p>
	<p>console.log("Your name includes an 'i': " + lname.includes('i'));</p>
	
	<p>![3d](img/pic_q3d.png)</p>
</section>
<h3 id="Q3e">Question 3 (e)</h3>
<section class="answer">
	<p>![3e](img/pic_q3e.png)</p>
</section>

<h2 id="Q4">Question 4</h2>

<h3 id="Q4a">Question 4 (a)</h3>
<section class="answer">
	<p>sentence = "A long, long, time ago in a galaxy"; // A string</p>
	<p>myArray = sentence.split(' '); // (i) what does this do? Generate array with elements which divided by space</p>
	<p>console.log("The number of words is: " + myArray.length);</p>
	<p>myArray.push("far"); // (ii) what do each of these calls do? add elements to the array (3 element, 2 with same value)</p>
	<p>myArray.push("far");</p>
	<p>myArray.push("away");</p>
	<p>console.log("The number of words is: " + myArray.length);</p>
	<p>console.log(myArray.join('_')); // (iii) what does join do? This command return string with elements of the array, separated by _</p>
	<p>tempIndex = myArray.indexOf('galaxy'); // (iv) What does this do? This function </p>
	<p>myArray[tempIndex] = "college"; // (v) did I change an element? Yes</p>
	<p>console.log(myArray.join(' '));</p>
	<p>myArray.pop(); // (vi) what does this do? Remove last element </p>
	<p>console.log("The number of words is: " + myArray.length);</p>
	<p>![4a](img/pic_q4a.png)</p>
</section>
<h3 id="Q4b">Question 4 (b)</h3>
<section class="answer">
	<p>i. Convert xString to upper case</p>
	<p>ii. Call function upper for each element of myArray2, and store result of the function to myArray3</p>
	<p>iii. Function which compare 2 string without case sensetive</p>
	<p>iv. Ordering array for source array without taking into account case, source array will be not changed</p>
	<p>![4b](img/pic_q4b.png)</p>
</section>

<h3 id="Q4c">Question 4 (c)</h3>
<section class="answer">
<p>![4c](img/pic_q4c.png)</p>
</section>

<h3 id="Q4d">Question 4 (d)</h3>
<section class="answer">
	function speedCompare(x, y) {
	  if (parseFloat(x.max2sec) < parseFloat(y.max2sec)) 	  
		return -1;
	  else 
		if (parseFloat(x.max2sec) > parseFloat(y.max2sec))
		   return 1;
	  return 0;
	}

	function distanceCompare(x, y) {
		if (parseFloat(x.distance) < parseFloat(y.distance))
				return -1;
		else 
			if (parseFloat(x.distance) > parseFloat(y.distance))
				return 1;
		return 0;
	}
	<p>![4d](img/pic_q4d.png)</p>
</section>

<h2 id="Q5">Question 5</h2>
<h3 id="Q5a">Question 5(a)</h2>
<h3 id="Q5b">Question 5(b)</h2>
<section class="answer">
<p>	```javascript</p>
<p>		h2::first-letter,h3::first-letter</p>
<p>		{</p>
<p>		  color:blue;</p>
<p>		}</p>
<p>	```</p>
</section>
<h3 id="Q5с">Question 5(с)</h2>
<section class="answer">	
		<p>#toc</p>
		<p>{</p>
		  <p>background-color:#ccccff;</p>
		<p>}</p>
</section>
<h3 id="Q5d">Question 5(d)</h2>
<section class="answer">	
		<p>	.answer</p>
	<p>{</p>
	  <p>background-color:#ffffcc;</p>
	  <p>border: solid black;	</p>
	<p>}</p>
</section>
<h3 id="Q5e">Question 5(e)</h2>
<section class="answer">	
	<p>![5e](img/pic_q5e.png)</p>
</section>
