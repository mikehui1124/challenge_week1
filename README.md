# challenge_week1

This is a html sourecode for the landing page of Horiseon, a digital marketing company. The client instructs us to refactor the code to improve largely the accessibility of the site to meet a set of acceptance criteria, while keep the page layout unchanged.
The refactored html and CSS sourcecode is available in this Github repo as Master branch, file names as listed below. The deployed URL of webpage is available in Github Page @ https://mikehui1124.github.io/challenge_week1/

•	Index.html
•	\assets\css\style.css

Brief description
The landing page points to 3 main business areas of the client in digitalmarketing, namely search engine optimize, online reputation management and social media marketing. The nav-bar contains links to each of these core areas on the lower part of the page. Besides the core area is a section listing out 3 benefits available to the service customers.  The way the header, background graphic, main content and the footer is arranged on the webpage have to be maintained, while refactoring the code’s accessibility merits.
![image](https://user-images.githubusercontent.com/105307687/177594926-3732e03b-a85d-427a-9071-93435590491d.png)


Acceptance criteria
The webpage will meet the following accessibility standards requested by client,
-	Viewing the source code, I find sematic HTML elements
-	Viewing the structure of HTML elements, I find the elements follow a logical structure independent of styling and position
-	I find accessible alt attributes when view image elements
-	I find heading attributes all fall in sequential order
-	I find a concise, descriptive title at the top of the page

Refactoring Details
The html and CSS source code is refactored coherently to reflect the accessibility requirements in these manners,
Html code
-	Horiseon Digital Marketing is used as a concise & descriptive title
-	Each of the header, nav-bar, background graphic, main content and the footer components of html code now switches to semantic elements to replace repeated <div> . The structure and order of the webpage is easily identified from the semantic elements.
-	The background graphic, and all images for the core business areas now include alt attributes of a concise content description for the <img> elements, improving vision-impaired access.
-	Heading elements now follows sequential order h1 – h3, each grades being styled separately in CSS with the target font-size and color.

CSS code
-	The code now comments on the use of universal, class and element selectors
-	The order of CSS components follows the sequential structure of html codes to improve ease of cross-reference
-	Child elements of the header follows each other, the comment highlights they are displayed as inline elements
-	CSS components for the left section of main content follows the order from the top to the bottom element, starting from parent class to the child elements. CSS components are commented properly from parent class to its child elements.
-	CSS components for the right section of main content follows the order from the top to the bottom element, starting from parent class to the child elements. CSS components are commented properly in a similar fashion.
-	Images in main content that are displayed as float-left or float-right are properly commented in CSS

Snapshot of Refactored Source Code

 ![image](https://user-images.githubusercontent.com/105307687/177594882-2f1b7c7f-b31d-46fb-a94e-28feb1cf16e8.png)

 ![image](https://user-images.githubusercontent.com/105307687/177594764-10859494-d869-448d-83b6-b9e9938174af.png)

