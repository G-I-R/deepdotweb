---
title: "PGP Tutorial For Newbs (Gpg4Win)"
---
<span>Posted by: DeepDotWeb </span>
<span>November 11, 2013</span>

<div>
<p> <em>Tutorial for </em>Gpg4Win using Kleopatra can <a href="https://gir.pub/deepdotweb/2015/02/21/pgp-tutorial-for-windows-kleopatra-gpg4win/">be found here</a>.</p>
<p>We found a great tutorial posted on reddit today about how to stay safe and use PGP.</p>
<p>The link to the original article is this: <a href="http://www.reddit.com/r/DarkNetMarkets/comments/1qdzl8/guide_pgp_4_n00bz/" target="_blank">http://www.reddit.com/r/DarkNetMarkets/comments/1qdzl8/guide_pgp_4_n00bz/</a></p>
<p>All the credit for the tutorial goes out to this reddit user:  BenZoThr0w &#8211;  <a href="http://www.reddit.com/user/BenZoThr0w" target="_blank">http://www.reddit.com/user/BenZoThr0w</a></p>
<p>All we did is to embed the images inside the tutorial for easier access &amp; of course post it here to spread this important information.</p>
<p style="text-align: center;"><a href="https://gir.pub/deepdotweb/vpn-comparison-chart/">&gt;&gt;&gt;Add A Layer Of Encryption: Click For The Best VPN Services&lt;&lt;&lt;</a></p>
<p>=====</p>
<p>The goal here today is to try and educate n00bZ on what PGP is, how to install GPA, I&#8217;m making the guide because I educated myself on PGP and it took awhile for me to understand it. So here is a picture guide to installing and creating a PGP key to encrypt and de-crypt messages.</p>
<p>=== BACKGROUND of PGP ===</p>
<p>Basically, each individual has a unique PGP key. In the program GPA, you import peoples unique key to your list of keys. When you go to write a PGP message, you type it normally in the clipboard { you&#8217;l learn about the clipboard later, it&#8217;s your friend } and then press an encrypt button, which then lets you pick from your unique list of keys to encrypt to, where ONLY that person can read it. [ this is why people give their public keys out, so anyone can encrypt them a message ]
    === THE STEPS ===</p>
<p>&#8211; Step One &#8211;</p>
<p>Okay, so first things first, let&#8217;s get a PGP program. One of the most popular is GPA. Head over to this link to download gpg4win which includes GPA {you can see a list of the programs gpg4win contains to the left of the download page, GPA is one of them}</p>
<p>Download: <a href="http://gpg4win.org/download.html">http://gpg4win.org/download.html</a></p>
<p>IMPORTANT !!!!!!! ***********************</p>
<p>When installing gpg4win you get the option to install which programs you want from the package. By default, GPA is not checked. MAKE SURE YOU CHECK GPA! You need it in order to easily encrypt and decrypt messages. This is what it looks like during the installation:</p>
<p><img class="aligncenter size-full wp-image-1291" src="/imgs/2013/11/14.png" alt="Pgp Tutorial 1" width="503" height="418" srcset="/imgs/2013/11/14.png 656w, /imgs/2013/11/14-300x250.png 300w" sizes="(max-width: 503px) 100vw, 503px" /></p>
<p>Next, you want to make a PGP key. Remember, none of the details need to be valid. I&#8217;d use your online name or a different alias when making your key. Something that isn&#8217;t your gamertag for online games, or anything that may tie to you. A completely new alias. The e-mail doesn&#8217;t need to be valid at all. Here are some pictures to help you through the process. Also make a backup of your key!!!</p>
<p>First, click the keys in the menu at the top. Alternatively, you can click CTRL+N to begin the process of creating a key. Shown here:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/21.png" />

<p>You will go through a set up, where you make a name for your key, which I suggest you use an alias. Shown here:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/31.png" />

<p>After selecting your alias it asks for an e-mail adress. This e-mail should be non existent, and be linked to a website that also doesn&#8217;t exist. Shown here:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/41.png" />

<p>Then you&#8217;re asked to make a backup of your key. I highly suggest you do this! Although you can make a back up at any time, you should just do it now. This is where your public key will be that you give to others to contact you. Shown here:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/51.png" />

    &#8211; Step 2 &#8211; Find Your Key &#8211;</p>
<p>Find where you put the back up of your key. It will be an .asc file but no worries, when asked to open the file just tell windows or whatever OS to open it using Notepad. Here you will find a public key similar to this.</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/61.png" />

<p>When sharing your key with others, you wan&#8217;t to copy and paste from the beginning dashes to the end dashes. Exactly how I have copied and pasted above.</p>
<p>&#8212; HOW TO IMPORT SOMEONE ELSES PGP KEY TO YOUR GPA PROGRAMS &#8212;</p>
<p>You see people giving their public keys away so others can contact them. Simply open a notepad file, copy and paste their key and import it using the GPA program. I will show you how to do this.</p>
<p>First make a blank text file and copy the users pubic key to it. Shown here:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/71.png" />

<p>Then, in the Keys menu where you made your key, select import keys. Shown here:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/81.png" />

<p>Select the Text file you saved with the public key in it. Shown here:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/91.png" />

<p>Then you should get this if the key was successfully imported:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/101.png" />

<p>Now, lets send an encrypted message.</p>
<p>First, open the clipboard. You can get there through the Windows menu or through the clipboard icon on the quickbar. Shown here:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/111.png" />

<p>Then after opening clipboard type the message you&#8217;d like to send and select encrypt at the top of the clipboard window. Shown here</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/121.png" />

<p>When you press encrypt, you are given a menu shown below. In this menu you select what key you&#8217;re using to send the message, and what key is going to be receiving the message. I chose to send the fake account used to make this tutorial a message with my personal account. Here&#8217;s what that menu looks like:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/131.png" />

<p>After you select who&#8217;s sending and who&#8217;s receiving you should get an encrypted message that looks like this:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/141.png" />

<p>This encrypted message is what you send instead of cleartext. So when messaging on websites, simply paste the PGP message. If you receive a PGP message, you can also use the clipboard to decrypt the message you have received by opening the clipboard, pasting the PGP message you got, and then pressing the decrypt button, shown here:</p>
<img src="https://gir.pub/deepdotweb/imgs/2013/11/15.png" />

<p>That about sums it up. I hope that people with questions on PGP and how it&#8217;s used can be solved here, as I tried to make the tutorial as noob as possible. Please be safe when communicating confidential or sensitive information on websites. Always PGP. Never FE. Be safe people. If you have questions, comment, and I&#8217;ll try my best to answer them.</p>
<p>=====</p>
<p>Hope this helps.</p>
</div>


Updated: 2013-11-11