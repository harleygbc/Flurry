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
"[  
  {  
    "_id": "_user",  
    "username": "Amy Nguyen"  
  }  
]"      
Query found associated Flakes for Amy Nguyen

## Data Add/update/delete


Amy Nguyen
