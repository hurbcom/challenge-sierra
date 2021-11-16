# <img src="https://avatars1.githubusercontent.com/u/7063040?v=4&s=200.jpg" alt="Hurb" width="24" /> Sierra Challenge

[[English](README.md) | [Português](README.pt.md)]

Create a smart contract for a decentralized application (dapp) so we can rent Hurb's shareable bike!

<p align="center">
 <img src="hurb-bike.jpg" alt="Hurb's Bike" />
</p>

The fictitious dapp user will borrow Hurb's bike by hour, every hour will cost 42 HRB token. As a guarantee to borrow a bike, the user will need to deposit 4 times the value of the tokens needed for the rental in a new escrow account.

When the bicycle is returned, the amount in the escrow account will be splitted in 1/4 into Hurb's wallet and 3/4 returned to the user's account. If the bicycle is not delivered, the amount in the escrow account will be fully transfered to Hurb's wallet.

> Example: 3 hours rent will require 504 HRBs on deposit. When the bike is returned the user will see 378 HRBs back into it's wallet.

User will buy HRB tokens with ETH. The current exchange rate is 1 ETH to 6626070 HRB tokens.

The Hurb's wallet is `0x80210180b22ac1762df30Bd0dD6810D3aF8C798a`

## Requirements

-   Fork this challenge and create your project (or workspace) using your version of that repository, as soon as you **end** the challenge, submit a pull request.
-   If you have any reason not to submit a pull request, create a private repository on Github, do every challenge on the **main** branch and don't forget to fill in the `pull-request.txt` file. As soon as you finish your development, add the user `automator-hurb` to your repository as a contributor and make it available for at least 30 days. **Do not add the `automator-hurb` until development is complete.**
-   If you have any problem creating the private repository, at the end of the challenge fill in the file called `pull-request.txt`, compress the project folder - including the `.git` folder - and send it to us by email.
-   Explain in the README how to implement and use the smart contract.
-   You must submit code tests in Solidity or Javascript as well
-   The smart contract must work on a private Ethereum network or on Ropsten.
-   To run your code, all you need to do is run the following commands:
    -   git clone \$your-fork
    -   cd \$your-fork
    -   command to install dependencies
    -   command to submit your smart contract
    -   command to execute a transaction (one borrow)

## Evaluation criteria

-   **Organization of code**: Separation of modules, folders, etc...
-   **Clarity**: Does the README explain briefly what the problem is and how can I run the application?
-   **Assertiveness**: Is the application doing what is expected? If something is missing, does the README explain why?
-   **Code readability** (including comments)
-   **Security**: Are there any clear vulnerabilities?
-   **Test coverage** (We don't expect full coverage)
-   **History of commits** (structure and quality)
-   **Technical choices**: Is the choice of components, patterns, architecture, etc. the best choice for smart contract?

Bonus: Extra points for those who create a routine to transfer the rented bicycle to someone else, with the extra garantee value going back to the original person.

## Questions

Any questions you may have, please check the [issues](https://github.com/HurbCom/challenge-sierra/issues) to find out if someone hasn't it before. If you can't find your answer, create a new issue and send your question!

Godspeed! ;)

<p align="center">
 <img src="ca.jpg" alt="Challange accepted" />
</p>
