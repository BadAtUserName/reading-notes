# reading-notes 
all notes for reading assingments

## Code 201 - Foundations of Software Development

###reading questions
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

8. What is the Difference between <article> and <section> element tags? Taken from mdn docs
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

14.Why should you use an < h1 > element over a <span> element to display a top level heading? <br>
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
            1. Code files – website made up of many dif files <br>
            2. Assets -> collective name of other stuff img, music, video, word, doc, pdf <br>
3. What happens
   a. Browser goes to DNS
   b. Browser sent http request
   c. Sever approve client req sends 200 ok message (ok to view website)
   d. Browser assemblies packet into complete webpage

4. Order which component files parsed <br>
   a. Html 1<sup>st</sup>
5. Order which component files parsed ,br.
   a. Html 1st,Br>

6. As parses html send req for css <br>
   a. Then JavaScript <br>

7. Browers make interim dob tree from parsed html <br>
   a. Makes cssom from parsed css <br>
   b. Complies and executes  parsed JS <br>
   c. As browser does all above visual representations show up <br>

## Code 301 - Intermediate Software Development

## Code 401 - Advanced Software Development


**I have questions that need answers right away**

_I have ideas_

I have been <sup>reading</sup>

Other<sub>thoughts</sub> 
That I have
