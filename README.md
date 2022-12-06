# POLYGON LOTTERY (RAFFLE) 
The smart contract of this dApp is situated in the <b>newBranch</b> branch

The dApp is hosted on:
<b>https://snowy-night-5724.on.fleek.co/</b>

The dApp was built using:
NextJS,
Solidity,
Chainlink,
Moralis,
web3uikit,
Hardhat,
IPFS

# TECH STACK OF DApp
<dl>
  <dt><b>Solidity (Hardhat):</b></dt>
  <dd>The smart contract was written with Solidity language using hardhat framework</dd>
  <dt><b>JavaScript:</b></dt>
  <dd>This was used to deploy, test the contract and to also write some scripts</dd>
  <dt><b>React and NextJS:</b></dt>
  <dd>The user interface to interact with the contract was built with React and NextJS</dd>
  <dt><b>Molaris:</b></dt>
  <dd>Molaris API was used to connect the user interface (frontend) with the smart contract (backend)</dd>
  <dt><b>Chainlink:</b></dt>
  <dd>The contract used the chainlink API to get the random number and automation</dd>
  <dt><b>web3uikit:</b></dt>
  <dd>This was used to connect the app to the wallet in the browser</dd>
  <dt><b>IPFS:</b></dt>
  <dd>The dApp was hosted on IPFS</dd>


# USE OF PRODUCT

Once you are on the website, ensure you have a wallet in your browser else you wont be able to use the app. A wallet like metamask in your browser allows you to interact with the application. Click on the <b>Connect Wallet</b> button on the top right of the app, your wallet opens and connect your wallet to the app. Also, ensure you have some Mumbai testnet in your wallet then click on the <b>Enter Lottery</b> button which will take some amount of ETHER in your wallet. You should see the <b>Current number of players increase </b> and after some time a <b>Random winner</b> will be picked and you will see the address of the previous winner. Once a winner is picked, you should be able to enter the raffle again. 

# A BRIEF DESCRIPTION

This is an application that allows users to participate in a completely decentralized and fair random lottery. Users will need to pay 
a specific amount of ETH to enter the lottery then a winner will be picked at random using the chainlink verifiable random number (VRF). Also, no admin will have control of this lottery because we used the chainlink keepers to keep track of when to start or end the lottery based on if all the parameters are met so nobody has control of when the lottery starts or end. 
