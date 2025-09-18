# Unitarian Christian Timeline

For my Code Institute Portfolio Project 1, I have implemented a historical timeline website. This timeline highlights particular, historical key events and persons regarding 
*the biblical teaching of the ONE GOD the Father and His Human Son, Jesus the Christ*; from the time of Christ up to 2023. 

The timeline highlights the opposition to such teaching and the perseverance of believers despite the opposition.

![image](https://user-images.githubusercontent.com/91061592/228402388-21d33f6d-182f-45d7-96a6-f162aa503b58.png)

Visit the deployed site: [Unitarian Christian Timeline](https://delroygayle.github.io/UnitarianChristianTimeline/)

## Features

* **Navigation**

   * Featured at the top of each page, the logo **Unitarian Christian Timeline** acts as a link to the page with the period **1 - 431**. This page is the Home Page.
   * What follows is the navigation bar which begins with links to the pages for the three timeline periods
  
      * **1 - 431**
      * **1326 - 1612**
      * **1662 - 2023**
   *  The other navigation links are to the right: *Gallery* and *Contact Us* 
   *  The navigation clearly tells the user the name of the website and indicates to the user which page the user is on by highlighting the current page with a shade of brown in contrast to the otherwise grey navigation bar

![image](https://user-images.githubusercontent.com/91061592/228494874-62c8c311-5262-4fab-bee0-c5633c8ed572.png)

* **The Header**
   * Because of the length of the time period covered I chose to split up the timeline into three webpages representing three periods
   * Each page has a black coloured logo which acts as a link back to the First page i.e. the Home page
   * The current time period is highlighted in brown 
   
---

* **Timeline Entries**
   * Each timeline entry consists of four parts
   1) A particular date or year
   2) Followed by a title
   3) A description of a particular event or person for that date/year
   4) An image related to the description, for example, a portrait of the person in question

* **Three webpages for three periods**
   * What follows is a look at each of the three pages of the timeline
   * The first page **1 - 431** is the Home Page. It therefore, has a hero image with cover text that gives a summary of the subject of the timeline.

---
   
   * ### First page: 1 - 431

![image](https://user-images.githubusercontent.com/91061592/229279795-0b0c5495-c79c-45cb-8d8a-f2d6b46b4a09.png)


---
   
   * ### Second page: 1326 - 1612

![image](https://user-images.githubusercontent.com/91061592/228495027-e3024924-336c-4c96-b4a1-5ebf2671ad4e.png)

---
   * ### Third page: 1662 - 2023


![image](https://user-images.githubusercontent.com/91061592/228495221-ab7ad4e7-c11d-4a0a-b1d0-6c0174ac15de.png)

---

* **The Gallery Page**

   * The Gallery section uses the masonry design style to display pictures of Unitarian (One-God-believing) Meeting Houses in the UK
   * On desktops the pictures are shown in three columns, on tablets two columns, and on mobiles, one column.

![image](https://user-images.githubusercontent.com/91061592/228496285-54942212-d789-4c1a-b3a5-d3299e4192f5.png)

* **The Contact Us Form**

   * The Contact Us section encourages users to get in contact if the user would like further information or have questions regarding the historical information shown on this website. 
   * There is a form to collect details of the user's name and email address.
   * There is an *optional* message box as well for the user to enter any further information.
   
![image](https://user-images.githubusercontent.com/91061592/228496614-60e78bee-afe2-4235-8877-ffb8e9f94399.png)

* **Thank You Page**

Once the user submits the form on the Contact Us page they will be redirected to this page thanking them. Thereby indicating to the user that the form was submitted correctly. After five seconds the user will be directed back to the Home page, that is, **1 - 431**  

![image](https://user-images.githubusercontent.com/91061592/229307906-1e9b37b1-2ad8-4cac-a54d-8f498cc934cb.png)


* **Social Media**

   * Each page includes social media icons so that users can find the Timeline on Facebook, Twitter, YouTube and Instagram.

* **Back To Top**
   * Because of the height of the Timeline and the Gallery pages, I have implemented a *Back To Top* Button; so that when clicked, the user would be taken to the top of the page so that the user can access the navigation bar.

![image](https://user-images.githubusercontent.com/91061592/229276144-037be972-003a-4895-86dc-6cefe893a44f.png)

------

## Typography and Colours

* From Google Fonts I used Nunito Sans
* I used Oswald for the logo and cover text
* I used Roboto for the headings h1 and h2

* Regarding Colours, I chose chiefly black on white
* However for the cover text and the highlight colour of the navigation bar I chose **##dd3300**

![image](https://user-images.githubusercontent.com/91061592/228528489-96fbdc45-ba5f-4665-8044-50057f939f23.png)

* The navigation bar uses a grey colour **#666**

![image](https://user-images.githubusercontent.com/91061592/228536955-880d4c62-68c7-4c4f-9059-40b0dd86789d.png)

## Testing

* I tested that the pages work in both Chrome and Firefox
* I confirmed that this project is responsive and functions correctly on all standard screen sizes using the browser's DevTools device toolbars.
* I confirmed that the navigation, header, Contact Us form and page contents are all readable and easy to understand.
* I have confirmed that the form works. That is, each mandatory field requires entries; the email field will only accept email addresses with the @ symbol.
* I have confirmed that the submit button works.


## Bugs

### Solved Bugs

* When I deployed my project to GitHub Pages I discovered my project was broken, that is, the link to *style.css* did not work.
* Even though I was using relative links I still had to prefix it with **a period . followed by a slash** in order for it to work
* * That is, *assets/* is not sufficient.
* Solution: link href="./assets/css/style.css"

* Had to remove the colour from the social media icons as it was leaving a grey rectangle on the page after an icon was selected
* These grey rectangles were only visible on mobiles and laptops; not on desktops!
* Solution: remove the colour

```
.social-networks i {
  font-size: 160%;
  margin: 1%;
  padding: 5%;
```  
  ~~color: #3a3a3a;~~

} 

------

## Validator Testing
* HTML 
  * No errors were returned when tested using [the official W3C Validator](https://validator.w3.org/nu/)
* CSS 
  * No errors were returned when tested using [the official Jigsaw Validator](https://jigsaw.w3.org/css-validator/)
* Accessibility
  * I confirmed that the colours and fonts chosen are easy to read and accessible by running the website through Lighthouse in DevTools

![image](https://user-images.githubusercontent.com/91061592/228220812-6e856e1f-8445-4072-a7a0-008e7ea45c1c.png)

## Unfixed Bugs

No unfixed bugs

------

## Deployment

* This site was deployed to GitHub Pages. The steps to deploy are as follows:
  * In the GitHub repository, navigate to the *Settings* Tab
  * Then select *Pages*
  * Use **main** as the branch for *Deploy from a branch*

The live link can be found here - [Unitarian Christian Timeline](https://delroygayle.github.io/UnitarianChristianTimeline/)

## Technologies

### Languages used:

* HTML5
* CSS

### Other tools:

* Google Fonts - for the typography
* TinyJPG - for compressing the larger images
* Chrome and Firefox Developer Tools - for inspecting and testing the site
* GitHub - for hosting the site
* Gitpod - for editing the files
* GitPages - for the deployment of the site
* Font Awesome - used for the social media icons, the up arrow icon of the 'Back To Stop' button and the people icon on the Contact Us page

---


## Future Features
* I would like to improve the image rendering in that, all the images irrespective of their original size, all have the same height/width when shown in the timeline

* I would like to implement the Back To Top button using JavaScript as opposed to CSS

* I would like to implement a Search Bar so that as the user types a particular keyword the user is directed to its location in the webpage

* I would like to create a thank you page for the user to be redirected to once the user has completed the Contact Us form


## Credits

### Responsive Timeline

The timeline I chose to use was adapted from the timeline designed by **Samet Erpik**.

The codepen for this timeline is at <https://codepen.io/samerpik/pen/OVKyVZ>

### Menu

I followed this [W3Schools tutorial](https://www.w3schools.com/css/css_navbar_horizontal.asp) 
in order to implement a Horizontal Navigation Bar

### Floating Back-To-Top Button

I went on to StackOverflow to find a suitable implementation of a Back-To-Top Button
   I chose the one designed by JakeFromSF as seen at 
   [JakeFromSF's button](https://stackoverflow.com/questions/32102747/how-to-make-a-back-to-top-button-using-css-and-html-only)
   
However it failed the HTML Validator tests because it is *bad practice to wrap a button within an **a element***  
So I re-coded it accordingly without using a button.

```
<a href="#top" id="back-to-top">Back<br>To<br>Top</a>
```

### Images 

* To the best of my knowledge, all images used are either Public Domain or pertain to an applicable Creative Commons (CC) licence.

* The pictures of the Unitarian Meeting Houses on the Gallery page are from the Unitarian Historical Society.

* Sirmium: The picture of "*A scale model of Sirmium in Sremska Mitrovica, Serbia*" is by 
Carole Raddato from FRANKFURT, Germany - Sirmium, Pannonia Inferior, Serbia, CC BY-SA 2.0.

* The Photo of [*a child reading the Bible*](https://unsplash.com/photos/NaWKMlp3tVs?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) is by Samantha Sophia on [Unsplash](https://unsplash.com/)

### Robert Spears

The biography of Robert Spears was written by Alan Ruston, courtesy of Unitarian Historical Society.

### Acknowledgements

Many thanks to my mentor Derek McAuley for his help, suggestions and advice.
