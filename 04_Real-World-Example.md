# A Real-World Example:
Now that you have seen how to use Whirlpool, it may be helpful to understand the implications of a fully transparant transaction ledger in the face of an ever increasing adversarial environment. This section will provide that background with a real-world example and an explaination of how bitcoin transactions are scrutinized in such a scenario using a real example.

## Timeline
Here is a time line of the recent Canadian Freedom Convoy with notable events as they relate to Bitcoin.

- January 28, 2022: Truckers start arriving in Ottawa, ON
- February 1, 2022: [@HonkHonkHodl](https://twitter.com/HonkHonkHodl) receives first bitcoin donation via [@tallycoinapp](https://twitter.com/tallycoinapp). ([Link to tweet](https://twitter.com/HonkHonkHodl/status/1488625113406717952?s=20&t=3OffQxFJg4Y0qIy9vi_RAg)). Not many people were using Bitcoin to donate to the Freedom Convoy, many more donations were being made with traditional crowd funding platforms. This would soon change.

<p align="center">
 <img src="assets/timeline00.png">
</p>

- February 5, 2022: [GoFundMe announced](https://twitter.com/gofundme/status/1489870510057877505?s=20&t=yIaTuK2kbAmCC1CL6FTaQw) that all donations to the Freedom Convoy would be refunded to the donors, banning any further involvement between the crowd funding platform and the Freedom Convoy. This was essentially an advertisement for unstoppable money like Bitcoin. Donations to the [@HonkHonkHodl](https://twitter.com/HonkHonkHodl) fundraising campaign through [@tallycoinapp](https://twitter.com/tallycoinapp) started to ramp up.

<p align="center">
 <img src="assets/timeline01.png">
</p>
  
- February 7, 2022: Under an [order](https://www.cbc.ca/news/canada/toronto/freedom-convoy-2022-donations-frozen-give-send-go-1.6347345) issued by the Ontario Superior Court of Justice, another crowd funding platform, [@GiveSendGo](https://twitter.com/GiveSendGo) was compelled to freeze access to millions of dollars donated to the Freedom Convoy. [Official statement](https://givesendgo.com/site/pressrelease). This further escalated fundraising via Bitcoin through the [@HonkHonkHodl](https://twitter.com/HonkHonkHodl) fundraising campaign. 

- February 11, 2022: Ontario [declares](https://www.cbc.ca/news/canada/toronto/ford-announcement-ontario-protests-1.6347810) state of emergency. This declaration explicitly made it "illegal and punishable to block and impede the movement of goods, people and services along critical infrastructure". Further clarifying that "Fines for non-compliance will be severe, with a maximum penalty of $100,000 and up to a year imprisonment. We will also provide additional authority to consider taking away the personal and commercial licences of anyone who doesn't comply with these orders".

- February 14, 2022: Canadian Prime Minister, Justin Trudeau [invoked](https://www.cbc.ca/news/politics/trudeau-premiers-cabinet-1.6350734) the Emergencies Act. Among expanding the powers and reach of the Canadian government beyond that which may not be appropriate in normal times, the Emergencies Act had two specific and sweeping financial implications. First, this would capture crowd funding platforms and payment service providers under the Proceeds of Crime and Terrorist Financing Act. Second, crowd funding platforms and the payment service providers they use had to register with and report large and/or suspicious transactions to the Financial Transactions and Reports Analysis Centre of Canada (FINTRAC), the national financial intelligence agency.

- February 14, 2022: The same day the Canadian government invoked the Emergencies Act, [@HonkHonkHodl](https://twitter.com/HonkHonkHodl) closed out the fundraising campaign on [@tallycoinapp](https://twitter.com/tallycoinapp), having exceeded their original goal, reaching nearly 21 bitcoin in total donation. 

<p align="center">
 <img src="assets/timeline02.png">
</p>

- February 15, 2022: The Ontario Superior Court of Justice inacted the [Mareva Injunction](https://ottawaconvoyclassaction.ca/order-mareva.pdf), a $306,000,000 class action law suit. This injunction named 17 individuals, 2 organizations, and 62 anonymous entities as defendants further stipulating that "Any other person who knows of this order and does anything which helps or permits the Defendant to breach the terms of this Order may also be held to be in contempt of court and may be fined or imprisoned". Essentially, anyone who did so much as [serve coffee](https://twitter.com/Ranting4Canada/status/1495471835420450816?s=20&t=h49vUtxlCn-6s__PI9vfXg) to a Freedom Convoy suspect would face fines and imprisonment. This injuction goes as far as to include several Bitcoin addresses, so if one of these ends up in connection with your identity then you would be in violation of this injuction.   

- February 16, 2022: [News broke](https://twitter.com/nobsbitcoin/status/1493978391099457536?s=20&t=3OffQxFJg4Y0qIy9vi_RAg) that the Royal Canadian Mounted Police (RCMP) publish a blacklist of cryptocurrency addresses related to the Freedom Convoy donations. Essentially, this meant that any funds connected to any of these addresses hitting a bitcoin-to-fiat off ramp would trigger seizure and immediate reporting to authorities based on the emergency measures put in place just days prior. 

## Summary
Essentially what transpired in the timeline above is that in less than two weeks the Canadian government managed to turn a swath of the population into criminals and then there was nothing stopping the government from disregarding the rights of this massive group of people. This is what I refer to as the "pendulum swinging". One day you are leading a perfectly normal and legal life, the next you are a criminal and face severe consequences for doing what was once inconsequential. If you value being able to communicate with your friends and family, the freedom of movement, and being able to access financial services or spend your money on the things you choose then it would benefit you to start taking small incremental steps to guard these freedoms. There are many resources available to those who want to learn more about the tools available to you in this fight. 

- [Bitcoiner.Guide](https://bitcoiner.guide/)
- [Diverter.HostYourOwn.Tools](https://diverter.hostyourown.tools/)
- [K3tan.com](https://www.k3tan.com/)
- [x21.tools](https://x21.tools/)

## Follow the money
This section will follow the flow of a donation on the Bitcoin blockchain to the Freedom Convoy Bitcoin address. Then beyond to the disbursed payements to the truckers. At points along this path, it will be pointed out where Whirlpool could have been used and how it would have helped prevent the targeting of specific individuals who allowed their identity to be linked with their on-chain activity. The Transaction ID's (txid), Bitcoin Addresses, and dates have been obfuscated but these are actual transactions surrounding the [@HonkHonkHodl](https://twitter.com/HonkHonkHodl) donations. 

This demonstration follows the transactions of an entity named Alice. Alice has about 28 bitcoin in her wallet, in a single Unspent Transaction Output (UTXO). One day, Alice decides to use the UTXO to make a 0.3 BTC deposit to her CoinBase account. In that transaction, the 28 BTC is used as the only input and there are two outputs. The first output is the 0.3 BTC to her CoinBase account. The second output is her remaining 28 BTC. 

As time goes on, Alice makes three more transactions with this 28 BTC. Each time providing the 28 BTC as an input with a small amount being spent and the remainder being returned to her as change. On the fourth transaction, Alice made a donation to the Freedom Convoy. 

![](assets/tx00.png)

Each time Alice made a transaction, the 28 BTC UTXO was used as an input and a little bit was spent, returning the bulk of that 28 BTC to Alice as the change. Then that change was spent as an input to the next transaction with a little bit peeled off as the spend and the remainder returned to Alice again. Because of this peel chain pattern of simple transactions, the 0.3 BTC spend to CoinBase in the first transaction means that CoinBase is aware of Alice's true identity and that she also owns the 28 BTC that she continued spending down stream. CoinBase can also see every transaction related to that bitcoin. 

By the time Alice made a donation to the Freedom Convoy, she used what was left of that original 28 BTC. In the donation transaction, Alice provided a 24.07 BTC input. The transaction had two outputs, a 0.25 BTC donation to the known Freedom Convoy Bitcoin donation address hosted on the Tally Coin website. The other output was 23.82 BTC being returned to Alice as change. 

Because CoinBase knows Alice's true identity and her on-chain activity is directly linked to her CoinBase account, her true identity can be revealed as a donor to the Freedom Convoy if authorities investigate the matter. After Alice made her donation, more bitcoin was consolidated and moved down stream. 

![](assets/tx01.png)

The entity in control of the Freedom Convoy donations makes several transactions that consolidate bitcoin and move the new balances to new addresses. Throughout the entirety of the Tally Coin fundraising campaign, the same Bitcoin donation address was used. 

<p align="center">
 <img src="assets/tx02.png">
</p> 

In order to disburse donations to Freedom Convoy truckers, the entity in control of the bitcoin established 101 different wallets for the truckers. They made 3 deposits to each wallet. Unfortunately, they used the same address in each wallet for each of the deposits. This graph shows many donations being made to the known Tally Coin Bitcoin donation address. Then those donations are consolidated and moved to new addresses in three transactions leading up to the transaction where the bitcoin was dibursed to 100 wallets in what seems to be a test transaction. Each deposit was only 4,800 sats. 

![](assets/tx03.png)

A few blocks later another deposit was made to the 100 wallets for the truckers. This transaction was funded by a 14.67 BTC consolidation of the Freedom Convoy donations. There were 100 equal sized outputs of 0.004 BTC, each going to the same address as the 4,800 sat deposit in each of the 100 wallets. There was a 14.27 BTC output from this transaction as well. 

![](assets/tx04.png)

The 14.27 BTC output was used a few blocks later as an input to the third trucker wallet deposit. This transaction deposited 100 equal sized outputs of 0.14 BTC, each going to the same address as the 4,800 sat deposit and the 0.004 BTC deposit in each of the 100 wallets. 

![](assets/tx05.png)

The majority of the trucker deposits have remained unspent. The ones that have been spent have gone to KYC exchanges like CoinBase, Ctypto.com, & Kraken. 

![](assets/tx06.png)

Unfortunately, the Canadian government has blacklisted several if not all of these addresses, ready to impose strict penalties on anyone who is associated with these donations. For the trucker who sent their deposit to CoinBase, this means that they will be identified as a guilty party. The exchanges will seize and report any activity on their platforms related to any of these donations. For Alice, it is now possible to directly tie her identity to some of the donated bitcoin because of her deposit to her CoinBase account several transactions prior to the donation. This means that Alice will be reported and possibly face penalties in relation to supporting the Freedom Convoy. 

![](assets/tx07_1.png)

## How Whirlpool fixes this
