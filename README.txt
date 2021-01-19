Packet Name :- Customisable ScrollBar

Current Problem: Lack of compatibilty leading to difficulty in customising scrollbars for user interfaces, especially for browsers such as Mozilla Firefox and Microsoft Edge.

Proposed Solution: A custom javascript and jquery based scrollbar to replace the standard browser scrollbars. 
		It would allow for customisation and even change in features like speedy scrolling and scrolling with different keys.

Functions of the packet: It has 4 basic functions
	1. Responding and moving accoring to mouse wheel
	2. Performing hold and drag function
	3. Click at a point to skip to that point on page
	4. Respond to key-presses

Content of the zip: This is a code packet containing of two files 
	1. scrollscript.js : Containing the JavaScript.
	2. scrollstyle.css : Containing the CSS.
	3. index.HTML : A demo of what a scrollbar would look like without further customisation.
	4. README

How to Use: It involves just 3 steps
	1. Download and add the the two files (scrollscript.js , scrollstyle.css) to the same folder as index.HTML
	2. Add the given lines to the bottom of body tag 

		<script src="http://code.jquery.com/jquery-3.4.1.min.js"></script>
		<script src="http://code.jquery.com/ui/1.12.1/jquery-ui.min.js"></script>
		<script src="scrollscript.js"></script>

	3. Make any changes required in the scrollstyle.css file to customise it to match the page formatting.

Made by: Aishwarya Agrawal
	
