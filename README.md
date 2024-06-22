#### Working Screenshot.

1) Add Candidate
   ![Add Canditate](https://github.com/pranjal-pandey1/Blockchain-Voting/assets/145914949/65739a35-f966-4c5e-99e6-368f0c6a5c7e)
2) Candidate Added.
   ![Canditate Added](https://github.com/pranjal-pandey1/Blockchain-Voting/assets/145914949/41774425-20d8-4a28-8c3c-b794413a0346)
3) Regiter User
   ![RegiterV](https://github.com/pranjal-pandey1/Blockchain-Voting/assets/145914949/c3ba4003-ade3-499f-9400-3be93c09efd2)
4) Voting.
   ![V](https://github.com/pranjal-pandey1/Blockchain-Voting/assets/145914949/478c2baa-8dd8-4556-ba0d-efc602875752)
5) Voted
   ![voted](https://github.com/pranjal-pandey1/Blockchain-Voting/assets/145914949/dee136b9-4abc-4e35-b331-cb45bdf97a71)

 ----------------------------------------------------------------------------------------------------------------------------------------------


#### Connecting metamask and ganache
1. In metamask, go to settings > networks > add network. You can also get to this by clicking the metamask extension pinned on your browser > clicking the profile picture > settings > networks > add network
2. Give your network any name of choice. 
3. For New RPC URL go to ganache where you'll copy the RPC server url and paste in Metamask. 
4. Chain ID for ganache is 1337. 
5. You can name currency symbol as "ETH" and save. 

#### Importing an account from ganache to metamask
1. Open ganache and select show keys on any account. The show keys button is the key icon.
2. Copy the private key and click done.
3. Open the metamask menu which can be accessed by clicking the profile picture and select import account.
4. Paste the private key copied from ganache and click import.

#### Cloning the project

```git clone https://github.com/faizscripts/blockchain-voting-system```

```cd blockchain-voting-system```

```npm i```

```truffle compile```

```truffle migrate```or```truffle migrate --reset``` for subsequent runs

```npm start```

The project will open in the browser and metamask will ask you to select an account. Select the account we had imported earlier.
