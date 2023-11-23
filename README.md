[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/pgC2zHhI)


This is a simple chat app built with React, Express, and WebSocket.

Heroku link: https://pg6301-davido0604-369e22c5708a.herokuapp.com/

Github repo link: https://github.com/davido0604/pg6301eksamen-davido0604-main

Developer instruction is quite simple - just to run 'npm install' when launching the project for the first time.

ISSUES:

1. In Heroku dashboard, when connected to the Github the "classrom repository" for exam delivery, wasnt availibale or visible. After defferent attempts I decided to create an identical repository on my personal Github to make the deployment to Heroku happen. After that it found/saw the repository and I was succsefully able to deploy the application. 

2. After many hours of working on local enviorment, when deploying to Heroku, I discovered that there is a major issue in my application with cookie-based authentication, I was trying to figure it out and make it work, but my time is running out... As of now the issue seems to be the .env file which contains 'SECRET_COOKIES' variable. This makes the whole thing run, but only on local enviorment. As mentioned many times in lectures, this sort of files (.env) should never be shared or posted, and for that reason I dont want to risk it and deciding not to share, even I really wanted to showcase full functionality of the chat app. Rather, I will attach screenshort of how it looks and works on local inviorment.

<img width="1440" alt="Screenshot 2023-11-23 at 06 44 15" src="https://github.com/kristiania-pg6301-2023/pg6301eksamen-davido0604/assets/100728190/949650ed-055b-4f87-9d0a-8ac2508ac98e">
<img width="1440" alt="Screenshot 2023-11-23 at 06 46 09" src="https://github.com/kristiania-pg6301-2023/pg6301eksamen-davido0604/assets/100728190/fe2dd3c2-ab76-4338-882b-aaed5042a8c2">
