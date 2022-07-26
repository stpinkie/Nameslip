#buildspace Polygon NFT Drop Site
## buildspace Polygon ENS Mint (Front-End)

![image](/public/livesite.png)

## Welcome 👋
This is the front-end for a Polygon ENS NFT mint site. You can see the full project, including how to create and edit the smart contract, on [buildspace](https://buildspace.so/polygon).

## How to get things working
To mint your own ENS style domain name on Polygon, change the following:

- Update Contract Address
- Update Front-End ABI File

**Contract Address**
```
/src/App.js
const CONTRACT_ADDRESS = "";
```
**ABI File**
```
/utils/Domains.json
{
    "_format": "hh-sol-artifact-1",
    "contractName": "",
    "sourceName": "",
    "abi": [],
    "bytecode": "",
    "deployedBytecode": "",
    "linkReferences": {},
    "deployedLinkReferences": {}
}
```

## Questions?
Have some questions make sure you head over to your [buildspace Dashboard](https://buildspace.so/p/build-polygon-ens) and link your Discord account so you can get access to helpful channels and your instructor!