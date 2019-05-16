---
title: "L2TP vs OpenVPN. The Ultimate Battle"
---

Posted by: DeepDotWeb 

<span>September 29, 2015</span>

<p>Over the last couple of years, a great number of VPN users have started using OpenVPN. You can find a lot of positive feedback online about this VPN protocol and why it&#8217;s superior to any other VPN implementation. But what is the force behind OpenVPN and do you really need to switch over from your standard L2TP/Ipsec option? In this article the <a href="https://www.privatoria.net/?ref=deepdotweb">Privatoria</a> team will investigate which one is better for specific cases.</p>
<p style="text-align: center;"><a href="/vpn-comparison-chart/">&#8211;&gt; Click here to see the best VPN&#8217;s for privacy &lt;&#8211;</a></p>
<p>OpenVPN has been around for a long time but it has only received prominence in recent years mostly because of multiple surveillance scandals in the US. Most users then started promoting the idea of open source software stressing the fact that surveillance is impossible in the open source world because any attempt to hide a tracking program inside a source code will be easily spotted. Things like Linux-based OS&#8217;s and Chromium Web browser have become a lot more popular. Open Source has unintentionally become a must-have (or a least a must-try) for every security enthusiast.</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/09/11.png">

<p>VPN, being a security-oriented technology, has also increased its popularity among casual personal users who want to hide and preserve their private info. In the world of VPNs, however, you don&#8217;t really have a choice; most protocols are proprietary (owned by a certain company) and therefore have closed source code. But there&#8217;s one exception and that&#8217;s OpenVPN. Users have rushed out and switched to OpenVPN but is L2TP/Ipsec better simply because you can find a standard option on MS Windows and Mac OS X? Let&#8217;s find out.</p>
<p><strong>Encryption and Security </strong></p>
<p>L2TP as a standard has been around since the late 90s and so has the IETF <a href="http://tools.ietf.org/html/rfc3193">RFC 3193</a> certification. During the 2000s Microsoft fully replaced their allegedly compromised PPTP with this VPN implementation. It also goes almost without saying that in 99% of cases L2TP is used to ensemble with Ipsec encryption technology as L2TP only offers tunneling. Ipsec can use different encryption algorithms including 3DES and AES. As the result of recent revelations in the security domain, some messages were leaked revealing certain governmental agencies are looking for potential vulnerabilities in IKE/Ipsec implementation. This automatically gives birth to the controversy around L2TP/Ipsec implementation. Concrete proofs of the protocol’s vulnerability (if they in fact exist) are yet to be made public though; but as it always happens, one negative comment triggers a chain of events.</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/09/24.jpg">

<p>OpenVPN uses SSL/TLS encryption protocol, namely OpenSSL library. This library supports different encryption algorithms including Blowfish, AES, RC5 and 3DES. OpenVPN being de facto open source standard obviously has no known or even alleged vulnerabilities. At this point, it is hardly possible to choose a winner but users often choose OpenVPN simply because it&#8217;s open.</p>
<p><strong>Speed and Stability</strong></p>
<p>L2TP uses fixed protocols and ports for connection, namely UDP 500 for initial key exchange, 50 for Ipsec encrypted data, UDP 1701 for initial L2TP configuration and UDP 4500 for NAT traversal. Most users consider this a weak point stating that such configuration can be easily blocked by firewall settings.</p>
<p>OpenVPN can be easily configured to use either UDP or TCP on any port. It is often advised to use TCP/443 configurations to bypass firewalls.</p>
<p>Both L2TP/Ipsec and OpenVPN offer relatively the same connection speeds. However, L2TP being more standardized (and henceforth easier to support for a VPN provider) may offer more stable connections and less configuration issues.</p>
<p><strong>Configuration</strong></p>
<p>This is a tricky one. In general, L2TP/Ipsec is easier to configure than OpenVPN and it also comes</p>
<p>pre-installed with major computing platforms including MS Windows and Mac OS X (Android and IOS also feature L2TP/Ipsec as a default VPN solution). However, it is different on the Open Source side of things. Most Linux or BSD distribution, including Ubuntu and Debian, will only come</p>
<p>pre-installed with insecure PPTP (even Microsoft openly admitted its poor security at one point; issuing a fix later) or no VPN support at all.</p>
<p>If you rush out and try to get L2TP/Ipsec up and running on Linux you will inevitably face a number of issues and a fairly complex configuration process which requires installing xl2tpd daemon and openswan/strongswan ipsec implementation. Furthermore, you will have to manually configure traffic routing and make sure your l2tp tunnel is used for that.</p>
<p>Below is just a part of the L2TP/Ipsec configuration process on Linux:</p>
<p>Ipsec (OpenSwan package) config</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/09/31.png">

<p>xl2tp daemon config</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/09/4.png">

<p>Routing traffic via VPN</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/09/5.png">

<p>Arch Linux has a nice set-up tutorial on their <a href="https://wiki.archlinux.org/index.php/L2TP/IPsec_VPN_client_setup">wiki</a></p>
<p>L2TP is also natively supported by most network routers which means you can easily connect a router directly to the VPN server and not tweak your computer settings at all.</p>
<p>OpenVPN is not natively supported by any platform. Installing it, though, is a fairly brief affair and only requires downloading a client app for Windows, Mac, Android and IOS. Linux and BSD users can get &#8216;openvpn&#8217; package from the official repositories and use the command-line interface to run it. Many VPN clients do not allow manual configuration and require a config file with all the settings and CA certificates inside. Most VPN providers (assuming they support OpenVPN) offer those files as a free download. Therefore, there should be few to no configuration issues, still most casual users might find the configuration process too difficult and unintuitive. OpenVPN is also much easier to configure on Linux/BSD systems. To use it you are only required to install the package and point it the correct VPN config file; traffic routing is done automatically.</p>
<p>This is how a config file may look like:</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2015/09/6.png">

<p>There is a way to enable OpenVPN support on a network router as well but it requires installing a custom firmware known as DD-WRT (assuming your router is compatible with it).</p>
<p><strong>Conclusion</strong></p>
<p>At the end of the day each user has a choice of VPN protocols and that&#8217;s a great thing. L2TP/IPsec is a more solid, standard choice with built-in support on every commercial computing platform. It is also quite secure and has no known vulnerabilities. All of the above makes it a great choice for most casual VPN users who want their VPN to be simple and stable.</p>
<p>OpenVPN is a new Open Source standard with the ability to use a wide range of port and protocols. It does not come pre-installed on any platform but can be installed on any modern OS both desktop and mobile. It is also much easier to configure on Linux/BSD systems than L2TP/Ipsec. OpenVPN is great choice for security nerds who want versatility and more control over their VPN. Nowadays most VPN providers support OpenVPN and L2TP. So, there shouldn’t be a problem connecting to a VPN server if you have the client configured correctly.</p>

Updated: 2015-09-29