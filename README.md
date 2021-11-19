# React Coronactu Challenge

Currently the international sanitary situation is not at its best and our users are confused with all the restrictions applied to different countries.
They really want to access informations about the destination they are going to visit.

**And we should provide them with the main informations they need to travel somewhere.**

Goal of this challenge is to create a ui component to display these informations in our search funnel.
It should have 2 simple props (string of iata country code) :
- origin
- destination

We have an API endpoint providing multiple informations for trip :
GET / https://ulysse-tooling-api.herokuapp.com/api/sherpa/country?origin=FR&destination=JP
Procedures & restriction for origin/destination are in the `included` array of response.

You decide on what information to show to users according to what you think may be important.

We expect :
- React / Next.js
- Tailwind (config file provided in this repo)
- Re-usable code (we won't actually re-use your code, but @ ulysse, when we're coding feature we have to think about exporting it to other products if needed)
- Clean and responsive UI
