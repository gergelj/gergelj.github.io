---
layout: page
title: Social media network
description: My first experience as a software developer intern at a company
img: 
importance: 3
category: work
related_publications: 
---

My first experience as a software developer intern involved developing a social media web application using the Scala programming language. With no prior experience in Scala, I was initially concerned about being overwhelmed by the new challenges. However, my fears quickly dissipated. After just two days of primarily learning the syntax, I was up and running with the server and database. I used the Play framework, written in Scala, and MySQL for the database.

The most challenging aspect of this project was the data layer within the Scala application. While the Play framework supports a wide range of relational databases, I found Slick, the “ORM-mapper” used to bridge Scala objects and database tuples, to be less straightforward than expected. Although I refer to it as an ORM-mapper, Slick is more accurately a database access tool: it returns tuples that need to be converted into objects for practical use. There are generally two approaches: 1) write the Slick mapping layer in Scala and generate DDL scripts, or 2) write DDL scripts and generate the mapping layer. I chose the second approach because my SQL knowledge was more robust than my Scala/Slick experience. Once the mapping layer was generated, I was able to proceed with the project.

The set of functionalities for this project was relatively small and was designed to demonstrate the intern’s capabilities, as well as their understanding of web applications and databases. The most important lesson I learned was that, no matter how intimidating a new technology might seem, it can be mastered quickly if you have a solid foundation in the relevant field. New experiences offer fresh perspectives, and you might even find enjoyment in the process.

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
