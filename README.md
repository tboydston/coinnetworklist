# Coin Network List
A list of over 190 cryptocurrency network prefixes. 

# Usage

Installation

``
npm install coinnetworklist
``

Accessing data 

`` 

const coinList = require('coinNetworkList')

console.log(coinlist.BTC)

``

Result

``
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
``

