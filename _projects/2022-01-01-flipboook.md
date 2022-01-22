---
layout: project
title: Flipboook
description: An online magazine viewer
summary: An online magazine viewer, mobile friendly and fully customizable.
categories: ["Web Application"]
tags: ["React", "ExpressJS", "Javascript", "Bull", "PM2"]
---

Flipboook allows to browse online magazines and documents converted from a PDF file. This project is not yet open sourced.

### Why Flipboook
This product was specifically designed and implemented to satisfy the client's needs.

There are multiple solutions already available out there, such as [issue.com](https://issuu.com/){:target="_blank"}.
However, these products do not fulfill the client's requirements.

### Implementation
Flipboook is implemented mainly in JS.

It is composed by:
- **dashboard**: it allows the user to login, upload and edit the documents. It interfaces with the backend APIs. It is developed using **React**, as a single application web page.
- **backend**: it provides all the APIs needed to perform CRUD operations on the documents, the document conversion login and the DB connection. It is implemented using **ExpressJS** and other libraries, such as **Bull**, are exploited for the documents background conversion.
- **viewer**: it allows to read the magazines online. It is designed to be fast and mobile friendly. It is written in plain JS.

### UI
#### Dashboard
![Flipboook dashboard](/assets/imgs/projects/flipboook-dashboard.png)

#### Viewer
![Flipboook viewer](/assets/imgs/projects/flipboook-viewer.png)

### Deployment
Flipboook is running on a private VPS.
