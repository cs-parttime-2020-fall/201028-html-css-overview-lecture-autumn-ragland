# 20-10-28 HTML CSS Overview Lecture

Today's lecture will focus on reviewing HTML and CSS covered in the last week and a half. We will also introduce a few new concepts to level up your webpages. 

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode
1. open the provided HTML file using `ctrl o` in the browser

### Linking files
1. create an html file called `index.html` and use the `html:5` shortcut to generate the html, head, and body elements
2. create an html file called `topic.html` and use the `html:5` shortcut to generate the html, head, and body elements
3. create a css file called `style.css`
4. link the css file to both html files using the `link` tag in the `head` of each - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
5. check that the files are linked by setting the `background-color` property of the body to any color other than white/gray and open each HTML file using `ctrl o` in the browser

### Content
- Index
    1. header element containing an heading 1 element with the text `Landing Page` and a navigation element containing a button with the text `Topic`
    1. div element containing a heading 3 element with the text `Check out this video` and a section element containing an iFrame rendering a YouTube video
    1. div element containing five paragraph elements with filler text
    1. footer element containing a div element containing a link to the Code Connector site that opens to a new page
- Topic
    1. header element containing a heading 1 element with the text `Topic One` and a navigation element containing a button with the text `Landing Page`
    1. div element containing an image
    1. article element containing a paragraph element and an unordered list containing three list items
    1. footer element containing a link to the website that you got the image used on the page
- Add the appropriate link to all navigation buttons

### Styling
1. Link a google fonts external style sheet with two fonts of varying weight selected : https://fonts.google.com/
1. Create a stylesheet and link in both html files
1. Add padding to the body and set the font family to one of the fonts chosen from google fonts
1. Set the font of all heading 1 text to the other google font and set the font weight to 800
1. Add padding and a bottom margin to the nav element and make the element gray
1. Add padding and a blue rounded border to all buttons and make them blue with white text
1. Change the button with the text "Landing Page" to be white with black text
1. Use the appropriate pseudo class so that when you hover over a button a red border is added
1. Set the width of the image on the topic page and the YouTube video on the landing page to 44% of their parent element and give them a thick blue border
1. Center the images on the two topic pages and the YouTube video on the landing page using margin
1. Remove the underline from all links and change the font family to match the heading 1 elements
1. Add a gray border to all child elements of the footer element with space to the left and right of the text and space between each child element
1. Update the bulleted list on the topic page to use circles instead of dots

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation Info on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/html.md)

[Google Fonts](https://fonts.google.com/)
