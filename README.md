# Blogman

## **Introduction**
Blogman is an informative blog on which users can like, view, edit posts and engage with others in the comment section. Blogman also has a log-in and sign-up option. It is a project which combines a user-friendly interface on the front end and also the functionality on the back end.

Blog is made for educational purposes with guidance from [Code Institute](https://codeinstitute.net) facilitators. Its core purpose is to apply new learnings and implement them in a practical example.
 
> Disclaimer! Blogman was made alongside guided mentorship, and it's meant to be strictly for educational purposes.

## **Preview**

Here is a [live preview](https://blogman-2022.herokuapp.com/) of the project. 

<img width="1433" alt="Screenshot 2022-11-01 at 06 59 47" src="https://user-images.githubusercontent.com/103571907/199169196-0d2f9d2c-88f1-4f2f-8c55-4bd4fd13bce3.png">


## **Features**

 - Responsive navigation
 - Login & Sign up function
 - View and post coments
 - Liking posts
 - Admin Dashboard (approve comments functionality, approve posts, delete,...)
 - Alerts
 - Summernote text editor
 - Data and Images stored on database

<img width="1440" alt="Screenshot 2022-11-01 at 06 36 21" src="https://user-images.githubusercontent.com/103571907/199169300-a8bc5d3b-043f-4985-bed2-d853a669d511.png">

<img width="1440" alt="Screenshot 2022-11-01 at 07 00 43" src="https://user-images.githubusercontent.com/103571907/199169380-30ae5bf0-327b-475c-9332-92bee08093c8.png">
 
<img width="816" alt="Screenshot 2022-11-01 at 06 53 14" src="https://user-images.githubusercontent.com/103571907/199169570-f579d163-37bd-40e7-8c85-7e6dbff94a72.png">
 
<img width="1139" alt="Screenshot 2022-11-01 at 06 58 55" src="https://user-images.githubusercontent.com/103571907/199169440-9fef7bd1-b5c3-4a4b-ab67-1f37b89f12e7.png">

> **Admin login information:**
> Username: *admin*
> Password: *admin123*

## **Technologies**

Technologies and their versions being used in this project:

 -   HTML 5
 -   CSS 3 
 -   Javascript ES6
 -   Python 3.8

#### Frameworks

 - [Django](https://www.djangoproject.com/) 3
 - [Bootstrap](https://getbootstrap.com/) 4

#### Packages, Libraries, Databases
 - [OAuthLib](https://oauthlib.readthedocs.io) 3.3.4
 - [Asgiref](https://pypi.org/project/asgiref/1.1.1/) 1.1
 - [Dj-database-url](https://pypi.org/project/dj-database-url/) 1.0.
 - [Django-allauth](https://django-allauth.readthedocs.io/en/latest/) 0.44.0
 - [Gunicorn](https://gunicorn.org/) 20.1
 - [Django-summernote](https://pypi.org/project/django-summernote/) 0.8.20.0
 - [Django-Crispy-Forms](https://django-crispy-forms.readthedocs.io/en/latest/) 1.11.2
 - [PyJWT](https://pyjwt.readthedocs.io/en/stable/) 2.1.0
 - [Sqlparse](https://pypi.org/project/sqlparse/) 0.4.1
 - [PostgreSQL](https://www.postgresql.org/)
 - [Python3-openid](https://pypi.org/project/python3-openid/) 3.2.0
 
#### Platform as a service 
 -  [Cloudinary](https://cloudinary.com/)
 -  [Heroku](https://dashboard.heroku.com)
 -  [GitPod](https://gitpod.io/)

## Testing

Testing was not performed yet. For now, is being on hold while waiting for the assessment results from [Code Institute's](https://codeinstitute.net) facilitators. It is being placed on my roadmap, to ensure the application's perfect capability. 



## Bugs

During the coding, I encountered few bugs:


-  Typos (missing **colons, semicolons**)
-  Code formating (unsufficient spaces)
-  Deployment issues (unable to deploy to Heroku)
-  Rendering issues (due to typos and wrong syntax)
-  Styles not being loaded (due to DEBUG turned TRUE in 'setting . py')
-  Unable to create screenshot of the application on the [Am I responsive](https://ui.dev/amiresponsive?url=https://blogman-2022.herokuapp.com/admin/blog/post/) website.
 
> Disclaimer! There are few lines of code in the project that exceed 79 characters.

Otherwise **Code passed** [PEP8](http://pep8online.com/)  validation. 



## Deployment

This project is deployed by [Heroku](https://www.heroku.com/home).

Steps I took for deployment:

-   Use [Code Institute's](https://www.codeinstitute.net) template.
-   Create new Heroku app.
-   Assign **Convig Vars** both in Heroku and in the Blogman. app
-   Set buildbacks to Python and NodeJs in that order.
-  Set **DEBUG** value (settings. py) to *FALSE*! 
-   Link the Heroku app to this repository.
-  Remove Local Database **Config Vars** in Heroku app.
-   Click on Deploy.


## Roadmap

 - [ ] Python Testing
 - [ ] Different Style ([Minimalistic](https://www.pinterest.se/pin/599471400416515685/) Inspiration)
 - [ ] Custom Logo Design
 - [ ] Improve Formating (Remove unnecessary comments and blank spaces )
 - [ ] Improve coding **KNOWLEDGE** !
 - [ ] Configure Social Media login/sign-up

## Credits

 - [Traversy Media](https://www.youtube.com/c/TraversyMedia) 
 - Instagram  [python.learning](https://www.instagram.com/python.learning/)  - tricks and ideas.
 - [Code Institute](https://codeinstitute.net/), their facilitators and mentors - templates and course contents. 
 - [Mosh Hamedani](https://codewithmosh.com/)  - nice easy to follow explanations.
 - [Kalle Hallden](https://www.youtube.com/c/KalleHallden/videos)  - awesome videos with explenations.
 - [W3Schools](https://www.w3schools.com/python/python_for_loops.asp)  - detailed explanations and runnable examples.
 - [Django](https://www.djangoproject.com) Documentation.
 - This code is not my creation. I only followed the steps from [Matt](https://www.linkedin.com/in/mattrudge73/)
