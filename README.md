
# Vote - Chain

## Overview

Welcome to the "VoteChain" – a pioneering platform utilizing ResilientDB and GraphQL, a cutting-edge blockchain technology, to revolutionize the landscape of electronic voting systems. Our primary focus is to ensure a secure and transparent voting process while emphasizing the significance of each voter's singular vote. VoteChain is designed to guarantee the permanence of votes, enabling every participant to cast a single vote per election. Our system strictly prohibits multiple votes, ensuring the integrity and fairness of the electoral process. One of the standout features of VoteChain is its user-friendly interface and the provision of a dedicated admin panel. Within the admin panel, a comprehensive display of all elections and their respective candidates' votes is showcased. These statistics are presented dynamically through visually intuitive representations such as bar graphs, pie charts, and polar area charts. At VoteChain, we are committed to fostering a trustworthy environment where the sanctity of each vote is upheld. Our utilization of ResilientDB technology ensures the highest standards of security, transparency, and reliability in electronic voting, empowering individuals to participate in the democratic process with confidence.

## Features

1) Secure and Transparent Election
2) Single Voting Instance
3) Immutable Votes
4) Limited Access to Results
5) Electronic Vote Visualisation in the Admin Panel
6) User Friendly interface

## Architecture Diagram

<img src="https://github.com/Kri-hika/vote-chain/assets/70900997/2282f2ba-6268-488c-9b79-999b05456be3" alt="Architecture Diagram" width="500">

## Tech Stack

1) **ResilientDB** - A cutting-edge blockchain technology chosen for its robustness and immutability, providing secure, transparent, and tamper-resistant data storage essential for our electronic voting system.
2) **GraphQL** - Utilised for efficient and versatile data querying, offering a streamlined interface to access blockchain based information. Implemented Fetch Transaction, Post Transaction and Send Request APIs using GraphQL.
3) **React.js** - It was utilized for building composable and interactive user interface within the VoteChain platform, facilitating the creation of modular components and seamless UI interactions.
4) **Material UI** - A responsive UI design library complementing React.js, ensured a consistent and visually appealing layout across various devices and screen sizes.
5) **Node.js** - It forms the foundational infrastructure for the VoteChain back end, managing server-side logic and acting as an intermediary between the user interface and ResilientDB blockchain

## Steps to run the system

Please follow the detailed procedure below and ensure that every step is successful.

### Setup Python3.10
Ensure you have Python3.10, otherwise download it and set it up as default.

## Installation

Follow these steps to set up the development environment and run the application locally.

### Prerequisites

Before you begin, make sure you have the following software installed on your machine:

1. **Node.js** - Download and install Node.js from [https://nodejs.org/](https://nodejs.org/)

2. **npm (Node Package Manager)** - npm is included with Node.js. Ensure that you have the latest version by running the following command in your terminal:

   ```
   npm install
   ```

## Clone the Repository
Clone this Git repository to your local machine using the following command:

 ```
 git clone https://github.com/Kri-hika/vote-chain.git
 ```
   

## Install Dependencies
Navigate to the project directory and install the project dependencies. Run the following commands in your terminal:

 ```
 cd vote-chain
 npm install
 ```
   
This will install all the required dependencies specified in the package.json file.

## Run the Application
Once the dependencies are installed, start the development server to run the application. Run the following command:
    
```
npm start
```

This will launch the application, and you can access it in your web browser at [http://localhost:3000](http://localhost:3000).

## For more information

Refer to the Blog - https://naitikjain3071.wixsite.com/my-site

