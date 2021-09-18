# Problem statement
* The donations done on a crowd funding project the funds of donator are most of the time misused by the receiver. Hence, making it much riskier option.
# Solution
* Stratup_fund uses a system of Etherum blockchain, to ensure that transactions are sequre and reduce fraudlent activity
* It uses Etherum on Rinkeby. With the help of metamask

### To Run the Project :

#### `cd startup_fund`

#### To install dependencies :

#### `npm install`

#### To run the application :

#### `npm run dev`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

#### To test the contract functionalities locally using ganache local ethereum network:

#### `npm run test`

### Note :
The contract is deployed on Rinkeby test network at address '0x6a31e79948af4E1554d14A9bFcda7fe39043d7bA' with the help of infura node api.<br/> 
If you want to deploy the contract on your own. 
* Checkout `deploy.js` file in the `ethereum` directory, do the neccessary changes as suggested over there. 
* Thereafter run the `deploy.js` file and replace the account address in `factory.js` file in `etherium` directory with value of the same printed on console.

## Demo Screenshot

***index page***
![index](https://user-images.githubusercontent.com/67409557/132615574-4b0771c8-8290-4788-9caf-67e6bfb7a574.png)

***Campaign Detail***
![campaign_show](https://user-images.githubusercontent.com/67409557/130391447-811ddf4a-2fe3-468a-9605-c01944200a5a.png)

***Create Campaign***
![create_campaign](https://user-images.githubusercontent.com/67409557/130391567-231f68a5-22b6-41f7-8799-c11052bb63bf.png)

***Request Detail***
![request](https://user-images.githubusercontent.com/67409557/130391478-bb3f426b-aec9-413d-a1c3-4a757f94e914.png)

***Create Request***
![create_request](https://user-images.githubusercontent.com/67409557/130391526-c4d52c8a-fd99-45e4-a7e2-cad2d5742dae.png)


