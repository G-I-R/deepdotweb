---
title: "Shadowcash Hits Zero-Knowledge Jackpot with Casino-style Anonymity"
---


Posted by: DeepDotWeb 

<span>January 28, 2015</span>


<p>A few months ago we cataloged a preview of Shadow’s recently released <a href="/2014/10/24/anonymous-shadow-eclipses-privacy-projects-zero-knowledge/" target="_blank">zero knowledge update</a> as well as alternative privacy technologies. However, before we go into the nuts and bolts of what makes Shadow’s new financial privacy update so impressive, let’s take a trip to the casino and see how the process emulates a very common and legal method of changing money.</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/01/fear.jpg">

<p>Imagine walking through the doors of your local casino. You’re met with the melodic ambient noise of jackpots and cheers orchestrating a collection of wins and losses. The notes of this orchestra literally lose their link with one another.</p>
<p>For example, a $100 bill can be exchanged into chips of equal value, which is as good as cash anywhere in the casino: tips, tables, vendors, gift stores—anywhere, except the machines. Likewise, bills inserted into a slot machine can be cashed out into printable tickets, worth the fiat amount printed on them. At any time, you may redeem those chips or slot tickets at a casino cashier and you will be presented with a new set of bills; ones not linked to the bills that were initially converted into chips or tickets. As a result you leave the casino with a fresh set of bills and hopefully more than you started out with!</p>
<p>The latest update from the team at Shadowcash takes this age-old process and renders it into a harmonious cryptographic orchestra with the maestro, ShadowSend, conducting a unique symphony of dual-key stealth addresses, anonymous tokens, ring signatures and non-interactive zero knowledge proofs (NIZKPs). The resulting melody is untraceable and unlinkable transactions that are trustless—Meaning they require no centralized servers, 3<sup>rd</sup> parties or master nodes to facilitate anonymity. Shadow’s technical whitepaper goes over the process in detail and is available <a href="http://shadow.cash/downloads/shadowcash-anon.pdf" target="_blank">here</a>.</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/01/shadowsend2.jpg">

<p>However, to better visualize the process, we’ll stick with the casino analogy and assign values relevant to the protocol:</p>
<p>A node (player) gives the network (casino) their SDC (cash), which the network accepts and issues the node Shadow tokens (chips) in denominations of 1, 3, 4 and 5 equal in value to the SDC received. For example, 1.7 SDC would be split into smaller tokenized Shadow values of 1.0, 0.3 and 0.4. To provide unlinkability, these anonymous outputs (Shadow) can only be sent to and from a node’s stealth address. To provide untraceability, the network validates the transaction with a ring signature, which signs the transaction on behalf of multiple players in the network, instead of the individual.</p>
<p>Now, this is where the ShadowSend flow differs from the casino model and furthermore what makes it such an improvement over coin mixing services like Coinjoin, DarkSend or Helix.</p>
<p>Instead of issuing bills or coins from a mixture pool, the Shadow network achieves zero knowledge anonymity by destroying the original coin (SDC) and issuing Shadow tokens of equal value—minus the network fee. Vice versa, when redeeming Shadow for SDC, the network mints new SDC equal in value to the Shadow tokens—minus the network fee. This fee is then sent to the nodes for securing the network; nodes earn approximately 2% per annum on their coins.</p>
<p>The result is that there is no connection between the destroyed and newly minted SDC or the Shadow used during the process. Meanwhile, the tokenized denominations of Shadow remain in the system for available anonymous outputs.</p>
<p>So just like a casino chip redemption, the casino takes ownership of the chips (Shadow) in question and issues the respective amount back to the player in cash (SDC). The chips are then put back into the system increasing the overall amount of chips available for other players.</p>
<p>The network prevents ‘double spending’ by requiring proof of ownership via a ‘traceable ring signature’ for redeeming anonymous outputs (Shadow). Proving ownership of a traceable ring signature requires a user to prove ownership of the Shadow or ‘Proof-of-Shadow’ to the network. Thus, if a user owns the stealth address the Shadow resides on; then they may redeem Shadow for SDC. If a user doesn’t own the stealth address the Shadow resides on; there is nothing to redeem. Since Shadow can only be assigned to stealth addresses by destroying SDC, it makes the Shadow unforgeable.</p>
<p>Going back to the casino analogy—when a player redeems chips or slot tickets at a cashier; all the casino needs to verify is if the chips or tickets are valid. Possession of a ticket or chip is enough for the casino to validate the ownership; without possession the casino has nothing to validate and thus nothing to redeem.</p>
<p>A full slideshow presentation can be found here:</p>
<div align="center"><iframe width="515px" height="470px" style="border: none;" src="http://www.slideshare.net/shadowcash/slideshelf" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" allowfullscreen="allowfullscreen" webkitallowfullscreen="webkitallowfullscreen" mozallowfullscreen="mozallowfullscreen"></iframe></div>
<p><strong>Pros</strong></p>
<p>The concept blends strengths from the Zerocoin and Zerocash protocols by enabling the Shadow network to destroy and mint new coins (SDC), as well as create anonymous outputs (Shadow), through the use of zero knowledge proofs; without the Zero project’s weakness of requiring a trusted setup. Another plus is that Shadowcash doesn’t require an equal input or output like the Zero protocols; making it much more efficient and flexible. It also retains the integrity of Satoshi’s core principals of trustless transactions, double-spend prevention, decentralization with distributed consensus.</p>
<p>At the same time it removes the misplaced conception of mixing ‘clean’ and ‘dirty’ coins by simply removing the link between the ‘dirty’ coinbase by minting new ‘clean’ coin. As a result, it also removes the need to trust any mixing services, as the protocol, ShadowSend, is native to the Shadow network. The new Shadowcash protocol has been live for about a month and with widespread adoption it could spell the end for Bitcoin mixing services as we know it.</p>
<p><strong>Cons</strong></p>
<p>One possible weakness could be timing and redemption analysis. Although, there would be no way to directly link transactions, if a user redeems Shadow for SDC shortly after being sent SDC for Shadow in the same amount, then a blockchain analyst could assume the transactions are linked, but wouldn’t be able to prove it. This would be time consuming, as the investigator would also have to search every transaction in order to do this. If the redeemer used multiple Shadow-to-SDC stealth addresses for redemption, then the analyst’s efforts would prove futile. Another way to solve this would be to redeem amounts in separate values, at separate times and to separate SDC stealth addresses, instead of redeeming the original amount sent. This is still a massive privacy improvement over Bitcoin’s linkability and traceability.</p>
<p>Outside of that, the system is still new and hasn’t received any high-level peer review. However, it is based on proven technology: Satoshi’s Bitcoin codebase, dual-key stealth addresses, traceable ring signatures and non-interactive zero knowledge proofs. Developers from other projects have praised the system’s design, but as of the time of this writing there hasn’t been comments made by any fancy pants cryptographers.</p>
<p><strong>Future Updates:</strong></p>
<p>Shadow is also working on a decentralized marketplace, codenamed ‘sBay’, built on top of their encrypted messaging system, <a href="http://www.shadow.cash/downloads/shadowcoin-p2p-em.pdf">ShadowChat</a>, with Shadowcash as the primary currency. Not much is known at this point regarding the marketplace specs, but according to the roadmap, it’s due out soon for open beta. Also, according to the Shadow website, “the marketplace will provide cash liquidity in <a href="https://localbitcoins.com/?ch=4v6y" target="_blank">localbitcoins</a> fashion, will enable users to buy and sell items anonymously and will provide end-to-end decentralized stability.”</p>
<p>A decentralized <a href="https://localbitcoins.com/?ch=4v6y" target="_blank">localbitcoins</a> concept could help preserve the idea of trustless decentralization by removing the clearing house mechanism associated with fiat transfers.</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/01/marketplace.jpg">

<p>Despite not being widely publicized, the creator of Darkcoin, Evan Duffield, one the leading altcoin projects and marketcap leader for privacy coins, attempted to <a href="http://shadowtalk.org/topic/252/darkcoin-proposal-statement/2" target="_blank">acquire Shadow</a>, which speaks volumes for the project’s future.</p>
<p>Shadow’s unique combination of proven technology will undoubtedly change the definition of financial privacy, but only after the system has made it’s way through the gauntlet of security experts. The code is open source, so anyone qualified is able to review the whitepaper and audit the code. German systems security expert and cryptographer Isidor Zeuner has taken up the task to analyze the system for a thorough peer review. The results of his findings will be posted on <a href="http://www.shadowtalk.org" target="_blank">www.shadowtalk.org</a> in the near future.</p>
<p>In a time where government crackdowns of hidden services are increasing and trust in market operators is decreasing—trustless anonymity couldn’t come at a better time. Vendors should be demanding market operators implement state-of-the-art open source technologies that use standard cryptographic primitives to provide transactional peace of mind. Market operators should focus on implementing greater security measures by providing users access to the best financial privacy toolset available and right now that toolset is Shadow.</p>
<p>For additional information visit <a href="http://www.shadow.cash">www.shadow.cash</a></p>
<p>Forums: <a href="http://www.shadowtalk.org" target="_blank">www.shadowtalk.org</a></p>
<p>Source Code: <a href="https://github.com/SDCDev/shadowcoin/" target="_blank">https://github.com/SDCDev/shadowcoin/</a></p>
<p>Freenode IRC: #shadowcash</p>
<p><strong>Exchanges:</strong></p>
<p>Bittrex: <a href="https://bittrex.com/Market/Index?MarketName=BTC-SDC" target="_blank">https://bittrex.com/Market/<wbr />Index?MarketName=BTC-SDC</a></p>
<p>Poloniex: <a href="https://poloniex.com/exchange#btc_sdc" target="_blank">https://poloniex.com/exchange#<wbr />btc_sdc</a></p>
<p>Cryptsy: <a href="https://www.cryptsy.com/markets/view/306" target="_blank">https://www.cryptsy.com/<wbr />markets/view/306</a></p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/01/shadowops.jpg">

<p>&nbsp;</p>

Updated: 2015-01-28

