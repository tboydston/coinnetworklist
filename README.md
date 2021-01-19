# Coin Network List
A list of over 190 cryptocurrency network prefixes. 

# Usage

Installation

`
npm install coinnetworklist
`

Accessing data 

 ```

const coinList = require('coinNetworkList')

console.log(coinlist.BTC)

```

Result

```
{
       "shortName":"BTC",
       "longName":"Bitcoin",
       "network":{
          "p2wpkh":{
             "baseNetwork":"bitcoin",
             "messagePrefix":"\\x18Bitcoin Signed Message:\n",
             "bech32":"bc",
             "bip32":{
                "public":78792518,
                "private":78791436
             },
             "pubKeyHash":0,
             "scriptHash":5,
             "wif":128
          },
          "p2wpkhInP2sh":{
             "baseNetwork":"bitcoin",
             "messagePrefix":"\\x18Bitcoin Signed Message:\n",
             "bech32":"bc",
             "bip32":{
                "public":77429938,
                "private":77428856
             },
             "pubKeyHash":0,
             "scriptHash":5,
             "wif":128
          },
          "p2wsh":{
             "baseNetwork":"bitcoin",
             "messagePrefix":"\\x18Bitcoin Signed Message:\n",
             "bech32":"bc",
             "bip32":{
                "public":44728019,
                "private":44726937
             },
             "pubKeyHash":0,
             "scriptHash":5,
             "wif":128
          },
          "p2wshInP2sh":{
             "baseNetwork":"bitcoin",
             "messagePrefix":"\\x18Bitcoin Signed Message:\n",
             "bech32":"bc",
             "bip32":{
                "public":43365439,
                "private":43364357
             },
             "pubKeyHash":0,
             "scriptHash":5,
             "wif":128
          },
          "p2pkh":{
             "messagePrefix":"\u0018Bitcoin Signed Message:\n",
             "bip32":{
                "public":76067358,
                "private":76066276
             },
             "pubKeyHash":0,
             "scriptHash":5,
             "wif":128,
             "bech32":"bc"
          }
       },
       "coinNumber":0
}
```

# Notes

The default network data for a coin is listing in the "p2pkh" object key. Some coins contain an "addressType" key. This is to indicate that they require special hashing logic or that they use the special hashing logic of a different coin. For example BSC uses ETH hashing logic.


# Credit

This list was consolidated from the source of [iancoleman.io/bip39](https://iancoleman.io/bip39). 

