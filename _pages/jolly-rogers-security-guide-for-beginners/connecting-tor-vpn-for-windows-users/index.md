---
layout: single
title: "VPN FOR WINDOWS USERs"
sidebar:
  - title: "Jolly Rogers Security Guide"
    nav: "jolly"
  - title: "DeepDotWeb"
    nav: "pages"
  - title: "Security Tutorials"
    nav: "security"
  - title: "Blog Archive"
    nav: "blognav"
permalink: "jolly-rogers-security-guide-for-beginners/connecting-tor-vpn-for-windows-users/"
redirect_from: "jolly-rogers-security-guide-for-beginners/connecting-tor-vpn-for-windows-users"
---


<p>After a long search, I have found a way you can connect TOR -&gt; VPN. It is not perfect, and some might not agree with doing things this way, but it works and I am giving it to you as an option, but it only works for Windows users at this time.</p>
<p style="text-align: center;"><a href="/vpn-comparison-chart/">&gt;&gt;&gt;Be sure to use a VPN with Tor. Click here to see the best VPN’s&lt;&lt;&lt;</a></p>
<p>If you look back at my previous posts regarding combining VPN and TOR then you will find the reasons why you would want to do so, and some of the reasons why you might not want to do it. But I was unable to provide you with a way to connect to a VPN using TOR so that the VPN does not know who you are. When it comes to TOR -&gt; VPN, if you cannot trust your VPN, which you rarely should, then keeping your identity anonymous from your VPN is a good idea. Also, with more and more people using TOR, but with only around 4000 TOR exit nodes, many of the exit node IP addresses are being flagged as spammers on popular websites and limiting the usage of well meaning TOR users to post on message boards like Stack Exchange and so forth.</p>
<p>The way that I found you can do TOR -&gt; VPN is by using a virtual machine, preferrably Virtual Box and running another instance of Windows, preferrably one that uses less memory than your current version. You also want to run TOR Expert and Tortilla on your host OS. I talk about how to do this in previous posts. Next set your Virtual Box to route all it&#8217;s network traffic through Tortilla (bridge adapter), which routes it all through TOR. Currently Tortilla is only supported by Windows, which is why this option is only available to Windows users at this time. Doing this also makes it easier to do things like watch videos on YouTube.</p>
<p>Now that you have your Windows Virtual Machine running on TOR, you can install a VPN of your choice, preferrably one using OpenVPN on your Windows Guest OS and connect to it. Check your IP address before connecting and after and you should see a different IP address. If all went well, you now have a virtual machine running TOR -&gt; VPN. Then if you want to add another layer, you can download TOR browser bundle onto your virtual machine and run that as well giving you TOR -&gt; VPN -&gt; TOR for another layer of security.  Also you have the option using this method to use a VPN on your host OS, then Tor Expert with Tortilla, then another VPN on your guest OS, then TOR browser, giving you VPN -&gt; TOR -&gt; VPN -&gt; TOR.</p>
<p>I am not advocating any whcih method, you need to make that decision on your own, I am just giving you the knowledge necesary to make an informed decison and you can ultimately choose which method you feel most comfortable with. Sometimes doing TOR -&gt; VPN is necessary because of the spam filter reasons I mentioned above and other times having TOR as your last node to the internet is necessary like when accessing the onion network. It is completely up to you and I know that we are trying to shy away from Windows usage because of all the exploits and other reasons spoken about in the previous posts, but if you have no other way of staying anonymous from your VPN than this, then I think it is a good compromise until we have something like Tortilla that is compatible with Linux distributions.</p>

Updated: 2014-02-12

