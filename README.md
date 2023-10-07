# reading-notes 
all notes for reading assingments

## Code 201 - Foundations of Software Development

### reading questions
1. Compose a short poem describing how HTTP sends data between computers.

I started out using chat gpt on this and asked it to write me a poem in the voice of jane austen. Then i moved on to a few haiku's I finally decided on using a rhyming website and trying to write it for myself. 

all of my notes were taken from the reading.

http hypertext protocol does enthrall like a little phone call. To start it all out your computer says with a shout “Dear sever please fetch me the data this human wants to zoom in on” and the server replies “200 ok” even if you are on Broadway which is such a cliché. Sending packets with the speed of a cannonball. Packets are small as they travel the tubes and create little cubes; displayed for you on your screen what a scene.

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.

   
Html and css are the first things the browser will render from top to bottom. Javascript follow second which is why we should not put a <script></script> tag in the middle of the doc unless you use defer which means the browser will run all html-css first  then come back to javascript. Or you can just place it at the bottom before closing body tag </body>


3.How can you find images to add to a Website?

To find an image to use on a website you would first do an image search then open it to make sure it’s appropriate, Then you save the image somewhere that makes sense. As most images are copyrighted it is a good practice to make sure to use a COMMON CREATIVE LISENCE

4.How do you create a String vs a Number in JavaScript?

To create a string in JS it needs to have quotes around it ex “23” or “twenty three” to create a number you do not need quotes, but it must be only number symbols and not words as words would get an error. Ex 23

5. What is a Variable and why are they important in JavaScript?
Variables store information for later use. It is important to use them to make interesting and flexible programs with values that can change.

6. What is an HTML attribute?
Attributes provide information about about html elements like an href which says where the hyperlink will land

7. Describe the Anatomy of an HTMl element. Taken from MDN docsar
Anatomy of html <p>My cat is very grumpy</p>
   1. < p > opening tag
   2. My cat is very grumpy -> content
   3. < / p > closing tag
   4. Entire thing is called element

8. What is the Difference between < article > and < section > element tags? Taken from mdn docs
   1. <article> encloses a block of related content that makes sense on it’s own w/o rest of page i.e. blogpost
   2. <section> is similar but more for grouping together a single part of page that constitutes one single piece of function . ie mini map or set of article headlines or theme

9. What Elements does a “typical” website include? Taken from MDN docs
   1. Header big strip across the top w. big heading, logo, tagline
   2. Nav bar link to sites main sections repped by menu button, links, tabs
   3. Main content, area in center contains most unique content of page like a video
   4. Sidebar -> peripheral info, links, quote, ads, ets usually contextual to main content
   5. Footer strip across the bottom of page generally contains fine print, copyright, notices, or contact information
  
10. How does metadata influence Search Engine Optimization? <br>
      a. You are able to tag your doc with keywords that search engines pick up on which could increase the visibility of your website in a web search.

11. How is the <meta> HTML tag used when specifying metadata? <br>
   a. The meta tag has the title, character set, author, keywords. Web browsers use meta to display html correctly

12. What is the first step to designing a Website? <br>
   a. What do I want to accomplish

13. What is the most important question to answer when designing a Website? <br>
   a. Is this really necessary and worth my time? Will it improve my life?

14. Why should you use an < h1 > element over a <span> element to display a top level heading? <br>
   a. An h1 is default styled to a large font which make it look like the heading. Span makes things look like a top heading but has no semantic value

15. Why should you use an < h1 > element over a <span> element to display a top level heading? <br>
   a. An h1 is default styled to a large font which make it look like the heading. Span makes things look like a top heading but has no semantic value

16. What are the benefits of using semantic tags in our HTML? <br>
   a. Seo <br>
   b. Screen readers can use it to navigate visually imapared people <br>
   c. Finding meaningful blocks of code rather than going though all the div tags <br>
   d. Suggests to the developer what kind of data will be populated <br>
   e. Semantic naming mirrors pro

### class 1 md notes
1. How the web works. <br>
   a. Clients and servers <br>
   b. Clients web server interconnection device ie comp, phone, tablet & web accessing software <br>
   c. Servers comps store webpage site or apps when client access webpage a copy of webpage download from server to client machine <br>
2. Other parts of toolbox
   a. Analogy road is client , shops are server, Road takes you there shops supply things. <br>
   b. Internet connections -> send and receive data <br> 
   c. Tcp transmission control & internet protocol define how the data moves, like a bike or a car on a road. <br>
   d. DNS domain name system -> address book for website, DNS look up address <br>
   e. HTTP hypertext protocol define language for the clients and server to speak to each other <br>
   f. Component files, website made of of many diff files like diff goods from store <br>
           - 1. Code files – website made up of many dif files <br>
            -2. Assets -> collective name of other stuff img, music, video, word, doc, pdf <br>
3. What happens
   a. Browser goes to DNS
   b. Browser sent http request
   c. Sever approve client req sends 200 ok message (ok to view website)
   d. Browser assemblies packet into complete webpage

4. Order which component files parsed <br>
   a. Html 1<sup>st</sup>
   b. Order which component files parsed <br>
   c. Html 1st<br>

   d. As parses html send req for css <br>
   e. Then JavaScript <br>

7. Browers make interim dob tree from parsed html <br>
   a. Makes cssom from parsed css <br>
   b. Complies and executes  parsed JS <br>
   c. As browser does all above visual representations show up <br>

8. DNS explained <br>
   a. Ip address res uniq local on web DNS looks up Ip based on typed web address

9. Packets <br>
   a. Data sent across web <br>
   b. Smaller easier to send and replace if corrupt <br>

10. Getting started w. web <br>
   a.Install software <br>
   b. Plan the look of site <br>
   c. Dealing w files create sensible file structure files sensibly <br>
   d. Html basics -> code used to structure web content <br>
   e. Css basics -> cascading style sheets <br>
   f. JS basics -> adds interactive features to website <br>
   g. Publishing code -> get it online <br>
   h. How the web works -> it’s a series of tubes <br>

11. Website Design Planning <br>
    a. What is website about <br>
    b. What info will you present <br>
    c.What does it look like <br>
    d. Sketch your design <br>
    e. Choose assets <br>
      - i. Text <br>
      -ii. Theme color <br>

11. Images to google search save image create common license. Font below <br>
    a. Font -> find font <br>
    b. Add ref in code to load font <br>
    c. Download font to file to system host font, used hosted copy on website <br>

 
12. Intro to HTML <br>
   a. @ heart HTML lang can be applied to pieces of text to give different meaning <br>
   b. What in the head Meta data in HTML <br>
    - i. The head of HTML doc part NOT displayed in browser when loaded <br>
    - ii. Contains info like <title> link to CSS <br>
   c. HTML text functions <br>
    - i. HTML give txt meaning (semantics) browser knows hot to display correctly <br>
   d. Creating hyperlinks – syntax to make links and how to use responsibly <br>
    - i. **See 1st reading assignment into to html** <br>
    - ii. **Advanced text formatting see article in reading** <br>
   e. Document website structure -> HTML is used to define areas of website header, nav menu, main content, column <br>
 
14. Getting started with HTML <br>
   a. Html consist of series of elements  which enclose, wrap mark up diff parts of content to appear certain way <br>
   b. Anatomy of html < p >My cat is very grumpy< / p > <br>
     - i. < p >  opening tag <br>
     - ii. My cat is very grumpy -> content <br>
     - iii. < / p > closing tag <br>
     - iv. Entire thing is called element <br>

13. Nesting element, elements can be placed within other elements ex < p > my cat is < strong >very< / strong >grumpy< / p>
       a. Tags have to open and close in a way they are inside or outside one another <br>
       b. Void elements -> elements that consist of single tag (self closing tag) used to embed/ insert something in document like < img > <br>
       c. Attribute should have <br>
       - i. Space between it and element name of elements >1 attribute, attributes should be separated by spaces <br>
       - ii. Attribute name followed by equal sign <br>
       - iii. Attribute value wrapped w. opening and closing quote marks <br>

15. Document & Website structure <br>
   a. Basic section of a document <br>
      - i. Header big strip across the top w. big heading, logo, tagline <br>
      - ii. Nav bar link to sites main sections repped by menu button, links, tabs <br>
      - iii. Main content, area in center contains most unique content of page like a video <br>
      - iv. Sidebar -> peripheral info, links, quote, ads, ets usually contextual to main content <br>
      - v. Footer strip across the bottom of page generally contains fine print, copyright, notices, or contact information <br>
         
   b. HTML for structuring content <br>
      - i. Can use pretty much any element to wrap around dif sections to get look wanted <br>
      - ii. However must respect semantics and use right element for the job <br>
      - iii. HTML an mark up section of content based on functionality <br>
      - iv.  Implemented mark-up HTML provides dedicated tags <br>
         - a. Header < head > <br>
         - b. Navigation < nav > <br>
         - c. Main content < main > various subsections <br>
         - d. < article > <br>
         - e. < section > <br>
         - f. < div > <br>
         - g. Sidebar < aside > often in <main> <br>
         - h. Footer < footer > <br>
 
   c. Difference between < article > < section > <br>
      - i.**< article > encloses a block of related content that makes sense on it’s own w/o rest of page i.e. blogpost** <br>
      - ii.**< section > is similar but more for grouping together a single part of page that constitutes one single piece of function. ie mini map or set of article headlines or theme** <br>
   
   d. Non semantic wrappers use when want to group set of elements together to affect all as single entity w. some CSS or JS. <br>
      - i. Use < div > and < span > elements <br>
      - ii. Should use with suitable class to provide some kind of label so can be easily targeted <br>
      - iii. < span > inline semantic element should only use if can’t think of better semantic text element to wrap content <br>
      - iv. < dif > is block <br>
      - v. level non-semantic element only use when necessary <br>
   
   e. Line breaks and horizontal rules <br>
      - i. < br > line break element creates a line break for paragraph <br>
      - ii. < hr > the thematic break element creates a horizontal rule in doc, denotes thematic change in text, such as change in topic or scene <br>
   
   f. Planning simple website <br>
      - i. Make a plan simple stuff first <br>
      - ii. Sketch it out <br>
      - iii. Brainstorm all the other not common content of pate <br>
      - iv. Sort content into groups <br>
      - v. Draw sketch of site map <br>
      
   g. Have bubbles for each page of site draw lines to dif workflows <br>

15.What in the Head? Metadata <br>
   a. What is in the HTML Head <br>
      - i. < head > heads content is not displayed on page head contents metadata <br>
   b. Adding a tile <br>
      - i. h1  elements appear on page when loaded in the browser. <br>
      - ii. < title > element is metadate that reps title of overall HTML doc <br>
   c. Meta data <meta> element. Metadata describes data and HTML way to add is < meta > <br>
      - i. Specify your docs character encoding < meta charset = ” utf-8” / > **spaces added for readability** <br>
   d. Universal character set that includes pretty much all human lang form. <br>
   e. Adding author description <br>
      - i. Name specs the type of meta element what type of info contained <br>
      - ii. Content specs actual meta content <br>
   f. Adding custom icons to site <br>
      - i. See MDN web docs on this <br>
   g. Applying CSS & JS to HTML most websites now use HTML & JS to have interactive function <br>
      - i. <link> should always go inside head of doc takes 2 attributes <br>
   h. Rel = ” style shee t” docs style sheet and href which contains the path to the style sheet. <br>
      - i. <script> goes IN head & included src attribute containing JS you want to load and defer <br>
   j. Defer instructs browser to load the JS after page has parsed HTML <br>
   k. Setting primary lang od doc you can and should get land of you page. <br>
      - i. Lang attribute ex <html lang = ” en-US ”> … </ html > <br>
 
16. How to start website design <br>
   a. Summarize <br>
      - i. What do I want to accomplish <br>
      - ii. How will a website help me reach my goals <br>
      - iii. What needs to be done and in what order to reach goals <br>
   b. Dive deeper= a musician does not write music w/o inspo. <br>
      - i. Hour discussion is good start. Need more sit down and structure ideas into clear view <br>
      - ii. What do I want to accomplish <br>
   c. Create goals for website <br>
   d. Prioritize those goals <br>
      - iii. What needs to be done in order to reach colas <br>
      - iv.  Conclusion “make a website generates a long to do list” <br>
 
17. Semantics -> refs meaning o piece of code. What effect does running JS have here? What is the purpose of HTML rather than what does it look like. <br>
   a. Semantics in JS consider func takes 1 param & returns li element w. string as text content would you need to look a code to see what it did <br>
   b. Semantics CSS -> styling li repping dif fruit would you know which part of DOM is being selected w. div>ul>li or .fruits_item <br>
   c. Semantics in HTML <br>
      - i. h1 semantic element which give text it wraps around the role of top level heading on page <br>
      - ii. benefits from writing semantic mark up <br>
   b. seo <br>
      - i. screen readers can use it as signpost to help visual navigation for visually impaired <br>
      - ii. finding meaningful blocks of code easier than going though <dif> <br>
      - iii. Suggest to the developer the type of date that will be populated <br>
      - iv.Semantic naming mirrors proper custom element/component naming <br>

18. What is Javascript<br>
   a. JS scripting/programing lang allow of implimentations of complex features on webpages <br>
   b. Real possibilites <br>

      - i. store useful values inside of variable like name (string), num of storing function as variable. <br>
      - ii. operation on pieces of test <br>
      - iii. running code in respone to certain things happing on webpage. <br>
      
   c. api (application programming interface) ready mad set of code that all devs to use program s that would be hard or impossible to implement <br>
      - like ikea furniture<br> 
   d. 2 something<br>
      a. browser api<br>
         - 1. dom (document object model) api allows manipulation of html + css<br>
      b. geolocation api gets (retrieves) geopraphical info<br>
      c. canvas & webGL creat 2d and 3d graphics <br>
      d. audio & video api like html media elemtn ad webrtc allow multimedia into webpage <br>
      e. 3rd party api not built into browser by default must get code info like twitter, google maps<br>
      f. js run order JS runs in order of top to bottom.<br>
      g. interpreted vs. complied<br>
         - 1. complied languates run from computer not broweser c/c++ complied into machine and run on computer<br>
         - 2. interp langs run from browser. code runs from top to bottom<br>
         - 3. JS is lightweight interped land Js interp run technique is called just in time compliling<br>
      h. server side vs. client side <br>
         - 1. client side runs on uses computer <br>
         - 2. server side run on serve ex of langs included <br>
            - php
            - python
            - ruby
            - asp. net
            -JS
      i. Dynamis vs. static code
         - 1. dynamis used to describe both client side and server side ability  to update display of webpage/app to show diff stuff in dif circs<br>
         - 2. Server side dynamic generation new conetne on server puling data from database<br>
         - 3. bebpage w/o dynamic updates is static<br>
      j. How to add js to pg. 
         - 1. JS applied to HTML sim to css. use < script > <br>
         - 2. **see mdn web docs on internal js** <br> 
         - 3. External JS see MDN web docs on internal js <br>
      k. Using add event listener instead <br>
         - 1. use pure javascript construct the quere selector <br>
      l.  script loading strageies <br>
      m. Async and defere <br>
         - 1. 2 features can use to bypass prob of blocking script
         - 2. Scripts loaded usng async will download script w/o  page while script being fetched 
         
      
      
   
         
 



## Code 301 - Intermediate Software Development

## Code 401 - Advanced Software Development


**I have questions that need answers right away**

_I have ideas_

I have been <sup>reading</sup>

Other<sub>thoughts</sub> 
That I have
