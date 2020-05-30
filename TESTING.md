# Testing

Used [W3C HTML validator](https://validator.w3.org/#validate_by_input) website via the direct input path. Results: No significant errors found.


Used [Jigsaw](https://jigsaw.w3.org/css-validator/#validate_by_input) via the direct input path. Results: No errors found.

#### User stories:

- User wants a simple and clean looking website as messy, busy pages with lots of information overwhelms them.

- User wants an easy to navigate website to save time and not get frustrated or lost.

User goes to the website and on the home page, resource page and contact us page there is a simple navigation bar fixed on the top of the page. Wherever they scroll down to on each page the navigation menu bar is there for them to click and go to another page. When you hover over the words the colour of the text goes a darker grey colour.

- User wants to be able to use it on desktop, tablet and mobile devices.

- User wants to find out what eco homes are.

Go to the home page and scroll down to underneath the ‘About Us’ section is ‘Why live in an eco home?’ This section gives an explanation of the benefits and what eco homes are.

- User is interested in one of the three eco home concepts introduced and would like to know more.

Go to the home page and scroll down to the section underneath the ‘Why live in an eco home?’ And there are three cards each introducing a different eco home concept with a corresponding image. When you hover over the ‘More Info’ green buttons they turn a darker green colour. To find out more click on the green button ‘More Info’ and it will open a new tab to an external website, the green button also stays a dark green with a light green border around it, to indicate it has been clicked.

- User wants to find out more about one of the three related interests introduced on the home page.

Go to the home page and scroll down to the ‘Related Interests’ section where there are three cards introducing ‘Off Grid Living’, or ‘Zero Waste Living’ or ‘Eco Home Products’ with a corresponding image. When you hover over the green buttons they turn a darker green colour. To find out more click on the green button ‘More Info’ and it will open a new tab to an external website, the green button also stays a dark green with a light green border around it, to indicate it has been clicked.

- User would like to sign up to Greener Homes latest news.

Go to the bottom of the home page by scrolling down and there is a green form labelled ‘Receive the latest news from Greener Homes’.

If you hover over the ‘Sign Up!’ Area the button goes a darker green colour but does not stay dark green. This does not happen in iPad or phone view it only goes a darker green when it is clicked on and it stays dark green until you click another area of the screen.

If you click on the ‘Sign Up!’ The button without filling in the form it will indicate with a message to ‘Please fill in this field’ indicating the area to type into.

If the form has been filled in but with an invalid email address and you click the ‘Sign Up!’ Button then another message comes up ‘Please include a ‘@‘ in the email address ‘___’ is missing a ‘@‘.

If the form has been partly filled in with half the email address and you click the ‘Sign Up!’ Button then another message comes up ’Please enter a part following ‘@‘, ‘___@‘ is incomplete’.

If the form has been filled correctly with a full email address and you click the ‘Sign Up!’ Button then the page goes to the top and the form clears.

- User wants to know even more information about one of the eco homes introduced on the home page.

Go to navigation menu bar and click on ‘More Resources’. Under the ‘Website Links’ There are three lists corresponding to the three eco home concepts, each list has five links which open up a new tab to an external link giving more information. All links open up into a new tab so the user doesn’t forget Greener Homes website and can go back to it easily.

*Bug*: The last link of the three lists has a blue border once it has been clicked which is useful for the user to know when they come back from the external link which was the last link they clicked. But the other links do not do that.

The other three white background links go light grey when it has been clicked and the green background link does not indicate anything when clicked.

- User doesn’t want to read any more information and wants to watch an informative video of one of the eco home concepts.

Go the resource page and scroll down to the section ‘Video Links’ there are three short YouTube videos introducing each of the three eco home concepts.

*Bug*: The left and middle videos are unable to go to full screen within the website, only if you click ‘YouTube’ to watch via the Youtube website. Rectified by moving the `>` to the end of `allowfullscreen` 

All videos play on the website when you click on them.

- User wants to know what kind of resources are available to help them know more about eco homes.

Go to the resource page and when you scroll down you will find three types: Website Links, Video Links and Book Resources.

- User wasn’t able to find the information they needed so would like to contact Greener Homes via the contact page.

Go to the navigation menu bar and click on ‘Contact Us’

Scroll down to the form.

Fill in the ‘Full Name’ field, ‘Email Address’ field and ‘Message’ field, if the form has been filled in correctly and click on the ‘Submit’ green button, then it goes to the top of the page and the form clears.

*Bug*: The ‘Full Name’ field is accepting all characters and numbers and just one name. So would like to validate it so it only accepts letters and two names at least.

If the ‘Full Name’ field is not filled then the message ‘Please fill in this field’ appears.

If the ‘Email Address’ field is not filled then the message ‘Please fill in this field’ appears.

If the ‘Email Address’ field is not valid and you click the ‘Submit’ button then the message ‘Please include a ‘@‘ in the email address ‘___’ is missing a ‘@‘ appears.

If the ‘Email Address’ field has been partly filled in with half the email address and you click the ‘Submit’ Button then another message comes up ’Please enter a part following ‘@‘, ‘___@‘ is incomplete’.

*Bug*: The form goes to the top of the page and the form clears when the ‘Full Name’ and ‘Email Address’ fields are filled, even without the ‘Message’ field being filled.

The ‘Submit’ button goes a darker green when you hover over it and when you click it and then goes back to the previous green colour.

- User has read through the information of the home page and feels this is too much change in their lives but still wants to change a small part of their lifestyle and wants to know what eco products they can buy.

Go to the navigation menu bar and click on ‘Home’, scroll down to the ‘Related Interests’ section and click on ‘More Info’ in the ‘Eco Home Products’ card.

  - User wants to know the cost of an earthship, tiny house or shipping container home in the UK.

# Responsiveness of website

### Home.html in Desktop view.
In desktop mode, the navigation menu bar on the top is fixed and the words are clearly displayed. The screen shows the hero image displaying the full width of the browser. The main heading ‘Greener Homes’ and sub-headings ‘About Us’ and ‘Why live in an eco home?’ and the horizontal dividers and its content are centred on the page.

The three cards displaying the three eco homes are in a row neatly spaced and in line, the content is justified and centred within the border. The green buttons are on the bottom of the card within the border.

The next heading ‘Related Interests’ and the horizontal divider are centred on the page.

The three cards displaying ‘Off Grid Living’, ‘Zero Waste Living’ and ‘Eco Home Products’ are in a neat row equally spaced and in line, the content is centred within the border of the card. The green buttons are on the bottom of the card also within the border.

The green form ‘Receive the latest news from Greener Homes’ at the bottom of the page is centred on the page. All the text and text box area is equally spaced and within the border of the form.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row.

### Home.html in iPad/iPad Pro view.

In iPad mode, the navigation menu bar on the top is fixed and the words are clearly displayed. The ‘Home’, ‘More Resources’ and ‘Contact Us’ text, once clicked the font colour goes a dark grey and then goes back to the original light grey and the page opens. The hero image displays the full width of the browser with no distortions just trimmed on either side of the image. The main heading ‘Greener Homes’ and sub-headings ‘About Us’ and ‘Why live in an eco home?’ and the horizontal dividers and its content are centred on the page. The fonts have decreased in size to adjust to the smaller size and looks in proportion to each other.

*Bug*: When you scroll up the top of the words are hidden on the navigation bar but still clickable. For the top margin to appear user has to scroll down.

The three cards displaying the three eco homes are in a row neatly spaced and in line, the content is justified and centred within the border. The green buttons are on the bottom of the card within the border. The shape of the cards have elongated to adjust the narrower width but still looks good.

The next heading ‘Related Interests’ and the horizontal divider are centred on the page. The font size and length of the horizontal divider have decreased and are in proportion to each other.

The three cards displaying ‘Off Grid Living’, ‘Zero Waste Living’ and ‘Eco Home Products’ are in a neat row equally spaced and in line, the content is centred within the border of the card. The green buttons are on the bottom of the card also within the border. The shape of the cards have elongated to adjust the narrower width but still looks good.

The green form ‘Receive the latest news from Greener Homes’ at the bottom of the page is centred on the page. All the text and text box area is equally spaced and within the border of the form. Everything has decreased in size and is still in proportion to each other.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row.

### Home.html in iPhone X, 6, 7, 8 view.

In mobile phone mode, the navigation menu bar on the top is fixed and the burger icon appears. When clicked the drop down menu appears with the ‘Home’, ‘More Resources’ and ‘Contact Us’, when you click on them the font colour goes a dark grey and then goes back to the original light grey.

*Bug*: When you scroll up the top of the burger icon are hidden on the navigation bar but still clickable. For the top margin to appear user has to scroll down.

The hero image displays the full width of the browser with no distortions just trimmed on either side of the image. The main heading ‘Greener Homes’ and sub-headings ‘About Us’ and ‘Why live in an eco home?’ and the horizontal dividers and its content are centred on the page. The fonts have decreased in size to adjust to the smaller size and looks in proportion to each other.

The three cards displaying the three eco homes are now displaying the full width of the screen one at a time, one after another, the content is centred within the border. The green buttons are on the bottom of the card within the border.

The next heading ‘Related Interests’ and the horizontal divider are centred on the page. The font size and length of the horizontal divider have decreased and are in proportion to each other.

The three cards displaying ‘Off Grid Living’, ‘Zero Waste Living’ and ‘Eco Home Products’ are in a neat row equally spaced and in line, the content is centred within the border of the card. The green buttons are on the bottom of the card also within the border. The shape of the cards have elongated to adjust the narrower width but still looks good.

The green form ‘Receive the latest news from Greener Homes’ at the bottom of the page is centred on the page. All the text and text box area is equally spaced and within the border of the form. Everything has decreased in size and is still in proportion to each other.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row.

### Resources.html in Desktop view.

In desktop mode, the navigation menu bar on the top is fixed and the words are displayed. The ‘Home’, ‘More Resources’ and ‘Contact Us’ text, once clicked the font colour goes a dark grey and then goes back to the original light grey and the page opens.

The screen shows the hero image displaying the full width of the browser. The main heading ‘Greener Homes’ and sub-heading ‘More Resources’ and the horizontal dividers and its content are centred on the page.

The next heading ‘Website Links’ and the horizontal divider are centred on the page.

The three group lists displaying the website links are in three columns, each with five rows of clickable text. The three containers are neatly spaced and in line, the content is centred within the border.

All links open up to an external website in a new tab so the user doesn’t forget Greener Homes website and can go back to it easily.

*Bug*: The last link of the three lists has a blue border once it has been clicked which is useful for the user to know when they come back from the external link which was the last link they clicked. But the other links do not do that.
*Debugged*: Added the same code from the last link to the rest of the links. Now they all show a blue border when the link has been clicked.

*Bug*: The other three white background links go light grey when it has been clicked and the green background link does not indicate anything when clicked.
*Debugged*: Changed all the background colour links to green and added the border code to all the links. Now when user hovers over the link it goes a darker green and when clicked shows a blue border to indicate it was the last link clicked.

The next heading ‘Video Links’ and the horizontal divider are centred on the page.

The three embedded videos are neatly in line and in a row, equally spaced apart. Only the right video can go to full screen when you click the full screen icon.

*Bug*: The left and middle videos are unable to go to full screen within the website, only if you click ‘YouTube’ to watch via the Youtube website. 
*Debugged*: Rectified by moving the `>` at the end of `allowfullscreen`

The next heading ‘Book Resources’ and the horizontal divider are centred on the page.

The five cards displaying the five recommended books: ‘Zero Waste Home’, ‘Tiny House Living’, ‘Building with Cob’ ‘Zero Waste’ and ’How to Live Off Grid’, are in a neat row equally spaced and in line, the content is centred within the border of the card.
*Bug*: There is too much white space between the text and the card footer. 
*Debugged*: Added media queries to change the height of the card footer for desktop and tablet screens.

The green text links are in the card footer also within the border. *Bug*: Needs to be centred. 
*Debugged*: Added text-center class.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row.

### Resources.html in iPad/iPad Pro view.

In iPad mode, the navigation menu bar on the top is fixed and the words are clearly displayed. The ‘Home’, ‘More Resources’ and ‘Contact Us’ text, once clicked the font colour goes a dark grey and then goes back to the original light grey and the page opens.

*Bug*: When you scroll up the top of the words are hidden on the navigation bar but still clickable. For the top margin to appear user has to scroll down.

The hero image displays the full width of the browser with no distortions just trimmed on either side of the image. The main heading ‘Greener Homes’ and sub-headings ‘More Resources’, its content, ’Website Links’ and the horizontal dividers and its content are centred on the page. The fonts have decreased in size to adjust to the smaller size and looks in proportion in relation to each other.

The three group lists displaying the website links are in three columns, each with five rows of clickable text. The three containers are neatly spaced and in line, the content is centred within the border, although the height sizes differ due to the text.

All links open up to an external website in a new tab so the user doesn’t forget Greener Homes website and can go back to it easily.

*Bug*: The last link of the three lists has a yellow border once it has been clicked which is useful for the user to know when they come back from the external link which was the last link they clicked. But the other links do not do that. The other three white background links go light grey when it has been clicked and the green background link does not indicate anything when clicked.

*Debugged*: Added the same code from the last link to the rest of the links. Now they all show a blue border when the link has been clicked so it's easier for the user to know which link they last clicked on. The background of the links go a darker green when you hover over them.
 
The next heading ‘Video Links’ and the horizontal divider are centred on the page.

The three embedded videos are neatly in line and in a row, equally spaced apart. All videos play but only the right video can go to full screen when you click the full screen icon.

*Bug*: The left and middle videos are unable to go to full screen within the website, only if you click ‘YouTube’ to watch via the Youtube website.
*Debugged*: Rectified by moving the `>` at the end of `allowfullscreen`

The next heading ‘Book Resources’ and the horizontal divider are centred on the page.

The five cards displaying the five recommended books: ‘Zero Waste Home’, ‘Tiny House Living’, ‘Building with Cob’ ‘Zero Waste’ and ’How to Live Off Grid’, are in a neat row equally spaced and in line, the content is centred within the border of the card.

All links opens up a new tab to the external website.

*Bug*: There is too much white space between the text and the card footer.
*Debugged*: Added media queries to change the height of the card footer for desktop and tablet screens.

The green text links are in the card footer are within the border. *Bug*: Needs to be centred.
*Debugged*: Added text-center class.
 
The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row. All links opens up a new tab to the external website.

### Resources.html in iPhone X, 6, 7, 8 view.

In mobile phone mode, the navigation menu bar on the top is fixed and the burger icon appears. When clicked the drop down menu appears with the ‘Home’, ‘More Resources’ and ‘Contact Us’, when you click on them the font colour goes a dark grey and then goes back to the original light grey.

*Bug*: When you scroll up the top part of the burger icon is hidden on the navigation bar but still clickable. For the top margin to appear user has to scroll down.

The hero image displays the full width of the browser with no distortions just trimmed on either side of the image. The main heading ‘Greener Homes’ and sub-headings ‘More Resources’, the content and ‘Website Links’ and the horizontal dividers are centred on the page. The fonts have decreased in size to adjust to the smaller size and looks in proportion to each other.

The three group lists displaying the website links are in one column displaying the whole width of the screen, each with five rows of clickable text. The three containers are neatly spaced and in line, one after another, the content is centred within the border, and equally spaced in between.

All links open up to an external website in a new tab so the user doesn’t forget Greener Homes website and can go back to it easily.

*Bug*: The last link of the three lists has a yellow border once it has been clicked which is useful for the user to know when they come back from the external link which was the last link they clicked. But the other links do not do that. 
*Debugged*: Added the same code from the last link to the rest of the links. Now they all show a blue border when the link has been clicked.

*Bug*: The other three white background links go light grey when it has been clicked and the green background link does not indicate anything when clicked.
*Debugged*: Changed all the background colour links to green and added the border code to all the links. Now when user hovers over the link it goes a darker green and when clicked shows a blue border to indicate it was the last link clicked.
  
The next heading ‘Video Links’ and the horizontal divider are centred on the page.

The three embedded videos are neatly in one column fitting the width of the screen with margin, equally spaced apart. All videos play but only the right video can go to full screen when you click the full screen icon.

*Bug*: When in full screen the full screen icon disappears but if you click in that area it goes back to a smaller screen.

*Bug*: The left and middle videos are unable to go to full screen within the website, only if you click ‘YouTube’ to watch via the Youtube website.
*Debugged*: Rectified by moving the `>` at the end of `allowfullscreen`
  
The next heading ‘Book Resources’ and the horizontal divider are centred on the page.

The five cards displaying the five recommended books: ‘Zero Waste Home’, ‘Tiny House Living’, ‘Building with Cob’ ‘Zero Waste’ and ’How to Live Off Grid’, are in one column equally spaced and in line, one after another, the content is centred within the border of the card.

All links opens up a new tab to the external website.

The green text links are in the card footer are within the border. *Bug*: Text needs to be centred.
*Debugged*: Added text-center class.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row. All links opens up a new tab to the external website.

### Contact.html in desktop view.

In desktop mode, the navigation menu bar on the top is fixed and the words are displayed. The ‘Home’, ‘More Resources’ and ‘Contact Us’ text, once clicked the font colour goes a dark grey and then goes back to the original light grey and the page opens.

The screen shows the hero image displaying the full width of the browser. The main heading ‘Greener Homes’ and sub-heading ‘Let’s Get In Touch’ its content and the horizontal dividers are centred on the page.

The form is centred is centred on the page. All the text and text box areas are equally spaced and within the border of the form.

When user selects a text area a thin blue border appears.

*Bug*: The ‘Full Name’ field is accepting all characters and numbers and just one name. So would like to validate it so it only accepts letters and two names at least.

If the ‘Full Name’ field is not filled then the message ‘Please fill in this field’ appears.

If the ‘Email Address’ field is not filled then the message ‘Please fill in this field’ appears.

If the ‘Email Address’ field is not valid and you click the ‘Submit’ button then the message ‘Please include a ‘@‘ in the email address ‘___’ is missing a ‘@‘ appears.

If the ‘Email Address’ field has been partly filled in with half the email address and you click the ‘Submit’ Button then another message comes up ’Please enter a part following ‘@‘, ‘___@‘ is incomplete’.

*Bug*: The form goes to the top of the page and the form clears when the ‘Full Name’ and ‘Email Address’ fields are filled, even without the ‘Message’ field being filled.

When you click the ‘Submit’ button it goes a darker green and then goes back to the previous green colour.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row. All links open into a new tab to the external website.

### Contact.html in iPad/iPad Pro view.

  

In iPad mode, the navigation menu bar on the top is fixed and the words are displayed. The ‘Home’, ‘More Resources’ and ‘Contact Us’ text, once clicked the font colour goes a dark grey and then goes back to the original light grey and the page opens.

*Bug*: When you scroll up the top of the words are hidden on the navigation bar but still clickable. For the top margin to appear user has to scroll down.

The hero image displays the full width of the browser with no distortions just trimmed on either side of the image. The main heading ‘Greener Homes’ and sub-heading ‘Let’s Get In Touch!’, its content and the horizontal dividers are centred on the page. The fonts have decreased in size to adjust to the smaller size and looks in proportion in relation to each other.

The form is centred is centred on the page. All the text and text box areas are equally spaced and within the border of the form.

When user selects a text area a thin blue border appears. 
*Bug*: Border is too thin it's very hard to see.

*Bug*: The ‘Full Name’ field is accepting all characters and numbers and just one name. So would like to validate it so it only accepts letters and two names at least.

If the ‘Full Name’ field is not filled then the message ‘Please fill in this field’ appears.

If the ‘Email Address’ field is not filled then the message ‘Please fill in this field’ appears.

If the ‘Email Address’ field is not valid and you click the ‘Submit’ button then the message ‘Please include a ‘@‘ in the email address ‘___’ is missing a ‘@‘ appears.

If the ‘Email Address’ field has been partly filled in with half the email address and you click the ‘Submit’ Button then another message comes up ’Please enter a part following ‘@‘, ‘___@‘ is incomplete’.

*Bug*: The form goes to the top of the page and the form clears when the ‘Full Name’ and ‘Email Address’ fields are filled, even without the ‘Message’ field being filled.

When you click the ‘Submit’ button it goes a darker green and stays that colour until you click on another part of the screen.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row. All links opens up a new tab to the external website.

### Contact.html in iPhone X, 6, 7, 8 view.

In mobile phone mode, the navigation menu bar on the top is fixed and the burger icon appears. When clicked the drop down menu appears with the ‘Home’, ‘More Resources’ and ‘Contact Us’, when you click on them the font colour goes a dark grey and then goes back to the original light grey.

*Bug*: When you scroll up the top part of the burger icon is hidden on the navigation bar but still clickable. For the top margin to appear user has to scroll down.

The hero image displays the full width of the browser with no distortions just trimmed on either side of the image. The main heading ‘Greener Homes’ and sub-headings ‘Let’s Get In Touch’, the content the horizontal dividers are centred on the page. The fonts have decreased in size to adjust to the smaller size and looks in proportion to each other.

The form is centred on the page. All the text and text box areas are equally spaced and within the border of the form. There are no margins on either side of the form but looks good, it is consistent with the hero image.

When user selects a text area a thin blue border appears. 

*Bug*: The border is too thin it's very hard to see.

*Bug*: The ‘Full Name’ field is accepting all characters and numbers and just one name. So would like to validate it so it only accepts letters and two names at least.

If the ‘Email Address’ field is not filled then the message ‘Please fill in this field’ appears.

If the ‘Full Name’ field is not filled then the message ‘Please fill in this field’ appears.

If the ‘Email Address’ field is not valid and you click the ‘Submit’ button then the message ‘Please include a ‘@‘ in the email address ‘___’ is missing a ‘@‘ appears.

If the ‘Email Address’ field has been partly filled in with half the email address and you click the ‘Submit’ Button then another message comes up ’Please enter a part following ‘@‘, ‘___@‘ is incomplete’.

*Bug*: The form goes to the top of the page and the form clears when the ‘Full Name’ and ‘Email Address’ fields are filled, even without the ‘Message’ field being filled.

When you click the ‘Submit’ button it goes a darker green and stays that colour until you click on another part of the screen.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row. All links opens up a new tab to the external website.

## Bugs whilst creating the website:

Navbar code was copied from Bootstrap 4, I found the dropdown menu wouldn’t work and searched on slack and found I had to change the script order of bootstrap to JS, JQuery, CSS.

Changed the height size of the card decks on home page with bootstrap card custom css sizing, but undid the code for this as the content was coming out of the box when the screen was reduced.

Used a card element for sign up form and added a form element inside and changed the width with grid size.

Font was different on one of the three pages, so had to re-copy and paste the code again.

My images weren’t showing up in preview or GitHub but a tutor saw that I had ‘../‘ in front of the pathway and by deleting them it worked.

Tutor Tim helped clarify what code to use when with col sizes and directed me to css page https://www.w3schools.com/cssref/pr_background-image.asp to help with background image responsiveness. So updated all the hero images on 4 pages.

Used codes from this website to help with font-size responsiveness:
https://css-tricks.com/books/fundamental-css-tactics/scale-typography-screen-size/

Also got advice from tutor Stephen advising me what options I had for image responsiveness. With https://code-institute-a61370e921d3.intercom-attachments-1.com/i/o/210427055/093851c6c8c5e651e89f9cbc/ex.png

Mentor gave link to help rectify the white space on the right on mobile device: https://stackoverflow.com/questions/34284976/blank-space-right-side-screen-on-small-device-or-window/34285689#34285689?newreg=609753b69d114fe8855ce8929c156ee3 - checking each parent element on devtools.
Answer was applying zero to margin and padding to body in css.

Horizontal divider line on resource page was going across the width of page so had to move the container end tag div to the end of the section so the padding would apply to all the child elements.


5) List any bugs you came across while creating the site and while testing it. Include the fixes you came up with. (I have two sections here, one for fixed bugs and one for bugs I have not found a solution for yet.)

