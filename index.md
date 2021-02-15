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
pm.variable.get('variable')  ''For collectionVariables, environment, global use pm. format''
Set <br>
pm.variable.set('variable')  
Unset <br>
pm.variable.unset('variable')  
Replace (use the var)
pm.variables.replaceIn("Hi, my name is {{variable}}");


## Postman common pre requests

## Writing Postman Assertions
## Chaining Postman Requests
