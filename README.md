# BuyMeACoffee

Smart contract on Goerli - https://goerli.etherscan.io/address/0xEe0Ed278E3caB0A8dF5cFe174fCfB30341C797aB#code

Demo available on Replit - https://buymeacoffee-2.0xed.repl.co/?

## Description

This is a Next.js app that allows users to buy the owner of the app a cup of coffee using ETH along with a message. The message is stored on the blockchain as a memo and can be retrieved later. withdrawTips allows the contract owner to withdraw all the funds stored in the contract. This function requires that the caller is the contract owner and sends the entire balance of the contract to the owner's address.

## Getting Started

Prerequisites
To get started, you'll need to have the following installed on your system:

- Node.js 
- Git 

### Installing

First, clone this repository using Git:

```
git clone https://github.com/edwardtay/buymeacoffee.git
```

Next, navigate to the project directory and install the dependencies:

```
cd buymeacoffee
npm install
```

Running the app
To start the app, run

```
npm run dev
```

## Credits

[Alchemy](https://docs.alchemy.com/docs/how-to-build-buy-me-a-coffee-defi-dapp)

## License

This contract is licensed under the MIT License.
