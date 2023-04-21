# Nasa Mission Control

<img src="https://user-images.githubusercontent.com/53094729/233561800-a91ebfb0-65a4-4f99-aede-83441391c2a6.gif" style="width: 200px" />

#### A web application that allows users to schedule a mission to one of the Kepler Exoplanets. The application is built using the MERN stack and Arwes- A Futuristic Sci-Fi UI Web Framework.

#### Live Demo: https://nasa-mission-control.onrender.com

### Tecnologies Used

* ![Express](https://img.shields.io/badge/EXPRESS-Middleware-orange)
* ![Node](https://img.shields.io/badge/NODE-JS-brightgreen)
* ![Mongo DB](https://img.shields.io/badge/MONGO-DB-green)
* ![React](https://img.shields.io/badge/React-JS-blue)
* ![Mongoose](https://img.shields.io/badge/MONGOOSE-JS-yellowgreen)
* ![Arwes](https://img.shields.io/badge/ARWES%20-Futuristic%20Sci--Fi%20and%20Cyberpunk%20Graphical%20User%20Interface%20Framework-blue)

#### Users can--- 
* Schedule a mission launch for interstellar travel to one of the Kepler Exoplanets.
* View Upcoming missions including both SpaceX launches and newly scheduled.
* View the history of mission launches including SpaceX launches starting from the year 2006.

#### Schedule a mission using only confirmed planets matching the following criteria from kepler_data.csv
* Planetary radius < 1.6 times Earth's radius.
* Effective stellar flux > 0.36 times Earth's value and < 1.11 times Earth's value.

<img src="/1.png" />

## Getting Started

1. Ensure you have Node.js installed.
2. Create a free [Mongo Atlas](https://www.mongodb.com/atlas/database) database online or start a local MongoDB database.
3. Create a `server/.env` file with a `MONGO_URL` property set to your MongoDB connection string.
4. In the terminal, run: `npm install`

## Running the Project

1. In the terminal, run: `npm run deploy`
2. Browse to the mission control frontend at [localhost:8000](http://localhost:8000) and schedule an interstellar launch!

<img src="/4.png" />
