1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
   ![console output](https://github.com/helmihidzir/nervos/blob/main/task-3/output.png)


2. The transaction hash from the console output (in text format).
   0xd644977f7e70d796e3957dada527c92aeaa0fe2746b9584d318b57a847ed0674


3. The contract address that you called (in text format).
   0x4ee57D1C87c8469b655ef215A61957f08385FBEC


4. The ABI for contract you made a call on (in text format).
```
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```