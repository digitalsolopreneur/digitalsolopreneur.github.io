# digitalsolopreneur.github.io

Digitalsolopreneur Ltd. Website

* [![Stories in Ready](https://badge.waffle.io/digitalsolopreneur/digitalsolopreneur.github.io.png?label=ready&title=Ready)](https://waffle.io/digitalsolopreneur/digitalsolopreneur.github.io)
* [![Join the chat at https://gitter.im/digitalsolopreneur/digitalsolopreneur.github.io](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/digitalsolopreneur/digitalsolopreneur.github.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


# Bank Accounts Comparison

<!-- API Documentation -->
[1]:https://api-docs.transferwise.com/v1/use-cases
[4]:https://bank.mistertango.com/api_v1_doc#/
[7]:https://apisandbox.mycashplus.co.uk/swagger/ui/index#!/Root_Infrastructure
[12]:https://tideapi.github.io/docs/
[19]:https://developer.starlingbank.com/
[20]:https://fire.com/docs/#authentication

<!-- GitHub -->
[2]:https://github.com/transferwise

<!-- Twitter -->
[13]:https://twitter.com/transferwise
[15]:https://twitter.com/tidebanking
[16]:https://twitter.com/mistertangolt
[18]:https://twitter.com/cashplus
[12]:https://twitter.com/RevolutApp
[14]:https://twitter.com/StarlingBank
[17]:https://twitter.com/PaywithFire

<!-- Detailed Pricing -->
[9]:https://mistertango.com/en/wp-content/uploads/Mistertango-pricelist.pdf
[3]:#cashplus
[5]:#revolut
[6]:#starling
[8]:#fire.com
[10]:#tide
[11]:#transferwise

|                 |[TransferWise][11]| [Tide][10]  |[MisterTango][9]|[CashPlus][3]| [Revolut][5]|[Starling][6]|[fire.com][8]|
|-----------------|------------------|-------------|----------------|-------------|-------------|-------------|-------------|
|main currency    |    GBP           | GBP         |    EUR         |  GBP        | GBP         |  GBP        |  GBP/EUR    |
|for UK Ltd.      |    YES           | YES         |    YES         |  YES        | YES         |  ------     |  YES        |
| APP             |  iOS/android     | iOS/android | iOS/android    | iOS/android | iOS/android | iOS/android | iOS/android |
| - needs SIM     |    ?             | ?           |    ?           |  ?          | YES         |  ?          |  ?          |
| API             |    [D](1)        | [D](12)     |    [D](4)      |  [D](7)     | ------      |  [D](19)    |  [D](20)    |
| GitHub          |    [G](2)        | ------      |    ------      |  ------     | ------      |  ------     |  ------     |
| twitter         |    [@](13)       | [@](15)     |    [@][16]     |  [@](18)    | [@](12)     |  [@](14)    |  [@](17)    |
|CreditCard       |    YES           | YES         |    YES         |  YES        | YES         |  YES        |  YES        | chip + pin + magnet stripe
| setup           |    0,00          | 0,00        |    0,00        |  ?          | ?           |  ?          |  100+40     |
|subscribe        |    0,00          | 0,00        |    2,00        |  YES: x/12  | ?           |  0,00       |  0,00       |
|FX rate          |    (1)           | ?           |    ------      |  ?          | (2)         |  (1)        |  1,25%      | (1)midMarket (2)interbankRate 
|FX margin        | 0,5-2% (min 2,-) | ?           |    ------      |  2,85%      | 0,00        |  X          |  ?          |
|googleRate       |    YES           | ------      |    ------      |  ------     | ?           |  ?          |  ?          |
|reutersRate      |    YES           | ------      |    ------      |  ------     | ?           |  ?          |  ?          |
|TX in  SWIFT     |    0,00          | ?           |  - & 10,- fine |  15,00      | ?           |  ?          | min(1%,0.49)| WORLDWIDE
|TX in  BACS      |    0,00          | ?           |    1,5%        |  0,00       | ?           |  0,00       | min(1%,0.49)| UK FastPayments/BACS/CHAPS
|TX in  SEPA      |    0,00          | ?           |    ?           |  15,00      | ?           |  ?          | min(1%,0.49)| EU
|TXoutSWIFT <4tx/m|    0,00          | 0,20        |   0,5% + 50,-  |  0,00       | 0,00        |  ?          |.49+max.05,1%|
|TXoutSWIFT >3tx/m|    0,00          | 0,20        |   0,5% + 50,-  |  0,99       | 0,00        |  ?          |.49+max.05,1%|
|TX out BACS (<5k)|    1,00          | 0,20        |    ------      |  ?          | 0,00        |  ?          |.49+max.05,1%| UK FastPayments/BACS/CHAPS
|TX out BACS (>5k)|    1,00          | 0,20        |    ------      |  ?          | 0,5%        |  ?          |.49+max.05,1%| UK FastPayments/BACS/CHAPS
|TX out SEPA      |    1,00          | 0,20        |    0,15        |  ?          | 0,00        |  ?          |.49+max.05,1%|
| AER on debt     |    ?             | ?           |    ?           |  ?          | ?           |  ?          |  ?          |
|AER on funds(<2k)|    ?             | ?           |    ?           |  ?          | ?           |  0,5%       |  ?          |
|AER on funds(>2k)|    ?             | ?           |    ?           |  ?          | ?           |  0,25%      |  ?          |
|shopping offline |    ?             | ?           |    2%          |  ------     | 0,00        |0,00 FP,DD,SO|  0,40       | use card
| | | |                              .... DirectDebit,StandingOrders ...                                                  | |
|shopping online  |    ?             | ?           |    2%          |  ------     | 0,00        |  0,00       |  0,40       | use card
|ATM out (<200/m) |    0,50          | 1,00        |    0,00        |  ?          | 0,00        |  0,00       |2+1%!EUR/!GBP|
|ATM out (>200/m) |    0,50          | 1,00        |    max(2%,3)   |  ?          | ?           |  ?          |2+1%!EUR/!GBP|
|ATM out (<300/m) |    0,50          | 1,00        |    max(2%,3)   |  ?          | ?           | 0,00 max:6tx|2+1%!EUR/!GBP|
|ATM in  (<49/m)  |    ?             | ?           |    ------      | 0,00        | 0,00        |  0,00       |  1%         |
|ATM in  (<400/m) |    ?             | ?           |    ------      | 0,00        | 0,00        |  0,00       |  0,49       |
|ATM in  (>400/m) |    ?             | ?           |    ------      | 0,00        | ?           |  0,00       |  ?          |
|ATM in  (<1000/m)|    ?             | ?           |    ------      | 0,00        | ?           |  0,00       |  ?          |
|ATM in  (>1000/m)|    ?             | ?           |    ------      |0,25%max20inP| ?           |  0,00       |  ?          |
|chargeback       |    ?             | ?           |0,70 / 25(fraud)|  ?          | ?           |  ?          |  ?          |
|FSCS             |  ------          | ------      |  ------        |------       | ------      | YES         | ------      |
|BitCoin TX       |  ------          | ------      |    0,50        |------       | ?           |  ?          |  ?          |
|countries        |    50+           | UK          |    EU          |  1          | 26+         |  ?          |  ?          |
|currencies       |    50+           | 1           |    1           |  1          | ?           |  ?          |  ?          |
|Acount+Sort CHAPS|   YES            | ------      |  ------        | YES         | ?           |  ?          |  ?          | GBP (AccountNumber+SortCode)
|IBAN             |   YES            | ------      |   YES          |------       | ?           |  ?          |  YES        | EUR (SWIFT/BIC+IBAN)
|ABA              |   YES            | ------      |  ------        |------       | ?           |  ?          |  ?          | USD (Routing/ABA+AccountNumber)
|BSB              |   YES            | ------      |  ------        |------       | ?           |  ?          |  ?          | AUD (BSBcode+AccountNumber)
