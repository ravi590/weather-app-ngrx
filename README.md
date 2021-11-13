# To Run the application
please run below command at the package.json directory level to install npm packages and its necessary dependencies of the weather application
npm install

once all the packages are installed, please run below command at the package.json directory level to start the weather application
npm start

Once application starts you can access the application using below url
http://localhost:4200


## Flow of the application

maint.ts will load the app module.
App Routing in App Module has reference to to load weather App Module.
Once Weather App Module is loaded, weather App module related routing will be triggered.It will load weather component of weather app module.

By default in the search bar, it will show the London city and below the search bar, it will show the forecast details.
User can change the respective city to get forecast details.



