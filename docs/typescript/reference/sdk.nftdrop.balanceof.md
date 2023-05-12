---
slug: /reference/sdk.nftdrop.balanceof
title: NFTDrop.balanceOf() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# NFTDrop.balanceOf() method

Get NFT Balance

## Example

```javascript
const walletAddress = "{{wallet_address}}";
const balance = await contract.balanceOf(walletAddress);
console.log(balance);
```

**Signature:**

```typescript
balanceOf(address: AddressOrEns): Promise<BigNumber>;
```

## Parameters

| Parameter | Type                                  | Description |
| --------- | ------------------------------------- | ----------- |
| address   | [AddressOrEns](./sdk.addressorens.md) |             |

**Returns:**

Promise&lt;BigNumber&gt;

## Remarks

Get a wallets NFT balance (number of NFTs in this contract owned by the wallet).