# Kalendaryo

## Description

The goal of this project is to create a backend part of an application where the user can collect event data from multiple Google calendars into one calendar that can be shared with the right people. 
The project has an already existing Android frontend, which handles the authentication with Google OAuth 2.0. The team has to develop the backend application for this frontend, which communicates with the Google Calendar API on behalf of the user to get the calendars, get the events from said calendars and finally create a new calendar and insert the collected events into the new calendar.

## Technologies

In this project the apprentices are using Spring to work with the Google Calendar API. First they build the basics for the application and for storing the data in a MySQL database. After that they create the necessary endpoints, through which the communication between the Android frontend and the backend happens. Later they implement the authorization and communication with the Google Calendar API, so we can manipulate the calendars and their data - including events and sharing options.

- Google Calendar API
- SpringBoot
- MySQL
- Flyway for database migration
- Mockito mock framework for unit testing
- MockMVC for integration testing
