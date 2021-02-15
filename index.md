# Postman Scripting

## Postman Variables
### Types of variable
- Global
- Environment
- Collection
- Data
- Local
### Get , Set, unset format
For collectionVariables, environment, global use pm. format <br>
Get <br>
```
pm.variable.get('variable') 
```
Set <br>
```
pm.variable.set('variable') 
```
Unset <br>
```
pm.variable.unset('variable')
```
Replace (use the var) <br>
```
pm.variables.replaceIn("Hi, my name is {{variable}}");
```
## Working with Requests
The request URL: <br/>
```
const req = pm.request.url.getHost()
const query = pm.request.url.getPathWithQuery()
const raw = pm.request.url.getRaw()
console.log(req, query, raw)
```
<img src = 'url_req.png'/>

# Postman common pre requests

# Writing Postman Assertions
# Chaining Postman Requests
