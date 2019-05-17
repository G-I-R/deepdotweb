---
layout: single
title: "COMBINING TOR WITH A VPn"
sidebar:
  nav: "jolly"
permalink: "jolly-rogers-security-guide-for-beginners/combining-tor-with-a-vpn/"
redirect_from: "jolly-rogers-security-guide-for-beginners/combining-tor-with-a-vpn"

---


<p>Welcome back readers!</p>
<p>Today I want to talk about a greatly debated topic.</p>
<p><strong>Should I use a VPN with TOR?</strong><br />
<strong>Should I use TOR to connect to a VPN, or use a VPN to connect to TOR?</strong></p>
<p style="text-align: center;"><a href="/vpn-comparison-chart/">&gt;&gt;&gt;Be sure to use a VPN with Tor. Click here for the best VPN’s&lt;&lt;&lt;</a></p>
<p>Let me say first of all, that when you are browsing the internet without TOR, you should probably be using a VPN regardless of whether or not you are using TOR. And make sure that the VPN uses some form of encryption as well. For those of you who are very beginner, think about when you connect to a public wifi network at a coffee shop, or an airport and you get all these warnings that your requests sent over this network are vulernable.</p>
<p>All networks, but especially public wifi networks are vulnerable to traffic analysis. Put this together with the fact that some internet service providers monitor your activity to some level, and you can see why it might be a good idea to always use an encrypted method of using the internet. At the very least to protect your personal information when you are entering credit cards, usernames and passwords, as well as other personal data online. Again, especially if you are using a public wifi network.</p>
<p>Choosing a VPN that uses at least 128 bit encryption like TOR is good practice, and will stop the majority of eavesdroppers. But if you can get 256 bit encryption, you are even safer. Before we get into whether or not we should be using a VPN together with TOR, I want to give you a few warnings regarding how you should be using a VPN.</p>
<p>If you are going to be using a VPN for any type of freedom fighting, make damn sure that your VPN does not keep logs. This is actually a lot harder than you might think. Many VPN providers will claim to not keep logs of your activity in order to gain you as a customer, because they have to compete with the other providers out there. Customers are going to trend towards providers who offer no identifying data retention. Unfortunately, this claim of theirs is not always the real case and I will give you an example.</p>
<p>There is a well known VPN provider named HideMyAss that previously claimed not to keep logs of its users. Unfortunately, when met with a court order from their government in the UK, they handed over evidence of a suspected hacker from an internet group LulzSec which helped lead to his arrest. The story can be found below.</p>
<p>http://www.theregister.co.uk/2011/09/26/hidemyass_lulzsec_controversy/</p>
<p>One of the take home quotes from this article is the following.</p>
<div>
<div>Quote</div>
</div>
<blockquote><p>We are not intimidated by the US government as some are claiming, we are simply complying with our countries legal system <strong>to avoid being potentially shut down and prosecuted ourselves.</strong></p></blockquote>
<p>A very smart man that goes by the online handle The Grugq, said when doing your freedom fighting online that nobody is going to go to jail for you, and he is 100% correct. When it comes down to it, no VPN provider is going to risk jail to protect a $20 a month subscriber. No matter how tough they sound, no matter how much they claim to care about protecting their customers, when faced with a choice to give you up or go to jail, they will always choose freedom.</p>
<p>Another thing to consider however, is using a VPN does hide your internet activity from your internet service provider. It can also hide the fact that you are using TOR, which may flag some suspicion when the feds start asking ISPs to provide data about their users. This may or may not be relevant, since many people use TOR and you can argue there are many legitimate reasons to use TOR and nothing suspicious about TOR. But it is just another factor to arouse suspicion that may or may not come into play and should be considered.</p>
<p>If you choose to use TOR over a VPN, the benefits are that you would be again, hiding from your ISP the fact that you are using TOR. Also, your VPN would only be able to see that you are connecting to TOR nodes and that you are sending encrypted data. The VPN would not be able to see what data you are sending over TOR unless they decrypted it, because remember, all information relayed over TOR is encrypted.</p>
<p>The downsides of course, as mentioned are that VPN providers may or may not log everything that you do in the form of meta data or even content if they have the storage capacity, and keep those logs on hand for a long time. In this case, it is no better than connecting to TOR through an ISP. Another thing to mention to those who will use VPNs when not using TOR, but also use VPNs when using TOR is remember when you are, and are not connected to your VPN. Sometimes VPNs can unexpectedly drop connections and you may not even be aware of it. If the reason you are using a VPN is to hide TOR activity from your ISP, then if your VPN drops, your ISP will start seeing your TOR traffic instead.</p>
<p>Or, maybe you forget that you are connected to your VPN and end up punching in your address on Google Maps to find directions somewhere. Well guess what Google does with all data entered into their system? They keep it. And they likely keep it indefinitely. So if one day the NSA identifies you on the TOR network by occupying a large number of nodes and using traffic analysis to identify you based on statistical analysis, it will link them to your VPN IP address.</p>
<p>At this point, they will likely ask the VPN to turn over data on their users, but if the VPN refuses to comply because they are not subject to US law, or the laws of other countries, they may check some of the big surveillance websites out there to see if you slipped up and used that IP address for anything else online. They will check logs from Google, Yahoo, Facebook, Twitter, Netflix and other big data collection companies to see who has been using that IP address to connect to their servers.</p>
<p>If you accidentally punched in your address on Google when connected to that VPN, you are now a suspect. So always keep things like this in mind. Just because you are covered behind a VPN does not mean you are not traceable by human error. The benefits of TOR, are that you get a new identity every time you connect. This may or may not be the case with your VPN, so please check and make sure.</p>
<p>Next post we will talk about the advantages and disadvantages of using TOR to connect to a VPN.</p>

Updated: 2014-02-12

