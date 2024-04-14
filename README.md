# okx-connector

> Okx injected provider API
> https://www.okx.com/web3/build/docs/sdks/chains/evm/provider

## Usage with web3-react@^6.0.0

### Install

```
yarn add web3-react-okx-connector
```

### Arguments

```
supportedChainIds?: number[]
```

### Example

```
import { InjectedConnector } from 'web3-react-okx-connector'

const injected = new InjectedConnector({ supportedChainIds: [1, 3, 4, 5, 42] })
```

### Error

1. NoOkxwalletProviderError
2. UserRejectedRequestError
