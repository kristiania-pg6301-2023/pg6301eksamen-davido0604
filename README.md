[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/pgC2zHhI)


This is a simple chat app built with React, Express, and WebSocket.


Heroku link: https://pg6301-davido0604-369e22c5708a.herokuapp.com/

Github repo link: https://github.com/davido0604/pg6301eksamen-davido0604-main

Developer instructions are quite simple—just run 'npm install' when launching the project for the first time.

ISSUES:

1. In the Heroku dashboard, when connected to Github, the "classrom repository" for exam delivery was not available or visible. After different attempts, I decided to create an identical repository on my personal Github to make the deployment to Heroku happen. After that, it found or saw the repository, and I was successfully able to deploy the application.

2. After many hours of working on local environments, when deploying to Heroku, I discovered that there is a major issue in my application with cookie-based authentication. I was trying to figure it out and make it work, but my time is running out... As of now, the issue seems to be with the.env file, which contains the 'SECRET_COOKIES' variable. This makes the whole thing run, but only in the local environment. As mentioned many times in lectures, this sort of file (.env) should never be shared or posted, and for that reason, I don't want to risk it and decide not to share, even though I really wanted to showcase the full functionality of the chat app. Rather, I will attach a screenshot of how it looks and works in a local environment.

<img width="1440" alt="Screenshot 2023-11-23 at 06 44 15" src="https://github.com/kristiania-pg6301-2023/pg6301eksamen-davido0604/assets/100728190/949650ed-055b-4f87-9d0a-8ac2508ac98e">
<img width="1440" alt="Screenshot 2023-11-23 at 06 46 09" src="https://github.com/kristiania-pg6301-2023/pg6301eksamen-davido0604/assets/100728190/fe2dd3c2-ab76-4338-882b-aaed5042a8c2">
