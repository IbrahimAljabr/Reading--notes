## Read 1:

## Array.map()

The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

## Array.reduce()

The reduce() method executes a reducer function (that you provide) on each element of the array, resulting in single output value.

## superagent()

### then()
```
 request
   .post('/api/pet')
   .send({ name: 'Manny', species: 'cat' })
   .set('X-API-Key', 'foobar')
   .set('Accept', 'application/json')
   .then(res => {
      alert('yay got ' + JSON.stringify(res.body));
   });
```
### async() / await()

```

  const https = require('https');
  https.get('https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY', (resp) => {
    let data = '';
    
    // A chunk of data has been received.
    resp.on('data', (chunk) => {
      data += chunk;
    }); 
    
    // The whole response has been received. Print out the result.
    resp.on('end', () => {
      console.log(JSON.parse(data).explanation);
    });
    
  }).on("error", (err) => { 
    console.log("Error: " + err.message);  
  });
```
  ## Promise
  
  The Promise object supports two properties: state and result. While a Promise object is "pending" (working), the result is undefined. When a Promise object is "fulfilled", the result is a value. When a Promise object is "rejected", the result is an error object.
  
  ## Are all callback functions considered to be Asynchronous ?
  
  Simply taking a callback doesn't make a function asynchronous. There are many examples of functions that take a function argument but are not asynchronous. ... It iterates over each item and calls the function once per item.
  
  
  
  
