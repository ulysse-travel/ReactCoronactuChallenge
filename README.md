# React Coronactu Challenge

It is an understatement to say the world health situation is not at its best. And it would be an understatement to say that our customers are really confused about all the different restrictions in all the different countries they want to travel to. 

**We aim to provide them with the info they need to travel with peace of mind.**

## Instructions
The goal of this challenge is to create a UI component to display the relevant info in our search funnel.

It should have 2 simple props (string of iata country code) :
- origin
- destination

We have an API endpoint providing multiple information for the Trip object:
GET / https://ulysse-tooling-api.herokuapp.com/api/sherpa/country?origin=FR&destination=JP
Procedures & restrictions for origin/destination are in the `included` array of the response.

You will on what information to show customers according to what you think may be important.

That's it!

We expect:
- Using React / Next.js
- Tailwind (config file provided in this repo)
- Re-usable code (we won't actually re-use your code, but @ ulysse, when we're building we have to think about exporting it to our products if needed, such as our backoffice or a mobile app)
- Clean and responsive UI

Useful libraries we use @ulysse :
- swr
- date-fns
- formik
- prettier

If you have any extra ideas/features, you are welcome to add them. Please let us know if you have any questions, be sure to contact us if something is not quite clear! 

Good luck!
