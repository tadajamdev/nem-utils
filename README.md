# nem-utils
NEM's NanoWallet Utils

##Install
```sh
npm install nem-utils
```

##Usage
```typescript
import { Network, Address, KeyPair } from "nem_utils";
console.log(Address.toAddress(KeyPair.create("").publicKey.toString(), Network.char2Id("N")));
```
