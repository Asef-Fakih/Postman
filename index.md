# Postman Scripting

## Postman Variables
### Types of variable
- Global
- Environment
- Collection
- Data
- Local
### Get , Set, unset format
Get
pm.globals.get('variable')
pm.environment.get('variable')
pm.collectionVariables.get('variable')
pm.variable.get('variable')
Set
pm.globals.set('variable')
pm.environment.set('variable')
pm.collectionVariables.set('variable')
pm.variable.set('variable')
Unset
pm.globals.unset('variable')
pm.environment.unset('variable')
pm.collectionVariables.unset('variable')
pm.variable.unset('variable')

Also there is Replacein method to use the variable in a string: 
pm.variables.replaceIn("Hi, my name is {{$randomFirstName}}");

## Postman common pre requests
## Writing Postman Assertions
## Chaining Postman Requests
