# Online Job Portal – Full Stack Application
<!-- TOC -->
* [Online Job Portal – Full Stack Application](#online-job-portal--full-stack-application)
  * [Overview](#overview)
  * [Features](#features)
    * [For Job Seekers (Employee)](#for-job-seekers-employee)
    * [For Job Posters (Employer)](#for-job-posters-employer)
  * [Technologies](#technologies)
  * [Application Structure](#application-structure)
* [Credits](#credits)
<!-- TOC -->
## Overview

This orgainzation contains the source code for a full-stack job portal application built with React for the Frontend
and Spring Boot, Hibernate, and Postgres for the Backend. It offers a user-friendly platform for job seekers
and employers to connect effectively.

## Features

### For Job Seekers (Employee)
1. Create and manage profiles
2. Search for jobs based on various criteria (job description, location, keyword, etc.)
3. Apply for available positions
4. Track application status

### For Job Posters (Employer)
1. Post job openings
2. Manage and review applications

## Technologies
1. Frontend: React
2. Backend: Spring Boot, Java, Hibernate
3. Database: Postgres

## Application Structure
```
src/main/java/com
└── portal
    └── jobsphere
        ├── application
        │   └── ServerPortListener.java
        ├── controller
        │   ├── HomeController.java
        │   ├── PostController.java
        │   └── ProfileController.java
        ├── enums
        │   ├── Gender.java
        │   └── Role.java
        ├── JobsphereApplication.java
        ├── model
        │   ├── Post.java
        │   ├── Profile.java
        │   └── ResponseObject.java
        ├── repository
        │   ├── PostRepository.java
        │   └── ProfileRepository.java
        ├── service
        │   ├── PostService.java
        │   └── ProfileService.java
        └── utils
            ├── AppConfig.java
            ├── Constants.java
            └── DatabaseConfig.java
```

# Credits
Credits to [Niharika](https://github.com/Niharika2803) (a.k.a. NightFlick) for project idea and other features suggestion(s).