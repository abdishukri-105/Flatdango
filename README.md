# FLATADANGO
Flatdango is a web application for flatiron movie theater that allows a user to purchase movie tickets from the
theater.

## DOCUMENTATION

#### As a user, I can:

- See the first movie's details, including its **poster, title, runtime,
   showtime, and available tickets** when the page loads. The number of
   available tickets will need to be derived by subtracting the number of
   `tickets_sold` from the theater's `capacity`. 
   
- See a menu of all movies on the left side of the page when the page loads.

- Buy a ticket for a movie. After clicking the "Buy Ticket" button, I should
   see the number of available tickets decreasing on the frontend. I should not
   be able to buy a ticket if the showing is sold out (if there are 0 tickets
   available). **No persistence is needed for this feature**.

- Click on a movie in the menu to replace the currently displayed movie's
   details with the new movie's details.



# HOW TO USE Flatdango

### 1.  Run locally

Clone the project

```bash
  git clone git@github.com:abdishukri-105/Flatdango.git
```

Go to the project directory

```bash
  cd Flatdango
```

Install dependencies

```bash
  npm install
```

Start the json server

```bash
  json-server --watch db.json
```




### 2.visit the app directly

#### to visit the app directly click here https://abdishukri-105.github.io/Flatdango/




## Author

- github link [@abdishukri-105](https://github.com/abdishukri-105)
## Acknowledgements

- Dennis Kiboi - Technical Mentor
- Ian Okumu - Seniour Technical Mentor
## Feedback

If you have any feedback, please reach out to me at abdishukrimohamed105@gmail.com

