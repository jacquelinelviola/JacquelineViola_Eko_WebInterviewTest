JacquelineViola_Eko_WebInterviewTest
====================================
Jacqueline Viola
jlv78@cornell.edu

Eko Communications, Inc.
Web Interview Test

[December 18, 2014]

First, I made a new file called test.html to run on the localhost to work out the kinks in the HTML. I used the W3 Schools HTML validator to ensure that the HTML code was written correctly. Using this tool, I found and corrected several syntax errors. For example, some lines contained a backslash (\) when they should’ve used a forward slash (/). Additionally, the ampersand was used in a URL, but in code it must be escaped. In other words, it should be &amp instead of & when it is used in a string. Through the validation process, I saw that there was an attribute called button in the link tags that were formatted as buttons. At the moment, this attribute is not permitted within <a> tags. Because these link tags used the class btn btn-default btn-store, which are styled with CSS in style.css, we don’t need this button attribute. Additionally, in some lines, there was a comma between attributes. This is not valid syntax; attributes must be separated by spaces. In some parts of the code, there were extra end tags, such as </p> when there was no opening tag in scope. After checking that there weren’t missing opening tags, I removed the extra closing tags. Once I had the HTML validated, I converted this test file into index_2.php so I could test the PHP functionality using an XAMPP server. When I worked everything out, I replaced the original index.php file with the contents of index_2.php. I then deleted the test files test.html and index_2.php to avoid confusion.

When I was looking at the files from GitHub, I noticed that there was a stylesheet already created, but not used in the code for the landing page. So I linked the landing page to the main stylesheet. I also saw that there were several navigation panel-esque elements. I tested each button and link in these panels, and noticed that several did not point anywhere. This led me to search look more closely at the existing Loop website (sendaloop.com). I linked the “About,” “Privacy,” and “Terms” navigation elements to the corresponding pages from the Loop website.

Once I made sure that the buttons and links pointed to the correct destinations, I looked at some design elements to change. The Loop logo in top the navigation panel was coded as a link, but it did not point anywhere. I turned this logo into a link that acts as a home button. It points to the landing page. Now, no matter where the user is on the website, they can always return to the main page by clicking the logo.

Please refer to this GitHub link for the corrected code: https://github.com/jacquelinelviola/JacquelineViola_Eko_WebInterviewTest/tree/master/Eko_WebInterviewTest.
