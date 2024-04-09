# BlockChainVoting

A blockchain-based E-voting system. Teammates include me, Vivek Dhiman, Vansh Gupta, Vansh Dixit, Vasu Gupta.
> The application is MIT-Licensed.

### install dependencies

```bash
# install dependencies
npm install
# or
yarn
```

### compile to generate artifacts

```bash
npm run compile
# or
yarn run compile
```

### (important) run local hardhat network on a new terminal from root of the project

```bash
npm run chain
# or
yarn run chain
```
Note: in docker or VM use `--hostname 0.0.0.0`

```bash
yarn hardhat node --hostname 0.0.0.0
```

### deploy
```bash
npm run deploy
# or
yarn run deploy
```

Note: update the `VotingAddress` variable with deployed contract address (i.e. 0x9fE46736679d2D9a65F0992F2272dE9f3c7fa6e0) in `context/constants.js`.

### start the web app

```bash
npm run dev
# or
yarn run dev
```

Create your own <b>.env</b> file and the file should contain:
```bash
EMAIL=YOUR_EMAIL_ID
PASSWORD=YOUR_PASSWORD_FOR_EMAIL_ID
```
Install MetaMask extension (https://metamask.io/download.html) and make sure to have some Ether to test the application locally.


###### Please star the repo if it helped you in any way!

## Tech Stack:

- Solidity/Web3 (for writing/connecting the Blockchain contract)
- Next.js & Semantic UI React (front-end)
- IPFS (file storage for images)

## Screenshots of the app:

Homepage of the application:



Company registers/logs in:



List of candidates for the election (here, you can add candidates):


List of voters for the election (here, you can add voters):


Successful voting scenario:



Unsuccessful voting scenario:


Notification to each candidate and voter for the winner of candidates:


