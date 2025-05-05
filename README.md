# programming-paradigms-lab-9-revising-haskell-wholemeal-programming-solved
**TO GET THIS SOLUTION VISIT:** [Programming Paradigms Lab 9-Revising Haskell. Wholemeal programming Solved](https://www.ankitcodinghub.com/product/programming-paradigms-lab-9-revising-haskell-wholemeal-programming-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100214&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Programming Paradigms Lab 9-Revising Haskell. Wholemeal programming Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Programming Paradigms

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Lab 9. Revising Haskell. Wholemeal programming

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Outline

<ul>
<li>● &nbsp;Side-scrolling game</li>
<li>● &nbsp;Rotating background</li>
<li>● &nbsp;Working with an infinite universe</li>
<li>● &nbsp;Generating random infinite universe</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Inferring types

Exercise 6.1.

What is the type of the following definitions? Provide the most general type. Verify your answer against the compiler.

<pre>exercise_6_1_a = 2 + 3
</pre>
<pre>exercise_6_1_b (x, y) = sqrt (x^2 + y^2)
</pre>
<pre>exercise_6_1_c x y = [x, y]
</pre>
<pre>exercise_6_1_d [] = ""
exercise_6_1_d (x:xs) = exercise4 xs ++ [x]
</pre>
<pre>exercise_6_1_e x = (x, x)
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Wrapper types

Exercise 6.2.

Consider the following type declarations representing cartesian and polar coordinates of a 2D point. Implement conversion functions.

data Cartesian = Cartesian Double Double data Radians = Double

data Polar = Polar Double Radians

<pre>toPolar :: Cartesian -&gt; Polar
fromPolar :: Polar -&gt; Cartesian
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Higher-order functions

Exercise 6.3.

Implement higher-order function concentric, that renders concentric shapes. Using concentric, render a picture of practice target:

<pre>main :: IO ()
main = drawingOf
</pre>
<pre>  (concentric targetCircle 10)
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Algebraic data types + stateful computation

Exercise 6.4.

Consider the following type of commands. Implement a function that follows a sequence of commands to render a picture.

type Radians = Double

data Command

= Forward Double

| Rotate Radians

| TeleportTo (Double, Double)

<pre>runCommands :: [Command] -&gt; Picture
</pre>
<pre>main = drawingOf (runCommands
  [ Rotate (2*pi/3), Forward 2, Forward (-4)
  , TeleportTo (0, 0), Rotate (2*pi/3), Forward 2 ])
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
Input and output in Haskell

Exercise 6.5.

Implement an interactive program that records every user input and allows to search history via command /search &lt;phrase&gt;. Use Data.List.isInfixOf to search for previous inputs matching the search phrase. Example (user input is bold):

input&gt; something to record

input&gt; something else to record

input&gt; Haskell is strongly statically typed

input&gt; lazy evaluation is useful in purely-functional languages input&gt; /search something

Found 2 records:

– something to record

– something else to record

</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
Generating lists

Exercise 6.6(a)

Implement function renderCartesianGrid:

<pre>renderCartesianGrid
  :: (Double, Double)
  -&gt; (Double, Double)
  -&gt; Picture
</pre>
<pre>main :: IO ()
main = drawingOf
</pre>
<pre>  (renderCartesianGrid
     (-5.5, 5.5)
</pre>
(-5.5, 5.5))

</div>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<div class="layoutArea">
<div class="column">
Generating lists

Exercise 6.6(b)

Implement function renderPolarGrid:

<pre>renderPolarGrid
  :: Double
  -&gt; Int
  -&gt; Picture
</pre>
<pre>main :: IO ()
main = drawingOf
</pre>
<pre>  (renderPolarGrid 5.5 5)
</pre>
</div>
</div>
</div>
</div>
