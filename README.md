# - Facebook Epidemics
A project that aims to prevent Dengue epidemics using crowd sourced real time data through Facebook SDK devoloped in HackMTY-2018

## Inspiration
Dengue Is a vector borne disease that affects millions of people around the world, one of the mail challenges is that it takes between 30 and 45 days for a suspected case data to be available online. We believe this process can be optimized by allowing health organizations around the world to post suspected through our app, Facebook Epidemics

## What it does
Facebook epidemics connects health organizations in vulnerable areas through Facebook SDK, allowing them to post everytime they encounter a suspected case of Dengue, each case data Is anonimized and linked to a gps location. Researchers and health organizations around the world can access this information in real time to be able to react quickly in the brink or an epidemic.

Using Facebook-Prophet, which allows time-series predictions, we can predict Dengue outbreaks and notify users living near vulnerable areas so they can take precautions to minimize their risk of contracting the disease.

## How we built it
We used Facebook SDK to enable login of health organizations to the app, crowd sourced data Is stored in Firestore database

## Challenges we ran into
Handling time was our biggest problem, we posted this entry almost at the last minute!

## Accomplishments that we're proud of
Having developed the idea as a team and developing the prototype in only 24 hours

## What we learned
Database design, how to develop a product in a short amount of time.

## What's next for Facebook epidemics
Integrate Facebook-Prophet to be able to predict epidemics before they happen

## Built With
*[facebook-login-api](https://developers.facebook.com/docs/facebook-login/) - Login API
*[heroku](https://www.heroku.com/) - Host
*[firebase](https://firebase.google.com/?hl=es-419) - Database
*[android-studio](https://developer.android.com/studio/) - IDE Android
*[flask](http://flask.pocoo.org/) - The web framework
*[leaflet.js](https://leafletjs.com/) - Interactive Maps
## Try it out
 fb-epidemics.herokuapp.com
