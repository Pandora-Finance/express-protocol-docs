---

```javascript
const result = await ExpressSDK.erc721.collection.fetchTokenURI(
  web3, // Web3 instance configured with metamask
  collectionAddress, // Address of the collection
  tokenId // Id of token to fetch tokenURI of
);
```

Successful execution of this function will fetch the tokenURI associated with the respective token Id inside the collection.

---
