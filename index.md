# Postman Scripting

## Postman Variables
### Types of variable
- Global
- Environment
- Collection
- Data
- Local
### Get , Set, unset format
Get <br>
```
pm.variable.get('variable')  ''''For collectionVariables, environment, global use pm. format <br>
```
Set <br>
```
pm.variable.set('variable')  <br>
```
Unset <br>
```
pm.variable.unset('variable')  <br>
```
Replace (use the var) <br>
```
pm.variables.replaceIn("Hi, my name is {{variable}}"); <br>
```


## Postman common pre requests

## Writing Postman Assertions
## Chaining Postman Requests
