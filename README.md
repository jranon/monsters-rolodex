This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Completed for the Complete React Developer Udemy course taught by Andrei Neagoie and Yihua Zhang (https://www.udemy.com/course/complete-react-developer-zero-to-mastery/).

Basic concepts covered included:

- separating functions into separate, re-useable components: 
  - search box - uses App's handleChange function to filter monsters according to changes typed
  - card list - maps (filtered) state monsters into cards
  - card - provides the physical layout for each individual monster card:
    - uses monster id to generate a monster image at 'https://robohash.org/'
    - uses monster name as a header
    - uses monster email as a paragraph

- fetches .json data, then setting state to use this data

- binds component functions handleChange in order to setState for the App using search box