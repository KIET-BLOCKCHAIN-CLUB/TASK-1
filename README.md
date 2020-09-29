# TASK-1
## Create A Private Block Chain Using Javascript

The Data Model of the Blockchain should be like 
```js
{
   "hash": "",
   "height": 1325438,
   "body": [],
   "time": 1529001822,
   "previousblockhash": ""
 }
 ```

* set up a class with a constructor for a block data model:
* Then, create the addBlock function to push the newBlock to the chain.
* Keep in mind that all the functionalities in the data model should be satisfied .
* Next Task will be to link Blocks that is hash of previous Block into previousHash of new Block 
* Create Methods to see Height , chain ,and a validate method to Validate the chain .

* Use the Node js Environment with following Dependencies 
  * You can read documentation to know more about it .
  ```js
    "dependencies": {
    "bitcoinjs-lib": "^4.0.3",
    "bitcoinjs-message": "^2.0.0",
    "body-parser": "^1.18.3",
    "crypto-js": "^3.1.9-1",
    "express": "^4.16.4",
    "hex2ascii": "0.0.3",
    "morgan": "^1.9.1"
  }
  ```

  
  

