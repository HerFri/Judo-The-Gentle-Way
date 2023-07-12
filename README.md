# Judo-The-Gentle-Way
Visit the live page [here](https://herfri.github.io/Judo-The-Gentle-Way/)

Judo - The Gentle Way is an informational website providing a short overview of the martial arts of judo, its history and core philosophy. The website aims at presenting judo as a wholesome sport, making guests of the website curious about it and motivating potential starters to try it themselves. Therefore, guests of the website are encouraged to contact the website owner to receive additional information about judo and finding a fitting club in their region.
 
![mockup](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/mockup.PNG?raw=true)

The mockup image has been generated on [https://ui.dev/amiresponsive](https://ui.dev/amiresponsive)


# User Experience
## User Stories
* As a user, I want to get to know about judo and its history and core philosophy.
* As a user, I want to find easy understandable and well structured information on the website.
* As a user, I want to find clear navigation that leads me to the different sections of the website.
* As a user, I want to see detailed and well assorted media like pictures or a video that illustrate the way how judo works and how it looks like, when people are practicing judo.
* As a user, I want to be able to access the website from different devices like PC, mobile devices and tablets.
* As a user, I want to have the opportunity to get in contact with the website owner to receive additional information about judo and where I can practice it.

# Design
## Colors
For the color theme I chose the colors black(#000000) and white (#FFFFFF) for specific reasons. First, the black font on the white background contrasts very clearly, so there should be no difficulties to read text. This also holds true for the pictures of the black belt and the judo calligraphy in the welcome section, as these are also in black. Moreover, in combination with the black belt image, the white background represents the color of the 'judogi', which is the term for the white suit people wear when practicing judo. Additionally, the white background flows into each other with the white background of the Japanese flag, which is the hero image in the header section.

![colorpalette](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/colorpalette.PNG?raw=true)

The colorpalette above has been generated with [coolors.co](https://coolors.co/user/palettes/64add1736ab1ee000bab1832)

For the social network icons in the footer, these colors have been used:
* Facebook: HEX #2e68cc
* Instagram: HEX #000000
* YouTube: HEX #fa0000

## Fonts
As for the fonts, I imported two fonts, namely
* 'Samurai'-font from [fontget.com](https://www.fontget.com/font/samurai-warrior/)
* 'Shadow'-font from [Google Fonts](https://fonts.google.com/specimen/Shadows+Into+Light?preview.text=Judo%20is%20one%20of%20the%20most%20practised%20psorts%20in%20ur%20anus&preview.text_type=custom)

The 'Samurai'-font is being used for the headline 'Judo - The Gentle Way' in the header section, representing the lettering that has been drawn with a brush and black ink, which is typical for Japanese calligraphy. Moreover, it is being used for the `<li>`-elements of the navbar, the `<h1>`-elements in the sections and in the contact-form for the labels.

The 'Shadow'-font has been used for the rest of the text in the `<body>`. Its font style resembles handwritten text with black ink.


# Structure
## Wireframes
For the structural planning of my website, I created some wireframes using the wireframe software [Balsamiq](https://balsamiq.com/).

The website has 4 core sections, namely Welcome section, History Section, Philosophy Section and Contact Section. Additionally, the website is linked to a confirmation page, which opens a new tab and leads the user to the conformation page after filling out the textinputs and pressing the submit button of the contact form.

Here are the wireframes, including both the desktop and mobile view for each page:

* [Desktop wireframe of index page](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/wireframes/wholepagewf.png?raw=true)
* [Desktop wireframe of confirmation page](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/wireframes/confirmationwf.png?raw=true)
* [Mobile view wireframe of index page](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/wireframes/mobilewf.png?raw=true)
* [Mobile view wireframe of confirmation](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/wireframes/confirmationmobilewf.png?raw=true)


# Features
## Header with Hero Image
In the header area of the website, the user will find the hero image, which is the Japanese flag. In the middle of the Japanese flag is the red circle of the sun, on which the headline and title of the website, 'Judo - The Gentle Way', is positioned on. The hero image can be found on the same position in all pages of the website.
![heroimage](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/heroheader.PNG?raw=true)

## Navigation Bar
The navigation bar is located under the hero image and allows by clicking on one of the navigation elements navigation to the desired section of the website. By adding the `scroll-behavior: smooth;` CSS rule, smooth scrolling is provided. By hovering the cursor over one of the navigation bar elements, the respective element is highlighted by an underline.
![navbar1](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/navhis.png?raw=true)
![navbar2](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/navphil.png?raw=true)
![navbar3](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/navcontact.png?raw=true)


## Welcome Section
The welcome section consists of a centered textbox that is surrounded by images of a black belt on the left side and a image of Japanese calligraphy of the term 'judo' on the right side. Under these images are lines of text explaining the meaning of the images. The centered textbox comprises a text which welcomes guests of the website and states the purpose of the website. Moreover, the text comprises a short overview about the contents and encourages guests of the website to reach out to the website owner for further information by filling out a contact form.
![welcomesection](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/welcomesection.PNG?raw=true)

The text inside the textbox comprises three `<a>`-elements to establish hyperlinks to the different sections below for a quick navigation.

![hyperlinkhistory](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/hyperlinkhis.PNG?raw=true)
![hyperlinkphilosophy](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/hyperlinkphil.PNG?raw=true)
![hyperlinkcontact](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/hyperlinkcontact.PNG?raw=true)

## History Section
The history section consists of an image of the founder of judo next to a textbox including information about the history of judo.
![historysection](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/historysection.PNG?raw=true)

## Philosophy Section
The philosophy section consists of images next to informational textboxes. The first image is aligned on the right side, showing shaking hands to illustrate the key value respect in judo. Next to it on the left side is a textbox providing information about the key values and philosophy of judo. Under this textbox, aligned on the left side, is an image of fighting judokas, which is the term of people practicing judo. Next to this image, aligned on the right side, is a textbox providing information about the rules of judo fights in tournaments. On smaller screen devices, like mobile phones, these elements are aligned under each other.
![philosectionhand](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/philohand.PNG?raw=true)
![philosectionrandori](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/philorandori.PNG?raw=true)
Under the previously described elements is an embedded YouTube video with a quick guide to judo. Over the video is a short textfield which informs the user that the video is a quick guide to judo.
![video](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/video.PNG?raw=true)

## Contact Section
In the contact section the user will find a contact-form, which can be filled in with personal information and submitted for additional information that the website owner can send to the user afterwards. Note, however, that the actual information submitted in the form will not be forwarded, as there is no backend service connected to the website, because this is not in the scope of this project. The form comprises input types of text, date, email and a `<select>`-element, to choose up to three options. By adding the `<required>`-attribute, the user has to fill out the input-elements according to the type and has to choose an option, otherwise, by clicking the submit button at the very bottom, a pop-up will inform the user that some information has been not been filled in correctly or no option has been chosen.
![contactsection](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/contactform.PNG?raw=true)

Once the user has filled in all information correctly and submitted, a new tab will open, leading the user to a confirmation page that has the same header and footer as the Home-page. Under the header, the text of the textbox will inform the user that the information have been submitted successfully and that the user will be contacted as soon as possible.
![confirmationpage](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/confirmationpage.PNG?raw=true)

For marking the end of a section, all sections are divided by a `<hr>`-element.

## Footer
The footer comprises three clickable icons for the social network Facebook, Instagram and YouTube. By clicking the icons, a new tab is opened which leads the user to the respective social network.
The icon designs are imported from [Font Awesome](https://fontawesome.com/).

![footer](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/footer.PNG?raw=true)


# Future features
As a future feature a service could be implemented that automatically sends a newsletter or other additional information via email to the user, if the option in the contact-form has been submitted to receive additional information.

# Accessibility
For good accessibility `<arial-label>` and `alt`-attributes have been added to elements like links and images that do not provide sufficient information to support assistive technologies like screenreaders.

# Technologies Used
Following technologies have been used for building my website:

* HTML
* CSS
* JavaScript (one script to import icons from [Font Awesome](https://fontawesome.com/))
* GitHub
* GitHub Pages
* Visual Studio Code

# Testing
## Code Validation
The website has been tested with the W3C Validator and Jigsaw Validator 
* The W3C Validator test passed with no errors. [Test here](https://validator.w3.org/nu/?doc=https%3A%2F%2Fherfri.github.io%2FJudo-The-Gentle-Way%2F)
* The Jigsaw Validator test passed with no errors. [Test here](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fherfri.github.io%2FJudo-The-Gentle-Way%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=de)

## Performance Test
To test the performance of the website the Google Lighthouse test was used and showed good results:
![googlelighthouseresult](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/performance.JPG?raw=true)

## Responsiveness
To test responsiveness, I used the website [AmIresponsive](https://ui.dev/amiresponsive?url=https://herfri.github.io/Judo-The-Gentle-Way/) that generated the [mockup image](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/mockup.PNG?raw=true) and showed that my website was responsive on different devices.
Moreover, I used Chrome (Version 114.0.5735.199) Developer Tools to simulate viewports of different devices, which showed that my website was fully responsive:
![galaxyfoldvw](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/galaxyfoldvw.PNG?raw=true)
![iphone6vw](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/iphone6vw.PNG?raw=true)
![ipadairvw](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/ipadairvw.PNG?raw=true)

## Browser Testing

I tested the layout and appearance of my website for consistency on different browsers.
Moreover, I tested if the navigation, all links, form submission and video works on different browser. 

Tested browser: Chrome (Version 114.0.5735.199), Firefox, Safari, Edge

Result: Layout and all functions work throughout the tested browsers.

## Manual Testing

| Feature         | Expect                                                          | Action                    | Result                                          |   
|-----------------|-----------------------------------------------------------------|---------------------------|-------------------------------------------------|
| Navbar buttons  | When clicked the website scrolls down to the respective section | Clicked on Navbar buttons | Website scrolled down to the respective section |   |
| Text Hyperlinks | When clicked the website scrolls down to the respective section | Clicked on Hyperlinks     | Website scrolled down to the respective section |   |
| Embedded Video  | When play button clicked the video starts to play               | Clicked play button of video | Video started to play                           |
| Contact-Form Input-fields     | When clicked a textcursor appears and user can type in information                                                        | Clicked input fields                                          | Textcursor appeared, user can type in information                  |
| Submit button of contact-form | When input field have been filled in correctly and button is clicked, a new tab opens and leads user to confirmation page | Clicked submit button after filling in input fields correctly | New tab opens and shows confirmation page                          |
| Social networks buttons       | When clicked a new tab opens and leads user to respective social networks website                                         | Clicked Social networks buttons                               | New tab opens and leads user to respective Social networks website |


## Testing User Stories

| Expectation                                                                                        | Result                                                                                                                                                                                                                                   |
|----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| As a user, I want to get to know about judo and its history and core philosophy.                   | As a user, I find sufficient information about judo and its history and core philosophy.                                                                                                                                                 |
| As a user, I want to find easy understandable and well structured information on the website.      | As a user, I find texts that are easy to understand and the information is very well structured on the website.                                                                                                                          |
| As a user, I want to find clear navigation that leads me to the different sections of the website. | As a user, I can find the navigation bar very easily that leads me to the different sections of the website. Also, I can identify the hyperlinks in the welcome text, which lead me to the desired section of the website, very easily.  |
| As a user, I want to see detailed and well assorted media like pictures or a video that illustrate the way how judo works and how it looks like, when people are practicing judo. | As a user, I can view a good amount of pictures and a video about the practice of judo, which illustrate very well, how judo works.                            |
| As a user, I want to be able to access the website from different devices like PC, mobile devices and tablets.                                                                    | As a user, thanks to the responsive design of the website, I am able to access the website with different devices, such as PC, mobile devices and tablets.     |
| As a user, I want to have the opportunity to get in contact with the website owner to receive additional information about judo and where I can practice it.                      | As a user, I can use the contact-form of the website to contact the website owner for receiving additional information about judo and where I can practice it. |
|                                                                                                                                                                                   |                                                                                                                                                                |

## Fixed Bugs

In the Firefox browser one image was stretched in both desktop and mobile view.
![bug](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/jigorobug.PNG?raw=true)

I fixed it by setting `width: auto;` and `max-width: 40%,` in the style.css file.
![fixview](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/jigorofix.PNG?raw=true)
![fixcode](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/codefix.PNG?raw=true)

# Deployment

This website was deployed via GitHub pages. The steps to do that are as follows:
1. Go to the GitHub repository and click on 'Settings'.
2. On the left side click on 'Pages'.
3. In the 'Build and deployment' section find 'Source', click the dropdown menu and click 'Deploy from a branch'.
4. Change to main branch.
5. After saving, the website should go live after some minutes. From now on, after every undertaken Git push, the website will automatically refresh.

The link to the live site is: https://herfri.github.io/Judo-The-Gentle-Way/

To run locally, two options are possible:
1. In the GitHub repository, click the button 'Code', copy the HTTPS adress (https://github.com/HerFri/Judo-The-Gentle-Way.git) and use git clone followed by the HTTPS adress.
2. Or: Go to the GitHub repository, click the button 'Code', click 'Download the Zip file'. Once downloaded, extract the Zip file and use in your local IDE.

# Credits

## Contents
The information provided in the website is taken from [Wikipedia](https://en.wikipedia.org/wiki/Kan%C5%8D_Jigor%C5%8D) and from own knowledge.

## Media
Images:
[Black Belt](https://www.freepik.com/premium-vector/black-belt-logo-vector-karate-taekwondo-jiujitsu-judo_36330575.htm)
[Judo Calligraphy](https://commons.wikimedia.org/wiki/File:Judo.svg)
[Jigoro Kano](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3b/Jigoro-Kano-BW-4375px.jpg/1200px-Jigoro-Kano-BW-4375px.jpg)
[Japan Flag](https://www.rawpixel.com/image/396840/free-illustration-vector-japan-flag-japanese-tokyo)
[Randori](https://www.pexels.com/de-de/foto/menschen-manner-sport-kampf-6765037/)
[Handshake](https://creativemarket.com/product/14773664-Handshake-respect-and-discipline-with-mma-karate-and-fight-students-shaking-hands-before-a-match-or-combat-sport-in-a-training)

Video:
[Quick Guide to Judo](https://www.youtube.com/watch?v=pgfKasoI5yc&ab_channel=Judo)

All media was used for educational purposes only.

## Code 
[Responsive iframe](https://www.w3schools.com/howto/howto_css_responsive_iframes.asp)
[Smooth Scroll](https://www.w3schools.com/howto/howto_css_smooth_scroll.asp#section1)

# Acknowledgements
I want to thank the Slack community and the tutors of Code Institute for their very helpful support and valuable criticism!