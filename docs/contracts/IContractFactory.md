---
slug: /IContractFactory
title: IContractFactory
hide_title: true
displayed_sidebar: contracts
---

# IContractFactory

_thirdweb_

## Methods

### deployProxyByImplementation

```solidity
function deployProxyByImplementation(address implementation, bytes data, bytes32 salt) external nonpayable returns (address)
```

Deploys a proxy that points to that points to the given implementation.

#### Parameters

| Name           | Type    | Description                                                                                   |
| -------------- | ------- | --------------------------------------------------------------------------------------------- |
| implementation | address | Address of the implementation to point to.                                                    |
| data           | bytes   | Additional data to pass to the proxy constructor or any other data useful during deployment. |
| salt           | bytes32 | Salt to use for the deterministic address generation.                                         |

#### Returns

| Name | Type    | Description |
| ---- | ------- | ----------- |
| \_0  | address | undefined   |
