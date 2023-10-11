##Reading notes class-02.md
All notes taken from the reading. 
I.  Intro to HTML cont. <br> 
  a. See notes from first reading <br>

  b. boolean attributes <br>
    - i. attributes written w. o values boolen attributes <br>
    - ii. diabled attribure assing to form input element. Use to disable fom input elements. So user can make entries <br> 

  c. omitting quote around attribute values<br>
    - i. permitted in certain circs bu cna break mark-up<br>

  d. single or double quotes<br>
    - i. can use single or double quotes is stylistic choice<br>
    - ii. do not mix up un matche paris of quotes no " and '<br> 
    - ii. can use two types in different ways.<br.

  e. anatomy of an html doc.<br> 
    - i. < ! DOCTYPE > used to be very long in 91ish 92ish no is a historiccal artifact needs to be includd for thins to work<br> 
    - ii. < h. t. m. l. > < / h. t. m. l. > element wraps all content on page<br>
    -iii. < h e .a d > < / h e. a d > container for everyting tou want on page that isn't content  including keywords, page description that appera in search results. css to style content char sets.<br>
    -iii. < me. ta> </ met. a> reps metadata that can't be prepped by other html.<br>
      -- 1. <b. a. s. e. > w. closing tag<br>
      -- 2. < l. i. n. k.>closing tag<br>
      -- 3. < s.c.r.i.pt.>closing tag<br>
      -- 4. < s.t.y.l.e>closing tag<br>
      -- 5. <t.i.t.l.e>closing tag<br>
          -- a. char set reps how you write all human written lang<br>
      -iv. <t.i.t.l.e> </t.i.t.l.e> set the tile of the page with appears in browser tab when loaded.<br>
      -v. <b.o.d.y></b.o.d.y> contains all conent that display on page text , video img  hames, audio.<br>

  f. Whitespace<br>
    - 1. HTML parser reduces each seq of whitespace to singl space 4 readability<br>
    - 2. Easier to understand code if formatted nice. <br> 
    -3. can jave jes render white space w. whitespace or noWhitespace<br>

  g. Entity refs inclu spcl char html<br>
   - 1. if want to incl special char in text of htm must use char ref each car sts w. & < ampersand and end with ; semicolon.<br> 
    - 2. ex < & lt;<br>
        > & gt;<br>
        '& apos;<br>
        & & amp;<br>

     h. html comments <!- - stuff -->

I. Html text fundamentals <br>
  a. Heading and paragraph <br>
    i. Most structured text consists of headings and paragraphs <br>
    ii. Html paragraph ha to be wrapped in p tag < p > < / p > <br>
    iii. Heading wrapped in < h1 > < / h1 > <br>
    iv. 6 headers exist h1-h6 largest to smallest <br>
    v. Only use on h1 pre page <br>
    vi. Make sure in correct order do not but h3 before h2 <br>
    vii. Aim for no more than 3 per page unless really needed <br>
  b. Why structure<br>
    i. Users scan webpage to find content easier with headings<br>
    ii. Search engines indexing page consider content of headings very important. <br>
    iii. Visually impaired don’t read pages they listen<br>
    iv. To style content w. css or make it do interesting things with js, you need to have elements wrapping<br>

  c. Why semantics<br>
    i. Traffic lights green means go similar w. semantics make sure using correct elements giving content correct meaning , function or appearance<br>

  d. Lists
    i. Unordered in a random order no hierarchy <br>
          Starts w/ < ul > <br>
          < li > milk< /li > <br>
          < li >bread< /li > <br>
          < li >eggs< /li > <br>
          Ends with < /ul >
    ii.      Ordered lists where order matters<br>

e. Same as UL except all wrapped in < ol > < /ol ><br>

f. Nesting lists<br>
    i. Nesting list inside another like a recipe. Listing ingredients, then how to process them.<br>

g. Emphasis and importance<br>
    i. Emphasis on words can change importance<br>
    ii. Add emphasis on word wrapping in <e. m.></ e. m.><br>

h. Do not use to italicize use span and some css or < i > element<br>
 
i. Strong importance word in lang are highly stressed and bold on webpage.<br>    
    i. To bold use < s. t. r o. n. g><br>
    ii. To bold something use span and < b. > element<br>
    iii. Can nest emphasis in each other. <br>
    iv. To underline use < ul > <br>

 II. Html advance text formatting<br>

  a. Description lists <br>
    i.Purpose mark up set of items and associate descript such as terms and def or ? and answers<br>
    ii. Diff wrapper < d. l. > in addition each term wrapped in <d. t. > (description term) each descript wrapped in < d. d. > description definition element. <br>

  b. Quotations<br>
    i.Has mark up 4 quotes element used depend on block or inline<br>

  e. Blockquote<br>
    i. If section is paragraph multiple paragraph list quoted from elsewhere should be wrapped in < b. l. o. c. k q. u. o. t. e><br>

  f. Include URL pointing to sour of quite inside cite attribute<br>
  g. Inline quotations<br>
    i. Inline quote work same except use < q. > element<br>

 h. Citations useful but not displayed to view meant to contain < c. i. t. e> element to be quoted<br>
 
 i. Abbreviations <br>
   i.< a. b. b. r> use to wrap around abbreviation or acronym<br>
   ii. Use whole word in plain text along w/ < a. b. b. r> to mark up abbreviation<br>

 j. Marking up contact details<br>
   i. Html has element for contact < a. d. d. r. e. s. s > Chriss mills Manchester The Grim North U.K. <br>

 k. Superscript and subscript<br>
   i. < s. u. b. > </ s. u. b> goes down sup goes up<br>

 l. Repping comp code. <br>
  i. < c. o. d. e.> generic pieces of code<br>
  ii. < p. r. e.> retaining white space wrap in < p. r. e.> </ p. r. e.> whitespace will be rendered as written.<br>
  iii. < k. b. d. > marking up keyboard<br>
  iv. < v. a. r> variable names only<br>
  v. <s. a. m. p> marking up output of computer program<br>

  l. Marking up times and dates <  time date time= “2016-01-20” ………..This bit is nothing   > <br>
 

III. How css is structured<br>

a. -External style sheet<br>
  i. – separate file w/ a  css extension<br>
  ii. – common method bringing css to document<br>

b. -Can ref external css stylesheet w. html link<br>
c. -Href attribute of link need to ref style folder in system see written notes for example<br>
d. -Internal style sheet resides w. in html doc < s. t. y. l. e > is contained in head for sites<br>
e. -Inline styles don’t use them<br>
  i. – css rule starts w. selector example below<br>
    1. – h1<br>
    2. -- a : link<br>
    3. -- . many things<br>
    4. -- #  one thing<br>
    5. -- X <br>
    6. -- . box p <br>
    7. -- . box p : first-child <br>
f. H1 h2 intro<br>
g. - Specificity<br>
h. –many times will have 2 selectors same html can set to .   special (dot special) and will override other conflicting style<br>
 i. -Properties and values. <br>
    i. – properties human readable identifiers that that indicate which style you want to modify<br>
    ii. – values each prop has assigned value. Value indicates how to style property<br.
    iii. – when property is paired w. val is called css declaration<br>
    iv. –css declaration block we paid w. selector to produce css ruleset<br>

j. -Functions <br>
  i. –function does simple math w. in the css. <br>
  ii. –a function has a function name parentheses to enclose values for functions<br>

j. -Transform functions<br>
  i. –various values for transform such as rotate ( )<br>

K. -@ rules ( at rules )<br>
  i. –Common @ rule is @ media used for media queries<br>
  ii. –media queries use conditional logic for applying css style.<br>

l. -Shorthands properties like font and background, padding, border, margin, can, be combined in one line of code.  See MDN docs for examples<br>
m. -Comments /* stuff */<br>
n. -whitespace keeps code easy to read<br>
 

IV. Js Basics Comments though events<br>

a. – comments are the same in JS as CSS<br>
  i. – addition +<br>
  ii. – subtraction multiplication division<br>
  ii. -Operator math symbol that gives result based on 2 variables<br>
  iv. – addition + add together 2 numbers or 2 strings<br>
  v. -Subtraction multiplication division does the basic math using -, *, / <br>
  vi. – assignment = assigns value to variable<br>
  vii. – strict equal = = = tests to see if two values are equal and same data type<br>
  viii. –does not equal returns logically opposite value of what it precedes turn a true int a false . When used alongside  the equality operator tests weather 2 values are not equal<br>

b. -Conditionals<br>
  i. – code structures used to test if expression returns true<br>
  ii. – expression inside of if (   ) is the test. Uses strict equality operater to compare variable with  string to see if equal returns true 1st block of code run. If comparison not true second block will run. <br>

c. -Functions way of packaging functionality that you want to reuse<br>
  i. – funct look like the var but is just followed by parenthese<br.
  ii. – function take arguments<br>

d. – arguments  go inside the parentheses separated by commas if more than one argument<br>
  iii. – can define own functions<br>

 

 

V. Events<br>

a. - interactivity on website requires event handlers<br>
  i. – listen for activity in the browser run coed in response<br>

b. - number of wayt to add even listener can select HTML element cal event listener function passing name on even to listener and function when it happens<br>
c. – add event to anonymous function alt way to write as arrow funct  ( ) =>
 

VI. Making decisions in your code- conditionals<br>

a. - conditional statement allow us to rep such decision making in JS<br>
b. - if else if condition  {  run code if condition true } else { run some code }<br>
c. – anatomy of if else <br>
  i. -- keyword with parentheses<br>
  ii. -- conditional to test like is value greater than or does value exist<br>
  iii. -- the keyword else
  iv. -- another set of curly braces w. code to run if condition is false<br>
  v. -- second bloc always runs

c. - Else if (  elif  )  use to change outcomes<br>
  i. -- when function is run we set a var set ot current val select in select element use condition statement to show diff text dependent on  value<br>
  ii. -- checks if the 1st statement true if the fals move to 2nd and when finds if state that evaluates correctly if none true then ruins else<br>

c. - Note on comparison  operators<br>
  i. -- See written notes

d. - logical operators used to test multi conditions w/o nesting statement<br>
  i. -- see written notes<br>

e. -Switch statements<br>
  i. -- if else is good for a lot of things but not great for large numbers
  ii. -- switch statement take single expression value as input then look though several choices till finds match<br>
  iii. --Example see written notes<br>
  iv. -- the keyword switch followed by parentheses<br>
  v. -- an expression or value in the parentheses<br>
  vi. -- Keyword case follow by a SOMETHING that expression value could be followed by colon<br>
  vii. --Some code to run if choice matches expression<br>
  viii. -- break statement followed by semicolon if choice matches code will stop running. <br>
  ix. -- you can have as many cases as you want .<br>
  x. -- the keyword default followed by exactly the same code pattern. Default does not not have a choice after it doesn’t need break statement. <br>
  xi. -- Ternary operator syntax not tests a condition and returns value/expression if it is true and another is false this can be useful and can take up a log less code than if else block<br>
  xii. --  on change event listener tht runs a function containg a ternary operator starts w. test condtion  like select  value = = =  “black” if this returns true we run update w. parenthese bladk and white we end up black background and whitd text. If T and inverted if F

    
     
          
      

  
