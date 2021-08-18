# tech-blog

## Description

To visit the deployed application, click this link: [**tech-blog**](https://techblog-pablodlc.herokuapp.com/).

**tech-blog** is a study in the **M**odel **V**iew **C**ontroller ("**MVC**") Paradigm. The Models being `Comment.js`, `Post.js`, and `User.js`, each of which handling their namesake's data structure. I utilized Handlebars.js to handle the Views, making some pages and partials to render the page. Controllers have their own eponymous folder containing the routes necessary for the blog.

This application was written following the guidelines laid out in the provided [User Story](#User%20Story) and [Acceptance Criteria](#Acceptance%20Criteria).

### Table of Contents

-   [User Story](#user-story)
-   [Acceptance Criteria](#acceptance-criteria)
-   [Installation](#installation)
-   [Future Developments](#future-developments)
-   [Questions?](#questions)

#### User Story

> AS A developer who writes about tech  
> I WANT a CMS-style blog site  
> SO THAT I can publish articles, blog posts, and my thoughts and opinions

#### Acceptance Criteria

> GIVEN a CMS-style blog site  
> WHEN I visit the site for the first time  
> THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in  
> WHEN I click on the homepage option  
> THEN I am taken to the homepage  
> WHEN I click on any other links in the navigation  
> THEN I am prompted to either sign up or sign in  
> WHEN I choose to sign up  
> THEN I am prompted to create a username and password  
> WHEN I click on the sign-up button  
> THEN my user credentials are saved and I am logged into the site  
> WHEN I revisit the site at a later time and choose to sign in  
> THEN I am prompted to enter my username and password  
> WHEN I am signed in to the site  
> THEN I see navigation links for the homepage, the dashboard, and the option to log out  
> WHEN I click on the homepage option in the navigation  
> THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created  
> WHEN I click on an existing blog post  
> THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment  
> WHEN I enter a comment and click on the submit button while signed in  
> THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created  
> WHEN I click on the dashboard option in the navigation  
> THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post  
> WHEN I click on the button to add a new blog post  
> THEN I am prompted to enter both a title and contents for my blog post  
> WHEN I click on the button to create a new blog post  
> THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post  
> WHEN I click on one of my existing posts in the dashboard  
> THEN I am able to delete or update my post and taken back to an updated dashboard  
> WHEN I click on the logout option in the navigation  
> THEN I am signed out of the site  
> WHEN I am idle on the site for more than a set time  
> THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments

## Installation

Clone tech-blog's repository from GitHub located here [pablodlc/tech-blog](https://github.com/pablodlc/tech-blog).  
Or enter this command in the folder on your device where you would like to store **tech-blog**:

```css
git clone https://github.com/pablodlc/tech-blog.git
```

After successfully cloning tech-blog on your device, run npm i in the terminal at the root of the application. This will install the dependencies that can be found in the package.json file. Below is an image of the dependencies in package.json:  
![dependencies](./public/images/dependencies.jpg)

## Future Developments

Clearly this application has room for improvement. The primary actions would be to finish the project following the specifications from the _Acceptance Criteria_. Once the application meets the MVP, I would personalize the app with a color scheme and a stylistic theme to the elements--something like consistent `border-radius` styles on elements on the page and changing the `text-families`.

## Questions

Please feel free to contact me with any questions or comments, or visit my GitHub to see more of my work.  
[Contact me by email](mailto:pablodlc@gmail.com)  
[GitHub User pablodlc](https://github.com/pablodlc)  
[**tech-blog** GitHub Repo](https://github.com/pablodlc/tech-blog)

**tech-blog** made with ❤️ by pablodlc
