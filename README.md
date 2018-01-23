# rd-leads-webapp

This is the very simple web application just to validate [guest-navegate-tracker](https://github.com/fabianopaes/rd-guest-navegate-tracker) javascript lib.

The lib will be listening every single page which the guest visit to send that to [rd-leads-api](https://github.com/fabianopaes/rd-leads-api)

It is hosting on [heroku](http://heroku.com) and you can access it [here](https://rd-leads-webapp.herokuapp.com/app/view)

## Running application on local environment

To run this app on your own machine you might have [nodejs](nodejs.org) installed. If you already have that properly installed, just execute the follow commands inside the project root folder:

```
npm install 
```


```
node index.js 
```

The application will be accessible on http://localhost:8080/app/view