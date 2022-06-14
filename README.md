# Ascend Yorkshire

## Author
Alexander Ward

## Project Overview

Ascend Yorkshire is a website aimed to enlighten people of all ages interested in walking with new places to explore in the Yorkshire Dales. Pages provide essential information such as places to stay, distance and average time of each walk. Events are displayed clearly to help people group up and engage in a social walk. Sign up to be notified by email or text message about upcoming events.

Ascend Yorkshire can be found at the following link: https://alexanderjward.github.io/ascend-yorkshire/

![image](https://user-images.githubusercontent.com/102811792/172921918-c6764198-c85f-45ba-9e4a-c0a7ebb435c9.png)

## Table of Contents

- [Ascend Yorkshire](#ascend-yorkshire)
  * [Author](#author)
  * [Project Overview](#project-overview)
  * [Table of Contents](#table-of-contents)
  * [UX](#ux)
    + [Project Goals](#project-goals)
    + [Design Choices](#design-choices)
      - [Colors](#colors)
      - [Typography](#typography)
      - [Images](#images)
      - [Animations and Transitions](#animations-and-transitions)
    + [Wireframes](#wireframes)
    + [Features](#features)
      - [Implemented Features](#implemented-features)
      - [Future Features](#future-features)
  * [Testing](#testing)
    + [Validation Testing](#validation-testing)
    + [Cross Browser and Cross Device Testing](#cross-browser-and-cross-device-testing)
    + [Manual Testing](#manual-testing)
    + [Defect Tracking](#defect-tracking)
    + [Defects of Note](#defects-of-note)
    + [Outstanding Defects](#outstanding-defects)
  * [Accessibility](#accessibility)
    + [Lighthouse Audits](#lighthouse-audits)
    + [Keyboard Navigation](#keyboard-navigation)
  * [Deployment](#deployment)
  * [Credits](#credits)
    + [Content](#content)
    + [Media](#media)
    + [Acknowledgments](#acknowledgments)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## UX

### Project Goals

The website is for people of all ages interested in walking in the countryside, the aim is to introduce people to what kind of walks are avaliable in the Yorkshire Dales and to make it as accessible as possible by providing information on a variety of essential topics. By showing events and letting users sign up to be notified brings like minded people together for walks they might have otherwise undertaken alone. There is also a challenge for more experienced hikers on offer with information on distance and average completion time avaliable.

### Design Choices

#### Colors

I've picked earthy colors that work well together to match my Ascend Yorkshire theme due to it being a website focused on the outdoors. The main color is a nice dark olive green/brown which I'm using alongside a white with very light green tones. There's also a complimentary dark green background being used throughout for some sections. I've also picked a bright white and rich black to potentially use to replace potential low contrast issues if they arise. I've tested multiple combinations of my colors in a contrast accessibility website, https://webaim.org/resources/contrastchecker/, to ensure my website is readable by people with visual impairment.

- #37371F - Olive Drab
- #F4FFF8 - Mint Cream
- #1F371F - Phthalo Green
- #F8F8F8 - Cultured (Possible contrast replacement)
- #0F1A20 - Rich Black (Possible contrast replacement)

![image](https://user-images.githubusercontent.com/102811792/172001155-349c1aae-9aa5-489a-a212-060f53978eac.png)

Below are my color contrast tests on WebAIM:

![image](https://user-images.githubusercontent.com/102811792/169293422-8e36411b-7468-44c2-85c5-164761951ce8.png)

![image](https://user-images.githubusercontent.com/102811792/169293279-b391790b-3ced-4339-84d4-651b5a85c075.png)

![image](https://user-images.githubusercontent.com/102811792/169846135-672f0428-81f8-4c5c-ab8f-e8ff0ef1dde7.png)


#### Typography

For my title font I've chosen __Skranji__ as it looks very rugged and outdoorsy, fitting for the theme of my hiking website. Some of the letters look primative and can be pictured as part of a rock formation on a mountainside which I really think invokes the theme of Ascend Yorkshire. I'll mainly be using regular 400 but I've included bold 700 incase I decide to go with this instead.
The link to the Google font is here: https://fonts.google.com/specimen/Skranji

![image](https://user-images.githubusercontent.com/102811792/169257661-e34d4356-d1fc-4b2f-9488-e759eae2b274.png)

My secondary font is __Tillana__ which I picked as it's in keeping with the theme of my title font and I think compliments it nicely. The edges aren't perfectly straight in places which makes it look rugged, this is why I think it's fitting with my title choice. I've chosen medium 500 as it's a nice balance between thick and thin, I've also picked bold 700 for any bold paragraph text that'll be needed throughout. The link to the Google font is here: https://fonts.google.com/specimen/Tillana

![image](https://user-images.githubusercontent.com/102811792/169259069-971dfd76-e980-4800-8a45-0caa79b8ecb7.png)

#### Images

I've created a simple logo in keeping with the theme of Ascend Yorkshire that I think works well and is easily recognisable as a mountain range using the A from the website name. The logo is used both in the header and footer of Ascend Yorkshire on all pages.

![image](https://user-images.githubusercontent.com/102811792/172003605-2e0fbbd1-e56a-4496-96e0-8780dd06d099.png)
![image](https://user-images.githubusercontent.com/102811792/172003621-8265f53f-8868-4434-b180-591da0bd86d6.png)

Images of the three peaks are used in the welcome section to show people what kind of walks to expect before even reading any text or scrolling down. The images are attributed in the code and included further down in the README using the Creative Commons License.

![image](https://user-images.githubusercontent.com/102811792/172003646-181fc249-102a-40ba-8246-4fa564ad8fbc.png)

Background images of all four hotels in the accommodation section are placed behind the text giving users a brief glimpse before visiting the site. Images are sourced directly from booking.com.

![image](https://user-images.githubusercontent.com/102811792/172003724-30da8f59-043b-48db-a986-5aacbfbfd951.png)

I used a generic image of parked cars giving the section something to break up paragraphs of text. The image used is a Creative Commons License and is attributed in the code and below in the README.

![image](https://user-images.githubusercontent.com/102811792/172004391-f429af27-ba05-40ea-87d3-fbc5fa7aa6dc.png)

The walks page and three peaks challenge page contain images of Google Maps routes for visitors to reference if needed when on the related walk.

![image](https://user-images.githubusercontent.com/102811792/172941408-c1451037-80db-4f93-8f77-0ee8dfccc85e.png)

Events page contains an eye catching image under the form and upcoming events to bring the page to life with color and showing aspects of what to expect when walking in the area.

![image](https://user-images.githubusercontent.com/102811792/172941982-301e2dc2-317e-4cdd-86c5-9f037d54b969.png)


#### Animations and Transitions

Hero image animation which transitions the image from bottom left to top right. Ascending slowly over 30 seconds.
![image](https://user-images.githubusercontent.com/102811792/172005547-f3715790-f90a-4a62-a70d-5c9c3b8d4292.png)

![image](https://user-images.githubusercontent.com/102811792/172005572-0168ba07-1d85-4d90-b254-2c7e5f35302e.png)

This changes on smaller screen sizes 650px and under to go from center bottom to center top as the previous animation was moving too quickly on the smaller screen.

![image](https://user-images.githubusercontent.com/102811792/172005689-ff46a50e-dffa-4c2d-8ca1-ff34bea51dfa.png)

![image](https://user-images.githubusercontent.com/102811792/172005707-90a0a7a5-a400-4947-b0b2-426d0e27d3fa.png)

Hover effect on navigation links to invert the colours.

![image](https://user-images.githubusercontent.com/102811792/172006392-6ad5287c-bee3-464b-a458-4c0e1c48821b.png)

![image](https://user-images.githubusercontent.com/102811792/172006411-1d1fb669-fadd-44d3-8a24-4c8424811e74.png)

Hover effect on the accommodation text to change opacity of background to make text more readable.

![image](https://user-images.githubusercontent.com/102811792/172006479-353e4cf9-a72d-4289-993b-d2e70ed96b4f.png)

![image](https://user-images.githubusercontent.com/102811792/172006506-89878839-549e-4f2c-810b-63f35f6ee1a6.png)

Hover effect on the three peaks challenge link to make it underlined.

![image](https://user-images.githubusercontent.com/102811792/172006660-46a879c0-256b-4bc0-ab7a-3b9cf6fd14e6.png)

![image](https://user-images.githubusercontent.com/102811792/172006704-94554493-6192-4855-b86a-2fd5806e267b.png)

Hover effect on reset button and submit button of form to visually show they can be interacted. Reset button has different color scheme to make it differ from the submit.

![image](https://user-images.githubusercontent.com/102811792/173548370-40705cb3-77e1-4ca9-b61e-354e926e09e9.png)

![image](https://user-images.githubusercontent.com/102811792/173548425-754f5f5b-97c2-483a-9b41-d6ac466cb761.png)


### Wireframes

Wireframe created in Balsamiq and exported as PDF:

[Ascend-Yorkshire-Wireframe.pdf](https://github.com/AlexanderJWard/ascend-yorkshire/files/8823256/Ascend-Yorkshire-Wireframe.pdf)

### Features

#### Implemented Features

- __Navigation bar__

The nav bar is featured at the top of all pages and contains the logo, title and links to the home page, walks page and events page. This bar is the exact same on all pages and changes on smaller screen sizes for a better viewing experience.

![image](https://user-images.githubusercontent.com/102811792/172923695-b0e6c800-cc7e-4889-a9c8-0da2b2dcb665.png)

![image](https://user-images.githubusercontent.com/102811792/172923774-5c426b46-9672-453a-a8a5-86306a601d38.png)

- __Hero Image__

The hero image is a photograph capturing the breathtaking views that can be experienced on these walks. It's placed right at the top so any visitor to the website will see this image first and get a feel for what they can expect from walks in the Yorkshire Dales.

![image](https://user-images.githubusercontent.com/102811792/172924643-9b935241-7a97-4a17-a126-6a52b8c16a5e.png)

- __Welcome Section__

This section gives visitors a quick taste of each of the Three Peaks and some reasons why to visit the area. This gives visitors the confidence that the area is popular and there are plenty of places to stay overnight if required. Mobile screen size changes adjacent paragraphs and images into a column format.

![image](https://user-images.githubusercontent.com/102811792/172925987-c99df30e-1606-4e3a-87f3-a2aef6c788cd.png)

- __Accommodation Section__

Useful information for visitors looking for a longer stay in the region. Showing a few examples of hotels to stay for both small and large groups. The background image shows a brief look at the outside of each hotel so visitors can judge straight away if it's somewhere suitable. On mobile the text box fills more of the screen to be easily readable on small screen sizes.

![image](https://user-images.githubusercontent.com/102811792/172926761-87d33934-9c32-4924-831d-0a9dff511b77.png)

- __Other Information__

Giving visitors useful extra information including where to park, places to grab food or drink when walking and toilet locations to give peace of mind for first time visitors to the area. Just like the welcome section on mobile the paragraphs are changed into a column format on the smaller screen sizes.

![image](https://user-images.githubusercontent.com/102811792/172927762-301ae039-af33-495d-8b76-6db301e3a576.png)

- __Google Map__

Just before the footer there is an interactive Google Maps showing the main village of Horton in Ribblesdale to not only inform where in the UK the walks are but also an easy way to get directions straight there.

![image](https://user-images.githubusercontent.com/102811792/172928210-ae14ecfb-625a-42c7-ab8a-9b751c97c837.png)

- __Footer__

The footer includes the Ascend Yorkshire logo as well as social media links for Twitter, Youtube, Instagram and Youtube. This allows visitors quick access to chosen social media site to view pictures of the area and learn of new events taking place. Footer is on all pages and increases the size and reduces the gap on smaller screen sizes to make links easier to click or tap.

![image](https://user-images.githubusercontent.com/102811792/172928743-be383c02-3294-437b-911d-f95efdcbe018.png)

![image](https://user-images.githubusercontent.com/102811792/172928800-0534ba5a-819a-4356-bb44-21c15dd2e24a.png)

- __Walks Page__

This page contains a selection of walks in the Yorkshire Dales and includes a map of the route from Google Maps and also some relevant information including distance and average time of completion. Information and images changes to a column format on smaller screen sizes including mobile and tablet.

![image](https://user-images.githubusercontent.com/102811792/172934647-9ea4a566-66e3-4f24-b1c7-3db8252632b1.png)

- __Weather Widgit__

The weather widgit gives visitors an immediate visual clue to what the weather is going to be like over the next week in Horton in Ribblesdale. Saves the visitor time from having to research this elsewhere before making a decision on a date to visit. The widgit wraps to look presentable on any screen size.

![image](https://user-images.githubusercontent.com/102811792/172935204-c668b02f-130f-4eaa-b557-0cc376802fb3.png)

- __Three Peaks Challenge Page__

Similar to the walks page this one focuses on the extreme challenge of all three peaks in one go. There is listed information such as distance and average time just like the individual walks however this page features close up stages of the route shown in Google Maps images. Like the walks page the content shifts into a column for mobile and tablet.

![image](https://user-images.githubusercontent.com/102811792/172936077-07b94e9b-f863-4fb0-9b37-f7254dca2d70.png)

![image](https://user-images.githubusercontent.com/102811792/172936034-09fa9043-5e28-44ff-9e05-5b713bc9ffd1.png)

- __Events Page__

There is a form where visitors can sign up to get notifications of upcoming events by email and or mobile phone SMS. The events themselves are displayed in individual boxes, each showing differnt organised events at different peaks during different days and times. Also there are special events which are unique such as three peaks challenge, time trial fel runs or charity fundraising. Finally the page has another awe inspiring image from the Yorkshire Dales to keep the page attractive even if seen in the visitors peripheral vision. On small screen sizes everything is put into a column and the events are displayed first followed by the sign up form and lastly the image.

![image](https://user-images.githubusercontent.com/102811792/172937405-623f194a-0989-49e1-b11d-7e4fd1f7fd41.png)

- __Thank You Page__

The thank you page is displayed when submitting the form to acknowledge the data has been sent, the visitor then knows this has been submitted and is not left guessing after clicking submit. This page also contains the header and footer to keep within the theme of the website and keep things familiar.

![image](https://user-images.githubusercontent.com/102811792/172940085-de8d8b7a-85a3-499e-bc18-2594edc2c649.png)

- __404 Page__

When the 404 page is displayed there is the same header and footer to keep consistant with all other pages. There is also a link to click to return to the home page of Ascend Yorkshire as well as an image from one of the peaks to reassure visitors this is related to the actual website.

![image](https://user-images.githubusercontent.com/102811792/172939180-4007be3c-1cdb-4d50-933f-8bec8185fd67.png)



#### Future Features

- Events page contains a scrolling calendar of all future events that can be scrolled left or right.

- Gallery of photos taken by people taking part in group events.

## Testing

### Validation Testing

HTML Validation from validator.w3.org

- __Home Page__

![image](https://user-images.githubusercontent.com/102811792/172944566-4d52e15e-661e-41c1-8251-dfbc3c430b66.png)

- __Walks Page__

![image](https://user-images.githubusercontent.com/102811792/172945766-9bea22a1-b90a-4ef8-8f61-6561773f338f.png)

- __Three Peaks Challenge Page__

![image](https://user-images.githubusercontent.com/102811792/172945864-a3ecd477-a1ba-4a09-aac6-8161f3944c42.png)

- __Events Page__

![image](https://user-images.githubusercontent.com/102811792/172947178-84149aa4-5486-43a5-81b5-d7c5c16b379f.png)

- __Thank You Page__

![image](https://user-images.githubusercontent.com/102811792/172947431-e16b62d9-0b50-41e9-a97b-6f8915286610.png)

- __404 Page__

![image](https://user-images.githubusercontent.com/102811792/172948231-7e635c0f-790d-4397-b478-77721c4bfb68.png)

CSS Validation from jigsaw.w3.org/css-validator/validator#css

- __Home Page__

![image](https://user-images.githubusercontent.com/102811792/173060236-cb7653c1-8e15-49c2-b051-9d520e1bd6ec.png)

![image](https://user-images.githubusercontent.com/102811792/173060285-de319c7f-ad12-4409-8137-5a0ebe3ad5e4.png)

- __404 Page__

![image](https://user-images.githubusercontent.com/102811792/173061306-8e4161e3-e831-4a54-9754-1241b9db4d76.png)

![image](https://user-images.githubusercontent.com/102811792/173061387-22b70dfb-b995-4e21-b722-b17fbff56b0f.png)

### Cross Browser and Cross Device Testing

| Device                              | Browser        | OS                    | Viewpoint   |
|-------------------------------------|----------------|-----------------------|-------------|
| Real laptop: Dynabook Satellite Pro | Microsoft Edge | Windows 11            | 1536 x 864  |
| Real phone: One Plus 7 Pro          | Google Chrome  | Android v11 Oxygen OS | 385 x 833   |
| Real laptop: HP 250 G7              | Google Chrome  | Windows 10            | 1306 x 864  |
| Emulation: Samsung Galaxy S8+       | Microsoft Edge | Windows 11            | 360 x 740   |
| Emulation: iPad Air                 | Microsoft Edge | Windows 11            | 1180 x 820  |
| Real desktop: Custom build          | Firefox        | Windows 10            | 2560 x 1440 |
| Real laptop: Microsoft Surface      | Google Chrome  | Windows 11            | 1280 x 720  |
| Emulation: iPad Mini                | Microsoft Edge | Windows 11            | 768 x 1024  |

### Manual Testing

__Google Doc Functionality Tests__

https://docs.google.com/spreadsheets/d/1ILO_Xfr7EwPuTWrMtrI-bIaQxpAzeNlQJ8k3SQowKhc/edit?usp=sharing

__Manual Testing For Upcoming Events Form__

Steps to test the form validation on the events page.

- [x] Attempt to submit form with all fields empty and verify message appears asking to fill in fields
- [x] Attempt to submit form with an invalid email address and verify message appaears asking to enter correct format
- [x] Attempt to submit form with no gender radio button selected and verify message asking to choose one
- [x] Attempt to submit form with all fields valid and verify that a success message appears in a new tab
- [x] No console errors
- [x] Submit button redirects to a thank you page in a new tab when successfully validated
- [x] Viewpoint looks good on mobile (label and input in column format, radio buttons spaced)
- [x] Viewpoint looks good on tablet (label and input in row format, radio buttons spaced)
- [x] Viewpoint looks good on desktop (label and input in row format, form width is 1/3 of total page width)

![image](https://user-images.githubusercontent.com/102811792/173553290-4f4681c9-732f-4872-bb3d-2560fa01adeb.png)

![image](https://user-images.githubusercontent.com/102811792/173553247-dc0f3620-c3d5-4d5a-abba-22e0658c5c4d.png)

![image](https://user-images.githubusercontent.com/102811792/173554246-db12de13-54c6-4ea4-86f5-33f6c9db681d.png)

![image](https://user-images.githubusercontent.com/102811792/173554040-124822bf-cc3f-4d47-a6a9-bbde7e4cad85.png)

- __Mobile Viewpoint__

![image](https://user-images.githubusercontent.com/102811792/173555149-0fe66c44-e1d7-4275-b2c1-ecc60d61b387.png)

- __Tablet Viewpoint__

![image](https://user-images.githubusercontent.com/102811792/173555575-2b476471-1b51-40bb-b660-2cb9af963d1e.png)

- __Desktop Viewpoint__

![image](https://user-images.githubusercontent.com/102811792/173555695-aeffa82a-c463-41e9-8549-db059ad813dd.png)


### Defect Tracking

Defects tracked via GitHub issues which can be viewed here: https://github.com/AlexanderJWard/ascend-yorkshire/issues

### Defects of Note

- I struggled early on in the development to move the logo I created close enough to the h1 title that I thought looked best. I spent quite a bit of time learning about relative and absolute positions before achieving the end result after some trial and error. This issue can be found here: https://github.com/AlexanderJWard/ascend-yorkshire/issues/2

- Another defect of note was during the development of the welcome images, they got pushed off the side of the screen. This was during my learning process of flexbox and took me more trial and error to successfully fit the images and get them to wrap instead of sticking off the page. The issue can be located here: https://github.com/AlexanderJWard/ascend-yorkshire/issues/5

- When I was developing the hero image animation I ran into issues with the speed of transition due to smaller screen sizes, the image has more space to travel therefore the movement speed is very high. I found help from online forums regarding changing the time the transition takes and how to move the image by percentages. This defect can be found here: https://github.com/AlexanderJWard/ascend-yorkshire/issues/4

### Outstanding Defects

One outstanding defect is on the home page accommodation section with the background images of each hotel. These images are set to cover so the image does get zoomed when going past 1600px screen size. This affects a very small subset of users as it looks fine on the majority of viewpoints and even when the image does zoom in it still looks okay, I would just rather the image stay at it's max size without zooming. I have a max width of the website at around 1600px so ideally the images need to not zoom past that max viewpoint.

## Accessibility


### Lighthouse Audits


### Keyboard Navigation

I've tested the ability to navigate each page by using Tab and Enter key. This works as expected and the links are selected in order and in the correct direction from top to bottom.

## Deployment

1. Open GitHub repository and navigate to the __Settings__ button.

![image](https://user-images.githubusercontent.com/102811792/169009036-b948fca3-af2c-4151-8add-4c0c9aea015c.png)

2. On the left menu panel navigate to the __Pages__ button.

![image](https://user-images.githubusercontent.com/102811792/169015308-75e274f9-d635-4c7d-aa1e-a26f113466bd.png)

3. Under the __Source__ heading click on the drop down that contains the word __None__.

![image](https://user-images.githubusercontent.com/102811792/169015829-c7be3f75-0ac0-4b0c-94a0-8fdbace49a09.png)

4. On the drop down list select the __main__ branch.

![image](https://user-images.githubusercontent.com/102811792/169016172-00520129-07ad-45f2-9955-e069d5dc90a8.png)

5. Click the __Save__ button.

![image](https://user-images.githubusercontent.com/102811792/169016299-f9e6ba13-9998-4b68-842a-f5735114f528.png)

6. Finally, there will now be a blue banner showing the live link to the page.

![image](https://user-images.githubusercontent.com/102811792/169017013-1eb9421d-d8ac-470c-989d-0b17ab75b3bc.png)

The live link is located at https://alexanderjward.github.io/ascend-yorkshire/

## Credits


### Content

__General__

- Multiple icons used throughout have been taken from Font Awesome's free collection. Here is the link source:

https://fontawesome.com/search?m=free

- Footer social media links and alt text have been taken from the Love Running project.

__Home Page__

- Paragraph text taken from Booking.com for each hotel I listed in the accommodation section. Here are the link sources:

https://www.booking.com/hotel/gb/the-crown-settle1.en-gb.html

https://www.booking.com/hotel/gb/dalecote-barn-bed-amp-breakfast.en-gb.html

https://www.booking.com/hotel/gb/the-whoop-hall.en-gb.html

https://www.booking.com/hotel/gb/newinnhotel.en-gb.html

__Walks Page__

- Weather Widgit taken from https://weatherwidget.io/

![image](https://user-images.githubusercontent.com/102811792/173595796-d5926a28-8210-4b60-b45a-c649db8c4213.png)

### Media

__Home Page__

- Hero image is attributed to Tim Hill and I have downloaded from pixabay. Here is the link source:

https://pixabay.com/users/timhill-5727184/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2443093

- Image of Pen-y-ghent is attributed to George Hodan and has been downloaded from Public Domain Pictures. Here is the link source:

https://www.publicdomainpictures.net/en/view-image.php?image=214238&picture=view-to-and-from-pen-y-ghent

- Image of Whernside is attributed to Cyberdemon007 and has been downlaoded from Wikipedia Commons. Here is the link source:

https://commons.wikimedia.org/wiki/File:Whernside_and_Ribblehead_Viaduct.jpg

- Image of Ingleborough is attributed to Nilfanion and has been downloaded from Wikipedia Commons. Here is the link source:

https://commons.wikimedia.org/wiki/File:Ingleborough_(7603).jpg

- Images of hotels used as background images in accommodation section have been taken from booking.com. As my accommodation content is directly linking the booking.com page I have decided to use a picture from their website to advertise it at attribute the source. Here are the link sources:

https://www.booking.com/hotel/gb/the-crown-settle1.en-gb.html

https://www.booking.com/hotel/gb/dalecote-barn-bed-amp-breakfast.en-gb.html

https://www.booking.com/hotel/gb/the-whoop-hall.en-gb.html

https://www.booking.com/hotel/gb/newinnhotel.en-gb.html

- Image of parked cars is attributed to Florian Pircher and has been downloaded from Pixabay. Here is the link source:

https://pixabay.com/users/fill-8988/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=825371

- Where in the UK iframe has been taken directly from Google Maps.

__Walks Page__

- Screenshots taken from Google Maps

__Three Peaks Challenge Page__

- Screenshots taken from Google Maps

__Events Page__

- Same three images used from home page of Pen-y-ghent, Whernside & Ingleborough. Attributed in home page section above.

- Image of Yorkshire Dales attributed to Tim Hill downloaded from Pixabay. Here is the link source:

https://pixabay.com/photos/cry-stone-walls-yorkshire-dales-2451428/

### Acknowledgments

See following small changes advised by Mentor that have been implemented into my project.

![image](https://user-images.githubusercontent.com/102811792/173596980-09b29c1f-8850-456d-a564-27ecaff23b3b.png)

![image](https://user-images.githubusercontent.com/102811792/173597083-fe5c6219-f61e-4911-9864-e44201aaea83.png)

![image](https://user-images.githubusercontent.com/102811792/173597166-f6109039-18bc-49ff-9e21-2799ec9c1895.png)

![image](https://user-images.githubusercontent.com/102811792/173597240-eeac96a0-67c5-404e-bb0f-b44eac8fbd62.png)
