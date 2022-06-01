# Flurry

## Install Fluree (Docker)
docker run -d --restart=always -p 8090:8090 fluree/ledger:latest  
Open Browser: http://localhost:8090


## Create a Ledger, Schema, Predicates
Add ledger "fluree/demo"  
Add some data using example data from [Fluree Guides](https://developers.flur.ee/docs/overview/fluree_basics/).  
Use Transact to add some Collections  
Use Transact to add some Predicates  


## Query
Selecting Query>FlureeQL  
Example Query to find Amy Nguyen  
"[  
  {  
    "_id": "_user",  
    "username": "Amy Nguyen"  
  }  
]" 



## Data Add/update/delete
Example Query to update a record using a two-tuple with a unique predicate  
[  
  {  
    "_id": ["person/handle", "anguyen"],  
    "age": 37  
  }  
]  

