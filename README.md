# NFTs
 
step 1 : Create a metamask account and add it from chrome extensions

step 2 : Connect goerli test network to metamask account


step 3 :The node modules folder is required throughout the web pack construction process because when you import a file 
	
	from the node modules, web pack will try to get the file from the specific node module folder recursively.
	
	for this we need to use ---- > npm install command in our command prompt

step 4 : Create a PINATA account and copy the new API key and secret key to the environment variables

step 5 : Create an Alchemy account and create a new app and copy the URL and paste it to the environment variables

step 6 : Now, we have to assign the private key of the metamask Account - 1 to the environment variables

step 7 : Set up your environment variables and Hardhat config

step 8 : Now perform this command ----> npm install dotenv --save

step 9 : For deploying the smart contract on Goerli we need to perform this command

	 -----> npx hardhat run --network rinkeby scripts/deploy.js

		Note : If you don't see any errors or warnings, your smart contract was successfully deployed! 

		       You should be able to see the address it was deployed to and the ABI of the smart contract in src/Marketplace.json

step 9 : To test the code we need to perform this command 

         -----> npm run start

step 10 : For accessing through the customer interface we need to switch to Account - 2 of the goerli network in the metamask
