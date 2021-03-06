---
title: "Major Windows Security Flaw Leaks VPN Users Real IP Address"
---


Posted by: DeepDotWeb 

<span>February 1, 2015</span>



<p><em><strong>To the author of this article</strong>:  We are mailing to your mail2tor.com mail, and don&#8217;t think you are getting those mails, please contact us from another address.</em></p>
<p>Just a few days after learning that the Canadian Government is tracking visitors of popular file-sharing sites security researchers have discovered a major security flaw that reveals Windows VPN users real IP address through WebRTC. Linux and Mac OS X users are not affected by this vulnerability as it is specific to Windows users running Google Chrome and Firefox.</p>
<p>With a few lines of code websites can make requests to <a href="http://en.wikipedia.org/wiki/STUN">STUN servers</a> and log users’ VPN IP address and their true IP address, as well as local network addresses.</p>
<p>A demo published on GitHub by developer Daniel Roesler allows people to <a href="https://diafygi.github.io/webrtc-ips/">check if they are affected</a> by the security flaw.</p>
<p>The demo claims that browser plugins can’t block the vulnerability, but luckily this isn’t entirely true. There are several easy fixes available to patch the security hole.</p>
<p><strong>Chrome</strong> users can install the <a href="https://chrome.google.com/webstore/detail/webrtc-block/nphkkbaidamjmhfanlpblblcadhfbkdm?hl=en">WebRTC block</a> extension or <a href="https://chrome.google.com/webstore/detail/scriptsafe/oiigbmnaadbkfbmpbfijlflahbdbdgdf?hl=en">ScriptSafe</a>, which both reportedly block the vulnerability.</p>
<p><strong>Firefox</strong> users should be able to block the request with the <a href="https://addons.mozilla.org/de/firefox/addon/noscript/">NoScript addon</a>. Alternatively, they can type “about:config” in the address bar and set the “media.peerconnection.enabled” setting to false. The Tor Browser Bundle includes the NoScript addon with Firefox but Windows users will want to verify that NoScript is configured properly.</p>
<p>While developments like this can appear frightening, the good news is there is a simple fix. <strong>The real problem here however is not the fix, but rather the fact that many users will go about their day to day activities without knowledge of this flaw.</strong> It is important to be aware of current security issues and ensure that the latest software updates or fixes are applied to remain anonymous and maintain our privacy and security.</p>
<p>More information on what this does is available from the researcher’s <a href="https://github.com/diafygi/webrtc-ips" target="_blank">github page</a>:</p>
<p><strong><em>“</em></strong><em>Firefox and Chrome have implemented WebRTC that allow requests to STUN servers be made that will return the local and public IP addresses for the user. These request results are available to javascript, so you can now obtain a users local and public IP addresses in javascript. This demo is an example implementation of that.</em></p>
<p><em>Additionally, these STUN requests are made outside of the normal XMLHttpRequest procedure, so they are not visible in the developer console or able to be blocked by plugins such as AdBlockPlus or Ghostery. This makes these types of requests available for online tracking if an advertiser sets up a STUN server with a wildcard domain.”</em></p>
<p><em>Two of the top anonymous VPN service providers TorVPN and Private Internet Access addressed the vulnerability on their blogs and forums suggesting that their users </em><em><span style="color: #222222;"><span style="font-family: Arial;"><span style="font-size: medium;"><span style="background: #ffffff;">test for DNS, email, and IPv6 IP address leaks when setting up their service. [See testing resource links below]</span></span></span></span></em></p>
<p class="western"><strong>How to fix the WebRTC Security Hole</strong></p>
<p>In Chrome browser there is now a free extension available that will patch this problem directly. You can install this add-on from the Chrome Store <a href="https://chrome.google.com/webstore/detail/webrtc-block/nphkkbaidamjmhfanlpblblcadhfbkdm?hl=en" target="_blank">here</a>.</p>
<p>In Firefox, there are a few more steps to patch the problem. First, type “about:config” directly into the URL bar and hit enter. Then search for “media.peerconnection.enabled” and double click this option to set it to false.</p>
<p style="margin-bottom: 0in;"><b>Testing Resources:</b></p>
<p style="margin-bottom: 0in;"><span style="font-family: Arial,Verdana;"><span style="font-size: medium;">DNSLeak: </span></span><a href="http://dnsleak.com/"><span style="font-family: Arial,Verdana;"><span style="font-size: medium;">http://dnsleak.com/</span></span></a></p>
<p style="margin-bottom: 0in;"><span style="font-family: Arial,Verdana;"><span style="font-size: medium;">IPLeak: </span></span><a href="http://ipleak.net/"><span style="font-family: Arial,Verdana;"><span style="font-size: medium;">http://ipleak.net/</span></span></a></p>
<p style="margin-bottom: 0in;"><span style="font-family: Arial,Verdana;"><span style="font-size: medium;">IPv6 Leak:</span></span><a href="http://ipv6leak.com/" target="_blank"><span style="font-family: Arial,Verdana;"><span style="font-size: medium;">http://ipv6leak.com/</span></span></a></p>
<p style="margin-bottom: 0in;"><span style="font-family: Arial,Verdana;"><span style="font-size: medium;">E-Mail IP Leak: </span></span><a href="http://emailipleak.com/" target="_blank"><span style="font-family: Arial,Verdana;"><span style="font-size: medium;">http://emailipleak.com/</span></span></a></p>
<p style="margin-bottom: 0in;">

Updated: 2015-02-01