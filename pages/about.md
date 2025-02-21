---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" %} 

{% include feature/nav-menu.html sections="About CollectionBuilder CSV;About the About Page" %}

{% include feature/timelinejs.html %}

## About the Homemaking Project

This project explores the community building efforts of Jewish Kansans from the early 1900s to the present day. By identifying employment opportunities, creating community centers, and developing Kosher foodways, Jewish Kansans have fostered relationships of mutual aid for their local communities. Various social organizations have formed out of efforts to create safe places for Jewish cultural expression in rural Kansas.

{% include feature/image.html objectid="js_001" width="75" %}

## Our Team

{% include feature/card.html header="Dominique Stringer" text="Dominique Stringer is a project lead for the Homemaking project. She is a museum studies student at the University of Kansas." objectid="js_001" width="25" centered=true %}

{% include feature/card.html header="Tyra Kalman;Dominique Stringer" text="Tyra Kalman is a project lead for the Homemaking project.;Dominique Stringer is a project lead for the Homemaking project. She is a museum studies student at the University of Kansas." objectid="js_001" width="25" %}

{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary" %}

{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" %}

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include cb/about_the_about.md %} 
