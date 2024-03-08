# Restaurants Questions
## Q1

* First argument to `find` is the filering
* Second argument to `find` is the projection,

```
db.restaurants.find({
    'cuisine':'Hamburgers'
},{
    'name':1,
    'address':1,
    'cuisine':1
})
```
## Q2
```
db.restaurants.find({
    'cuisine':'American',
    'borough':'Bronx'
}, {
    'name': 1,
    'address': 1,
    'cuisine': 1,
    'borough': 1
})
```