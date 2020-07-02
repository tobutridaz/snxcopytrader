# Synthetix Mirror trader

## Description:
Synthetix Mirror trader will provide the functionality of a watching executed-on-chain trades for a selected wallet address, and mirroring them according to the proportion between the copied investor's account and the copying trader's allotted copy trading funds.

## Motivation: 
Mirror trading functionality is the initial MVP functionality to a latter copy trading functionality, where copied traders will benefit through a to be defined fee model. Unlike with mirro trading, copy trading will  have the ability to disconnect a trader / copy trader relationship. 
Reference: [Wiki](https://en.wikipedia.org/wiki/Copy_trading)

## Additional information: 
### Solution:
On a high level, 3 different latyers will be required.
**Mirror trading contract**. This contract acts as an intermediary between the mirror trader and the trade execution node. 

**Trade execution node** This will allow an independent node operator to execute the trade function in the mirror trading contract when trade conditions are met. The node by default will watch for exdecuted trade transactions of the mirrored trader.

**Javascript Mirror trader Library** To provide developer tooling for both the official and unofficial Synthetix exchanges interfaces, we will either provide a separate Javascript library for Synthetix mirror orders. A frontend JS GUI will be built for the use by the mirror traders.

## Previous work: 
None

## Estimated hours: 
- 25 hours for research and spec
- 50 hours Mirror trading contract 
- 50 hours Trade execution node
- 50 hours Javascript library and GUI
- 25 hours Project management

Total: 175 hours

## Price (EUR): 
- 2500 EUR PM & research at 50EUR / hour (voided as investrment)
- 1050 EUR Development  at 7EUR / hour (junior)

Total investment costs: 1050 EUR
