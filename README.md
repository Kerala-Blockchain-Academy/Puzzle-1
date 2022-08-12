# Puzzle #1

### The Deployed Contract Address
 - <b>Sepolia</b>: 0x39AF971B0FAd4459d94DF4d979278f9526754A97
 - <b>Goerli</b>: 0xDda9867Fa0664f1126D1bA5Bf44FBFA5a7AcD9F5
 
 
### ABI
```
[
	{
		"inputs": [],
		"name": "code",
		"outputs": [
			{
				"internalType": "string",
				"name": "",
				"type": "string"
			}
		],
		"stateMutability": "view",
		"type": "function"
	},
	{
		"inputs": [],
		"name": "question",
		"outputs": [
			{
				"internalType": "string",
				"name": "",
				"type": "string"
			}
		],
		"stateMutability": "view",
		"type": "function"
	}
]
```

Upon calling the contract functions you will obtain a code and a question. Combine the code and question answer to get the final coupon code.

### Example

Code: KBA  
Question: When was the bitcoin white paper released?  

Coupon Code: KBA2008
