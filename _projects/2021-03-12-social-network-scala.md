---
layout: page
title: Social media network
description: My first experience as a software developer intern at a company
img: 
importance: 3
category: work
related_publications: 
---

My first experience as a software developer intern at a software company was to develop a social media web application in Scala programming language. Having no previous experience in Scala I thought I would be overwhelmed by the amount of "spikes" in my daily routine. My initial fears have quickly vanished because after 2 days of (mostly) syntax learning I was able to get up and running the server and the database. I used the Play framework written in Scala and MySQL as the database.

The most challenging part of this project was the data layer in the Scala application. The Play framework supports the vast majority of the relational databases out there and the Slick "ORM-mapper" works as a connection between Scala objects and database tuples. Later on, Slick turned out to be not so slick. I put the term ORM-mapper in quotes because Slick is not really a mapper, more like a database access tool: it returns a tuple which needs to be organized into an object type to work with. There are generally two aproaches: 1) write the Slick mapping layer in Scala and generate DDL scripts, 2) write DDL scripts and generate the mapping layer. I went with the second approach because my knowledge in SQL is far more stable than Scala/Slick but after that the mapping layer has been generated I was off to the races.

The set of functionalities was small and this project was intended to show the capabilities of the intern, beginner's knowledge of web applications and databases. The most important thing I have learnt is that no matter how intimidating the unknown (technology) looks like it can be mastered pretty quickly if you possess fundamental knowledge in that particular field. New experiences open a different perspective and in the meantime you might as well have fun with it.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2021-03-12-social-network-scala/1.png" title="Register page" class="img-fluid rounded z-depth-1" zoomable=true %}
        <div class="caption">Register page</div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2021-03-12-social-network-scala/2.png" title="My profile" class="img-fluid rounded z-depth-1" zoomable=true %}
        <div class="caption">My profile</div>
    </div>
</div>
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2021-03-12-social-network-scala/3.png" title="Find friends" class="img-fluid rounded z-depth-1" zoomable=true %}
        <div class="caption">Find friends</div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2021-03-12-social-network-scala/4.png" title="Posts" class="img-fluid rounded z-depth-1" zoomable=true %}
        <div class="caption">Posts</div>
    </div>
</div>
