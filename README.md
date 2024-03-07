# Group Giphy Saga Project: Search and Favorites

## Description

_Duration: 2 days_

This is a group project I developed with several cohort mates during my time at Emerging Digital Academy. It is a CRUD app utilizing Giphy's 3rd party API. The app's primary functionality is broken down between two views as follows:

### Search View

- Allows a user to enter a search string and submit a search request.
- Queries the `Giphy API Search Endpoint` with the given search string from the server.
- Displays the results on the DOM.
- Allows a user to "favorite" any of the resulting images.

### Favorites View

- Allows a user to see all of the Giphy images they have made a favorite.
- Allows a user to set a category for a favorite image.
    - Each favorite image can only have one category at a time.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/en/)

## Set-Up Instructions

1. Create a database named `giphy_search_favorites`
2. 2. The queries in the `database.sql` file are set up to create al the necessary tables and populate the needed data to allow the application to run correctly. This project is built on [Postgres](https://www.postgresql.org/download/), so you will need to make sure to have that installed. I recommend using Postico to run the quereis as that is what was used to create the queries.
3. Open up your editor of choice and run `npm install`.
4. Run `npm run server` to start the server.
5. Run `npm run client` to start the client.
6. Click the link given by `npm run client` to open a new tab with the running project!

## Built With

*React
*Redux
*Postgres
*Express
*Axios
*Giphy's 3rd Party API

## Acknowledgements

Thank you to Emerging Digital Academy for the support and opportunity to make this project possible! Special shoutout to Riley, Langston, and Seid who worked on this project with me and were fantastic team members!

