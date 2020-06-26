# fitbox-mobile

ApiRoutes.js file list all the API endpoints being used in the app. We can use it to keep all our routes consilidated at one place so managing and changing them becomes easier.

RestService.js file uses "Fetch" library to make http requests. It encapsulates the functionality of fetching the data from the server and validating session and handleing errors. We can use it for consuming the rest API.

App.js file contains the navigation logic. It is responsible for loading the main components. We can modify it to load appropriate components according to the logged in User.

Screens folder should contains the main components for the screens. We should also create separate screens folders for holding components for members and coaches.

Components folder should be used for holding the re-useable components of the app.
