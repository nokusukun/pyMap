# pyMap 

### Usage
```
>>> dictionary = {"name": "john doe", "age": 21, "state": "ohayou~"}
>>> import pymap
>>> new_dict = pymap.Map(dictionary)
>>> new_dict.name
'john doe'
>>> new_dict.name = "jane doe"
>>> new_dict.name
'jane doe'
>>> new_dict.country = "USA"
>>> new_dict
{'country': 'USA', 'age': 21, 'state': 'ohayou~', 'name': 'jane doe'}

```