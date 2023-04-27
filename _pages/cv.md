---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* Amazon Music: May 2022 – Aug 2022
  * Software Development Engineer Intern
  * Designed and implemented a full stack application that processes    user-uploaded files and modifies catalog data accordingly at Amazon Music Catalog.
  * Created a file upload form and tables with React.js, tested components with unit tests, and deployed to production.
  * Developed backend with Python Flask and handled HTTP requests with REST API.
  * Utilized AWS Cloud Development Kit to setup I AM roles, S3 bucket, SQS queue, and DynamoDB table.
  * Used S3 bucket to store files and send notification messages to SQS queue.
  * Devised a DynamoDB table for job statuses and implemented CURD operations.
  * Managed a queue listener to get messages and trigger multithreaded file processing, including file data validation, payload data generation, etc.

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Education
======
* B.S. in GitHub, GitHub University, 2012
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
