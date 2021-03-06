<div style="text-align: center;">

# I-Brary

<p>I-brary is a fully responsive, user based, book recommendation site.
You can browse the Homepage for book recommendations and reviews. You can log in and add your own book reviews, you have the option
to 'share', once shared your book will show up on the homepage. If you don't share, 
your book review will only been seen in your own view.</p>

</div>

## Tabel of Contents

[**Project Goals**](#project-goals)

[**User Goals**](#user-goals)

[**User Stories**](#user-stories)

[**Design Choices**](#design-choices)

[**Wireframes**](#wireframes)

[**Features**](#features)

[**Technologies used**](#technologies-used)

[**Testing**](#testing)

[**Deployment**](#deployment)

[**Credits**](#credits)

## UX

### Project Goals

To create a site that allows users to store books they have enjoyed/want to read. To allow the user to add a genre, review and rating
so if they decide to share their book, other users can get inspiration from the books they have added. 

### User Goals

I want to have a place online I can store my favourite books and also get information on other books I have not read. 

### User Stories

As a user I want...

* To be able to register quickly without the site taking any unnecessary information.
* To be able to find new books I haven't read before.
* To be able to see the Genre and rating of new books so there is enough information for me to decide whether I would enjoy it. 
* To be able to navigate around the site with ease.
* To be able to edit or delete my added books with ease.
* To know that I am the only person able to edit my books that I have added.
* To know my books will be saved when I log out, so when I revisit the site, my books are still there.


### Design Choices

I have decided to go for a simple, professional design. The demographic of my users are readers that use the internet as a resource to source new books.
This would be a large range of ages and backgrounds. Due to this I have stuck to a very classic look that I think is already paired with English Literature.

1. Font
* The font I chose was 'Playfair Display' due to it's 'old timey' design lending itself to the 18th century. 

2. Colour
* I chose Blue as my main colour because it is known as a very calm colour, reading is a peaceful activitie and so should looking into books online. 
* Also there are a lot of colours and patterns on the covers of the books. I want the books to stand out and be the main feature on the page, therefore a 
light blue background worked very well as it brings any elements to the foreground. 
* I chose a dark blue colour for the nav bar and the buttons. These are all points of contact for the user and I wanted them to stand out without
* contrasting with the rest of the sit. 
* I chose white for the register and social buttons in the footer, they stand out in contrast to the background-colour of the footer. 

3. Styling
* I used the Materialize framework which kept the site clean and simple.
* I decided not to curve off any edges on photos/cards, I want the site to have the resemblence of book corners throughout and the book images, 
to stay looking like books. 

## Wireframes 

All Wireframes were made using [Mock Plus](https://www.mockplus.com/)

* [Home Page Desktop](https://ibb.co/5K21mqw)    
* [My Books Desktop](https://ibb.co/DpCfWn6)
* [Log in Desktop](https://ibb.co/3f9GVdH)
* [Register Desktop](https://ibb.co/NjnygmY)
* [Add Book Desktop](https://ibb.co/0fcKBF6)

* [Home Page Mobile](https://ibb.co/bXJKL6p)    
* [My Books Mobile](https://ibb.co/dpNb3Lj)
* [Log in Mobile](https://ibb.co/X2LrHJL)
* [Register Mobile](https://ibb.co/mFjGqbM)
* [Add Book Mobile](https://ibb.co/xj2PQJG)


## Features

+ Nav Bar
 The Nav Bar is fixed at all times, includes a logo and links to 'Home', 'Log In' and 'Register' when not logged in, and 'Home', 'Add Book', 'My Books' and 'Log Out' when not
logged in. It also collapses on small and medium screens. 

+ Log In / Register options.
 There are Log in and Registration options in both the collapsable nav bar, standard nav bar and in the footer. It is important for this site to have register and log in Features
so you are able to add and save your own books. 

+ My books view.
 The My books views allows you to store, edit and delete all the books you have uploaded. 

+ Ability to add a book to your own view through the use of a switch. 
 Used to share a book onto the homepage or just store for your own purpose. 

+ Footer.
 The Footer includes copyright information in regards to the site, social links taking you to the developers GitHub and LinkedIn and a Register option if you aren't already a member.

## Features left to Implement

+ Search by Genre filter.
 Once the site is more established and therefore has more people uploading books, there will be a need to filter down the book choices via Genre.

+ Able to save other books from the homepage into your own 'My Books' view.
 The goal of the site in the long run will be to essentially save and 'buy/download' therefore we will need an option to save a book into the 'My Books' view, very similar to a shopping cart in online shopping. 

+ Ability to buy/download the books on the homepage.
 I would like my users to be able to watch advertisements and then download the book for a very small fee or preferably free. In the meantime I can provide a link to another site for my users to buy. 


## Technologies used

* HTML5
* CSS3
* Python

* [MongoDB](https://www.mongodb.com/)

* [Materialize](https://materializecss.com/)
* Jquery
* Flask
* PyMongo
* Brycpyt

* [Google Fonts](https://fonts.google.com/)
* [Font Awesome](https://fontawesome.com/)
* [Autoprefixer](https://autoprefixer.github.io/)
* [The W3C Markup Validation Service](https://validator.w3.org/)
* [The W3C Markup Validation Service](https://jigsaw.w3.org/css-validator/)

* [GitPod](https://gitpod.io/workspaces/)
* [GitHub](https://github.com/sw1ckham)

* Git

## Testing

I began my testing using.. 

- [HTML WC3 Markup Validation Service.](https://validator.w3.org/)
- [CSS WC3 Markup Validation Service](https://jigsaw.w3.org/css-validator/)

#### Mid-point CSS Validation bugs:

- line 227 - min-wdith is an unknown vendor extension (Corrected typo)
- line 213 - Same color for background-color and color (I kept this the same otherwise the line is not a block colour.)

#### Mid-point HTML Validation bugs:

- Throughout all my html pages I had forgotton to add an alt tag to my images (Corrected)

#### Final HTML Validation bugs:

-  The value of the for attribute of the label element must be the ID of a non-hidden form control.
- Attribute required is only allowed when the input type is checkbox, date, datetime-local, email, file, month, number, password, radio, search, tel, text, time, url, or week.

#### Final CSS Validation bugs:

- Congratulations! No Error Found.

### Bugs during developement

1. The columns the cards from Materialize were in, were not centering inside their row.
* [Solution](https://stackoverflow.com/questions/50671682/center-align-items-in-materializecss-row): Add a flexbox class to the column you need to center. Add custom styles to center. 

2. Edit book function, when you edit a book, the book would disappear. 
* Solution - I needed to add a 'username' field in the form, and in turn tell the function to pull the 'added by' username from the form and fill
that field in the database. Once I made those changes, the new edited version had the same username in the 'added_by' field as before and therefore
showed up correctly on the 'My Books' page with the correct changes made. 

3. Following from the bug above, I now need to make sure all fields are required, otherwise the book may not show in 'My Books', and the display will not look good. 
I added 'required' to the end of each input but this did not work. 
* [Solution](https://stackoverflow.com/questions/17966390/html5-required-attribute-seems-not-working) - I found a stack overflow post voicing the same bug, 
the solution was to close the input tags properly /> 

4. The height of my cards. The height of the card was changing dependant on how much text you wrote in the 'comments' sections. This was a problem
as design wise, it did not look good all the cards different heights. Also the cards overspill into other containers.
* Solution - Set a max charactor limit on each comments input. I found out what height the card was when all the charactors were used and set all cards
to be that height. 

5. The main heading 'Welcome to I-brary' would break at I-brary due to the hiphen.
* [Solution](https://css-tricks.com/forums/topic/prevent-word-breaks/) I copy and pasted a non-breaking-hyphen entity from the post linked. 

6. On the 'Add Book' and 'Edit Book' forms, I inserted a range slide from materialize but could not work out how to chnage the colour of the dot underneath the thumb. 
* [Solution](https://stackoverflow.com/questions/40534973/changing-the-color-of-the-range-slider-in-materializecss) The CSS needed was provided on this stack overflow post. 

7. The autofill background colour Google Chrome had as a default didn't suit the design of the site. 
* [Solution](https://stackoverflow.com/questions/2781549/removing-input-background-colour-for-chrome-autocomplete) Adding a few lines of css changing the default CSS. 

#### Client Stories Testing

1. To be able to register quickly without the site taking any unneccesary information.
* When signing up to the site I am currently only asking for a 'Username' and 'Password' to set up. As there is no purchasing from the site, I currently do not need anymore
    of their personal information. 
2. To be able to find new books I haven't read before.
* On the homepage is a library of all the books users have uploaded and decided to share. 
3. To be able to see the Genre and rating of new books so there is enough information for me to decide whether I would enjoy it. 
* Each book is displayed on a card, on this card are tabs displaying more information about the books. These fields have been set as 'required', so there will always be
  Genre and Rating information on each book on the site. 
4. To be able to navigate around the site with ease.
* The site's navigation bar is fixed therefore it is very obvious how to navigate from page to page. Also there is an option to 'Register' in the footer.
5. To be able to edit or delete my added books with ease.
* In the 'My Books' view, each book has an 'Edit' or 'Delete' button, when you choose to edit a book, it is required to input your username, this way the book will stay in 
  your 'My Books' view, and replace the old version of the book. 
6. To know that I am the only person able to edit my books that I have added.
* The Edit and Delete buttons only show up in the 'My Books' view, and you can only see 'My Books' when you are logged in. The books shows in the 'My Books' view, are only
  the books you have uploaded whilst being logged in. 
7. To know my books will be saved when I log out, so when I revisit the site, my books are still there.
* All books are save inthe MongoDB Atlas databse therefore will always be rendered to the site if added to the database. 

#### Manual Testing

Below is a checklist completed by the developer and 2 third parties. The checklist was completed on all devise sizes. 

1. Navbar/navigation
* When not logged in, the navbar shows - 'Home', 'Log In', 'Register'.
* Once registered or logged in, the navbar shows - 'Home', 'Add Book', 'My Books', 'Log Out'.
* When viewing the site on medium or small screens, the navbar becomes a dropdown from a toggle button in the top left hand corner. 
* At all times the Navbar is fixed to the top of the screen so you can see it at all times. 

2. Footer
* In the footer you have a link called 'Register' that takes you to the 'Register Form'. 
* There are also a GitHub and LinkedIn icon, when you click on the icons it opens a seperate browser taking you to the developers profiles. 
* Above the footer is an up arrow, once clicked it takes you back to the top of the homepage. 

3. Log In
* Try to Log In leaving one or/and both input fields empty - you will get an error message saying 'Please fill out this form'
* Try to Log In with credentials having not registered yet - an error message appears saying 'Incorrect username/password'.
* Click on the link underneath the form 'Sign up here', you are taken to the registration page to sign up. 
* Having already registered, try to log in with either the username inccorect - an error message appears saying 'This username does not exist'. I haven't specified which for added security. 
* Log in with your correct credentials - you are taken to the homepage and now have the option to 'Add Book' or view 'My Books' in the navbar. 

4. Register
* Try to Regitser leaving one or/and both input fields empty - you will get an error message saying 'Please fill out this form'
* Try to register with a existing user log in credentials, both username and password, and then just the correct username, and just the correct password - you will get an error saying 'This username already exists'. 
* Register as a new user with unique information, you will be taken to the homepage, you will have an 'Add Book' and a 'My Books' view, the 'My Books' view is empty. 
* Fill out the 'Add Book' form, click share, log out, log back in with your new user information. You will see you added book in your 'My Books' view and on the homepage. 

5. My Books
* When in your 'My Books' view, you have 'Edit' and 'Delete' buttons below each of your book entries.
* You click on 'Edit' and it takes you to an 'Edit Book' form, all of the original information autofilled.
* You are able to change one or all fields. 
* Try to Edit a book but leave one or/and more input fields empty - you will get an error message saying 'Please fill out this form'.
* Once edited, click edit book, it takes you to your 'My Books' view with the new version of the book replacing the old. 
* In 'My Books' click on 'Delete', the book disappears in 'My books' and also on the homepage. 

6. Add Book
* When you click on 'Add Book' in the navbar, it takes you to a form headed 'Add Book'
* Try and submit the form with one of the input fields missing - you will get an error saying 'Please fill out this form'. Do this for every input field. You will get an error
for every input field except, 'Rating' (as it's default is 5), Comments and 'Share' (as it's default is off).
* Fill out the form correctly and click share, your new book will render in your 'My Books' view and the homepage. Do this again and do not share, the book will only render on
your 'My Books' view. 

#### Bugs discovered during manual testing from a third party

No bugs or problems from the third party manual testing.

#### Bugs Disovered during manual testing from the developer

1. TESTING RESPONSIVENESS 
* When on looking at the site on Google Dev tools on the responsive mode, the carousel on the front page doesn't seem to change size like it should when you change screen sizes.
You have to refresh every time to see how the carousel actually looks on that screen size. Still have not solved this issue as it doesn't seem to be a problem with my code. 
All sizes given to the carousel are correct and are user friendly and responsive on all screens. 
* Solution - I spoke to my mentor Spencer Barriball about this, we think it is a bug within the carousel itself and I was told not to worry as it renders
properly and has been styled properly on my side so will look fine on each devise for the user. 

## Deployment

#### I developed this project using the GitPod, committing to Git and pushing to GitHub via the locally installed Git commands. 

#### The following steps are how to create an app in heroku and connect it to 

- Login to heroku and go into your personal apps.
- Click **New** in the top right corner and create a new app, pick your closest region.
- In your CLI associate the heroku application as our remote master branch - heroku git:remote - a [app name]

#### The following steps run through how I deployed this project to [Heroku.](https://dashboard.heroku.com/) 

- Add a requirements file (list of applications heroku requires to run the app) - **pip3 freeze --local > requirements.txt**
- Git add and commit requirements file
- Add a Procfile (we need to tell heroku which file is used as our entry point to the app) - **echo web: python app.py > Procfile**
- Git add and commit requirements file
- Push to Github and Heroku - **git push origin master && git push heroku master**
- Tell Heroku to get the app up and running - **heroku ps:scale web=1**
- Go to settings in Heroku - Reveal config vars - Put in IP and PORT values (remember if the values are IP: 0.0.0.0, PORT: 5000)
- Open app. 

#### Running this project locally... 

1. Log into your GitHub
2. Find the repository via this link [I-brary](https://github.com/sw1ckham/i-brary)
3. Click on **clone or download**, copy the clone URL under **clone with HTTPS**.
4. Open up your IDE, and open **git bash**
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type **git clone**, and then paste the URL you copied. example: **$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY**
7. Press Enter. Your local clone will be created.

## Credits

### Content

All content written in this project was written by the developer.

### Media

- I sourced all photos for the books from online mainly google images and copied the image url. 

- All icons came from [Materialize's library](https://materializecss.com/icons.html) 

### Code 
* Retrieved the [code](https://materializecss.com/cards.html) for my books cards from materialze and Edited.  
* This [Stack Overflow post](https://stackoverflow.com/questions/50671682/center-align-items-in-materializecss-row) helped me center the cards on index.html.*
* I used [CSS matic](https://www.cssmatic.com/box-shadow) to create my box shadows
* I used [W3 Schools](https://www.w3schools.com/tags/att_textarea_maxlength.asp) to help me work out how to apply a max-length to a text area.
* I used [Autoprefixer](https://autoprefixer.github.io/) to add broswer prefixes to my CSS code. 

### Acknowledgements

Thank you very much to my mentor Spencer who helped me throughout. 
Also to the student care tutors Tim, Stephen, Samantha, Cormac and Kevin. 
'Igor' on Slack who was always quick to lend a hand. 

