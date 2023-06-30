# Social Media Web Application

This is a social media web application built using the Django framework.
  
### Features

- Send friend requests to other users and accept/reject requests received
- User sign up and login
- Create and edit profile page
- Create and edit posts uploaded by the user
- Password Reset option available to user
- Like/Unlike posts
- Comment on user posts
- Search for users and posts through the search bar

###  Technologies Used


Backend : `Django`
<br/><br/>
Frontend : `HTML5, CSS(Bootstrap4 + Custom CSS), AJAX`
<br/><br/>
Database: `Sqlite3`
<br/><br/>

### Installation

1. - Fork the [repo](https://github.com/addy-1406/Social_Media/tree/master)
   - Clone the repo to your local system
   ```git
   git clone https://github.com/addy-1406/Social_Media.git
   cd Social_Media
   ```
   Make sure you have python installed on your system.
2. Create a Virtual Environment for the Project

   If u don't have a virtualenv installed

   ```bash
   pip install virtualenv
   ```
   **For Windows Users**
   ```bash
   virtualenv env
   env/Scripts/activate
   ```


   **For Linux Users**
   ```bash
   virtualenv env
   source env/Scripts/activate
   ```

  [//]: # ( If you are giving a different name than `env`, mention it in `.gitignore` first)

3. Install all the requirements

    ```bash
   cd photoshare
   ```

   ```bash
   pip install -r requirements.txt
   ```

4. Make migrations/ Create db.sqlite3

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Create a super user.
   This is to access Admin panel and admin specific pages.

   ```djangotemplate
   python manage.py createsuperuser
   ```
   

   Enter your username, email and password.

6. Run server
   ```bash
   python manage.py runserver
   ```
<br/>



### Screenshots of Website

**Sign Up Page**

<img width="1276" alt="SignUp" src="https://github.com/addy-1406/Social_Media/assets/53403138/11683166-36d0-440c-a52b-f9d147d9a66e">
<br/>

**Home Page**

<img width="1276" alt="HomePage" src="https://github.com/addy-1406/Social_Media/assets/53403138/e4311615-d436-48c8-bbf7-cb880e43bbf8">
<br/>

**Create Post Page**

<img width="1276" alt="CreatePost" src="https://github.com/addy-1406/Social_Media/assets/53403138/3661bd9d-aee6-474c-9c2b-5c05d65811ca">
<br/>

**Page to keep track of friend requests received and sent**

<img width="1276" alt="Socialize" src="https://github.com/addy-1406/Social_Media/assets/53403138/e78c3b64-b23c-4d7a-a117-343f7da7edf5">
<br/>

**Comments section for a post**

<img width="1276" alt="Comment Section" src="https://github.com/addy-1406/Social_Media/assets/53403138/a18c551f-f356-4243-a1fd-0bbeb1a2bc72">
<br/>

**Update Profile Page**

<img width="1276" alt="Update Profile" src="https://github.com/addy-1406/Social_Media/assets/53403138/2d3dfbdb-2abb-4d45-a83f-59f2142804e8">
<br/>






  
