# **Social Media App**

<p align="center">
<img src="https://github.com/mihir-vora1/social-media-app/blob/master/media/logo/websiter-logo.png" > 
</p>

<p align="center">

<a href="#" target="blank">
    <img src="https://img.shields.io/github/license/mihir-vora/social-media-app?style=flat-square" alt="github-profile-readme-generator license" />
</a>
<a href="https://github.com/mihir-vora/social-media-app/fork" target="blank">
<img src="https://img.shields.io/github/forks/mihir-vora/social-media-app?style=flat-square" alt="github-profile-readme-generator forks"/>
</a>
<a href="https://github.com/mihir-vora/social-media-app/stargazers" target="blank">
<img src="https://img.shields.io/github/stars/mihir-vora/social-media-app?style=flat-square" alt="github-profile-readme-generator stars"/>
</a>
<a href="https://github.com/mihir-vora/social-media-app/issues" target="blank">
<img src="https://img.shields.io/github/issues/mihir-vora/social-media-app?style=flat-square" alt="github-profile-readme-generator issues"/>
</a>
<a href="https://github.com/mihir-vora/github/pulls" target="blank">
<img src="https://img.shields.io/github/issues-pr/mihir-vora/social-media-app?style=flat-square" alt="github-profile-readme-generator pull-requests"/>
</a>

</p>


## **Contents**
- [Introduction](#introduction)
- [The Use Of Social Media application](#the-use-of-social-media-application)
- [Technology Used To develop Social Media App](#techonology)
- [The architecture of App](#the-architecture-of-app)
- [Features](#features)
- [Setup](#setup)


## Introduction
<p align="justify">
&rarr; After the online sign-up or Login process, users can sharing photos and videos with Type your caption(Get creative and write a nice, interesting caption to go with your photo and Video.) called "tweepy". 

&rarr; Then your followers can see your post then your followers can Like(Clicking Like Button below a post on Mumble way to let people know that you enjoy it without leaving a comment. Just like a comment, anyone who can see the post can see that you liked it and The person who posted the video will get a notification that you liked it.When you like something, this lets us know to show you other content that we think you’d also like to see) or DisLike(If you dislike your post, it means that the user did not like your post - image or video and caption) and Comment(Below every posts there are “Comment” buttons. 

&rarr; If the image has any recent comments they will appear below those posts. Comments allow your followers to write a comment on your post. Users are notified if you “Comment” their post.) on your post.
</p>

## The Use Of Social Media application

&rarr; Social media allows individuals to keep in touch with friends and extended family. Some people will use various social media applications to network and find career opportunities, connect with people across the globe with like-minded interests, and share their own thoughts, feelings, and insights online

&rarr; Social media is important because it allows you to reach, nurture, and engage with your target audience — no matter their location. When a business can use social media to connect with its audience, it can use social media to generate brand awareness, leads, sales, and revenue and it also helps poor people

## Techonology
- Front-end Tech

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

- Back-end Tech

![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)

## The architecture of app
<p align="center">
<img src="https://github.com/mihir-vora1/social-media-app/blob/master/media/img/System-architecture-A-preselected-Social-Network-will-be-the-interface-between-customer.png" alt="architecture")
</p>

## Features
1. Create New Account
    - Username
    - Email
    - Password
    - Password confirmation
    
2. Login Account
    - Username
    - Password
    
3. User Profile
    - indicates how many  posts you have ("posts")
    - indicates how many people are following you ("followers")
    - indicates how many people you're following ("following")
    - Other User Able To see Your Profile and Show the your Follower and Following People and  Posts in Your Account
    - You Can Follow Another User Account and also You can Unfollow to User Account 
    
4. User Edit  Your Profile Account
    - Add  Header(Background Image) Avatar
    - Add Profile Pic
    - Add Account Bio
    - Change Email Id
    - Change Username
    - Delete Account
    
5. User Can Tweepy(POSTS)
    - User Can Do  Add Either Image or Video with caption or without Caption can do
    - User Can Do Updating Posts
    - User Can Also Do Delete Posts 
    
6. User Can Like, Dislike, Comments On Posts

    - User Can Do Likes On Posts  and Remove Like On Posts
    - User Can Do Dislikes On Posts and Remove dislike On Posts
    - User Can Do Comment On Posts
    - Other User See The Total Like and Dislike 
    - Other User Read The Comments on Posts  
7. Search User Account
    - You can search people by their name or username

8. Notification System( this Feature We are Create in future )
    - If another user likes or dislikes and comments on your post, you will get a notification that this user has liked or disliked and commented.
    
9. Creating API(Using REST APIs)
    - Creating public API  Meaning, third-party apps can  access the API from Mumble without permission.


    
## Setup

1. Git Clone the project with: ```git clone https://github.com/ervoramihir/social-media-app.git```.

2. Move to the base directory: ```cd social-media-app```

3. Create a new python enveronment with: ```python3 -m venv env```.

4. Activate enveronment with: ```env\Scripts\activate``` on windows, or ```source env/bin/activate``` on Mac and Linux.

5. Install required dependences with: ```pip install -r requirements.txt```.

6. Make migrations with: ```python manage.py makemigrations``` and then ```python3 manage.py migrate```.

7. Run app localy with: ```python3 manage.py runserver```.

