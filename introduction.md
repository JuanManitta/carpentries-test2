---
title: "DSpace Angular Installation"
teaching: 15
exercises: 10
---

:::::::::::::::::::::::::::::::::::::: questions 

- What are the prerequisites for running the DSpace 7 user interface?
- How do I connect the Angular frontend to the REST API backend?
- How do I start the application in development mode?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Install necessary dependencies (Node.js, Yarn).
- Clone the DSpace Angular source code.
- Configure the connection to the DSpace REST API.
- Launch the application locally.

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

DSpace 7 introduces a completely new User Interface (UI) built on **Angular**. This UI talks to the DSpace backend purely via the REST API. This separation allows the frontend to be independent, but requires specific configuration to ensure both sides (Client and Server) can communicate.

For this demo, we assume you have a running DSpace backend (REST API) available.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Make sure learners have **Node.js** (v16.x or v18.x) and **Yarn** installed before starting this episode. Using `npm` instead of `yarn` may lead to dependency locking issues.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## Prerequisites

Before cloning the repository, verify that you have `node` and `yarn` installed:

```bash
node -v
yarn -v
```

## Installation Steps
1. Clone the repository: Download the source code from the official GitHub repository.
   ```bash
   git clone [https://github.com/DSpace/dspace-angular.git](https://github.com/DSpace/dspace-angular.git)
   cd dspace-angular
   ```
2. Install Dependencies: Use yarn to download all required Angular libraries.
3. 
