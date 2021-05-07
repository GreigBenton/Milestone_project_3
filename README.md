# The Book Finder

A collection and database of community suggested and reviewed books which allows users to search for, share, edit and delete books so that they can expand their experiences with reading material. Featuring login and logout functionality, collapsible sections, admin only Genre pages and the ability to complete all CRUD functionality.

--- 

##UX

*The Book Finder* design and user experience philosophy is all about simplicity and ease of use. The main landing page comprises and displays all books shared by the community with a search bar/function at the very top allowing users to search via Book Title, Author, Genre or keywords within the book summary/description. User's can then also share books they have read via a separate page allowing them to provide all neccessary information and provide a personal review of the book. From the user's profile page they can view all books that they have shared with the community and here have the ability to edit the book listing or remove it entirely.

* As a new user I want to know upon viewing the site what options I have in terms of signing up/registering and viewing the sites content. I want this to be presented via a clear and navigatable menu.

* As a user I want to be able to separate books I have shared from those other users/members of the community have shared. I want this to be displayed via a separate Profile page which will allow me to edit/change previously uploaded content and the ability to remove content should I no longer wish to share this information.

* As a user viewing the site I want to know key details at a glance including Genre etc so that I can pinpoint and hone my search.

* As a user I want to be able to view extended information once I see a book/information that interests me. This information should include a book cover image, a brief summary of the work and purchase information.

* As a user I want to be able to view different user's opinions about the book I am researching/looking at so that I can make a more informed decision about whether or not to purchase/read the aforementioned book.

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

## Deployment
1. Throughout project development, use of 'git add' and 'git commit' functions within project terminal to save changes and document development process. Each commit message explains and shows changes since the last version and provides information to users viewing the repository.
2. Throughout development regular use of 'git push' function. This function pushes changed/new code to GitHub and ensures the code is safe and protected from potential loss or system/cloud error.
3. Integrated GitHub to Heroku platform. Each new commit and push of changes will now be represented on both GitHub repository and Heroku. This allows for seemless protection of data and a backed up workspace.
3. Once the project completed visit the repository via GitHub @ *https://github.com/GreigBenton/Milestone_project_3*
4. From here visit Settings to find deployment steps.
5. Scroll down to the GitHub pages section.
6. Ensure the master branch is selected and *Save*.
7. Project is now visible and live @ *https://github.com/GreigBenton/Milestone_project_3* **AND** *https://dashboard.heroku.com/apps/milestone-3-book-database.*

#### Local Cloning
1. After downloading GitHub Desktop user logs into to their GitHub profile
2. Selects the repository and branch they wish to clone
3. Denotes the local path 
4. Clicks 'Clone'

## Credits

#### Content
- Book information specifically book summaries/description were taken from Wikipedia. [WikiPedia](https://en.wikipedia.org/wiki/Main_Page)

#### Media
- Book Covers/images were taken from Amazon pages. [Amazon](https://www.amazon.co.uk/ref=nav_logo)
- Purchase links etc were taken from Amazon pages. [Amazon](https://www.amazon.co.uk/ref=nav_logo)

## Inspiration 
- Inspiration was taken from Task Manager mini project to form structure and layout of page/project. Content was inspired by a desire to have a design focussed and easy to navigate book recommendation platform free from clutter.

----


