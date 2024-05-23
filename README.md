![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Welcome to GigFree 

Overview: GigFree is a website for freelance IT Infrastructure consultants to register to gain access to high quality assignments that have been qualified by a dedicated team of HR specialists. The reason for this site is because currently, freelancers have a couple of options when it comes to looking for work. After speaking with countless freelancers, all the ways that they are able to look for new assignments require them to get calls out of the blue from recruiters or have an incredible marketing skill to attract in-bound leads. 

GigFree hopes to fill a void and create more options for Infrastructure Freelance assignments by consolidating roles from various brokerage firms, using AI to identify absolute key factors in the assignments and match that with the best freelancers around. No more cold-calls from people that dont know what they are talking about and just interrupting your day. 

![Desktop view of GigFree](../Project1-final/assets/pictures/computer.JPG)
![Tablet view of GigFree](../Project1-final/assets/pictures/tablet.JPG)
![Mobile view of GigFree](../Project1-final/assets/pictures/phone.JPG)

## Features

This section will cover the features that were added to GigFree for functionality purposes. 

### Navigation Bar:
- Navigation bar was added to site with responsive design - when screen is below 768px, the navigation bar compresses into a clickable compas to provide navigation links. 
- navigation bar is also fixed on screen, so when scrolling down through-out the website, customers can easily find the navigation bar at the top of the screen allowing customers to navigate without pressing the back button or aggressivly scrolling. 

![Navigation Bar](../Project1-final/assets/pictures/nav%20bar.JPG)

### Landing Image: 
- The site include a landing page image with text overlay to allow users to easily and quickly identify the purpose of the website and if it is applicable to them. 
- This section introduces the user to GigFree with a colorful and eye catching landing space. 

![Landing page](../Project1-final/assets/pictures/Landing%20page.JPG)

### About Section:
- This section gives the users a quick overview of the plan of action and purpose of the site. 
- Users should quickly identify the "WIIFM" and the value of signing up. 

### Success Stories:
- This section is to show stories of previous users of the service and share insights of the market situation and how GigFree approaches the freelance market and roles. 
- This section is to again, show the value that GigFree can bring to freelancers that are interested in having a consolidated location to access freelance assignments. 

![Success Section](../Project1-final/assets/pictures/Success.JPG)

### Sign Up Section:
- The sign up section allows users to sign up to access GigFree services. The users can specify their current role and the working area that they are focused on. For example, a DevOps engineer can further specify they work more with Operations rather than Development or Infrastructure. 

![Sign Up Form](../Project1-final/assets/pictures/Sign%20up.JPG)

### Footer Section: 
- The footer section includes links to the relevant social media sites for GigFree. The links will open a new tab to allow easy navigation for users. 
- Social media liks are useful for the user to stay connected and get insights into the user base of services. 

### Features to implement: 
- Currently, signing up simply emails the web-domain. In the future, it would be best to add a section where consultants can go more in detail about their experience or upload a templated CV which can be combined with AI such as "Maker.ai" to maximise candidate matching with assignments. 
- Some form of database added to the backend to store data and to allow GigFree host to provide freelancers with assignments. 
- Additionally, for the success stories section, it would be best to only have 1 story visable with a swiping function, so users are able to swipe through different success stories. On each story, there could also be a link to read more instead of so much text which can cause friction for mobile users. 
- better background images would also be nice. perhaps learn about gradient colurs and how to reposition images within the background frame.

## Testing 
GigFree was developed from a mobile first perspective with larger screens kept in mind throughout the development process. With that said, there have been 2 previous versions of development trials:

### Version1 
The first version of GigFree was developed from a computer screen perspective, when it came to making the site reactive, a lot of the elements, placements etc. were too complex to scale down. It was decided to start a fresh and bring some core concepts from the first version into version 2. 

### Version2 
The second version was still built on a computer screen perspective with the intention to organize the div elements in a way that would allow reactive coding to be implemented. A navigation bar was created with the 4 links to various sections of the site. There was still a learning curve to overcome though. Instead of using the hero image as a background image, I attempted to have the img and div element relatively and absolutely placed to allow a text overlay. 

When testing how to make the site reactive, it was discovered that the navigation bar, by design, had no reactive ability. I was able to have the current navigation links disapprear and reappear but again due to the complexity of the class names that were done to patch work the problem, it was inevitably decided to start the development process again. 

### Version3 (final version)
Before starting the third vision, the "Love Running" section was re-visited and discovered there were sections previously missed which helped the development process. 

Version 3 began with a mobile first perspective and using the conent from the previous 2 versions, GigFree was able to take shape faster and with more reactive design in mind. Throughout the development process, a separate browser was kept open with the site and using the developer tools, mobile S view was selected. Everytime a change was made a soft or hard refresh was done depending on the types of changes made and if cache needed clearing. 

After completing a section, e.g the navigation bar, reactive CSS code were put in place to ensure smooth scaling. Once the scaling elements were completed, the new section went into development. This is believed to help keep the code within the reasonable limits of complexity, unline previous attempts. 

### Validator Testing: 

- HTML
  - 5 similar errors were found when running the site through the [validator](https://validator.w3.org/)
    - (The value of the for attribute of the label element must be the ID of a non-hidden form control.)
    - I googled the issue which suggested adjusting the structure so the inputs were nestled inside the lable element. That did not work. Another suggestion was to give a unique ID to each of the lables, which also did not work. Given more time, I believe a solution could be found. 

- CSS
  - 1 error was found when running the site through the [CSS Validator](https://jigsaw.w3.org/css-validator/)
    - (Value Error : display inline-flexbox is not a display value : inline-flexbox)
    - I tried changing the display value several times but found the design I wanted with the site required a display value that failed the CSS validator and I cant figure out why. I have googled the error code and it is suggested to use a different display value but the values that pass the validator do not pass my design requirement. 

## Deployment 

- The site was deployed to Github pages. The steps I took to do this were as follows: 
  - In Github repository, I navigated to settings for project1-Final 
  - On the "Pages" section - I ensured the source was "deploy from branch" and the branch was set to "main" with "/root" set and saved the settings. 
  - I navigated back to the code section and refreshed the page. 
  - on the right side of the page, I selected the "deployment" section where i found the link for my deployed project
  
  The live link can be found here: [Project1-Final deployed site](https://bjornbishop.github.io/Project1-final/).

  ## Credit

  This section will show links to sites that guided the development process for GigFree. Throughout the development process, a few sites were used to gain inspiration. In the first few versions of GigFree, I tried repurposing code that others had used however I found that my lack of understanding how the code worked meant I struggled to make the code reactive. It was decided then to instead of using section of code from others, to build the whole site with code that I have written so I can control the reactive development process with less complexity and more control. 

  [Font Awesome](www.fontawesome.com) - This was used for the images of social media links. 

  [Pexels](www.pexels.com) - This site was used for the images that can be found on GigFree site. 

  [Code Institute](www.codeinstitute.net) - this site gave a lot of guidance on the code and process for developing the site with a mobile first perspective. 

  [W3 school](https://www.w3schools.com/) - when i became stuck with challenges around the navigation bar or general troubleshooting issues, W3 schools was a useful source of information. 

  [Stack Overflow](www.stackoverflow.com) - Stack overflow was a great source for solutions to problems that were found throughout the development process. 

  [Changing font color](https://stackoverflow.com/questions/11430252/changing-the-color-of-a-part-of-text-in-stylus-css) - This solution helped correct validator issues regarding redundant code used to change the font color of text within a paragraph without changing the color of the whole paragraph. 

  [Center an image](https://www.w3schools.com/howto/howto_css_image_center.asp) - This was used to help aligning images to the centre of a div. 

  [Form emailing](https://www.tutorialspoint.com/How-do-we-send-an-email-using-HTML-forms#:~:text=To%20send%20an%20email%20using,%3Aemailid%40example.com.) - This was used to make the sign-up form have an automatic emailing function although it could be developed further for better functionality. 




    

