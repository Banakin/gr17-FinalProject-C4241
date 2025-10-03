# MBTA Tracking App  

**Team Members:** Ashley Fontaine, Yi Hong Jiang, Brendan Leu, Utku Yakar  
**Group 17 Final Project**  

### Project expectations  

This app is a utility for folks who live within the Boston subway. With this app, users can see **live arrival times** for various stops in the area, save the stops that they frequently use, see a map of the subway system with indicators of various trains in the system, see line availability alerts, and access other useful information regarding their travel in Boston.  

To make the experience more dynamic, we are planning a **real-time animation** of the subway system that updates with MBTA data. Users will be able to visually track trains as they move along their routes on the map, instead of just reading arrival times. We’re considering using WebSockets or similar technology here so that updates feel immediate rather than just periodic refreshes. This should give the project a more interactive, live feel that goes beyond static pages.  

### Technologies  

This project will use **React with Vite** for the front-end application, utilizing **PassportJS** for authentication (including GitHub SSO) and **shadcn** for UI components. Serving the frontend and the API will be **ExpressJS** running with **NodeJS**. The backend API will make calls to the **MongoDB database** using **Mongoose**, as well as pulling live transit data from the **MBTA API**.  