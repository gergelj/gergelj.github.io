---
layout: page
title: Relational Database Normalization
description: Quick solution to relational problems
img: assets/img/thumbs/2021-11-21-relational-normalization.jpg
importance: 1
category: work
related_publications: 
github_repo: rel-norm
---

Don’t you sometimes get a sudden idea that just keeps buzzing in your mind until you start working on it? That persistent itch that doesn’t go away, day or night? Recently, I had one of those moments with the concept of an application for relational modeling. It might not sound thrilling to everyone, but it intrigued me enough to dive into some research and start developing it.

I needed a compact console application that would take a relational schema description as input and generate a series of decomposed relational schemas as output. This tool would streamline my tasks as a teaching fellow and facilitate faster test reviews. It’s a testament to how far a programmer might go: spending days developing an app just to save an hour or two reviewing student tests. But even a small time-saving is still time-saving, so I jumped right into it.

I chose Java for this project because it suited the app’s needs well. Although I could have used a scripting language like Python or JavaScript, I found their collection operations a bit cumbersome. Java’s object-oriented approach fit perfectly for this use case, and I used Maven as a build automation tool to unit-test my methods.

I was pleasantly surprised by how quickly I completed the development of this app. My enthusiasm for the topic played a big role in this, and knowing that this software would directly aid my work made the development process both enjoyable and efficient.

More about the project on [github](https://github.com/{{ site.github_username }}/{{ page.github_repo }}). 