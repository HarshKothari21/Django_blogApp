# Blog Application With Python(Django)

- Blog App is similar web application as twitter. Here Users can view blogs created by other user.
 User first need to Sin-Up in order to create, Update and Delete their blog and view other users profile

## Features
- User Authentication(Login, Registeration)
- Forgot Password (Through Gmail)
- Create, Update, Delete User Blogs
- User profile 
- Template Inheritance

## Technology Stack
- Python | Django | HTML | CSS | Bootstrap | Javascript | MySQL | CrispyForm

## Project Description

- This project is divided in three apps:
1) Blog 
2) Users 
3) BlogWebsite

- Html files are Under Template folder.It contains one Base.html file that inherites all other html files.
- Mapping of these functions are under urls.py file.
- Models are created under models.py file.
- The User folder handles user Login, Logout, Registeration and User Profile. In views.py file functions are created which is basically logic behind these features . 
- The Blog folder consist of Blog part of Application. 
- All the static content i.e CSS and Javascript files contains under static folder
