![Travis badge](https://travis-ci.org/Firstbloodio/token.svg?branch=master)

<img src = "https://cdn-images-1.medium.com/max/1200/1*vSRfNm_bX1C6ntGFqfFX4A.png" width = "30%">

# FirstBlood Crowdsale Ethereum smartcontract

This is the code for the Ethereum smartcontract responsible for [FirstBlood](https://firstblood.io) crowdsale.

## Explore the Contract 
[View on etherscan.io](https://etherscan.io/token/firstblood)

## Tests

To run tests, first install mocha and Ethereum test dependencies:

    npm install

Then, launch a testrpc client:

    node_modules/.bin/testrpc --port 12345

Then, run the test framework:

    node_modules/.bin/mocha test

## Contract and Security Analysis

You can [read through commented contract Solidity source code](https://github.com/Firstbloodio/token/blob/master/smart_contract/FirstBloodToken.sol).

## Security Analysis Notes

[Price curve test](https://github.com/Firstbloodio/token/issues/2)

[Addressed issues](https://github.com/Firstbloodio/token/issues/7)

[Final acceptance process](https://github.com/Firstbloodio/token/issues/3)

## Terms and Risk Disclosure

Please read **CAREFULLY** through these documents which are also available on our official site before interacting with this smart contract.

[1ST Presale Purchase Agreement](presale_agreement.pdf) and
[FIRSTBLOOD RISK DISCLOSURE DOCUMENT](risks_disclosure.pdf)
