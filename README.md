
Youtube: https://youtu.be/QQWkklIEr1Q
# SquareTable
![Logo](https://i.ibb.co/VvDN7PC/1-B48-E313-613-F-438-A-934-B-A7-E984161676-modified.png)

The overall purpose of this application is to serve Harvard users who 
deem themselves “foodies” so that they can explore the amazing 
restaurants Harvard Square has to offer as well as connecting with 
other users who are also foodies.

    1: Register/Login Page
![App Screenshot](https://i.imgur.com/e7iWV5V_d.webp?maxwidth=1520&fidelity=grand)
With a similar setup as Finance, the register and login page take a username and password, and then register or log in a user. Users can not have the same username as another user. Additionally, users can sign in with a Google account, which is a lot more convenient for some users. Along with this page comes a feature that allows users to ask for a new password by clicking on the “forgot password” link. There is also an email confirmation to approve and verify a new account through Supabase that goes directly to the user's email address. The usernames are stored in a database that we can access in Supabase. Finally, there is a small button in the bottom right that allows users to message us directly should they have any questions, suggestions, or concerns with SquareTable. 

    2: Survey 
![App Screenshot](https://i.imgur.com/xOXOh3k_d.webp?maxwidth=1520&fidelity=grand)

Users, once (and only once) new to SquareTable, are immediately asked to fill out an entry survey to document their basic information (name, house, year, phone number, etc.), gustatory preferences, and three restaurants in Harvard Square that they feel they should review (for good or for bad). For the three restaurants section, users must enter the name of a restaurant, the cuisine that the restaurant offers, and a review to describe the restaurant (again, reviews can be negative in the survey should a user feel compelled to do so). This information is submitted with a button, and it is posted immediately to their profile page so that other users can see what they have to say and also contact them to set up a TableDate.

    3: About Us
![App Screenshot](https://i.imgur.com/Huzfv6j.jpg_d.webp?maxwidth=1520&fidelity=grand)
This page pays homage to Homepage, and it is a brief biography about SquareTable’s founders. We found that about us pages are quite common in start-up style websites, so we thought it would be appropriate for our foodie users to get to know us. There are a few images of us, a brief description of who we are, and links to multiple ways to get in touch with us (Instagram, email, direct message).

    4: Square Now
![App Screenshot](https://i.imgur.com/5fGVPk1.jpg_d.webp?maxwidth=1520&fidelity=grand)
This page, the main feature of SquareTable, serves as an explore page for users who are curious to see what is going on in the Square. SquareNow gives users the opportunity to read the reviews and ratings of other users on restaurants in Harvard Square. In this page, there are pictures of Harvard Square restaurants, multiple reviews of said restaurants, and a link to the user profile of each user who has posted a review. Additionally, SquareNow has a post button where users can add and edit their reviews.

    5: User Profile
![App Screenshot](https://i.imgur.com/KUeyFi4_d.webp?maxwidth=1520&fidelity=grand)
The User Profile uses information from the introductory survey, and makes it available for all users to see (this means that people who do not have an account can not see user profiles). In case a user notices that they have the same taste as another user, preferences, ratings, comments, etc. as another user, the user profile gives them access to the contact information of that user should they want to reach out and organize a “TableDate” at a restaurant they might enjoy together. Users can also edit or delete their user profiles at any time, and they have the option to change information in just one section, or change the entire profile completely.

    6: Restaurant Database
This SQL database stores information about restaurants in Harvard Square, including the name, address and cuisine. SquareTable incorporates the restaurant database in multiple pages, including the User Profile (where a user’s top three restaurants are displayed), Square Now (where users can read reviews and news about Harvard Square restaurants), and the intro survey (where we store a user’s top three restaurants and other gustatory preferences). 

    7: Navigation Bar
![App Screenshot](https://i.imgur.com/5ZkNqO9_d.webp?maxwidth=1520&fidelity=grand)

The top of every page in SquareTable includes a navigation bar, where users can seamlessly move from one page to another, clicking on one of multiple links that take them to the respective page, including all of the pages above. 

    8: Home Page
![App Screenshot](https://i.imgur.com/bklisM1.jpg_d.webp?maxwidth=1520&fidelity=grand)
The homepage is similar to SquareNow, but its purpose is to serve as an introduction for new users. In the homepage, users can read up about restaurants in the Square and start figuring out what they might want to review in SquareNow.

    Implementation
SquareTable is implemented in React, with elements of HTML, JavaScript, CSS, and SQL. Using an API, user information is stored on our end, which 1, secures the user information from malicious hackers who for some reason would want to see what a user’s favorite restaurant is, and more importantly 2, gives us direct access to communicate with a user in case there are suggestions or questions that they have, vulgar comments that we might have to speak with them about, complaints about a user’s behavior, or anything else that would warrant our involvement. 

    User Manual
Here is a step by step guide to navigating our website:

Step 1:
Go to www.squaretableharvard.com to begin.

Step 2: 
Enter a username and password (either using a Google account or not) and follow the instructions in your email to verify your account.

Step 3: 
Take the survey. When prompted for "Restaurant", "Cuisine", and "Describe", enter the name of a restaurant in Harvard Square, enter the kind of cuisine it offers, and enter a review for this restaurant (it can be vague or very detailed).

Step 4: 
Feel free to navigate the website freely, and do check out the SquareNow section by using the navigation bar to see what is going on in Harvard Square! Alternatively, read the reviews of other users and see if you have anything in common with a particular user. Who knows, you might even feel compelled to reach out to them and set up a TableDate! ![App Screenshot](https://i.imgur.com/z2GYKyr.png_d.webp?maxwidth=100&fidelity=grand)

And, that's it; you've finished. This was CS50!
