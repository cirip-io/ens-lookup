# ENS Reverse Lookup Cloudflare Worker

Reverse resolution in ENS - the process of mapping from an Ethereum address (eg, 0x1234...)

### Usage
Simply use a valid ENS Cirip URL to receive the ens informations:

GET
```
https://ens.cirip.io/0xeF8305E140ac520225DAf050e2f71d5fBcC543e7
```
RESPONSE
```
{
  "reverseRecord": "fabien.eth",
  "domains": [
    "fabien.eth",
    "textcoin.eth",
    "fabien.sismo.eth",
    "snapback.eth",
    "devcondemo.eth"
  ]
}
```
