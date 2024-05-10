README.md
#Organ donation management system using blockchain

[github] (https://github.com/sivaram-ram/organ-donation-management-system)

 This project introduces an innovative Organ Donation Management System (ODMS). By
 storing patient and donor data on a decentralized blockchain network, ODMS ensures immutability,
 transparency, and enhanced security of sensitive information.

## 1. Frontend
The Frontend of this project is built using html and css.An interface for users to interact was implemented using these tools.

## 2. Backend
The Backend is developed using node.js .It handles the buisness logic and facilitates communication with the smart contract.

## 3. Smart Contract
The smart contract component contains the blockchain smart contracts responsible for entering patient and donor data into the blockchain.


## Prerequisites

You would need these software installed on your machine to run the project.
### node.js

  #### Windows:
  1. Visit the NodeJS web page at https://nodejs.org/en/
  2. Download and install the LTS version.
  3. Download the installer and run it. This will install both NodeJS and NPM (Node
  Package Manager).
  
  Note: If you're on Windows 11 the latest npm version is preferred



  #### Ubuntu:
  Open a terminal and type these commands in order.
 
    sudo apt update
    sudo apt install nodejs
    sudo apt install npm
 


   
### Truffle
Open the command prompt or terminal and execute the following command.

npm install -g truffle


### Ganache
Visit the Ganache webpage at http://trufflesuite.com/ganache/
Download the platform binary for your OS and install it.

### Git

#### Ubuntu

sudo apt update
sudo apt install git


#### Windows
Install gitbash from https://gitforwindows.org/

## Installation

### Download
1. Open gitbash or terminal.
2. Clone the repo.
   
   git clone https://github.com/sivaram-ram/organ-donation-management-system
   
3. Traverse into the app folder.
   
   cd organ-donation-platform/app
   
4. Install npm dependencies.
  
   npm install
   

### Connect Ganache
While the npm dependencies are being installed, follow these instructions.
1. Open ganache.
2. Click on "New Workspace".
3. Select "Add Project" and add the truffle-config.js file located in the folder "organ-donation-management-system" you just downloaded.
4. Confirm by pressing "Save Workspace" on the top-right corner.
5. Navigate to the "Contracts" tab and you should notice DonorContract is not deployed.

### Deploy Contract
Back in the gitbash or terminal window instance in which you were downloading npm dependencies

truffle compile && truffle migrate


### Run the server
Now that everything is set-up, you can run the server.
1. Run the following command
   
   npm run dev
   
2. Open a browser and go to http://localhost:8080/



## Team Members
 1.Abhinav P S
 2.Hridul Rengith
 3.Siv Hari Nair
 4.Sivaram R
