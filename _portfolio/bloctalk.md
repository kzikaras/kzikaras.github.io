---
layout: post
title: BlocChat
feature-img: "img/sample_feature_img.png"
thumbnail-path: "/img/newroom.png"
short-description: BlocChat, chat with your friends online

---
Bloc chat is a web application which allows users to post messages to each other. The problem I needed to solve in this case was to find a way to save messages and display them dynamically on the site.

{:center}
![]({{ site.baseurl }}/img/newroom.png)

To solve this problem I utilized Google's Firebase backend service. I created a small database that would hold any messages posted, as well as let you create new chatrooms. All of this was tied together using the Angular framework which allowed me to reference my database to display posts dynamically.

