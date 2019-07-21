# Laconic

Laconic enables Youtube creators to optimize their videos click rates by allowing them to rapidly test how their video appears on Youtube's search result page.  A creator can easily test out multiple custom thumbnails, titles, descriptions and more while seeing how the results render in desktop, iphone or android app.

The code for the back end server can be found at [https://github.com/thinkful-ei-cheetah/capstone3-server-GOATful](https://github.com/thinkful-ei-cheetah/capstone3-server-GOATful).

## Live Link
A live version of the app can be found at [https://laconic.now.sh/](https://laconic.now.sh/)
 
## Quick App Demo

![Imgur](https://i.imgur.com/Ljct8Of.gif)

## Team

Laconic was built with 💙 by the following:

* Michael Verdi: [https://github.com/verdi327](https://github.com/verdi327)
* Elan Green: [https://github.com/elang5](https://github.com/elang5)
* Kristof-Pierre Cummings: [https://github.com/jamster10](https://github.com/jamster10)
* Peter Pae: [https://github.com/Paendabear](https://github.com/Paendabear)
* David Nordeen: [https://github.com/DavidNordeen](https://github.com/DavidNordeen)

## Technology

#### Front End

* React and OAuth
  * RESTful Api
  * Authentication via Google OAuth and JWT
* Testing
  * Smoketest (integration)
  * Snapshot with Jest and Enzyme
* Http Request
  * Axios
  * Fetch
* UI Libs
  * Font Awesome (icons)
  * Moment (time management)
  * React Modal (modals)

#### Production

Deployed via Zeit

## Running Locally

To get the Laconic client running successfully in development, you'll also need to have the laconic api running locally.  

The code for the back end server can be found at [https://github.com/thinkful-ei-cheetah/capstone3-server-GOATful](https://github.com/thinkful-ei-cheetah/capstone3-server-GOATful).

Please follow the API README on how to get the server up and running.

Then:

1) Start the laconic-api server with `npm run dev`
2) Clone this repo
3) Run `npm install`
4) Run `npm start`
