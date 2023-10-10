### Reading questions follow by reading notes


Why HTML/CSS/JS/ is important. It seems like the start of really making anything that is even a little bit interesting. It is the crawling you need to do before the walking. 


1. A poem about HTTP
   http hypertext protocol does enthrall like a little phone call. To start it all out your computer says with a shout “Dear sever please fetch me the data this human wants to zoom in on” and the server replies “200 ok” even if you are on Broadway which is such a cliché. Sending packets with the speed of a cannonball. Packets are small as they travel the tubes and create little cubes; displayed for you on your screen what a scene.

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.
Html and css are the first things the browser will render from top to bottom. Javascript follow second which is why we should not put a <script></script> tag in the middle of the doc unless you use defer which means the browser will run all html-css first then come back to javascript. Or you can just place it at the bottom before closing body tag

3.How can you find images to add to a Website?

To find an image to use on a website you would first do an image search then open it to make sure it’s appropriate, Then you save the image somewhere that makes sense. As most images are copyrighted it is a good practice to make sure to use a COMMON CREATIVE LISENCE

4.How do you create a String vs a Number in JavaScript?

To create a string in JS it needs to have quotes around it ex “23” or “twenty three” to create a number you do not need quotes, but it must be only number symbols and not words as words would get an error. Ex 23

5. What is a Variable and why are they important in JavaScript? Variables store information for later use. It is important to use them to make interesting and flexible programs with values that can change.

6. What is an HTML attribute? Attributes provide information about about html elements like an href which says where the hyperlink will land

7. Describe the Anatomy of an HTMl element. Taken from MDN docsar Anatomy of html

My cat is very grumpy

< p > opening tag
My cat is very grumpy -> content
< / p > closing tag
Entire thing is called element
What is the Difference between < article > and < section > element tags? Taken from mdn docs

encloses a block of related content that makes sense on it’s own w/o rest of page i.e. blogpost
is similar but more for grouping together a single part of page that constitutes one single piece of function . ie mini map or set of article headlines or theme
What Elements does a “typical” website include? Taken from MDN docs

8. Header big strip across the top w. big heading, logo, tagline
Nav bar link to sites main sections repped by menu button, links, tabs
Main content, area in center contains most unique content of page like a video
Sidebar -> peripheral info, links, quote, ads, ets usually contextual to main content
Footer strip across the bottom of page generally contains fine print, copyright, notices, or contact information
How does metadata influence Search Engine Optimization?
a. You are able to tag your doc with keywords that search engines pick up on which could increase the visibility of your website in a web search.

9. How is the HTML tag used when specifying metadata?
a. The meta tag has the title, character set, author, keywords. Web browsers use meta to display html correctly

10. What is the first step to designing a Website?
a. What do I want to accomplish

11. What is the most important question to answer when designing a Website?
a. Is this really necessary and worth my time? Will it improve my life?

12. Why should you use an < h1 > element over a element to display a top level heading?
a. An h1 is default styled to a large font which make it look like the heading. Span makes things look like a top heading but has no semantic value

13. Why should you use an < h1 > element over a element to display a top level heading?
a. An h1 is default styled to a large font which make it look like the heading. Span makes things look like a top heading but has no semantic value

14. What are the benefits of using semantic tags in our HTML?
a. Seo
b. Screen readers can use it to navigate visually imapared people
c. Finding meaningful blocks of code rather than going though all the div tags
d. Suggests to the developer what kind of data will be populated
e. Semantic naming mirrors pro

###class 1 md notes
How the web works.
a. Clients and servers
b. Clients web server interconnection device ie comp, phone, tablet & web accessing software
c. Servers comps store webpage site or apps when client access webpage a copy of webpage download from server to client machine

Other parts of toolbox a. Analogy road is client , shops are server, Road takes you there shops supply things.
b. Internet connections -> send and receive data
c. Tcp transmission control & internet protocol define how the data moves, like a bike or a car on a road.
d. DNS domain name system -> address book for website, DNS look up address
e. HTTP hypertext protocol define language for the clients and server to speak to each other
f. Component files, website made of of many diff files like diff goods from store
- 1. Code files – website made up of many dif files
-2. Assets -> collective name of other stuff img, music, video, word, doc, pdf

What happens a. Browser goes to DNS b. Browser sent http request c. Sever approve client req sends 200 ok message (ok to view website) d. Browser assemblies packet into complete webpage

Order which component files parsed
a. Html 1st b. Order which component files parsed
c. Html 1st

d. As parses html send req for css
e. Then JavaScript

Browers make interim dob tree from parsed html
a. Makes cssom from parsed css
b. Complies and executes parsed JS
c. As browser does all above visual representations show up

DNS explained
a. Ip address res uniq local on web DNS looks up Ip based on typed web address

Packets
a. Data sent across web
b. Smaller easier to send and replace if corrupt

Getting started w. web
a.Install software
b. Plan the look of site
c. Dealing w files create sensible file structure files sensibly
d. Html basics -> code used to structure web content
e. Css basics -> cascading style sheets
f. JS basics -> adds interactive features to website
g. Publishing code -> get it online
h. How the web works -> it’s a series of tubes

Website Design Planning
a. What is website about
b. What info will you present
c.What does it look like
d. Sketch your design
e. Choose assets

i. Text
-ii. Theme color
Images to google search save image create common license. Font below
a. Font -> find font
b. Add ref in code to load font
c. Download font to file to system host font, used hosted copy on website

Intro to HTML
a. @ heart HTML lang can be applied to pieces of text to give different meaning
b. What in the head Meta data in HTML

i. The head of HTML doc part NOT displayed in browser when loaded
ii. Contains info like <title> link to CSS
c. HTML text functions
i. HTML give txt meaning (semantics) browser knows hot to display correctly
d. Creating hyperlinks – syntax to make links and how to use responsibly
i. See 1st reading assignment into to html
ii. Advanced text formatting see article in reading
e. Document website structure -> HTML is used to define areas of website header, nav menu, main content, column
Getting started with HTML
a. Html consist of series of elements which enclose, wrap mark up diff parts of content to appear certain way
b. Anatomy of html < p >My cat is very grumpy< / p >

i. < p > opening tag
ii. My cat is very grumpy -> content
iii. < / p > closing tag
iv. Entire thing is called element
Nesting element, elements can be placed within other elements ex < p > my cat is < strong >very< / strong >grumpy< / p> a. Tags have to open and close in a way they are inside or outside one another
b. Void elements -> elements that consist of single tag (self closing tag) used to embed/ insert something in document like < img >
c. Attribute should have

i. Space between it and element name of elements >1 attribute, attributes should be separated by spaces
ii. Attribute name followed by equal sign
iii. Attribute value wrapped w. opening and closing quote marks
Document & Website structure
a. Basic section of a document

i. Header big strip across the top w. big heading, logo, tagline
ii. Nav bar link to sites main sections repped by menu button, links, tabs
iii. Main content, area in center contains most unique content of page like a video
iv. Sidebar -> peripheral info, links, quote, ads, ets usually contextual to main content
v. Footer strip across the bottom of page generally contains fine print, copyright, notices, or contact information
b. HTML for structuring content
- i. Can use pretty much any element to wrap around dif sections to get look wanted
- ii. However must respect semantics and use right element for the job
- iii. HTML an mark up section of content based on functionality
- iv. Implemented mark-up HTML provides dedicated tags
- a. Header < head >
- b. Navigation < nav >
- c. Main content < main > various subsections
- d. < article >
- e. < section >
- f. < div >
- g. Sidebar < aside > often in


- h. Footer < footer >
c. Difference between < article > < section >
- i.< article > encloses a block of related content that makes sense on it’s own w/o rest of page i.e. blogpost
- ii.< section > is similar but more for grouping together a single part of page that constitutes one single piece of function. ie mini map or set of article headlines or theme

d. Non semantic wrappers use when want to group set of elements together to affect all as single entity w. some CSS or JS.
- i. Use < div > and < span > elements
- ii. Should use with suitable class to provide some kind of label so can be easily targeted
- iii. < span > inline semantic element should only use if can’t think of better semantic text element to wrap content
- iv. < dif > is block
- v. level non-semantic element only use when necessary

e. Line breaks and horizontal rules
- i. < br > line break element creates a line break for paragraph
- ii. < hr > the thematic break element creates a horizontal rule in doc, denotes thematic change in text, such as change in topic or scene

f. Planning simple website
- i. Make a plan simple stuff first
- ii. Sketch it out
- iii. Brainstorm all the other not common content of pate
- iv. Sort content into groups
- v. Draw sketch of site map

g. Have bubbles for each page of site draw lines to dif workflows

15.What in the Head? Metadata
a. What is in the HTML Head
- i. < head > heads content is not displayed on page head contents metadata
b. Adding a tile
- i. h1 elements appear on page when loaded in the browser.
- ii. < title > element is metadate that reps title of overall HTML doc
c. Meta data element. Metadata describes data and HTML way to add is < meta >
- i. Specify your docs character encoding < meta charset = ” utf-8” / > spaces added for readability
d. Universal character set that includes pretty much all human lang form.
e. Adding author description
- i. Name specs the type of meta element what type of info contained
- ii. Content specs actual meta content
f. Adding custom icons to site
- i. See MDN web docs on this
g. Applying CSS & JS to HTML most websites now use HTML & JS to have interactive function
- i. should always go inside head of doc takes 2 attributes
h. Rel = ” style shee t” docs style sheet and href which contains the path to the style sheet.
- i. <script> goes IN head & included src attribute containing JS you want to load and defer
j. Defer instructs browser to load the JS after page has parsed HTML
k. Setting primary lang od doc you can and should get land of you page.
- i. Lang attribute ex <html lang = ” en-US ”> … </ html >

How to start website design
a. Summarize

i. What do I want to accomplish
ii. How will a website help me reach my goals
iii. What needs to be done and in what order to reach goals
b. Dive deeper= a musician does not write music w/o inspo.
i. Hour discussion is good start. Need more sit down and structure ideas into clear view
ii. What do I want to accomplish
c. Create goals for website
d. Prioritize those goals
iii. What needs to be done in order to reach colas
iv. Conclusion “make a website generates a long to do list”
Semantics -> refs meaning o piece of code. What effect does running JS have here? What is the purpose of HTML rather than what does it look like.
a. Semantics in JS consider func takes 1 param & returns li element w. string as text content would you need to look a code to see what it did
b. Semantics CSS -> styling li repping dif fruit would you know which part of DOM is being selected w. div>ul>li or .fruits_item
c. Semantics in HTML

i. h1 semantic element which give text it wraps around the role of top level heading on page
ii. benefits from writing semantic mark up
b. seo
i. screen readers can use it as signpost to help visual navigation for visually impaired
ii. finding meaningful blocks of code easier than going though
iii. Suggest to the developer the type of date that will be populated
iv.Semantic naming mirrors proper custom element/component naming
What is Javascript
a. JS scripting/programing lang allow of implimentations of complex features on webpages
b. Real possibilites

i. store useful values inside of variable like name (string), num of storing function as variable.
ii. operation on pieces of test
iii. running code in respone to certain things happing on webpage.
c. api (application programming interface) ready mad set of code that all devs to use program s that would be hard or impossible to implement
- like ikea furniture
d. 2 something
a. browser api
- 1. dom (document object model) api allows manipulation of html + css
b. geolocation api gets (retrieves) geopraphical info
c. canvas & webGL creat 2d and 3d graphics
d. audio & video api like html media elemtn ad webrtc allow multimedia into webpage
e. 3rd party api not built into browser by default must get code info like twitter, google maps
f. js run order JS runs in order of top to bottom.
g. interpreted vs. complied
- 1. complied languates run from computer not broweser c/c++ complied into machine and run on computer
- 2. interp langs run from browser. code runs from top to bottom
- 3. JS is lightweight interped land Js interp run technique is called just in time compliling
h. server side vs. client side
- 1. client side runs on uses computer
- 2. server side run on serve ex of langs included
- php - python - ruby - asp. net -JS i. Dynamis vs. static code - 1. dynamis used to describe both client side and server side ability to update display of webpage/app to show diff stuff in dif circs
- 2. Server side dynamic generation new conetne on server puling data from database
- 3. bebpage w/o dynamic updates is static
j. How to add js to pg. - 1. JS applied to HTML sim to css. use < script >
- 2. see mdn web docs on internal js
- 3. External JS see MDN web docs on internal js
k. Using add event listener instead
- 1. use pure javascript construct the quere selector
l. script loading strageies
m. Async and defere
- 1. 2 features can use to bypass prob of blocking script - 2. Scripts loaded usng async will download script w/o page while script being fetched
