# Dmusic
Dmusic is decentralized application to sell and purchase music contents

When ever we use a mobile app like spotify, we use data which is stored in a centralized system. This centralised authorithy has full access to the data, they can delete or block the content without any prior notice, which effect both content creator and the listener. Most creators are paid by the centralised authority, which involves bias. Fans have to resort to collect physical merchandise sold by the artist from the central authority, which cost them to pay more.
Dmusic solve all of the issues mentioned above. since blockchain is immutable, in which details are stored securely.
we use filecoin to store the data, and the hash is stored in mumbai(polygon testnet)which runs on ethereum evm.
Now the music creator can directly sell his content to his fans, they can even resell it with ease.




## Tech Stack Used

- Solidity
- Truffle Suite
- mumbai testnet
- web3.storage - IPFS and Filecoin
- Openzeppelin contracts
- ReactJS
- react-bootstrap
- ethereum
- polygon

## Dmusic Smart Contract Deployment



## Run Locally

### Pre-Requisites

- Truffle Suite
- Ganache CLI

```
$ npm install -g truffle
$ npm install -g ganache-cli
```  
Clone the project

```
$ git clone https://github.com/UltimateRoman/EduChain.git
$ cd EduChain
```
### Setting up a local Blockchain
Install dependencies

```
$ npm install
```

Compile Smart Contracts

```
$ truffle compile
```

Run ganache

```
$ ganache-cli
```  

Run migrations to deploy the smart contracts

```
$ truffle migrate
```  

### Setting up the client

Start the App

```
$ npm start
```

Visit https://localhost:3000/ to view the app


## Running Tests

To run tests, run

```
  truffle test
```
