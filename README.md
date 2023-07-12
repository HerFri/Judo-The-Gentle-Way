# Judo-The-Gentle-Way
Visit the live page [here](https://herfri.github.io/Judo-The-Gentle-Way/)

Judo - The Gentle Way is an informational website providing a short overview of the martial arts of judo, its history and core philosophy. The website aims at presenting judo as a wholesome sport, making guests of the website curious about it and motivating potential starters to try it themselves. Therefore, guests of the website are encouraged to contact the website owner to receive additional information about judo and finding a fitting club in their region.
 
![mockup](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/mockup.PNG?raw=true)

The mockup image has been generated on [https://ui.dev/amiresponsive](https://ui.dev/amiresponsive)


# User Experience
## User Stories
* As a user, I want to get to know about judo and its history and core philosophy.
* As a user, I want to find easy understandable and well structured information on the website.
* As a user, I want to find clear navigation that leads me to the different sections of the website
* As a user, I want to see detailed and well assorted media like pictures or a video that illustrate the way how judo works and how it looks like, when people are practicing judo.
* As a user, I want to be able to access the website from different devices like PC, mobile devices and tablets.
* As a user, I want to have the opportunity to get in contact with the website owner to receive additional information about judo and where I can practice it.

# Design
## Colors
For the color theme I chose the colors black(#000000) and white (#FFFFFF) for specific reasons. First, the black font on the white background contrasts very clearly, so there should be no difficulties to read text. This also holds true for the pictures of the black belt and the judo calligraphy in the welcome section, as these are also in black. Moreover, in combination with the black belt image, the white background represents the color of the 'judogi', which is the term for the white suit people wear when practicing judo. Additionally, the white background flows into each other with the white background of the Japanese flag, which is the hero image in the header section.

![colorpalette](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/colorpalette.PNG?raw=true)

The colorpalette above has been generated with [coolors.co](https://coolors.co/user/palettes/64add1736ab1ee000bab1832)

## Fonts
As for the fonts, I imported two fonts, namely
* 'Samurai'-font from [fontget.com](https://www.fontget.com/font/samurai-warrior/)
* 'Shadow'-font from [Google Fonts](https://fonts.google.com/specimen/Shadows+Into+Light?preview.text=Judo%20is%20one%20of%20the%20most%20practised%20psorts%20in%20ur%20anus&preview.text_type=custom)

The 'Samurai'-font is being used for the headline 'Judo - The Gentle Way' in the header section, representing the lettering that has been drawn with a brush and black ink, which is typical for Japanese calligraphy. Moreover, it is being used for the li-elements of the navbar, the `<h1>`-elements in the sections and in the contact-form for the labels.

The 'Shadow'-font has been used for the rest of the text in the body. Its font style resembles handwritten text with black ink.


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

## Navigation bar
The navigation bar is located under the hero image and allows by clicking on the title of the respective section navigation to the desired section. By adding the `scroll-behavior: smooth;` CSS rule, smooth scrolling is provided. By hovering the cursor over one of the navigation bar elements, the respective element is highlighted by an underline.
![navbar1](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/nav1.png?raw=true)
![navbar2](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/nav2.png?raw=true)
![navbar3](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/nav3.png?raw=true)


## Welcome section
The welcome section consists of a centered textbox that is surrounded by images of a black belt on the left side and a image of Japanese calligraphy of the term 'judo' on the right side. Under these images are lines of text explaining the meaning of the images. The centered textbox comprises a text which welcomes guests of the website and states the purpose of the website. Morover, the text comprises a short overview about the contents and encourages guests of the website to reach out to the website owner for further information by filling out a contact form.
![welcomesection](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/welcomesection.PNG?raw=true)

The text inside the textbox comprises three <a>
-elements to establish hyperlinks to the different sections below for a quick navigation.

![hyperlinkhistory](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/hyperlinkhis.PNG?raw=true)
![hyperlinkphilosophy](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/hyperlinkphil.PNG?raw=true)
![hyperlinkcontact](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/hyperlinkcontact.PNG?raw=true)

For marking the end of a section, all sections are divided by a `<hr>`-element.

## History section
The history section consists of an image of the founder of judo next to a textbox including information about the history of judo.
![historysection](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/historysection.PNG?raw=true)

## Philosophy section
The philosophy section consists of images next to informational textboxes. The first image is aligned on the rigt side, showing shaking hands to illustrate the key value respect in judo. Next to it on the left side is a textbox providing information about the key values and philosophy of judo. Under this textbox, aligned on the left side is a image of fighting judokas, which is the term of people practicing judo. Next to this image, aligned on the right side, is a textbox providing information about the rules of judo fights in tournaments. On smaller screen devices, like mobile phones, these elemements are aligned under each other.
![philosection1](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/philosection.PNG?raw=true)
![philosection2](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/philosection2.PNG?raw=true)
Under the previously described elements is an embedded youtube video with a quick guide to judo. Over the video is a short textfield which informs the user that the video is a quick guide to judo.
![video]()

## Contact section
In the contact section the user will find a contact-form, which can be filled in with the personal information and submitted for additional information that the website owner can send to the user afterwards. Note however that the actual information submitted in the form will not be forwarded, as it is not in the scope of this project. The form comprises input types of text, date, email and a <select>-element, to choose up to three options. By adding the <required>-attribute, the user has to fill out the input-elements according to the type and has to choose an option, otherwise, by clicking the submit button at the very bottom, a pop-up will inform the user that some information has been not been filled in correctly or no option has been chosen.
![contactsection](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/contactform.PNG?raw=true)

Once the user has filled in all information correctly and submitted, a new tab will open, leading the user to a confirmation page that has the same header and footer as the index page. Under the header, the text of the textbox will inform the user that the information have been submitted successfully and that the user will be contacted as soon as possible.
![confirmationpage](https://github.com/HerFri/Judo-The-Gentle-Way/blob/main/readmeimages/confirmationpage.PNG?raw=true)