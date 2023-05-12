---
slug: /reference/sdk.nftcollection.burn
title: NFTCollection.burn property
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# NFTCollection.burn property

Burn a single NFT

## Example

```javascript
const result = await contract.burnToken(tokenId);
```

**Signature:**

```typescript
burn: {
        (tokenId: BigNumberish): Promise<Omit<{
            receipt: import("@ethersproject/abstract-provider").TransactionReceipt;
            data: () => Promise<unknown>;
        }, "data">>;
        prepare: (tokenId: BigNumberish) => Promise<Transaction<Omit<{
            receipt: import("@ethersproject/abstract-provider").TransactionReceipt;
            data: () => Promise<unknown>;
        }, "data">>>;
    };
```