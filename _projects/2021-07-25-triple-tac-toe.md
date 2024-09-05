---
layout: page
title: Triple-Tac-Toe
description: Extended version of the classic Tic-Tac-Toe game
img: assets/img/thumbs/2021-07-25-triple-tac-toe.jpg
importance: 1
category: fun
related_publications: 
github_repo: TripleTacToe
---

TripleTacToe is a two-player game that follows the rules of the extended version of Tic-Tac-Toe, known as Ultimate Tic-Tac-Toe. You can find the rules here.

The project was originally created in 2019 as an Android game. This was my first foray into Android programming, and I wanted to build a fun app. Standard Tic-Tac-Toe felt too simplistic for my goals, but one day my friend introduced me to the *ultimate* version of the game on paper, I thought, “Why not bring this to our phones?” That was the inspiration behind the game.

Initially, the Android app supported local multiplayer, allowing two players to compete on a single phone. While this was enjoyable for a time, I wanted to introduce a real multiplayer mode. During my artificial intelligence classes, I considered implementing an AI opponent, but that idea never materialized — perhaps someday it will.

Eventually, I decided to transition the game to a web application, making it accessible to anyone with a browser. You can try it out through the link in the post details. (The link might be dead by the time you are reading this, as hosting a web app costs money, honey.) It was hosted as a free-tier Heroku application.

Here's how the game works: When a user sets their player name, they enter a waiting room. If no other players are present, they wait until someone joins. Once two players are in the waiting room, they are paired, and the game begins. Players take turns according to the rules, and at the end, a winner is determined. After the game, players can choose to start a rematch or quit. Below are some screenshots of the game:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2021-07-25-triple-tac-toe/1.png" title="Login page" class="img-fluid rounded z-depth-1" zoomable=true %}
        <div class="caption">Login page</div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2021-07-25-triple-tac-toe/2.png" class="img-fluid rounded z-depth-1" zoomable=true %}
        <div class="caption">Exes vs. Ohs</div>
    </div>
</div>

More about the project on [github](https://github.com/{{ site.github_username }}/{{ page.github_repo }}). 