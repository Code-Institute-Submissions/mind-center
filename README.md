# Mind Center    

Mind Center offers information for beginners to learn simple meditation techniques. The website targets busy people with limited sparetime, and in particular those who experience issues such as stress or anxiety. Warm colors and uplifting design is mixed with a few meditation guides to make users interested in spending time on meditating. 

# Features  

### Header and navigation

The header includes a navigation bar with links to home, videos and a contact form on the page.
[Header, navigation](header,nav.jpg)


### Subheader

The image and text directly below the header gives further clarity into what the website is about.

### Meditation instruction

A simple, first meditation exercise is quickly available on the site. Hopefully a user will be interested in reading more and trying out meditation early. 

### Video section

Two videos are added to the page. More exercises/inspiration available could create motivation for users to continue meditating.

### Newsletter

A form allows users to sign up on an email list. The user will then continuously receive relevant information. 

### Footer

The footer section contains links to Facebook, Twitter, Youtube, and Instagram. The users can connect to and learn more about the company. 


# Testing

To test my website, I have done the following:

- Links in navigation menu lead to the correct sections.

- Navigation items change colors during hover.

- Social media links in footer lead to the relevant pages, and each link open in a new browser.

- The videos can be played and expanded. 

- In the form, clicking the submit button does not work unless name and email has been entered. 

- The parallax scrolling effect in the main section works. The background spring image is fixed, while the base sections move. As a result of the parallax scrolling, there are two scroll bars on the page. I have tried hiding the parallax scroll-bar, however that had affected the websie scrolling. The extra scrollbar works well, without having a negative impact on the user experience. 

- Media queries for several screen sizes were included. Most challenging was aligning the two videos horisontally. I was unable to keep the descriptions below each video for the smaller screen sizes. However, each video contain some descriptory text which would still give users a hint of what the videos are about. 

### HTML5 validation

After testing with W3C validator, several errors were found. They are connected to the videos onto the page. Because I used videos embedded from Youtube I did not use the video element but rather the iframe element which was provided. The attributes used in the iframe elements might not be as suitable as they would've been in the video element, which would lead to errors. 

### CSS3 validation

No errors were found during validation of the CSS using jigsaw validator.

# Deployment

- ### The site was deployed to GitHub pages. The steps to deploy are as follows:
* In the GitHub repository, navigate to the Settings tab
* From the source section drop-down menu, select the Master Branch
* Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The finished website can be found here: 


# Credits

### Media

The meditation videos are from youtube.com. 

The images are from pixabay.com. 

The icons are from fontawesome.com.

### Code

The parallax scrolling effect are from css-tricks.com. Link: https://css-tricks.com/pure-css-parallax-scrolling-websites/

To center text in an image, code from w3schools.com was used. Link: https://www.w3schools.com/howto/howto_css_image_text.asp
