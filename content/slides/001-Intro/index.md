---
title: Intro to Flask
summary: An introduction lecture to Flask
authors: []
tags: ['Tutorials']
categories: []
date: '2023-09-22'
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: sky
  # Choose a code highlighting style (see Hugo docs on Chroma)
  #   Light style: github-light. Dark style: dracula (default).
  highlight_style: github-light
---


## Learning Goals
- Request-Response Cycle
- Web Servers and WSGI/Werkzeug
- Creating a Flask Application
- Flask Routing and Views
- SQLAlechmy in Flask

---

## What is Request-Response Cycle?

{{< figure src="https://cdn-images-1.medium.com/max/1600/1*Bqctt72kLrkmHzm8qAQfwQ.png" >}}


---

## Client
- User Interface
- Responsible for styling, layout, and event functionality
- Makes requests to a web server using HTTP protocols

---

## Web Server
- Responsible for data storage and management 
- Sends a response back to the client
- Uses HTTP protocols to respond to requests
- Changes in data may be triggered by the client, but the actual change is handled by the server side

---

## What is an API (Application Programming Interface):
- Facilitates communication and interaction between software components or systems.
- Can be used for both internal (within a single application) and external (between separate applications) communication, not limited to web-based interactions.

---

## What is a Web API (Web Application Programming Interface):
- Specifically designed for remote access to web-based services and resources.
- Accessible over the internet using standard web protocols such as HTTP, commonly used for providing data and functionality to external applications, websites, and mobile apps.


--

{{< figure src="https://miro.medium.com/v2/resize:fit:1372/format:webp/1*-IrjezfdqfpO1WSwkU-E6A.png" >}}

---

{{< figure src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*pSHwGTsBYsaPpN02FK5NIA.png" >}}