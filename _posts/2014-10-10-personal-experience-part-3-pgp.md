---
title: "Personal Experience: Part 3 &#8211; PGp"
---


Posted by: Joseph Meehan
<span>October 10, 2014</span>
    

<p><em>This a post in series of posts describing a personal experience from learning about the DNM’s to becoming a vendor – all the parts of this series will be available to here: <a href="tag/ExperienceTag/">ExperienceTag</a></em></p>
<p>Part 3:</p>
<p>Before today I had never sent an encrypted email. It was relatively easy to get started, especially with the built-in tools that TAILS comes with. There is also no shortage of easily-accessed tutorials. I won&#8217;t be guiding you through the process here, but instead recording my thoughts on the experience of using it for the first time.</p>
<p>The idea of public and private keys was slightly confusing to me at first. The TAILS documentation gave me some of the insight that I needed to understand. An entity &#8212; a website, an individual, a vendor on the Darknet, etc. &#8212; can post their public key for people to use to encrypt messages to them. That individual can then use their private key to decrypt the message that was encrypted with their public key. As I researched it became clear how the encryption works.</p>
<p>More than one source about using <a title="PGP Tutorial For Newbs (Gpg4Win)" href="2013/11/11/pgp-tutorial-for-newbs-gpg4win/">PGP</a> emphasized that to be as secure as possible with your communication you want to encrypt should NOT be typed out in a browser. It should be written in a different application, encrypted and then pasted into the browser.</p>
<p><a href="https://g-i-r.github.io/deepdotweb/2014/06/14/simple-tails-installation/">TAILS</a> comes with OpenPGP for managing your public and private PGP keys. It also has a built-in applet used to encrypt text on the fly. It&#8217;s as simple as opening a word processor, typing your message, using the secure clipboard from the toolbar, and pasting into your browser/email client/instant messenger program.</p>
<p>I started up TAILS to send a trial email to myself. I wrote up a test message in gedit and used the applet to encrypt the text. I had two options at this point: open a browser and log on to my email to send the message, or use the included Claws email client to send the message. I decided to use the browser for now. Later on I will tackle setting up a persistent volume for Claws to save my email information and save my personal PGP keys, but for now I wanted simplicity. I logged in and pasted the encrypted text into an email to one of my other email addresses. When I copied the encrypted text to the clipboard the same applet that encrypted the text gave me the option to decrypt the message.</p>
<p>All in all PGP was an easy encryption method to get started with. The integration into TAILS is seamless and the experience needed is minimal.</p>


Updated: 2014-10-10

    
