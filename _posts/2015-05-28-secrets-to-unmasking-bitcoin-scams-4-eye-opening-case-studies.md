---
title: "Secrets to Unmasking Bitcoin Scams &#8211; 4 Eye Opening Case Studies"
---

Posted by: DeepDotWeb 

<span>May 28, 2015</span>
    

<p><em>Guest post by Ofir Beigel is the owner of <a href="http://99bitcoins.com/">99Bitcoins</a></em> &#8211; Bitcoin offers great opportunities for people to exchange money online instantly and anonymously. However, many sites take advantage of Bitcoin’s pseudo anonymous nature and use it in order to scam people out of their coins.</p>
<p>I’m sure this is not something you didn’t already know. But here’s the kicker:</p>
<p>I’m going to show you how you can easily expose these websites for the frauds they are and avoid being scammed. For a short while we are going to become Bitcoin detectives and I will give you the tools to solve the puzzle of is this site a “Sting or Bling” ?</p>
<p><strong>Case #1 &#8211; EarnTomorrow &#8211; Make 10% a day on your Bitcoins</strong></p>
<p>Sounds awesome doesn’t it ? Earn 10% on your Bitcoin for life. Let’s investigate.</p>
<p>The first thing I’m going to do is Google “EarnTomorrow review” and see what comes up:</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/13.png">

<p>Well that was easy.</p>
<p>Just by reading the results you can see that a lot of people are saying that this is a scam. Apparently after you open your account and deposit some coins you receive an email that your account is hacked and you will not be able to do anything about it.</p>
<p>My guess is that most of the top sites in the Google results are people who are pissed off about EarnTomorrow stealing their money. Including one guy who actually love 1.1BTC and decided to upload a video with proof about the story.</p>

{% include video id="IhSCJv0DRU8" provider="youtube" %}

<p>So solving our first case was pretty simple, but what if you can’t find any reviews about your requested service ?</p>
<p>here are some more tool to solve your puzzle:</p>
<p><strong>Check the “About Us” page</strong> &#8211; Usually when a site is a scam it will not give explicit information about the company’s team. It will state something vague like “We are a team of Bitcoin experts”. In EarnTomorrow’s case I found this paragraph on the FAQ page:</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/22.png">

<p>So it’s legally registered in the UK ? Interesting…</p>
<p>Let’s check out the contact us page and see where the company is located:</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/32.png">

<p>Well maybe I was wrong about this.</p>
<p>Maybe this is a legit company. Since today is a Sunday I can’t call their offices but what I can do is Google their address. Here’s what matches their company name and address:</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/42.png">

<p>An air conditioning company in the UK.</p>
<p>This is pretty clever, my guess is that they think people won’t dig in as deep as we just did and just believe their story once the they see the actual physical address.</p>
<p>EarnTomorrow is what is called a <a href="https://en.wikipedia.org/wiki/High-yield_investment_program">HYIP</a> (High Yield Investment PRogram) and usually it will work for a while and actually give you your payout. Once you’ve invested a big amount of money in the company it will disappear into thin air on some sunny afternoon. I actually fell for such a HYIP myself with a website called Bitcoin Trader almost a year ago.</p>
<p><strong>Case #2 &#8211; Bitcoin Field, finding clues under the rug</strong></p>
<p>Here’s another example &#8211; Bitcoinfield.net ( I’m not linking to them so they won’t enjoy the benefit of free traffic).</p>
<p>On Bitcoin Field’s homepage there is box indicating how many members are currently online.</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/5.png">

<p>As you can see it states that there are 385 members online. What caught my attention was that no matter how many times I visited the pages, this page stayed constant. So I went deeper into the page’s html source and found out that this number is actually just static text inserted by whoever built the website in order to make it look that there are users online:</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/62.png">

<p>The funny thing is that while I was writing this article the website actually changed the static text from 385 to 386. This is either done manually or by some sort of script. My guess is that if you’ll go to the website right now you’ll see the same number.</p>
<p>This kind of check can be done easily by right clicking your mouse and choosing “View page source”, then I just hit “CTRL + F” (or CMD + F on a mac) and search for the number 385.</p>
<p>But assuming this does not supply hardcode evidence let’s look at some more factors:</p>
<p><strong>Site traffic</strong> &#8211; using <a href="http://www.alexa.com/">Alexa’s</a> ranking algorithm the site seems to have a lot of traffic &#8211; ranking around 130,000. But if you look at the stats a bit deeper you can see that this ranking came only from a one time peak of traffic around April.</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/74.png">

<p>This was probably some form of junk traffic you can buy for as cheap as $25 around the web in order to fake your Alexa score to seem higher than it actually is. Just Google “Buy website traffic” and see what comes up if you want to find such a service.</p>
<p><strong>Whois lookup </strong>&#8211; Last thing we’ll want to check is who registered the domain. This can be done with <a href="http://whois.domaintools.com/">a simple lookup tool</a>. Usually when someone has something to hide they will use a private registration which will not allow you to track the domain back to them. Such is the case of Bitcoin Field.</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/81.png">

<p>Interestingly enough, if you go back to viewing the page source you can actually find the company’s info:</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/9.png">

<p>But apperantly they decided to leave this out of the visitor’s view. I can only assume that this was first shown in order to gain credibility and once people started calling out their scam they removed any identifying tracks. I may be wrong about this of course, but if this company is legit I have no idea why they would cover their registration information.</p>
<p><strong>Case #3 &#8211; The spirit of Mt.Gox lives!!</strong></p>
<p>This next case was sent to me by one of my readers at 99Bitcoins. He claims that he purchased Bitcoins using Paypal from a site called Mt.Goox.com. If you go to the website today you’ll see that it is “under construction”, but since Google keeps a cached version of all web pages it indexed I found out how it looked back when it was operational:</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/10.png">

<p>Lucky for us, the inner pages of the site are still working so we can examine them and see if we could have marked this site as spam before making a purchase.</p>
<p><strong>Trust seals</strong> &#8211; On the bottom of each page of the site there are several trust seals from different companies like TRUSTe, BBB and Norton.</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/111.png">

<p>When you click on any of these trust seals you should be presented with a certificate that this is a trusted site. However in this case you are pointed to different social media pages of Zen Cart which is probably the provider of this site’s template.</p>
<p>If you continue investigating the footer you’ll find out some more interesting evidence of an inoperational website such as the fact that the “Email Us” link leads to a local host address, the customer support phone number just links to the homepage and my personal favorite &#8211; The Terms of Use and Privacy Policy are just blank pages:</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/121.png">

<p><strong>Case #4 &#8211; Are there any legit Bitcoin investment sites left ?</strong></p>
<p>Now I want to show you a different angle. I want to review a legit Bitcoin investment website and show you how it should look like. Keep in mind that I am not affiliated with this site in any way, I just think they have an awesome service.</p>
<p>BTCJam is a website that allows you to loan out Bitcoins to people and get them back with a large interest over time (almost 20% Annual Percentage Rate).</p>
<p>If you take a look at the site’s traffic you can see it is ranked around 20,000 by Alexa and has a stable stream of visitors:</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/131.png">

<p>The contact us page shows clear profiles of the team which adds to its credibility. in the past this site also used to display a physical address which is currently not visible.</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/14.png">

<p>The company’s blog is rich with content and is updated daily, TOS and privacy policy are up to date and in general everything just seems solid.</p>
<p>If you check the registrant of the domain you’ll also get the actual company who owns BTCJam &#8211; Ovo Cosmico.</p>

<img src="https://gir.pub/deepdotweb/imgs/2015/05/15.png">

<p><strong>In conclusion</strong></p>
<p>Using the tools displayed in this article you can easily differentiate the stings from the blings. Here’s a short recap of them:</p>
<ul>
<li>Googling the website’s name + review</li>
<li>Website stats via Alexa &#8211; What’s the traffic rank and is it stable over time ?</li>
<li>About us page &#8211; Are there real profiles connected to the company ? Is there a physical address ? Google the address to cross check the data.</li>
<li># of users / members &#8211; Is this an actual number or just static text &#8211; View the page source.</li>
<li>Trust seal &#8211; Do they show the actual trust certificate ?</li>
<li>Privacy Policy and TOS &#8211; Are they available ? If so, who is registered as the company’s owner ?</li>
<li>Whois lookup &#8211; Is the domain listed under private registration ?</li>
</ul>
<p>Hopefully the tools demonstrated here will allow you to avoid giving your Bitcoins away to fraudulent websites and invest them in legit ones instead. If you have any other methods of separating Bling from Sting I’d love to hear about them in the comment section below.</p>
<p><strong>Bio Box:</strong></p>
<p>Ofir Beigel is the owner of <a href="http://99bitcoins.com/">99Bitcoins</a> and the Author of “<a href="http://99bitcoins.com/my-dirty-little-bitcoin-secret-lp/">My Dirty Little Bitcoin Secret</a>”. 99Bitcoins is a blog dedicated to helping people getting started with Bitcoins. My Dirty Little Bitcoin Secret is a book describing how Ofir managed to make over $100K in one year by taking advantage of the growing Bitcoin industry.</p>

Updated: 2015-05-28

