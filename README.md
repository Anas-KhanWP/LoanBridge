# LoanBridge

Peer 2 peer lending platform on the Ethereum blockchain network.

# About

We all know that in the Banking industry it is all about the constant search of bigger profits without caring about customers.

Credit borrowers are paying higher interest rates every day while people investing are having poor returns. There are also a few hidden fees that the customer doesn't know about.

So we said stop. We've built a p2p blockchain lending service, fair and transparent.

# Features

- Ask for funding (borrow)
- Provide details of the requested funding.
- Withdrawal of funding after successfully reached goal of full funding.
- Repayment installments functionallity.
- Invest in project/credit (lend)
- Vote for revoke contract / refund investments.
- Mark project as Fraud.

## Chart flow

![Chart flow](https://i.imgur.com/vRq7nAN.png)

### Further development

- Improve external contract calls.
- Minimize gas cost.
- Create more investors protection.

### Requirements

* [Node.js](https://nodejs.org/)
* [Truffle](https://truffleframework.com/)
* [Ganache](https://truffleframework.com/ganache/)
* [MetaMask](https://metamask.io/)

### Installation

1. Start Ganache on `localhost:7545`
2. Build and migrate smart contracts

```sh {"id":"01J8NFNWVW1VDZ4X1KYJD03Y3F"}
$ cd p2p-lending/smart-contracts
$ truffle compile
$ truffle migrate --reset --network development --verbose-rpc
```

3. Set the `PeerToPeerLending` contract newly published address in the [client-app/public/js/contract_interaction.js LINE:3](https://github.com/mradkov/p2p-lending/blob/370bde2a452caff4831d5e91157f733ce9921a99/client-app/public/js/contract_interaction.js#L5)
4. Install the dependencies and devDependencies and start the server.

```sh {"id":"01J8NFNWVW1VDZ4X1KYPB63QFV"}
$ cd p2p-lending/client-app
$ npm install --save
$ npm start
```

5. Your app is running on `http://localhost:1337`

### Development

Want to contribute? Great!

# Authors

    Anas Khan - anaskhanwp@gmail.com
        Email - anaskhanwp@gmail.com
        LinkedIn - https://www.linkedin.com/in/anas-khan-mak/

# Acknowledgments

    SoftUni - https://softuni.bg/
    ACADEMY: SCHOOL OF BLOCKCHAIN - http://www.kingsland.academy/

# License

MIT

**Free Software, Hell Yeah!**
