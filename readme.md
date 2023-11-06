# Serial Winners

Serial Winners is a fictitious competition website, offering particapants the chance to win an island located off the northern coast of Sicily.  
{See homepage screenshot here} (assets/readme-images/Serial Winners Homepage Top.png)

[Link to site: ](https://townsend75.github.io/Win-an-island/)
[Link to repository:](https://github.com/townsend75/Win-an-island.git)

#Table of Contents

1. [## Features](https://github.com/townsend75/Win-an-island/blob/main/readme.md#features)
2. [#UX/UI](https://github.com/townsend75/Win-an-island/blob/main/readme.md#uxui)
3. [## Testing](https://github.com/townsend75/Win-an-island/blob/main/readme.md#testing)
4. [## Deployment](https://github.com/townsend75/Win-an-island/blob/main/readme.md#deployment)
5. [## Sources](https://github.com/townsend75/Win-an-island/blob/main/readme.md#sources)
6. [## Future features and Considerations](https://github.com/townsend75/Win-an-island/blob/main/readme.md#future-features-and-considerations)

## Features:

### header

[Header](assets/images/Header.png)

Featured on all three pages, includes the site logo and links to all three pages. The header is identical on each page. The page currently being viewed is underlined in the menu.

### landing page

[Homepage on chrome](assets/images/Homepage%20Google%20Chrome.png)

The landing page features a photo of the island in the competition and introduces the concept of winning an island. There is also a section about the organisers of the competition.

### the prize page

Features information about the island itself and the surrounding area, photos of the island from various perpectives and details about the specifics of the prize to be won.

### enter competition page

features a simple signup form, a radio style survey and more pictures of the island.

### footer

[Footer](assets/images/Footer.png)

The footer is also featured on every page and includes icon style links to the four main social media sites, which all open in separate browser windows.

All three pages were created for three different screen sizes.

# UX/UI

## Site Goals:

The goal of the site is to tempt a large amount of traffic by offering a huge prize, At the same time, the site aims at providing information abaout the island and the surrounding region, possibly encouraging people to visit the area in future.

### Design Choices

With my limited experience, I chose a simple, clean design structure. The header and footer both have a pale yellow background, which complements the Aeolian island pictures on each page. Using flex displays allowed me to keep everything neatly spaced throughout the project.

#### User Stories

- As a user, I want a chance to win my own island.
- As a user, I would like to find out as much about the island as possible from the site.
- As a user, I want to be able to register for the competition on the site via a sign up form.
- As an admin, I want to have as many competition entries as possible.
- As an admin, I want to provide information about the island in an attempt to attract visitors.

## Testing

| Feature                | Expect                                             | Action                                 | Result                                           |
| ---------------------- | -------------------------------------------------- | -------------------------------------- | ------------------------------------------------ |
| Home nav link          | Homepage should be opened                          | Click home button                      | Homepage loaded correctly                        |
| The prize navlink      | Prize page should open                             | click prize link                       | prize page opens as expected                     |
| Enter competition page | Entry form page should open                        | Click enter link                       | Entry page loads as expected                     |
| Form                   | Input should be possible in first two input fields | Entered first and last names           | Names filled in correctly                        |
| Email input            | Only valid email address permitted                 | entered text with no email address     | received reminder to enter correct email address |
| Email input            | Only valid email address permitted                 | Entered valid email address            | Address was accepted                             |
| Radio button           | It should only be possible to select one option    | Selected various options               | Radio function works as expected                 |
| Social media icons     | New window should open for each icon clicked       | Clicked on all four social media icons | Pages opened as expected                         |

Bugs:

I spent a long time trying to resize the images and paragraphs as the pages shrunk for use with smaller screens. I'm not sure if I have suceeded 100% with my methodology but I tried my best!
Update: After a long session with my mentor re-sizing certain elements for smaller screens, the full sized second page doesn't quite reach the bottom of the screen. I have sadly run out of time to address this issue. I tried everything I could think of but nothing works, even though the html meta data should ensure the screen is filled.

Validator testing:

HTML
-No errors were returned when passing through the official W3C validator

[index.html validator](assets/images/Index.html%20validator.png)

[island.html validator](assets/images/island.html%20validator.png)

[form.html validator](assets/images/Form.html%20validator.png)

CSS

-No errors were found when passing through the official (Jigsaw) validator

[CSS Validator](assets/images/CSS%20Validator.png)

All pages scored highly on the Google Chrome Lighthouse Inspector in both the desktop and mobile versions

[Homepage desktop](assets/images/Homepage%20desktop.png)

[Homepage mobile](assets/images/Homepage%20mobile.png)

[Prize page desktop](assets/images/Prize%20page%20desktop.png)

[Prize page mobile](assets/images/Prize%20page%20mobile.png)

[Form page desktop](assets/images/Form%20page%20desktop.png)

[Form page mobile](assets/images/Form%20page%20mobile.png)

## Deployment

The site was deployed to GitHub pages. The steps to deploy were as follows:
Open the settings tab.
Select the main branch from the source section
The page then refreshes with a link to a website, indicating a successfull deployment.
The link to the site is :https://townsend75.github.io/Win-an-island/

### Sources

Content:
I referenced the code used in all of the teaching videos to some extent, particularly when creating the form element. The menu navigation is based on the love-running project.
The factual information on the island was gleaned from Wikipedia pages about Filicudi and also the Aeolian islands.
The photos were taken from from two different sources. One from google images and the rest from istockphotos.com
The links to social media include icons taken from fontawesome.com, as was described in the love-running tutorial.
I referenced stack overflow for many questions and found various suggestions which helped further my understanding of the code. 
My mentor, Sherly S Goldberg was a great help throughout the project and my thanks go to her for both her advice and also many usefule articles that she shared with me. 

### Future Features and considerations

Were I to build a real competition website, I am aware that there would have to be a separate page listing the terms and conditions of the competition as well as all the legal necessities.
I would also include more links to information about the area, including links to hotel websites, travel information and things to do in the area.
As I progress, I would like to use more radical styling, e.g. I would like to have had small boat icons instead of buttons for the nav menu.
