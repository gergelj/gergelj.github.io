---
layout: page
title: Triple-Tac-Toe
description: Extended version of the classic Tic-Tac-Toe game
img: assets/img/thumbs/2021-07-25-triple-tac-toe.jpg
importance: 1
category: fun
related_publications: 
---

TripleTacToe is a simple two player game which follows the rules of the extended version of the notorious game called Ultimate Tic-Tac-Toe. The rules can be found [here](https://en.wikipedia.org/wiki/Ultimate_tic-tac-toe).

This project initially came to life in 2019 as an Android game. That was my first experience with Android programming and I wanted to make a fun app first. The standard Tic-Tac-Toe was too simple for a fun game. One time I saw my friends playing the ultimate version of this game, on paper though. So I got the idea: "Hm, how about playing it on our phones?". So that's the short story behind the idea of the game. Now let's discuss details. At first, the Android app was multiplayer in a way that two people could play it on one phone. That was fun for a while but I wanted real multiplayer mode. At the time I attended artificial intelligence classes and I got an idea to implement an AI as a second player but that idea never came to life. Maybe one day..

So eventually I decided to create a web application and move everything to the cloud. That way not only Android users but everyone with a browser could join the game. There's a link to the website in the details of this post, so everyone can try it out. It is hosted as a free-tier Heroku application so it could be slow sometimes or it could hang and lose the connection. But oh well.. It is for testing purposes, right?

Once the user sets the name of the player, they are introduced to the waiting room. If no one else is waiting there, they should wait for somebody to join. Once there are two players in the waiting room, they get paired, and the game starts. According to the rules, players take their turns and in the end there's a winner. The players then choose whether they want a rematch or if they want to quit the game. Below there are some screenshots of the game.

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
