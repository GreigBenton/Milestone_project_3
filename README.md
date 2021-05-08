# The Book Finder

A collection and database of community suggested and reviewed books which allows users to search for, share, edit and delete books so that they can expand their experiences with reading material. Featuring login and logout functionality, collapsible sections, admin only Genre pages and the ability to complete all CRUD functionality.

--- 

##UX

*The Book Finder* design and user experience philosophy is all about simplicity and ease of use. The main landing page comprises and displays all books shared by the community with a search bar/function at the very top allowing users to search via Book Title, Author, Genre or keywords within the book summary/description. User's can then also share books they have read via a separate page allowing them to provide all neccessary information and provide a personal review of the book. From the user's profile page they can view all books that they have shared with the community and here have the ability to edit the book listing or remove it entirely.

* As a new user I want to know upon viewing the site what options I have in terms of signing up/registering and viewing the sites content. I want this to be presented via a clear and navigatable menu.

<img width="1280" alt="Screenshot 2021-05-07 at 15 11 03" src="https://user-images.githubusercontent.com/68287350/117462835-f2bd5d00-af46-11eb-9920-ef4dfa6b8dab.png">

<img width="1280" alt="Screenshot 2021-05-07 at 15 11 16" src="https://user-images.githubusercontent.com/68287350/117462951-0ff22b80-af47-11eb-8c1e-a23900cc390c.png">

* As a user I want to be able to separate books I have shared from those other users/members of the community have shared. I want this to be displayed via a separate Profile page which will allow me to edit/change previously uploaded content and the ability to remove content should I no longer wish to share this information.

<img width="1114" alt="Screenshot 2021-05-07 at 15 11 43" src="https://user-images.githubusercontent.com/68287350/117463007-1ed8de00-af47-11eb-9629-bfc38c0725f6.png">

* As a user viewing the site I want to know key details at a glance including Genre etc so that I can pinpoint and hone my search.

<img width="909" alt="Screenshot 2021-05-07 at 15 12 08" src="https://user-images.githubusercontent.com/68287350/117463069-2ef0bd80-af47-11eb-8855-4c04d34ecc4c.png">

* As a user I want to be able to view extended information once I see a book/information that interests me. This information should include a book cover image, a brief summary of the work and purchase information.

<img width="896" alt="Screenshot 2021-05-07 at 15 12 34" src="https://user-images.githubusercontent.com/68287350/117463105-3748f880-af47-11eb-83e1-5645513fe21b.png">

* As a user I want to be able to view different user's opinions about the book I am researching/looking at so that I can make a more informed decision about whether or not to purchase/read the aforementioned book.

<img width="897" alt="Screenshot 2021-05-07 at 15 12 46" src="https://user-images.githubusercontent.com/68287350/117463148-4465e780-af47-11eb-8d14-d2ad98fdb59a.png">

## Features

#### Exisiting Features

1. Navigation bar - allows users to navigate between pages easily with identifiable descriptors and an easy to understand structure. Is consistent across the entire platform. The brand logo takes the user's back to the home/landing page as is industry standard

2. Collapsible content - this allows to collapse and expand content so that page real estate is easy to view and not cluttered. Upon expanding a new piece of information the previously collapsed content will then close.

3. Share Book - this allows a user who has logged in/signed up to share a book with the community. Upon selecting this option the user will be able to provide all neccessary information about the book to inform and provide their fellow user with as much content as possible.

4. Tooltips/Icons - creates visual and hoverable aids that help a user edit/share a new books. Each tooltip will open whe the associated icon is hovered over and will provide a piece of useful information to the user.

5. Curated Profile page - allows logged in users to view any and all books they have personally shared/uploaded. From here a user can then edit the specific book entry or remove it from the site and database.

6. Search Function - allows users to search for and pinpoint their use of *The Book Finder* by searching using keywords/indexing. This search can then be reset and will show if their are no options found for their current query.

7. Admin Only Genres - allows admin/super users to edit and create/remove Genres which can then be selected by user's when sharing a new book with the community.

#### Future Feature Ideas

1. Confirmation Functionality - this new feature will prompt a user when choosing to remove/delete a shared book. This will be presented in form of a popup/modal which will ask the user explicitly if they wish to continue with the action of deletion.

2. Interactive Reviews - this feature will allows other users aside from the original creater the option/ability to leave their own reviews of books that are listed on the database. This will provide the community with more varied and a wider range of information and opinions.

3. Separate Genre specific tabs/content - this feature will expand upon the current collapsible content allowing our users to tab through each Genre at the top on the expandable content. Each option within that tab will then only be associated with/be of the selected Genre. This will speed up user enquiries.

## Technologies Used

* [HTML](https://html.spec.whatwg.org/#is-this-html5?) 
    * Used to write the fundamental content of the project

* [CSS](https://www.w3.org/TR/CSS2/)
    * Used to style the project

* [Python](https://www.python.org/)
    * Used to provide vast majority of content and allows for integration of databases and apps such as Flask

* [Flask]( https://flask.palletsprojects.com/en/1.1.x/)
    * Mini framework used alongside Python to create and form content used within project

* [MongoDB](https://www.mongodb.com/)
    * Database used to create, store and collate information and data used in this project.

* [Materialize](https://materializecss.com/)
    * Used to style the project and provides interactive frameworks

* [JQuery](https://jquery.com/)
    * Used to allow functionality of dropdown menus in conjunction with Materialize framework 

## Testing

#### Navigation Links/bar
1. **Expected Results**

        - All links should open their associate html file successfully from all pages. 
        - Site logo should navigate user back to index.html page/landing page.
2. **Reasons for testing**

        - User performs extensive testing on this feature as this is the user's main port of call for navigating through the site.
        - If links are broken then user is unable to access full content.
3. **Tests performed**

        - To test links are working correctly and are opening appropriate HTML the user visits each link from each HTML page, ensuring that each link opens appropriate file and can navigate the entire site via each page.
        - To test logo is directing users back to index.html the user clicks this logo from each page and ensures that they are redirected back to the landing page.
4. **Testing Results**

        - Each link opened the appropriate page when clicked on from each html page as intended.
        - Clicking logo from each page resulted in the user being directed back to landing page as intended.

#### Sign-Up/Login functionality

1. **Expected Results**

        - Both username and password fields should display as red if incorrect value type has been input/entered. 
        - Password field should be encrypted and not displayed when entering password.
        - Upon signing up/logging in the user should be rdirected to the correct page with accompanying Flash/info to inform user of success.
        - Upon signing up, user data including username and hashed password should be inserted into database.
        - Upon logging in the user should be redirected to their profile page.
        - Upon logging out the user should be redirected to the correct page and any user options other than Home etc should not be visible.
2. **Reasons for testing**

        - The ability to share books and effectively build the content of the site is dependent on users being able to sign-up and login. 
        - If a user has an issue when signing up they are unlikely to return to use the site. This is a bad user experience.
        - If a users password security is compromised this can cause data breaches and potentially break GDPR protocols.
3. **Tests performed**

        - Used dummy accounts to test login/sign-up process. 
        - Entered username and password field and then left field without entering value data to see if defensive programming would activate.
        - Checked MONGODB for inserted data upon signup
4. **Testing Results**

        - Upon signing up/logging in. User is redirected to their personal profile page as intended.
        - Upon signing up. New user data is inserted into appropriate database collection as intended.
        - When inputting/entering username/password if incorrect or unsuitable values are entered the form will not let the user continue with process as intended.
        - Upon signing out user was redirected to the appropriate page.

#### Home page - Search functionality

1. **Expected Results** 
        
        - When searching and submitting form, user should be presented with any data entries that meets search criteria via Book name, author name, genre or book description. Picking up keywords and displaying the appropriate entries.
        - Upon resetting the search form all data/list entries should appear
        - When searching, if no results are found then a message should appear to show the user that their search hasn't yielded any results.
2. **Reasons for testing** 

        - Search functionality is incredibly important as to be a useful database the community needs to be able to filter results based on their desires and tastes. A poorly executed search function or one limited in scope will result in poor UX.
3. **Tests performed**

        - Searched for various terms that may or may not appear within the indexed fields. These varied from names of authors to genres and keywords that may have been included in a book description e.g. 'Mystery'
        - After each successful search hit the reset button to test its functionality.
        - Used keyword searches I knew were not in any current entries to see if correct flash message appeared.
4. **Testing Results**

        - When searching, each time results/entries which were applicable appeared as intended.
        - Each hit of the Reset button correctly cleared the search data and returned the intitally listed entries.
        - When searching for a term that wasn't present or applicable the correct message appeared to inform the user that their search garnered no results as intended.

#### Home page - Collapsible card

1. **Expected Results** 
        
        - When clicking on the collapsible header containing both book title and genre the collapsible body should appear to show further information about the entry.
        - Upon clicking the purchase link within the card the user should be redirected to a new tab with the correct purchase link
2. **Reasons for testing** 

        - The data in which users will learn about new books and ultimately decide whether or not they are interested in them is contained within these collapsible cards. If these do not function correctly then the site does not meet it's intended purpose.
        - The business model of the site is an affiliate based system and therefore correct working links to each shared book is of utmost importance.
3. **Tests performed**

        - Clicked on each and every entry to ensure that each one collapsed/extended correctly while the previously selected entry closed to execute good UI.
        - Clicked each link to ensure that the user is directed to the purchase site in a new tab providing good UX.
4. **Testing Results**

        - When collapsing each field, the correct data appeared and was displayed intuitively and in a well laid out space.
        - When visiting each purchase link the correct new tab and page opened ready for the selected book to be purchased.

#### Profile page 

1. **Expected Results** 
        
        - When viewing the profile page only the entries created by the current user should appear, allowing them to edit/remove their entry.
        - When clicking 'Edit' the user should be redirected to the appropriate page
        - When clicking 'Remove' the correct entry should be deleted from the site and also the link database.
2. **Reasons for testing** 

        - The ability to only see entries that the current user has made creates a better UX and allows for easier editing and removal of the intended entry. This functionality is essential to CRUD.
3. **Tests performed**

        - Logged in using multiple dummy accounts which has created different entries to ensure only entries created by that user account appeared.
        - Clicked edit on each entry to ensure the user was directed to the correct edit template.
        - Removed test entries from multiple accounts to ensure the selected entry was removed.
4. **Testing Results**

        - When visiting the user profile page on multiple accounts, the correct and appropriate entries appeared when filtering via the created user.
        - Each use of the edit button resulted in the user being directed to the edit template as intended.
        - Each use of the remove button resulted in the selected and associated entry being removed. Upon checking and referring back to MONGODB the entry was also removed from the database as intended.

#### Share/Edit Book page

1. **Expected Results** 
        
        - When visiting the share book navigation link the user should be directed to the correct template.
        - When on the share book template and hovering over the field icons a tooltip should appear presenting further information/examples.
        - When sharing/editing a book if the user attempts to input incorrect data/values the field should display a message if the currently input data doesn't meet the field standards.
        - When a user confirms the listing the user should be redirected to the home page with an accompanying success flash.
        - When sharing a book if a user decides to cancel their entry they should be redirected to the home page.
        - When editing a book the initial data should be represented upon the page being loaded so that the user can see the data they will be replacing.
2. **Reasons for testing** 

        - Search functionality is incredibly important as to be a useful database the community needs to be able to filter results based on their desires and tastes. A poorly executed search function or one limited in scope will result in poor UX.
3. **Tests performed**

        - Searched for various terms that may or may not appear within the indexed fields. These varied from names of authors to genres and keywords that may have been included in a book description e.g. 'Mystery'
        - After each successful search hit the reset button to test its functionality.
        - Used keyword searches I knew were not in any current entries to see if correct flash message appeared.
4. **Testing Results**

        - When searching, each time results/entries which were applicable appeared as intended.
        - Each hit of the Reset button correctly cleared the search data and returned the intitally listed entries.
        - When searching for a term that wasn't present or applicable the correct message appeared to inform the user that their search garnered no results as intended.


## Deployment
1. Throughout project development, use of 'git add' and 'git commit' functions within project terminal to save changes and document development process. Each commit message explains and shows changes since the last version and provides information to users viewing the repository.
2. Throughout development regular use of 'git push' function. This function pushes changed/new code to GitHub and ensures the code is safe and protected from potential loss or system/cloud error.
3. Integrated GitHub to Heroku platform. Each new commit and push of changes will now be represented on both GitHub repository and Heroku. This allows for seemless protection of data and a backed up workspace.
3. Once the project completed visit the repository via GitHub @ *https://github.com/GreigBenton/Milestone_project_3*
4. From here visit Settings to find deployment steps.
5. Scroll down to the GitHub pages section.
6. Ensure the master branch is selected and *Save*.
7. Project is now visible and live @ *https://github.com/GreigBenton/Milestone_project_3* **AND** *https://milestone-3-book-database.herokuapp.com/.*

#### Local Cloning
1. After downloading GitHub Desktop user logs into to their GitHub profile
2. Selects the repository and branch they wish to clone
3. Denotes the local path 
4. Clicks 'Clone'

#### Differences deployed and development version
1. No changes in deployed version to note

## Credits

#### Content
- Book information specifically book summaries/description were taken from Wikipedia. [WikiPedia](https://en.wikipedia.org/wiki/Main_Page)

#### Media
- Book Covers/images were taken from Amazon pages. [Amazon](https://www.amazon.co.uk/ref=nav_logo)
- Purchase links etc were taken from Amazon pages. [Amazon](https://www.amazon.co.uk/ref=nav_logo)

## Inspiration 
- Inspiration was taken from Task Manager mini project to form structure and layout of page/project. Content was inspired by a desire to have a design focussed and easy to navigate book recommendation platform free from clutter.

----


