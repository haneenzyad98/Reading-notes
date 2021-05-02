# Review

- ### Array.map()
method creates a new array with the chaing for every array element as  function calling afect .


- ### Array.reduce() 
  method run yaur function on each element of the array
  the result is single output value.

- ### superagent()
  - With normal Promise .then() syntax

             superagent.get(url).then(x=>{
                        })

  - Again with async / await syntax

          async function readFile(filePath) {
  try {
    const data = await fs.readFile(filePath);
    console.log(data.toString());
  } catch (error) {
    console.error(`error`);
  }
}


 - the Promise object represents the eventual completion (or failure)

 - Are all callback functions considered to be Asynchronous? Why or Why Not?           
 callback doesn’t make a function asynchronous
 like forEach in array                 




