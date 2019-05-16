---
title: "Agora Admin Explains: Why is Agora Always down?"
---

Posted by: DeepDotWeb

<span>September 1, 2014</span>
    

<p>For the first time, <a href="marketplace-directory/listing/agora-market">Agora market</a> (the most successful market at this time) admins offered a complete explanation about &#8220;why the market is down all the time?&#8221; &#8211; an important read for those who are asking this question every time that the market is down.</p>
<p>Original post on Agora forums can be found here: http://lacbzxobeprssrfx.onion/index.php/topic,33275.0.html</p>
<p><strong>Here is the full quote:</strong></p>
<blockquote><p>Since you have all recently had to tolerate certain problems with the market availability, we want to address some of your concerns. We don&#8217;t intend to defend the mediocre availability of the market up to this point, and we still assure you that we are frantically working on making the situation much better, but this is just an explanation about why the problems have appeared in the first place, since many of these questions seem to pop up every now and then.</p>
<p><strong>TL;DR;</strong></p>
<p>Our primary goal is to stay hidden from LE agencies and secure from hackers. We implement much more security measures than many others, which causes problems with availability.</p>
<p><strong>What could go wrong so often? I never see my local electronics webshop being down that much&#8230; </strong></p>
<p>Our setup it not simply a regular web server with extra Tor daemon running on it. We had to implement other levels of protection on top of that, including proxy VPN connections, constant changing of servers, additional software which is not found on any normal web server which handles intrusion detection. History has shown that Tor, even though it might be a work of art, has flaws, potential vulnerabilities, and what is worse, open research problems (like traffic confirmation attacks), which is basically another term for known vulnerabilities which could realistically be implemented by a properly motivated attacker. For the level of security that we are aiming at, it is simply not enough to rely just on Tor for providing the anonymity and security.</p>
<p>Moreover, there is little public research about this topic. Try to find guides for setting up a local electronics webshop and you will find thousands. Have you seen a proper guide for setting up an anonymous market with original research into risk assessment etc.? We have for example found numerous problems with Tor software which haven&#8217;t been found in any of their docs, and that is still considering the fact that among the anonymity software we use, Tor is one of the best-documented ones.</p>
<p>This does not mean so much that it is impossible to make the market run more stable than we have done up until this point, it just means that we need additional time to make the proper research and setup the system in a way that is also stable. We feel that this is a much better approach than fix the availability first, and then figure out the way to make it secure, because by the time we would do that, it might be too late, and not too late in a way that we get a few users that go to other markets due to bugs, but in a way that we shall find ourselves in jail before that happens&#8230;</p>
<p><strong>Why don&#8217;t you just buy 100+ extra servers and be done with it? </strong></p>
<p>While achieving simple horizontal scalability for a web service is not an easy task in itself, it is especially difficult when it has to be done securely. Servers need to sync, and that has to be done securely as well. There is too much risk of anybody sniffing any part of the traffic and figuring out what the servers are doing, if it is not done completely securely.<br />
    Apart from that, just simply installing a server in a secure way is not a 10-minute thing. The more servers we have, the more setup time we need to spend on them, and if they are too many, we will end up with putting all the time into setting up servers, setting up all the encryption and and anti-hacking gimmicks and not have any time developing the actual market. This is not something that we feel secure with outsourcing either, do you really want some random dude setting up a server which will hold your bitcoins and protect them from the countless threats out there?</p>
<p><strong>Why don&#8217;t you just get 100+ more professional developers that could to all this in a week.</strong></p>
<p>We cannot just go to a software company and tell them hey, we need help with this illegal ass darknet market which has millions on it, which facilitates drug trade and money laundering, please help us develop it. Neither can we just give access to our servers or software to random people from the internet who, while claiming to have proper skills, could easily be just looking for easily stolen bitcoins, or worse yet working for LE or having been converted by LE.</p>
<p><strong>Why don&#8217;t other markets have as much problems?</strong></p>
<p>First of all you should compare with markets of a similar size. Running a small website securely is much easier than running a market of a size of Agora. Secondly, we don&#8217;t have exact information of course, but it seems that others don&#8217;t implement nearly as much security measures as we do.</p>
<p>The measures that we do implement, we do so in the best known way to us, and we are no amateurs when it comes to this technology. Keep in mind that we are one of the few markets that haven&#8217;t been hacked in any way ever since the very start, and we haven&#8217;t lost a single one of your bitcoins. We feel that the level of security that we have been aiming at from the very start is one of the top ones among the contemporary darknet markets.</p>
<p><strong>Isn&#8217;t this too much security?</strong></p>
<p>We don&#8217;t know exactly how much security is needed. As you can imagine, the world&#8217;s top authorities don&#8217;t exactly tell us what methods they have of capturing sites like this. Even after big public busts only a limited amount of information is required. We have to gather all the pieces of information from busts, hacking forums, rumors, keep an eye on the recent research and deduct from all that how the current technology might be susceptible to which realistic attack vectors, and based on all this somehow establish an accurate threat model.<br />
    So in order to have a chance to stay here for any substantial amount of time we have always be on the safe side and implement as much security as we can.</p>
<p><strong>We just can&#8217;t conduct business this way!</strong></p>
<p>Then you should probably not be selling illegal substances.<br />
    We are getting paid to provide a very specific service, and as we see it, the main nature of that service is anonymity and security of your money and your information. It is NEVER going to be as stable as a similar legal marketplace. Even when we fix our current issues there are still going to be situations when the market will be offline, where there will be problems, etc. In the exact same way that you can&#8217;t insure your street-corner drug enterprise, the main difference being that on the street you have to risk dealing with LE directly, and here you shift most of that risk to us and accept getting hit with some market downtime or bugs caused by our security protocols.</p></blockquote>
<img src="https://G-I-R.github.io/deepdotweb/imgs/2014/09/agora-Downtimes.png" />

<img src="https://G-I-R.github.io/deepdotweb/imgs/2014/09/agora-Downtimes2.png" />

<p>From now on we will provide this post as an explanation every time that some one will mail us asking about the market being down.</p>

Updated: 2014-09-01
    
