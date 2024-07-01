# Lecture-I.-Sequences

<div class="tytulpunktu">1. SEQUENCES</div>
  
<p>First we shall grasp the idea of a sequence intuitively. Let us arrange
some fixed real numbers, placing them one after another according to a certain
recipe. We say that they form a sequence of numbers or simply a sequence.
For example, if we arrange the set of even numbers in an ascending order,
we obtain the following sequence of even numbers: 2, 4, 6, 8, ..., 2(<i>n</i>
 + 1), ... Similarly, a sequence of natural numbers is the set of natural
numbers arranged in an ascending order: 0, 1, 2, 3, 4, 5, ..., <i>n</i>,
... </p>
  
<p>Before defining a sequence of numbers formally, let us recall the definition
af a function. Let <i>X, Y </i> be non empty sets of numbers. </p>
  
<div class="def"> 
<p><b>Definition</b></p>
  
<p>A function <i>f</i> defined on a set <i>X </i>with values from a set <i>
Y </i>is a mapping that assigns to each number <i>x</i> from the set <i>X</i>
 <u>exactly one number</u> <i>f</i> (<i>x</i>) from the set <i>Y</i>. </p>
 </div>
  
<p>This mapping may be denoted in different ways: </p>
  
<p><i>f : X</i> &#8594; <i>Y</i> or <i>y </i> = <i>f</i> (<i>x</i>), <i>x</i> <font face="Arial">
&#8712;</font> <i>X</i> or <i>X</i> <font face="Arial">'</font> <i>x </i> &#8594; <i>
f </i>(<i>x</i>) <font face="Arial">&#8712;</font> <i>Y</i>.</p>
  
<p>If X is the set of natural numbers <i>N</i> (or its subset of the form
{<i>n</i><sub>0</sub>, <i>n</i><sub>0</sub> + 1, ,,, }), then the function
<i>f</i> is called<a name="EDU.skorowidz.termin sequence infinite_number 4_11"></a> 
 an infinite sequence of numbers or simply a sequence. Thus a sequence is
a special kind of a function with real values. For <i>n</i> <font face="Arial">
&#8712;</font> <i>N</i> (or <i>n</i> &#8805; <i>n</i><sub>0</sub>), <i>f</i> (<i>n</i>) is called the "<i>n</i>th element" of a sequence or the general term. A
set of indices for which the elements of considered sequences are defined,
i.e. the set of natural numbers or a set of natural numbers greater or equal
than a given number <i>n</i><sub>0</sub>, will be denoted by <i>N</i>. This
notation will be used hereafter. </p>
  
<div class="def"> 
<p><b>Definition</b></p>
  
<p>A sequence of numbers (<i>a</i><sub>n</sub>) is a function that associates
a real number <i>a</i><sub>n</sub> with every natural number <i>n</i> <font face="Arial">
&#8712;</font> <i>N.</i></p>
 </div>
  
<p>Usual notations for sequences are: (<i>a</i><sub>n</sub>) or <i>a</i><sub>
0</sub>, <i>a</i><sub>1</sub>,.., or <i>a</i><sub>n</sub>, <i>n</i> = <i>
n</i><sub>0</sub>, <i>n</i><sub>0</sub>+1, ..., or {<i>a</i><sub>n</sub>}, 
 (<i>a</i><sub>n</sub>)<sub>n</sub><sub><font face="Arial">&#8712;</font>N</sub>,     (<i>a</i><sub>n</sub>, <i>n</i> <font face="Arial">&#8712;</font> <i>N</i>).</p>
   
<p>The number <i>a</i><sub>n</sub> is called<a name="EDU.skorowidz.termin general_term_of_a_sequence 4_12"></a> 
 <b>the general term of a sequence or the <i>n</i>th</b><a name="EDU.skorowidz.termin element_of_a_sequence 4_13"></a> 
 <b>element</b><a name="EDU.skorowidz.termin term of_a_sequence 4_14"></a> 
 <b>of a sequence</b>. General terms are often denoted by: <i>a</i><sub>n</sub>, <i>b</i><sub>n</sub>, <i>c</i><sub>n</sub>, <i>x</i><sub>n</sub>, <i>y</i><sub>
n</sub>, ...</p>
  
<p><b>Examples</b></p>
  
<ul>
   
  <li>(<i>n</i>&#8243;) is a sequence with <i>a</i><sub>n</sub> = <i>n</i>&#8243;, <i>
n</i> <font face="Arial">&#8712;</font> <i>N</i>. That is, every natural number
    <i>n</i> is mapped onto its square. This sequence could be also described
by making a list of its elements: 0, 1, 4, 9, 16, ..., <i>n</i>&#8243;, ... , or
as a function     
    <dir>     
    <dir><p><i>f : N</i> &#8594; <i>R</i>, where <i>f</i>(<i>n</i>) = <i>n</i>&#8243; =
    <i>a</i><sub>n</sub> </p></dir>
     </dir>
   </li>
 
</ul>
 
<ul>
   
  <li>The sequence <img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1377.gif" align="Center" height="50" width="38">, <i>n</i> = 0, 1, 2,..., is the well-known<a name="EDU.skorowidz.termin sequence geometric 4_15"></a> 
 geometric progression with the common ratio <i>q</i> = 1/2. Alternative
notations of this sequence are:       
    <table align="Center">
       <tbody>
         <tr>
           <td><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1625.gif" height="50" width="454">
 </td>
         </tr>
       
      </tbody>     
    </table>
 	   </li>
 
</ul>
 
<ul>
   
  <li>The sequence (-1)<sup>n</sup>, <i>n</i> = 0, 1, 2, ... , reads: 1,
-1, 1, -1, 1, ,,, . Even (incl. 0) and odd numbers are mapped onto 1 and
-1, respectively. The image of this sequence is a two-element set. </li>
 
</ul>
 
<ul>
   
  <li><i>a</i><sub>n</sub> = <i>c</i> + <i>nr</i>, <i>n</i> <font face="Arial">
&#8712;</font> <i>N</i>, (<i>c </i>and<i> r</i> are fixed real numbers), is known
as<a name="EDU.skorowidz.termin sequence arithmetic 4_16"></a> 
 arithmetic progression with the common difference <i>r</i>. </li>
 
</ul>
 
<ul>
   
  <li><i>a</i><sub>n</sub> = <i>cq</i><sup>n</sup>, <i>n</i> <font face="Arial">
&#8712;</font> <i>N</i>, (<i>c</i> and <i>q</i> are fixed real numbers), is known
as<a name="EDU.skorowidz.termin sequence geometric 4_17"></a> 
 geometric progression with the common ratio <i>q</i>. </li>
 
</ul>
  
<p>In the above examples the sequences were given by defining <b>a formula
for the general term</b>. It is also possible to define a sequence <b>descriptively</b>, e.g.: <i>a</i><sub>n</sub> = <i>n</i>th prime number, (<i>b</i><sub>n</sub>) = a sequence of squares of natural numbers, a sequence of primes, ... .</p>
  
<p>Very often, especially in computer science, sequences are defined <b>recursively</b>. For instance, the first element of a sequence is defined directly as a
fixed number <i>x</i><sub>0</sub>, and every next element <i>x</i><sub>n</sub><sub>
+1</sub> is given as a function of the preceding one <i>x</i><sub>n</sub>
: <i>x</i><sub>n</sub><sub>+1 </sub>= <i>g (x</i><sub>n</sub>), where <i>
g</i> is a known function.  </p>
<p><b>Examples</b></p>
  
<ul>
   
  <li><i>x</i><sub>1</sub> = 1, <i>x</i><sub>n+</sub><sub>1</sub> = 2<i>x</i><sub>
n</sub>, <i>n</i> = 1, 2, ..., - geometric progression with the common ratio
    <i>q</i> = 2   </li>
  <li><i>c</i><sub>1</sub>    = 1, <i></i>c<sub>2</sub> = 1, <i>c</i><sub>
n</sub><sub>+2</sub> = <i>c</i><sub>n</sub><sub>+1</sub> + <i>c</i><sub>n</sub>,   <i>n</i> = 1, 2, ... </li>
</ul>
  
<p><b>Exercise 1.1</b> </p>
  
<p>Find the general term of the sequence defined recursively: </p>
  
<p><i>x</i><sub>1</sub> = 5, <i>x</i><sub>n+</sub><sub>1</sub> = <i>x</i><sub>
n</sub> + 5, <i>n</i> = 1, 2, ...</p>
  <a class="ODP" href="javascript:https://gakko.pjwstk.edu.pl/materialy/259/lec/okno%28%27odpowiedzi/odp1_1.htm%27%29">
Answer</a>

<details>
  <summary>Answer 1.1:</summary>
<p><i>x<sub>n</sub></i> = 5<i>n</i>, <i>n</i> = 1, 2, ... , -
arithmetic series with the common remainder <i>r</i> = 5. </p>
  
<p>A graphical representation of a sequence is its graph, i.e. a set of points
on a plane</p>
</details>
  
<p>{ (<i>n</i>, <i>a</i><sub>n</sub>), <i>n</i> <font face="Arial">&#8712;</font>
 <i>N</i> }. </p>
  <img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/rys1/rys_1_1.gif">  
<p><b>Fig. 1.1 Graph of the sequence <i>a</i><sub>n</sub> = 0,1· <i>n</i>
&#8243;</b></p>
  
<p>The set of elements of the sequence { <i>a</i><sub>n</sub>, <i>n</i> <font face="Arial">
&#8712;</font> <i>N</i> } can be represented graphically as a subset of a real
axis. </p>
  <img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/rys1/rys_1_2.gif">  
<p><b>Fig. 1.2 The set of values of the sequence <i>a</i><sub>n</sub> = (-
1)<sup>n</sup>· 0,1· <i>n</i>&#8243;</b></p>
  
<div class="def"> 
<p><b>Definition </b></p>
  
<p>A sequence (<i>a</i><sub>n</sub>) is: </p>
 
<ul>
   
  <li><a name="EDU.skorowidz.termin sequence non-decreasing 4_18"></a> 
 <b>non-decreasing</b>, if <b><i>a</i><sub>n+1</sub> &#8805; <i>a</i><sub>n</sub></b>, for any <i>n</i> <font face="Arial">&#8712;</font> <i>N</i></li>
 
</ul>
 
<ul>
   
  <li><a name="EDU.skorowidz.termin sequence increasing 4_19"></a> 
 <b>increasing</b>, if <b><i>a</i><sub>n+1</sub>     &gt; <i>a</i><sub>n</sub></b>, for any <i>n</i>     <font face="Arial">&#8712;</font> <i>N</i></li>
 
</ul>
 
<ul>
   
  <li><a name="EDU.skorowidz.termin sequence non-increasing 4_20"></a> 
 <b>non-increasing</b>, if <b><i>a</i><sub>n+1</sub>     &#8804; <i>a</i><sub>n</sub></b>, for any <i>n</i>     <font face="Arial">&#8712;</font> <i>N</i></li>
 
</ul>
 
<ul>
   
  <li><a name="EDU.skorowidz.termin sequence decreasing 4_21"></a> 
 <b>decreasing</b>, if <b><i>a</i><sub>n+1</sub>     &lt; <i>a</i><sub>n</sub></b>, for any <i>n</i>     <font face="Arial">&#8712;</font> <i>N</i></li>
 
</ul>
 
<ul>
   
  <li><a name="EDU.skorowidz.termin sequence bounded 4_22"></a> 
 <b>bounded</b>, if there exists a number <i>A</i> such that the absolute
value of each element in the sequence is not greater than <i>A,</i> i.e.
    <b><font face="Arial">&#124;</font><i>a</i><sub>n</sub> <font face="Arial">
&#124;</font>     &#8804; <i>A</i></b>, for any <i>n</i> <font face="Arial">&#8712;</font>
 <i>N</i></li>
 
</ul><a name="EDU.skorowidz.termin sequence unbounded 4_23"></a> 
 
<ul>
   
  <li><b>unbounded</b>, if it is not bounded, i.e. for an arbitrarily chosen
number <i>A</i> there exists an element of the sequence such that its absolute
value is greater than <i>A, </i>that is, there exists a natural number <i>
n</i> such that <b><font face="Arial">&#124;</font><i>a</i><sub>n</sub> <font face="Arial">
&#124;</font> &gt; <i>A</i></b></li>
 
</ul><a name="EDU.skorowidz.termin sequence bounded below 4_24"></a> 
 
<ul>
   
  <li><b>bounded below</b>, if there exists a number <i>m</i> such that <b><i>
a</i><sub>n</sub> &#8805; <i>m</i></b> for any <i>n</i> <font face="Arial">&#8712;</font>
 <i>N</i>. The number <i>m</i> is called a <b>lower bound</b> of the sequence 
  </li>
 
</ul><a name="EDU.skorowidz.termin sequence bounded above 4_25"></a> 
 
<ul>
   
  <li><b>bounded above</b>, if there exists a number <i>M</i> such that <b><i>
a</i><sub>n</sub> &#8804; <i>M</i></b> for any <i>n</i> <font face="Arial">&#8712;</font>
 <i>N</i>. The number <i>M</i> is called an <b>upper bound</b> of the sequence 
    
    <p></p>
   </li>
 
</ul><a name="EDU.skorowidz.termin sequence unbounded above 4_26"></a> 
 
<ul>
   
  <li><b>unbounded below (above)</b>, if it is no bounded below (above). 
   
    <p></p>
   </li>
 
</ul>
 </div>
  
<p><b>Examples</b></p>
  
<ul>
   
  <li>the sequence of squares of natural numbers is increasing and unbounded<br>
   </li>
 
</ul>
 
<ul>
   
  <li>the geometric progression with the common ratio 1/2 is decreasing and
bounded (<i>A</i> = 1)</li>
 
</ul>
 
<ul>
   
  <li>the sequence <img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1610.gif" align="Center">
 is decreasing and bounded:     
    <p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1626.gif" height="41" width="341">
    </p>
   </li>
 
</ul>
 
<ul>
   
  <li>the sequence ((- 2)<sup>n</sup>) is bounded (<i>A</i> = 2)</li>
 
</ul>
 
<ul>
   
  <li>the sequence (<i>a</i><sub>n</sub>) such that <i>a</i><sub>2n</sub>
 = <i>a</i><sub>2n+1</sub> = 1 -1/<i>n</i>, <i>n</i> = 1, 2, ... , is non-decreasing
and bounded (<i>A </i>= 1). A graph of this sequence is displayed in Fig.1.3.
  </li>
 
</ul>
  <img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/rys1/rys_1_3.gif">  
<p><b>Fig. 1.3 Non-decreasing and bounded sequence</b></p>
  
<p><b>Exercise 1.2</b> </p>
  
<p>Is the sequence  </p>
<p> <img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1611.gif" align="Center" width="77">
  </p>
<p>increasing and bounded? </p>
 <a class="ODP" href="javascript:okno2%28%27odpowiedzi/odp1_2.htm%27%29">
Answer</a>
  
<p></p>
 
<div class="stwier"> 
<p><b>Corollary </b> </p>
  
<p><a name="EDU.skorowidz.termin sequence non-decreasing 4_27"></a> 
 A sequence that is non-decreasing<a name="EDU.skorowidz.termin sequence non-increasing 4_28"></a> 
 (non-increasing) and<a name="EDU.skorowidz.termin sequence bounded above 4_29"></a> 
 bounded above<a name="EDU.skorowidz.termin sequence bounded below 4_30"></a> 
 (below) is<a name="EDU.skorowidz.termin sequence bounded 4_31"></a> 
 bounded.</p>
 </div>
  
<p> <a class="ODP" href="javascript:okno2%28%27odpowiedzi/odp_stwier.htm%27%29">
Proof</a>
  </p>



  
<p>A <b>monotone</b> sequence is a sequence that is either<a name="EDU.skorowidz.termin sequence monotone 4_32"></a> 
 non-decreasing or non-increasing, whereas a sequence that is either decreasing
or increasing<a name="EDU.skorowidz.termin sequence strictly_monotone 4_33"></a> 
 is said to be strictly monotonic. Let us notice that the definition implies 
directly that an increasing (decreasing) sequence is also non-decreasing
(non-increasing). Hence a sequence that is strictly monotone is monotone
as well. </p>
  
<div class="stwier"> 
<p><b>Corollary</b></p>
  
<p>A sequence (<i>a</i><sub>n</sub>) is bounded <font face="Arial">&#8660;</font>
 (<i>a</i><sub>n</sub>) is bounded both below and above.</p>
 </div>
  
<p><b>Proof</b></p>
  
<p>(necessity: <font face="Arial">&#8658;</font>) For any <i>n</i>: <font face="Arial">
&#124;</font> <i>a</i><sub>n</sub> <font face="Arial">&#124;</font> &#8804; <i>A</i> <font face="Arial">
&#8660;</font> - <i>A</i> &#8804; <i>a</i><sub>n</sub> &#8804; <i>A</i>. Thus the sequence
is bounded below by <i>m</i> = - <i>A</i> and above by <i>M</i> = <i>A</i>.</p>
  
<p>(sufficiency: <font face="Symbol">Ü</font>) Assume that - <i>m</i> &#8804; <i>
a</i><sub>n</sub> &#8804; <i>M</i>. Taking <i>A</i> = max {<font face="Arial">
&#124;</font> <i>m</i><font face="Arial">&#124;</font>,<font face="Arial">&#124;</font>
 <i>M</i><font face="Arial">&#124;</font> } we obtain <font face="Arial">&#124;</font>
 <i>a</i><sub>n</sub> <font face="Arial">&#124;</font> &#8804; <i>A.</i> </p>
  
<div class="def"> 
<p><b>Definition </b></p>
  
<ul>
   
  <li><a name="EDU.skorowidz.termin sum of_sequences 4_34"></a> 
 <b>A sum of     </b>sequences (<i>a</i><sub>n</sub>), (<i>b</i><sub>n</sub>) is the sequence (<i>a</i><sub>n</sub> + <i>b</i><sub>n</sub>)</li>
 
</ul>
 
<ul>
   
  <li><a name="EDU.skorowidz.termin difference_of_sequences 4_35"></a> 
 <b>A difference</b> of sequences (<i>a</i><sub>n</sub>), (<i>b</i><sub>n</sub>) is the sequence (<i>a</i><sub>n</sub>     - <i>b</i><sub>n</sub>)</li>
 
</ul>
 
<ul>
   
  <li><a name="EDU.skorowidz.termin product of_sequences 4_36"></a> 
 <b>A product</b> of sequences (<i>a</i><sub>n</sub>), (<i>b</i><sub>n</sub>) is the sequence (<i>a</i><sub>n</sub> <i>b</i><sub>n</sub>)</li>
 
</ul>
 
<ul>
   
  <li><a name="EDU.skorowidz.termin quotient_of_sequences 4_37"></a> 
 <b>A quotient</b> of sequences (<i>a</i><sub>n</sub>), (<i>b</i><sub>n</sub>) is the sequence (<i>a</i><sub>n</sub> / <i>b</i><sub>n</sub>), if <i>b</i><sub>
n</sub> &ne; 0, for any <i>n</i> <font face="Arial">&#8712;</font>     <i>N</i></li>
 
</ul>
 </div>
  
<p><b>Exercise 1.3</b></p>
  
<p>Find the general term of the quotient of sequences (<i>a</i><sub>n</sub>), (<i>b</i><sub>n</sub>) such that</p>
  
<p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1629.gif" height="50" width="296">
 </p>
  <a class="ODP" href="javascript:okno%28%27odpowiedzi/odp1_3.htm%27%29">
Answer</a><br clear="all"><table width="100%" border="0" cellspacing="0" cellpadding="0"><tr><td align="right">&nbsp;<a href="index05.html" target="_top" class="NAWIGACJA">next&nbsp;&#8776;</a></td></tr></table><!--/td-->
<!--/tr-->
<!--/table-->

<div class="tytulpunktu">2. THE LIMIT OF A SEQUENCE</div>

<p></p>
  
<div class="def"> 
<p><b>Definition</b></p>
  
<p>A number <i>g</i> is called<a name="EDU.skorowidz.termin limit of_a_sequence 5_39"></a> 
 <b>the limit of a sequence (<i>a</i><sub>n</sub>)</b>, if for any number
<img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1631.gif" align="Center" height="18" width="37">
 there exists a number <i>&#948;</i> such that for any <i>n</i> &gt; <i>&#948;</i>
the inequality <font face="Arial">&#124;</font> <i>a</i><sub>n</sub> - <i>g</i><font face="Arial">
&#124;</font> &lt; <i>&#949;</i> holds.</p>
 </div>
  
<p>The fact that a sequence (<i>a</i><sub>n</sub>) has the limit
<i>g</i> is denoted by:  </p>
<p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1632.gif" height="33" width="329">
 </p>
  
<p>Using the quantifiers for every: " <font face="Arial">&#8704;</font> " and
there exists: " <font face="Symbol">$</font> " we can state the equivalent
definition of the limit: </p>
  
<div class="def"> 
<p><b>Definition</b></p>
  
<p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1633.gif" height="34" width="413">
</p>
 </div>
  
<p><b>Interpretation of the limit of a sequence</b></p>
  
<p>The limit of a sequence (<i>a</i><sub>n</sub>) is a number <i>g</i> such
that any neighborhood, no matter how small, more precisely the interval (<i>g</i> - <i>&#949;</i>, <i>g</i> + <i>&#949;</i>) of the length 2<i>&#949;</i>, contains
almost all elements of the sequence, that is except for at most a finite
number. In other words, for every <i>n</i> &gt; <i>&#948;</i> (<i>&#948;</i> usually
depends on <i>&#949;</i>) all elements of the sequence are contained in the interval
(<i>g</i> - <i>&#949;</i>, <i>g</i> + <i>&#949;</i>), since <font face="Arial">&#124;</font>
 <i>a</i><sub>n</sub> - <i>g</i><font face="Arial">&#124;</font> &lt; <i>&#949;</i>
 <font face="Arial">&#8660;</font> <i>a</i><sub>n</sub> <font face="Arial">&#8712;</font>
 (<i>g</i> - <i>&#949;</i>, <i>g</i> + <i>&#949;</i>).</p>
  
<p>Hence, looking at the graph of the sequence, we see that the points (<i>n</i>, <i>a</i><sub>n</sub>), <i> n</i> &gt; <i>&#948;</i>, lie within a belt
of the width 2<i>&#949;</i> (see Fig 1.4). </p>

  <img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/rys1/rys_1_4.gif">
    
<p><b>Fig. 1.4 Graphical interpretation of the limit of a sequence</b></p>
  
<p><b>Example</b></p>
  
<p>We will show that</p>
  
<table align="Center">
   <tbody>
     <tr>
       <td><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1634.gif" height="42" width="80">
       </td>
     </tr>
   
  </tbody> 
</table>
  
<p>Let an arbitrary number <i>&#949;</i> &gt; 0 be fixed. We have to find a natural
number <i>&#948;</i> such that for every <i>n</i> &gt; <i>&#948;</i> holds: </p>
  
<table align="Center">
   <tbody>
     <tr>
       <td><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1635.gif" height="45" width="304">
       </td>
     </tr>
   
  </tbody> 
</table>
  
<p>Let <i>&#948;</i> be a fixed natural number greater than 1/&#949;, e.g.,</p>
  
<table align="Center">
   <tbody>
     <tr>
       <td><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1636.gif" height="45" width="118">
      </td>
     </tr>
   
  </tbody> 
</table>
  
<p>where <i>E</i> (1/&#949;) denotes the greatest integer less than or equal to
1/&#949;. </p>
  
<p>Now if <i>n</i> &gt; <i>&#948;</i>, then</p>
   
<table align="Center">
   <tbody>
     <tr>
       <td><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1637.gif" height="45" width="196">
      </td>
     </tr>
   
  </tbody> 
</table>
  
<p>QED. </p>
  
<div class="stwier"> 
<p><b>Corollary</b></p>
  
<p>If 0 &lt; <font face="Arial">&#124;</font> <i>q</i> <font face="Arial">&#124;</font>
 &lt; 1, then </p>
 
<p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1638.gif" height="38" width="84">
 </p>
 </div>
  
<p><a class="ODP" href="javascript:okno_szer%28%27dowody/dow1_1.htm%27%29">
Proof</a>
</p>
  
<div class="stwier"> 
<p><b>Proposition</b></p>
 
<p>If <i>a</i> &gt; 0, then </p>
 
<p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1639.gif" height="37" width="78">
.</p>
 </div>
  
<p> <a class="ODP" href="javascript:okno3%28%27dowody/dow1_2.htm%27%29">Proof</a>
 </p>
  
<p><b>Exercise 1.4 </b></p>
<p></p>
  
<p>Using the definition of a sequence show that</p>
 
<p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1642.gif" height="44" width="85">
</p>
 <a class="ODP" href="javascript:okno3%28%27odpowiedzi/odp1_4.htm%27%29">
Answer</a>
<p></p>
  
<p>The following proposition is a direct consequence of the definition of
a sequence. </p>
  
<div class="stwier"> 
<p><span style="font-weight: bold; ">Proposition</span></p>
  
<p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1647.gif" height="34" width="253">
</p>
 
<p>Particularly: </p>
 
<p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1648.gif" height="34" width="228">
</p>
 </div>
  
<p><a class="ODP" href="javascript:okno_duze%28%27dowody/dow1_3.htm%27%29">
Proof</a>
</p>
  
<p><b>Exercise 1.5</b></p>
  
<p>Using the proposition show that</p>
  
<p><img src="https://gakko.pjwstk.edu.pl/materialy/259/lec/an1/Image1651.gif" height="49" width="101">
</p>
 <a class="ODP" href="javascript:okno1%28%27odpowiedzi/odp1_5.htm%27%29">
Answer</a>
  
<p>If there exists the limit <i>g</i> of a sequence (<i>a</i><sub>n</sub>), we say that the sequence (<i>a</i><sub>n</sub>) has the limit <i>g</i>, or that the sequence (<i>a</i><sub>n</sub>) is<a name="EDU.skorowidz.termin sequence convergent 5_40"></a> 
 <b>convergent</b> to the limit <i>g</i>. Each sequence, that has the limit
is called a <b>convergent sequence</b>. We know already that e.g., the sequences
1/<i>n</i>, <i>q</i><sup>n</sup>, for <font face="Arial">&#124;</font> <i>q</i><font face="Arial">&#124;</font> &lt; 1, converge to 0. <b>Any convergent sequence has only one limit.</b></p>
  
<p>Each sequence, created by removing some elements from the given sequence
is called<a name="EDU.skorowidz.termin subsequence_of_a_sequence 5_41"></a> 
 <b>a subsequence</b> of this sequence. For instance a sequence of even numbers
is a subsequence of the sequence of natural numbers.</p>
  
<p><b>The limit of a sequence</b><a name="EDU.skorowidz.termin limit of_a_sequence 5_42"></a> 
 <b>does not necessarily exist</b>. A sequence that has no limit<a name="EDU.skorowidz.termin sequence divergent 5_43"></a> 
 is said to be <b>divergent</b>.</p>
   
<p><b>Exercise 1.6 </b></p>
  
<p>Using the definition show that the sequence ((-1)<sup>n</sup>) has no
limit.</p>
<a class="ODP" href="javascript:okno2%28%27odpowiedzi/odp1_6.htm%27%29">Answer</a>
  
<p><br clear="all"><table width="100%" border="0" cellspacing="0" cellpadding="0"><tr><td align="left"><a href="index04.html" target="_top" class="NAWIGACJA">&#8596;&nbsp;previous</a>&nbsp;</td><td align="right">&nbsp;<a href="index06.html" target="_top" class="NAWIGACJA">next&nbsp;&#8776;</a></td></tr></table><!--/td-->
<!--/tr-->
<!--/table-->
