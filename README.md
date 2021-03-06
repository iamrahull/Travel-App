Traveller

 This project helps people find weather forecast for planning in future.

![FrontPage](https://github.com/iamrahull/Traveller/blob/master/Project%20ScreenShots/FrontPage.jpg?raw=true)
![QueryForParis](https://github.com/iamrahull/Traveller/blob/master/Project%20ScreenShots/Query%20For%20Paris.jpg?raw=true)
![QueryForNYC](https://github.com/iamrahull/Traveller/blob/master/Project%20ScreenShots/Query%20for%20New%20York%20City.jpg?raw=true)
![SavedLocations](https://github.com/iamrahull/Traveller/blob/master/Project%20ScreenShots/Viewing%20Saved%20Locations.jpg?raw=true)

 Pre-requisites

This project is heavily dependent on third-party APIs. In order to get this project up and running you need `API_KEYS`.

- Create `.env` file in the root of the folder and replace the following with your API_KEYS
- Replace `GEONAME_API_KEY` with your [Geonames](http://www.geonames.org/export/web-services.html) username
- Replace `WEATHER_API_KEY` with your Weather Bit API Key, you can create it [here](https://www.weatherbit.io/account/create) username
- Replace `PIXABAY_API_KEY` with your [Pixabay API](https://pixabay.com/api/docs/) username

 Installation

1. Make sure you have node installed and install the packages


npm install


2. This project can run in two different modes.

- Development
- Production

For Developement use


npm run build-dev


Note: After this you have to run the server to see the results

For `Production`, you have to build the project first and then run the server

 Build the project


npm run build


 Run the server


npm run start

Yeah you did it, the server is up and running. Open your browser type (http://localhost:6580).
