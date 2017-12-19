Questions for ICO Organizers
============================

Your idea is worth millions of dollars, and an ICO might provide you with a platform to 
raise them. But before you approach a solidity developer to realise your dream, you should
be prepared to ask yourself several questions, inorder to have an efficient and healty plan.
In many cases asking the right questions is a very important job, as it can reduce planning
time drastically and can help you proceed to the required solution. This document will help
you understand basic questions you must ask yourself before finalizing a crowdsale or a token
strategy. Their answers will shape the smart contracts and the way you’ll handle your investment
plan.

Crowdsaale Questions
--------------------

Your crowdsale would be handling people’s money, moreover it will be collecting money for
you. Therefore, you should plan properly before proceeding. We at Tokeny, are there to help
you through that:

* **When will your crowdsale begin?** This is among the most basic questions a crowdsa
* **What should be the duration of your crowdsale?**
* **Do you want the duration of your crowsale to be dependent on timestamp of a block or block number?** In ethereum blockchain the essence of a block is realized through (block timestamp is recommended)
* Do you want a presale, for special investors? If yes, answer the following: 
    * When will it begin?
    * What will be it’s duration?
    * What are the special conditions (bonus, minimum amount, etc.)
* Do you want your crowdsale to be divided into milestones? If yes, answer the following:
    * What determines a milestone (price intervals, bonus intervals)?
    * How many milestones do you need?
    * When will each milestone start?
    * What will be the duration of each milestone?
    * Will there be a cap for each milestone or an overall cap?
* Do you want your crowdsale token swap rate to be based on fiat currencies (USD/EUR) or ether (ETH)? We recommend ether because crowdsale ether to fiat exchange rates are subjected to change during the duration of a crowdsale.
* Do you want a Cap? If yes, answer these:
    * What should be your minimum ether/fiat cap?
    * What should be your maximum ether/fiat cap?
    * Do you want to accept multiple contributions from an investor or do you want a limit on number of investments from a single investor?
    * Do you want an individual min/max cap for each investor? If yes, how much? 
    * Do you need a fixed token supply (max token cap) or you want them to be created every time someone buys your tokens, until your ether/fiat cap is reached?  If latter is your choice, just decide the token swap rate considering the max ether/fiat cap and the duration of your crowdsale (also include, presale and milestone strategy, if any). Otherwise, answer the following:
        * What should be the total supply of your tokens? (Or max token cap)
        * What should be the swap rate of your tokens? Decide this on the basis of maximum ether/fiat cap and total supply of your tokens.
        * If required total supply is not reached during the crowdsale, i.e. some tokens are left even after crowdsale ends, what should happen to them? Should they be sent to some reserve or they’re to be distributed among crowdsale owners. Another strategy is Airdrop, where left over tokens will be distributed among token holders according to their fair share after crowdsale.
* What will be your refund policy if cap is not reached? Usually ethers are transferred to a vault contract for safe keeping until min/max cap is reached.
* Do you want token transfer and other basic ERC20 functions to be active during the crowdsale, else they should be inactive until the crowdsale is finished or some other time/block limit?
* Would new tokens be available to buy after crowdsale?
* Do you want a referral policy during your crowdsale? If yes, answer these:
    * What should be the percentage of tokens assigned for referrals.
    * How many referrals should be allowed for a single user?
* Do you want a pause feature for your crowdsale? (crowdsale owner will be able to stop investors from buying tokens)
* Do you want your crowdsale to be extendable? (You will be able to change start and end time of your crowdsale, advisable only without milestone strategy)
* Do you want your crowdsale to have a KYC logic implemented before your crowdsale begins or you want your contributors to complete their KYC before they can begin transferring their tokens? (Non KYC contributors won’t be able to participate in your crowdsale). How should it work?
* Do you need an owner assigned token mechanism for your crowdsale? (not advisable, promotes centralization, owner will be able to allocate tokens at will, But it can be useful in bug bounty programs, share distribution etc..)
* Any other special functionality for your crowdsale?
* What will be your initial share distribution scheme?
* How do you vision the ether to be handled after the crowdsale?
    * Straightaway transfer to a private account.
    * Handle using a multisig on the blockchain.
* Owner of the crowdsale should be single account or multisig? (multisig recommended)

Token Questions
---------------


