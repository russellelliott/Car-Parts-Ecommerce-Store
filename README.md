# Car Parts Ecommerce Store
Headstarter Summer Fellowship Week 4 Project

## Functionality
The website in question should advertise various car parts, to which the user should be able to enter their credit card information to purchase said parts.

The Company Scenario from Microsoft introduced the idea of an ecommerce site which sells car parts.

## Setup
### Public and Secret Keys
To use this project with your own Stripe account, you need your public and secret keys from your Stripe Account.

To view your codes, go you your Stripe account dashboard and click “Developers”.

On the left side of the screen, click “API Keys”. Click the respective key to copy it to your clipboard.

-   Your secret key is hidden by default. Click “Reveal Secret Key” to reveal it. From there, click it to copy it to your clipboard.

### `.env` File
The Public and Secret Keys are stored in the .env file. This is for storing the environment variables for the site. Copy-paste your keys in their respective areas, ensuring there are no spaces in between the variable name, equal sign, and the key itself. The file should look something like this:

`STRIPE_PUBLIC_KEY=[yourPublicKey]`

`STRIPE_SECRET_KEY=[yourSecretKey]`

This filename is included in the `.gitignore` file, which prevents the keys from being pushed onto a git repo, or otherwise visible to other users beside yourself.

## Running the App
Enter the command `source .env` to save the environment variables to the project so they can be reused.
To verify this worked, type `echo $STRIPE_PUBLIC_KEY` on the command line. If the public key prints on the console, the setup worked.

Enter the command `node server.js` to run the server on localhost 3000. The app can then be accessed from [http://localhost:3000/](http://localhost:3000/)

## Sources
Starter Code: https://github.com/HelalChow/StripeProject

Original creators GitHub: https://github.com/WebDevSimplified

Video Tutorial: https://www.youtube.com/watch?v=mI_-1tbIXQI