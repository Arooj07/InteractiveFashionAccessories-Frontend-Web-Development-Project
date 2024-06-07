# GirlsOnly_InteractiveFashionAccessories-Frontend-Web-Development-Project
Create an interactive web application that showcases a variety of fashion accessories, emphasizing both their functionality and fashion appeal. The final product will be a visually appealing, user-friendly website that can be used to display and interact with different accessories.

This HTML document creates a webpage for showcasing a collection of fashion accessories. Let's break down each section:

1. Document Type Declaration and HTML Structure:
<!DOCTYPE html>: Specifies that the document is an HTML5 document.
<html lang="en">: Defines the root element of the HTML document with the language attribute set to English.
  
2. Head Section:
Contains metadata and links to external resources.
Sets the character encoding (<meta charset="UTF-8" />) and viewport (<meta name="viewport" content="width=device-width, initial-scale=1.0" />).
Sets the title of the webpage (<title>Fashion Accessories</title>).
Includes internal CSS styles within the <style> tags to style the webpage.

3. Body Section:
Contains the main content of the webpage.
Starts with a <header> element for the page header, including a title and description.
Includes a <main> element with an ID of "gallery" where accessory items will be displayed.
Contains a <section> element with an ID of "accessory-gallery" for the accessory collection.
Inside the "accessory-gallery" section, there's an input field for searching accessories and a dropdown menu for filtering accessories by category (<input type="text" id="search" /> and <select id="filter">).
The accessory items will be dynamically added to the <div id="gallery-items"> within this section.

4. Footer Section:
Contains information about the website, including sections for "About Us," "Quick Links," and "Contact Us."
Each section is styled and organized using CSS flexbox layout.
At the bottom, there's a copyright notice and attribution for the website design.

5. JavaScript Section:
The JavaScript code is enclosed within <script> tags at the end of the document.
It waits for the DOMContentLoaded event before executing to ensure that the HTML content is fully loaded.
Defines an array of accessory items with properties such as name, category, image URL, and description.
Defines functions to display accessories, filter accessories based on search and category, and event listeners for user interactions (typing in the search field and selecting a category).
Finally, it displays the initial set of accessories when the page loads by calling the displayAccessories function with the array of accessories.
This HTML document combines HTML, CSS, and JavaScript to create a dynamic and visually appealing webpage for showcasing fashion accessories.

![image](https://github.com/Arooj07/GirlsOnly_InteractiveFashionAccessories-Frontend-Web-Development-Project/assets/100277795/13839772-ebe6-466e-b6a2-ca6501d58338)
![image](https://github.com/Arooj07/GirlsOnly_InteractiveFashionAccessories-Frontend-Web-Development-Project/assets/100277795/936c4f62-af09-4cd8-85be-73175bbb1762)

