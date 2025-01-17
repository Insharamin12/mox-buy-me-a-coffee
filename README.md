Buy Me A Coffee (Vyper Implementation)

Overview

This repository contains a "Buy Me A Coffee" app built using the Vyper smart contract language. The project enables users to send ETH as a form of appreciation, while maintaining a minimum contribution threshold in USD. The contract also supports owner-controlled fund withdrawals.

Features

Minimum Funding Threshold: Ensures that all contributions meet a minimum USD value equivalent.

Owner-Only Withdrawal: Only the contract owner can withdraw funds.

ETH to USD Conversion: Uses a Chainlink price feed to determine the ETH-to-USD conversion rate.

Decentralized Funding: Keeps track of all funders and their contributions.

Extendable and Secure: Adheres to secure smart contract practices with clear assertions and access control.

Setup & Deployment

1. Clone the Repository

```git clone https://github.com/your-repo/buy-me-a-coffee-vyper.git```

```cd buy-me-a-coffee-vyper```

2. Install Dependencies

3. Compile the Contract

```mox compile```

4. Deploy the Contract
   
```mox run deploy```

6. Run Test
7. 
   ```mox test```

Update the deployment script to include your desired Chainlink price feed address. Then deploy the contract using Brownie:
_For documentation, please run `mox --help` or visit [the Moccasin documentation](https://cyfrin.github.io/moccasin)_
