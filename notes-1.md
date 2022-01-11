# Readings: Node Ecosystem, TDD, CI/CD

this reading includs alot of information from W3 schools

## Array.map()

- creates a new array from calling a function for every array element.

- calls a function once for each element in an array.

- does not execute the function for empty elements.

- does not change the original array.

## Array.reduce()

- returns a single value

- executes a reducer function on array elements to get 1 value.

- does not execute the function for empty array elements.

- method does not change the original array.

## superagent using .then()

`const getCharacters = () => {
  superagent.get('https://swapi.dev/api/people')
    .then( data => {
      var final_results = {}
      var results = data.body.results;
      for (var i=0; i< results.length; i++){
        var name = results[i].name;
        var url = results[i].url;
        final_results[name] = url;
      }
      console.log(final_results)
    })
    .catch(err => console.error(err));
}`

## superagent using async/await

`async function getCity(cityName){
  let results = await superagent.get(`https://geocode.xyz/${cityName}?json=1`);
  let lat = results.body.latt
  let lon = results.body.longt
  console.log(`${cityName} - latitude:${lat}, longitude:${lon}`)
}`

## explaining promises

because javascript is synchronous by nature, whenever you start an action, nothing else can start until that action is done or 'taken care of'. Promises are how we handle that. instead of waiting around for our action to be done, we send back a 'promise' that will allow the code to continue running and know that once that action is done it will be added to our call stack with everything else.

## Callbacks

callbacks are 'higher order' functions. they are not asynchronous by nature but can be used for asynchronous stuff.