<div align="center">
    <img src="https://raw.githubusercontent.com/Secure-Booking-Service/.github/main/paper-plane-regular.svg" alt="Paper Plane icon by Font Awesome" width="100">
    <br>
    <h2>Secure Booking Service</h2>
    <br>
</div>

### ✈️ Welcome on Board

> Please take your seat, close your seat belt, ensure that your seat is in an upright position and that your table is folded up. We will soon arrive at our destination airport.

The Secure Booking Service is a proof of concept full stack application written in TypeScript. With its terminal based web interface, it allows travelagents to book and manage flight bookings for their clients or an administrator to manage user access. A Role-Based-Access-Control ensures that users have only least privileges. The application can be split into two parts.

The **frontend** is accessabile via the browser. It represents a linux-based terminal where the user can submit commands like `login <email>` or `booking new`. All commands are validated and will be send to the REST-API. The REST-API is priovided by the **backend** NodeJS application. It is build with the express framework and handles all the logic to manage all documents stored within the MongoDB database.

<details>
  <summary>Repository Overview</summary>
  
  * [**Secure-Booking-Service/frontend**](https://github.com/Secure-Booking-Service/frontend) - Terminal-like web application running in a common browser.
  * [**Secure-Booking-Service/backend**](https://github.com/Secure-Booking-Service/backend)  - REST-API written in TypeScript with NodeJS as the runtime and the express framework.
  * [**Secure-Booking-Service/common-types**](https://github.com/Secure-Booking-Service/common-types) - Internal npm package containing various values and types shared by frontend and backend.

</details>

### ✨ Features

* 🔑 Passwordless authentication powered by WebAuthn/FIDO!
*  ❱ Minimal GUI - It is a Terminal, running right in your browser!
* 🛫 Real-Life flight data provided by Amadeus Flight Api.
* 🔐 Strong encrypted database.

### 🏆 What was the objective? 

This project has been build as an exam of the course "Security by Design". The objective was not only to put security from the beginning on as the top priority, but also to apply different touchpoints of a Secure Development Lifycycle to ensure security in various development steps. This Secure Development Lifecycle includes among others Static Application Security Tests (SAST) by SonarQube, regular threat modeling sessions or secure-code-reviews. 


---
Icon by Font Awesome published under [CC BY 4.0](https://fontawesome.com/license)
