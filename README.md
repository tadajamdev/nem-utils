# nem-utils
NEM's NanoWallet Utils

NanoWallet version 1.3.4

## Install
```sh
npm install nem-utils
```

## Usage
```typescript
import { Network, Address, KeyPair } from "nem_utils";
console.log(Address.toAddress(KeyPair.create("").publicKey.toString(), Network.char2Id("N")));
```
