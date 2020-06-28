How to run


1. Add some products in ecommpoc database using Mongodb compass
  
  1. Run &"C:\Program Files\MongoDB\Server\4.2\bin\mongod.exe" --dbpath=" " on command prompt
  
  2. Connect to localhost:27017
  
  3. Create a new collections users and products in ecommpoc
  
  4. In products collection add the following data using ADD DATA>Insert Document
   [
  {   
      "name": "Banana",
      "image": "/images/Fruits/banana.PNG",
      "category": "Fruits",
      "price": 50,
      "brand": "Keventer Bananas",
      "ratings": 4.0,
      "numReviews": 10,
      "countInStock": 6
  },
  {
      
      "name": "Cabbage",
      "category":"Vegetables",
      "image": "/images/vegetables/cabbage.PNG",
      "price": 30,
      "brand": "Savoy",
      "ratings": 4.5,
      "numReviews": 10,
      "countInStock": 6
  },
  {
      
      "name": "Capsicum",
      "category":"Vegetables",
      "image": "/images/vegetables/capsicum.PNG",
      "price": 45,
      "brand": "Green chilli",
      "ratings": 4.8,
      "numReviews": 10,
      "countInStock": 6
  },
  {
      
      "name": "Potatoes",
      "category":"Vegetables",
      "image": "images/vegetables/potatoes.PNG",
      "price": 35,
      "brand": "",
      "ratings": 4.8,
      "numReviews": 10,
      "countInStock": 6
  },
  {
      
      "name": "Corn Bread",
      "category":"Breads",
      "image": "/images/Breads/cornbread.PNG",
      "price": 25,
      "brand": "",
      "ratings": 9.8,
      "numReviews": 10,
      "countInStock": 6
  },
  {
      
      "name": "Banana Bread",
      "category":"Breads",
      "image": "/images/Breads/banana-bread.PNG",
      "price": 55,
      "brand": "",
      "ratings": 8.5,
      "numReviews": 10,
      "countInStock": 6
  },
  {
      
      "name": "Challah",
      "category":"Breads",
      "image": "/images/Breads/Challah.PNG",
      "price": 47,
      "brand": "",
      "ratings": 4.9,
      "numReviews": 10,
      "countInStock": 6
  },
  {
      
      "name": "Butter",
      "category":"Dairy",
      "image": "/images/Dairy/butter.PNG",
      "price": 47,
      "brand": "",
      "ratings": 4.4,
      "numReviews": 10,
      "countInStock": 6
  },
  {
      
      "name": "Cheese",
      "category":"Dairy",
      "image": "/images/Dairy/cheese.PNG",
      "price": 100,
      "brand": "",
      "ratings": 4.6,
      "numReviews": 10,
      "countInStock": 6
  },
  {
      
      "name": "Milk",
      "category":"Dairy",
      "image": "/images/Dairy/milk.PNG",
      "price": 55,
      "brand": "",
      "ratings": 4.7,
      "numReviews": 10,
      "countInStock": 6
  }  
  
  ]



2. Run Backend
  
    1. open terminal 
  
    2. npm install
  
    3. npm start


3. Run Frontend
  
    1. open new terminal
  
    2. cd frontend
  
    3. npm install
  
    4. npm start
