## A buy and sell platform - Olx Clone
This is a buy and sell platform developed for the campus community. We have used waterfall SD-methodology (outdated, but just for fun) to create SRS, DFD and other related documents and testings. This project is still in its phase-I, this is just a working base product, some new creative features will be added soon (are noted down below).   
  
## Features
 * Login, logout and account recovery using E-mail.
 * User account and profile information (email, phone num, address)
 * Interface to sell a product (includes description, demanded price, title)
 * Global interface to see latest products
 * Search based on keywords and title (rudimentary search, not using any tokenization methods)
 * Interface to view a posted product and show interest 
## Sample images
![Screenshot from 2021-10-29 10-01-37](https://user-images.githubusercontent.com/91063960/139376405-043d6cfd-93b3-4486-a07a-2ff3382846d8.png)
![Screenshot from 2021-10-29 10-01-58](https://user-images.githubusercontent.com/91063960/139376440-1dcd424a-6979-4ec7-bfa0-9e9038ddcbd0.png)

## Future features in queue for next version
(in Jan 2023 probably)
* Enabling and configuring anonymous proxies to sellers and buyers for every transactions. (Generated using a probability table from a names database taken from a foriegn source).
* Providing a interface to negotiate and bid prices among buyers and seller involving only numbers, without any test messages.
* Encorporating a rating and star system to encourage users to sell un-need products for the benefit of community. (Encourages users). Code components are ready, integration is pending.
  
## Tech Stack

**Client:** React, Context, CSS

**Server:** Firebase

## Installation

  1. Clone/Download the repo.
  2. Run npm install.
  3. Config the BackEnd FireBase Change the values in src/firebase/config.js to suit your firebase console project api key values.
  4. Run npm start to spin the up the local dev server port 3000.(http://localhost:3000).

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

