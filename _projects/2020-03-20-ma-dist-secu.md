---
title: "Ma distance de sécurité"
collection: projects
permalink: /projects/2020-03-20-ma-distance-de-securite
excerpt: "Web and mobile applications that help users to manage the social distancing during the pandemic COVID-19."
data: 2020-03-20
---

![dist-secu](/images/dist-secu.png)

[**Ma distance de sécurité**](https://www.youtube.com/watch?v=uSn7Oznno-E) is a web and mobile applications that help users to manage the social distancing during the pandemic COVID-19.

During the lockdown in March 2020 in France I developed these applications as a side project. I had the idea from the [haversine](https://en.wikipedia.org/wiki/Haversine_formula) distance that computes the distance between two geographical points (latitude and longitude). I then use the Google Maps API to track users positions and their distances.

The user interface of the applications contain two fields **Ville** and **Distance** in which the user respectively set the city and the minimum distance the later want to keep from the other users. Once the user clicks the button start his distance is tracked he stops the tracking.

I learned a lot from this project. It was my first time developing an Android application and deploying a website on Google Cloud.

I used the following technologies for the development: Python (Flask), JavaScript, HTML, CSS, Bootstrap, MySQL, Android, Google Cloud.

Code source available [here](https://github.com/abdjiber/prototype-distance-securitaire).