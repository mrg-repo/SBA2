# SBA 2 - Accessible Design Co.

## Summary 
* This is a single page website for Accessible Design Co. It includes header, main, and footer sections. As I was creating the site, my primary focus was making sure I used containers so elements would be properly targeted.

## Viewing Instructions
* To view this site, pull the files index.html , style.css , and all files in the Img folder to your local repo from the linked GitHub repo. Once pulled to your local repository, you can open the index.html file in your browser of choice, or you can use a "Live View" extension in your IDE of choice to view the site. 

## Reflection Questions
* Question 1: What accessibility challenges did you face, and how did you address them?
  * The biggest challenge I faced regarding accessibility was my choice of background image. Because it was very colorful and had both dark and bright spots, I had to adjust the text to make sure it was easier to read. I also had to adjust the color of my button because my initial choice was below level AA contrast minimum. 

* Question 2: How did you ensure that your design was responsive and accessible to all users?
  * One of the ways I ensured my design was responsive was by using media queries to make sure my site is responsive to a variety of screen sizes. As I was implementing this, I learned that CSS uses whatever property comes last regarding an element if the two properties conflict. This was because I placed a media query for widths up to 600px before the media query for widths below 1024, and my site didn't reflect the services grid properly because of it. Some of the ways I ensured my site was accessible were by making sure I included labels for form fields, using aria labels, and adding roles where helpful such as on the call to action button in the hero section.

* Question 3: What tools or resources did you find most helpful during this project?
  * The tools/resources I found most helpful were the lessons from class, projects from non-graded assignments, w3schools.com, css-tricks.com, and developer.mozilla.org
