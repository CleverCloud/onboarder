# Clever Cloud Onboarder

Hello, you want to try [Clever Cloud](http://www.clever-cloud.com/)? This is the perfect starting point to do so.

Editing code? Open the file `index.js`, we have commented a REST call. You just need to uncomment it. It will be automatically called at the end of the application deployment. This call will get you in our user base and register you for our ongoing draw. Don't forget to modify the JSON opbject sent by the API call. It will help us to contact you.

And then, what's next? Two choices:

## Use Clever Cloud CLI client

Start with the documentation here: [https://www.clever-cloud.com/doc/clever-tools/getting_started/](https://www.clever-cloud.com/doc/clever-tools/getting_started/).

Install `clever-tools` with npm:

````
npm install -g clever-tools
````

Or with yarn:

````
yarn global add clever-tools
````

Once `clever-tools` is installed, change directory to the Git repository and:

````
clever login
clever create --type node myApp
clever deploy
clever open
````

You have just deployed this application to production, congrats 👏 ! And don't forget to modify the file `index.js`.

## Use Clever Cloud Console

Follow the documentation here [https://www.clever-cloud.com/doc/nodejs/nodejs/](https://www.clever-cloud.com/doc/nodejs/nodejs/). And don't forget to modify the file `index.js`.
