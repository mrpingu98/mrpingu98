Manvir’s Personal project

- https://green-bay-02bd95803.4.azurestaticapps.net/technical
- Front-end repo: https://github.com/mrpingu98/personalProject
- Back-end repo: https://github.com/mrpingu98/personalProjectAPI

**Description**

Created a simple website for my own self-learning. Main features include:
- Once users authorise access to their Spotify data, they can view their listening
habits such as their most played songs/artists
- Merchandise page which is fetching from my database. Eventually will allow
users to add products to a cart
- Admin page where admins must login to use protected add/edit/delete
endpoints

**Technologies Used**
- Typescript, Javascript, C#, .NET

**Aim of project**
- To improve my understanding of all aspects of creating an app (front-end,
back-end, deployment)
- As the main aim of this project was for self-learning + working on this in my
spare time, I’m aware that parts of my code could definitely be
refactored/more efficient – when I have time I do try to update and clean up
my code

**Front-End**
- Javascript, Typescript, MUI (Material UI)
- Redux
- React hooks - useState, useEffect, useCallback, useMemo, usRef, useContext, useTransition, useDeferredValue
- Custom hooks
- React Query - useQuery and useMutations to handle API requests and cache data + error handling with try/catch statements
- Basic unit testing using Cypress
- Connecting to Spotify API - currently using PKCE Authentication. Once login functionality has been created for the app, will switch to using oAuth2 with token authentication

**Back-End**
- Basics of OOP Programming
- Configuring and setting up a Web API project (handling Nuget packages, understanding configuration of Program.cs file - services, middleware etc)
- Controller, Handler, Repository structure
- Dependency Injection
- DbContext
- Database migrations
- Entity Framework Core
- Using swagger to test endpoints
- Custom error messages
- Login functionality using Microsoft.EntityFrameworkCore.Identity / authorised endpoints / oAuth2 flow. At the moment I have made one 'Admin' account for myself to add/edit/delete products for the Merchandise page 

**Azure**
- Front-end deployed to an Azure Web App, back-end deployed to an Azure
Web API connected to a SQL Server
- Used application Logs to debug issues, e.g. API app initially wouldn’t run,
using the logs could see connection to my Db had failed and was expecting
the wrong data types
