---
title: "The Drugslist Lesson: Why Marketplace Security should not be taken lightly! (Complete Timeline)"
---

Posted by: DeepDotWeb

<span>January 27, 2014</span>
    

<p>This is one of the saddest of the latest stories, a marketplace who did not take the security warnings seriously and rather deny than fix, luckily, in this case no harm was done yet, beside the ruining of  the drugslist marketplace reputation, but this is a lesson that should be learned by all marketplace admins. address all issues, not matter how small you think they are.</p>
<p>We bring you here the complete timeline of the events &#8211; <span style="color: #ff0000;"><strong>Full credit goes to <a href="http://www.reddit.com/user/the_avid"><span style="color: #ff0000;">the_avid</span></a> for helping us organize this huge amount of information into a clear chain of events</strong></span><span style="color: #ff0000;">:</span></p>
<p>So this is how it began&#8230;</p>
<p>1. <a href="http://www.reddit.com/user/gwern">Gwern </a> and TMPSchultz (Themarketplace.i2p admin) take issue with Drugslist&#8217;s implementation of multi-sig (which we have reported before on this site) which really isn&#8217;t multi-sig (was referred as multisig lite by drugslist. This was posted in <a href="http://www.reddit.com/r/DarkNetMarkets/comments/1vtn44/tmps_multisig_vs_drugslists_multisig/">this thread</a></p>
<p>2. The user <a href="http://www.reddit.com/user/Magnus0">magnus0 </a>finds a simple sql injection in the registration form that allows him to signup without an invite code. That might sound benine, but the implication of an SQL Injection is that you have complete control of the database, he just chose to use it to register to prove his point. This is all done in private messages, since he just wanted to get the issue fixed. Drugslist pay him $14 and minimize the impact of the bug (it is very common in these circles to be paid for bugs, it isn&#8217;t out of the ordinary to ask for a bounty and most vendors would pay a bounty, since it is good practice). This private conversation leads mangus0 to post <a href="http://www.reddit.com/r/DarkNetMarkets/comments/1w3z17/thanks_for_the_beer_drugslist/">this thread</a>, This is the Pm exchange between them:</p>
<img src="https://G-I-R.github.io/deepdotweb/imgs/2014/01/durgslist.png" />

<p>3. At this point, some of the Darknet markets mods  and drugslist admin are beating up magnus0 in his thread &#8211; as are a lot of other users who join in, not realizing the issue is serious. Magnus0 throws in the towel and leaves.</p>
<p>4. 6-8 hours later another user &#8211; <a href="http://www.reddit.com/user/the_avid">the_avid</a> is coming on the Darknetmarkets sub and find the thread where drugslist announce their API, which he finds little interest in. At this point (as he told us) he knew little about drugslist &#8211; and had done not much more than sign up and click a few links perhaps 2 weeks earlier.</p>
<p>5. The same user &#8211; <a href="http://www.reddit.com/user/the_avid">the_avid</a>, reading the post from Drugslist about their <a href="http://www.reddit.com/r/DarkNetMarkets/comments/1w2rq9/drugslist_launching_optional_new_full_api/" target="_blank">full multisig api </a> noticing on 2nd paragraph &#8216;client-side PGP&#8217; and can&#8217;t believe what hes reading, he than continue to check their site and see they are doing PGP in web forms &#8211; a big no-no, so he posts <a href="http://www.reddit.com/r/DarkNetMarkets/comments/1w2rq9/drugslist_launching_optional_new_full_api/ceyi9zp" target="_blank">this comment</a>:

<img src="https://G-I-R.github.io/deepdotweb/imgs/2014/01/avid.png"/>
<p>6. Then, he started getting into a ridiculous back and forward with drugslist. In 99% of cases you&#8217;d report something like this, you would expect the admin to fix it and would move on, but drugslist persisted.  then the_avid noticed the API implementation.<br/>
<strong><span style="text-decoration: underline;">Note</span></strong>: A bit of background on that. The API implementation they are using is called jsonRPC and is used in bitcoin. But when used with bitcoin it only accesses a local server on the same computer, it isn&#8217;t meant to be used over the internet &#8211; not even over tor, since it isn&#8217;t a secure design. the_avid points out the poor API design as well, and again this is denied by drugslst.</p>
<p>7.  Now It is pretty clear at this point that drugslist doesn&#8217;t even <em>understand</em> the issues  that&#8217;s being reported to him, so as it was explained to us by the_avid he is being puzzled as to why Drugslist admin defending them so vigorously. He eventually concedes that implementing PGP in the browser can be unsafe (although he concedes this point for the wrong reason), but by this point he became more curious as to who this drugslist guy is and why he was behaving in that way. than, by looking through his comment history and  only need to scroll down half a page to see this comment from him on an earlier <a href="http://www.reddit.com/r/DarkNetMarkets/comments/1vtn44/tmps_multisig_vs_drugslists_multisig/cevpmbd" target="_blank">thread</a>:</p>
<img src="https://G-I-R.github.io/deepdotweb/imgs/2014/01/avid2.png" />

<blockquote><p>It&#8217;s also safe guard, and one of the many we have to reduce our members risk (others include: auto-withdrawal, <strong>client side PGP</strong>,shipping methods with concrete time frames and selected membership).</p></blockquote>
<p>As its was explained to us: &#8220;In that thread he was pitching what is a security vulnerability as a security feature, which was just amazing.&#8221;</p>
<p>8. As further check trough Drugslist post history was done it was easy to note that  hes entire comment history for the past 3 days is filled with arguments with other people who are reporting either security or technical issues to him.</p>
<p>9. In the words of a the_avid: &#8220;My jaw dropped when I saw the SQL injection thread (&#8216;thanks for the beer&#8217; thread) and how stupid and simple a bug it was&#8221;. he than went on and message magnus0 and told him &#8220;i&#8217;m going through the same thing as him with drugslist, and pointed him to my PGP thread.&#8221;</p>
<p>10. The user the_avid then decided to checkout the drugslist site himself, using hes own registration from 2 weeks earlier. he tested a half-dozen parameters on 3 different pages &#8211; the types of pages that usually have these bugs (search, product page, etc.) he finds that not a single one of them is properly handling input, which means they are also vulnerable to SQL injection.</p>
<p>he than goes on and pm drugslist and say: &#8220;you need to stop arguing, your site is a mess &#8211; i just found injection points on the search and product pages. take your site down&#8221;</p>
<p>11. With a few more minutes of investigating he got the server to leak debug info and quickly worked out how this site had been put together. he did an online search for project job listings and found a listing on the clearnet that he believed was Drugslist hiring developers to build his site (the cheap &#8216;program me a website&#8217; type marketplaces).</p>
<p>12.  than the_avid message him to tell him that he is just a couple of clicks away from doxxing him, and tell him that he know that he hired cheap offshore/contract labour to build his site. Drugslist pm&#8217;s him with &#8216;do you have torchat, I want to speak to you about that&#8217;. I reply with &#8216;no, I only do jabber + OTR&#8217;. then went to bed at this point.</p>
<p>13. The next day apparently Drugslist posted a thread in a private subreddit that only vendors can access (we can confirm this, as we saw this thread) for everybody to &#8216;be wary&#8217; of the_avid because he is law enforcement. his evidence was that he insisted on chatting to him over jabber (he didn&#8217;t realize that jabber runs over tor and is encrypted end-to-end) rather than torchat. he didn&#8217;t mention that it was he who wanted to speak to him.</p>
<p>14. A vendor takes a screenshot of that post and sends it to the_avid. In the meantime he is also speaking to the mods about Gabralkhan and his behavior in all this. when he strongly suspect that Gabralkhan and drugslist are the same person or that he is involved in the site. (<strong>which is NOT true, and it is now well confirmed with everyone, and also us in DeepDotWeb are vouching for Gabralkhan&#8217;s integrity</strong>)</p>
<p>15. At that point because of his LE post and that constant harassment and negative comments and denials from both Gabralkhan (who the_avid consider to be a part of Drugslist) and Drugslist the_avid decide that he is no longer going to work with them privately to fix bugs, but that he is going to do a complete writeup and let everyone know about all the bugs All posted in this <a href="http://www.reddit.com/r/DarkNetMarkets/comments/1w6ju4/warning_drugslist_is_extremely_insecure/" target="_blank">thread</a> (too long to quote, just see there).</p>
<p>16.  He than went on and left a ton of details and bugs out of that description because he was trying to keep it brief (!). He believed that Gabralkhan&#8217;s first comment in that thread was insulting him because he wanted to chat to drugslist over jabber:

<img src="https://G-I-R.github.io/deepdotweb/imgs/2014/01/insult.png"/>
<p>17. at that point drugslist steps in, and he attempted the same but despite floating all sorts of conspiracy theories (that the_avid work for TMP, that magnus and the_avid are the same person, etc.) and a lot of weird stuff none of what he was saying was taking hold much with readers apparently.</p>
<p>18. For the grand finale &#8211; Drugslist created a username &#8216;drugslist_developer&#8217; and attempting a mea culpa, but at this point, everyone saw through that &#8211; in <a href="http://www.reddit.com/r/DarkNetMarkets/comments/1w7syv/from_the_main_drugslist_developer_im_sorry_and_it/" target="_blank">this thread</a>:</p>
<img src="https://G-I-R.github.io/deepdotweb/imgs/2014/01/developer.png" />

<p>19. Than as if it wasnt enough already, the final blow landed &#8211; as magnus0 posted a thread (that was later deleted, but we had it screenshot), in the &#8220;<a href="/2013/12/14/tormarket-hacked-database-leaked-by-dread-pirate-roberts/" target="_blank">we hacked tormarket DPR Style</a>&#8221;  and dumping all the usernames data from Drugslist Database, proving the world that it is in fact, very vulnerable to hacking:</p>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2014/01/dumpdata.png"/>

<img src="https://G-I-R.github.io/deepdotweb/imgs/2014/01/dump2.png"/>
<p>20. Later, when we thought this could not get any worse in any way &#8211; it has brought to our attention that the hacker himself (Magnus0) was doxxed (probably by someone from drugslist staff?), and we received a copy of the full details, obviously we blacked them out:</p>
<p style="text-align: center;"><span style="color: #ff0000;"><strong>{We have remove the Blacked Out Doxx &#8211; since it was too much revealing anyway, and by now the point was made}</strong></span></p>
<p>The reason that we post this is it could stop a bunch of innocent users&#8217; information from being released or held hostage for money from the owners of DrugsList. it makes it less likely it is that Magnus0 will release the information he has on DrugsList users.</p>
<p>====</p>
<p>We have asked the_avid by he did not start by hacking them to prove hes point and make this long story short, he replied:</p>
<p>the reasons why I didn&#8217;t hack them:</p>
<ol>
<li>Showing that parameters aren&#8217;t being filtered properly is easy &#8211; I do that with nothing more than a web browser and the development console. Developing that further into an exploit can take anywhere from 2-48 hours since you need to go through a process of discovering their database schema</li>
<li>In 99% of security reports that initial test is all you need to show there is a bug, it is commonly accepted amongst most programmers that it is proof enough</li>
<li>My interest is in protecting users and vendors, I don&#8217;t really want to take advantage of their data and privacy to prove a point against a marketplace</li>
<li>I felt I had enough in my post in any case &#8211; anybody impartial would see it for what it is. I&#8217;d prefer these things are settled without user and vendor data being used as ammo.</li>
</ol>
<p>&#8212;</p>
<p>Let this be a warning for all admins, please for the benefit of your vendors and users, your Marketplace Security should not be taken lightly! address and fix every issue, even the ones you think are  small.</p>
</div>

Updated: 2014-01-27
    
