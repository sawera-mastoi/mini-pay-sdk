# minipay

SDK for interacting with the Celo Talent April Reward Event contract.

## Installation

```bash
npm install minipay
```

## Usage

```javascript
const { MiniPaySDK } = require('minipay');

// Initialize the SDK
const sdk = new MiniPaySDK();

// Example interaction
async function run() {
  // Add your logic here
  console.log("MiniPay SDK initialized for contract:", sdk.contractAddress);
}

run();
```

## Contract Details

- **Network:** Celo
- **Contract Address:** `0xc8b20fd2c23f2db1d7f27736b0e20bdafbf2672c`
