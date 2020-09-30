![Completion 1.0.0](https://img.shields.io/badge/completion%20v1.0.0-0%25-red) ![Help Wanted](https://img.shields.io/badge/%20-help--wanted-%23159818) ![Version 0.9.3](https://img.shields.io/badge/version-v2.4.0-blue) ![Sponsors](https://img.shields.io/badge/sponsors-0-red)

## Quest Engine

## Description

An Angular compatible NodeJS library for the use with [Quest OS](https://github.com/QuestNetwork/quest-os-js) that allows to create and participate in quests on the network.

We have chosen Angular/Electron as an example environment because we believe it offers the best accessibility for developers coming from any other language/framework. It is already being used in Python on PyQt5 and we aim to provide the underlying library in Go and wherever possible in Rust as well.

qDesk makes it possible to build custom, secure and decentralized social networks in less than 20 days.

0.9.5+ allow to connect qDesk Social profiles to Twitter without sharing information with Twitter as an additional layer of verification. It is planned to add passive verification for a custom list of external networks to verify the peer identities.

1.0.0+ complies with privacy regulations and can be used for confidential information as a production social network for enterprises worldwide.

[qDesk](https://github.com/QuestNetwork/qDesk) works in the browser, as an Electron on Windows, Mac and Linux and Android using Cordova.

Check out other [Awesome Quest Network dApps](https://github.com/QuestNetwork/awesome/blob/master/README.md)!

## Security
![Completion 1.0.0](https://img.shields.io/badge/OAEP-4096%20Bit-green) ![EC](https://img.shields.io/badge/EC-P&#8208;521-green) ![AES](https://img.shields.io/badge/AES-256%20Bit-yellow)

[Quest OS](https://github.com/QuestNetwork/quest-os-js) uses [4096 Bit RSA-OAEP](https://en.wikipedia.org/wiki/RSA_(cryptosystem)#Operation) encryption, [256 Bit AES-CBC](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) encryption and [NIST P-521 EC](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography#Fast_reduction_(NIST_curves)) signatures.

## Lead Maintainer

[StationedInTheField](https://github.com/StationedInTheField)

## Support Us
Please consider supporting us, so that we can build a non-profit for this project (ツ)

| Ethereum| Bitcoin |
|---|---|
| `0xBC2A050E7B87610Bc29657e7e7901DdBA6f2D34E` | `bc1qujrqa3s34r5h0exgmmcuf8ejhyydm8wwja4fmq`   |
|  <img src="doc/images/eth-qr.png" >   | <img src="doc/images/btc-qr.png" > |

## Development

### Planning 

See our [Kanban](https://github.com/orgs/QuestNetwork/projects/1) for the development of 0.9.4, feel free to add or pick up features!

### Building

qDesk Social is a module of [qDesk](https://github.com/QuestNetwork/qDesk), so please see https://github.com/QuestNetwork/qDesk#development for instructions.

### Commands

**Prepare Package**

``npm run inst`` Removes `package-lock.json` and runs ``npm install``

We added an example ```swarm.json``` to the ```src/app``` folder with an example node to make reproduction easier, but we strongly recommend to use our [Quest CLI](https://github.com/QuestNetwork/quest-cli) to test and build the app.

Pro Tip: Put a file in your `/bin` that runs the quest-cli like so `node /path/to/quest-cli/index.js` from any folder on your system. It's much nicer!

## Features

**0.9.3**
- Public Profile
- Invite Only Profile
- Alias, Full Name, About

**0.9.4**
- Pair by QR Code
- Search For Social Profiles Received From All Connected Modules

## Roadmap

**0.9.4**
- Native Posts
- Share Private Profiles 
- Report Posts & Users
- Ban Users

**0.9.5**
- Native Followers
- Comments On Posts
- Connect To Twitter

**0.9.6**
- Use up To 5 Social Profiles Simultaneously 
- Change Profile Picture
- Change Poster


**0.9.9**
- Connect To Facebook/Instagram/Other Platforms
- Connect [Markets](https://github.com/QuestNetwork/qd-market-ts)

**1.0.0**
- Connect [Vibenarium](https://github.com/Vibenarium/vibenarium-platform)

## License
GNU Affero GPLv3
