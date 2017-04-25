# World Travel Guides Stores

### Setup

Create a repo to host this project and build it as an Angular app. 

### Requirements

For this project you need to use Angular to list a collection of travel guides in the DOM that can be purchased.  A user can add them to a cart and also checkout.  We would also like to show the current weather by each book.

_(Do not worry about payment processing or user management.)_

Use the following data as a mock API endpoint:
```
{
  "guides": [{
    "location": {
      "city": "Paris",
      "country": "France"
      },
    "title": "Paris on $10 a Day",
    "price": 18.99,
    "qty" : 4
  }, {
    "location": {
      "city": "Venice",
      "country": "Italy"
      },
    "title": "Venice: Canals and Stuff",
    "price": 14.50,
    "qty" : 3
  }, {
    "location": {
      "city": "Hoboken",
      "country": "USA",
      "state": "New Jersey"
      },
    "title": "Visiting Hoboken: Why?",
    "price": 1.25,
    "qty" : 4
  }, {
    "location": {
      "city": "Rio de Janeiro",
      "country": "Brazil"
      },
    "title": "Touring Brazil's Empty Olympic Stadiums",
    "price": 13.50,
    "qty" : 2
  }, {
    "location": {
      "city": "San Francisco",
      "country": "USA",
      "state": "California"
      },
    "title": "'Murica: Living in San Fran",
    "price": 20.00,
    "qty" : 1
  }, {
    "Location": {
      "city": "Sidney",
      "country": "Australia"
      },
    "title": "Sidney, Australia: Every Animal Here Can Kill You",
    "price": 18.00,
    "qty" : 2
  }, {
    "Location": {
      "city": "Vienna",
      "country": "Austria"
      },
    "title": "Touring Vienna on a Budget",
    "price": 12.48,
    "qty" : 5
  }, {
    "Location": {
      "city": "Panama City",
      "country": "Panama"
      },
    "title": "Beaches of Panama",
    "price": 15.00,
    "qty" : 3
  }, {
     "Location": {
      "city": "Mumbai",
      "country": "India"
      },
    "title": "Touring Mumbai:  Seeing the Sights",
    "price": 13.49,
    "qty" : 2
  },
  {
    "Location": {
      "city": "San Jose",
      "country": "Costa Rica"
      },
    "title": "Life in San Jose",
    "price": 15.51,
    "qty": 1
  }]
}
```

