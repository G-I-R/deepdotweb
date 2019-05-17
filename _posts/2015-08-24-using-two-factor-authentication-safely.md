---
title: "Using Two Factor Authentication Safely"
---

Posted by: Panic Moon 

<span>August 24, 2015</span>

<p>Darknet markets would not exist without Bitcoin but theft is rampant. Exchanges protect individual accounts by providing or even requiring two factor authentication. They are safer than markets, but how do you do this when you don’t want to give up an actual phone number? There is a solution, as long as your computer has the processor and ram needed to run VirtualBox.</p>
<p>You’re going to need the following pieces to make your untraceable two factor authentication system. First you’ll need to install VirtualBox itself, then download the gateway and workstation components of Whonix. This hardened Tor only environment is something anyone doing serious business via the darknet should be running.</p>
<p>My VirtualBox setup:<br/>


<img src="https://gir.pub/deepdotweb/imgs/2015/03/X5BeiVi1.png">

<p>The Whonix gateway and workstation come in OVA format, which you can import into VirtualBox. Once you’ve got this running go to a Tor friendly email provider, maybe GMX or Yandex, or your favorite throwaway email service, and make a new account. You’ll need this account for the next step.</p>
<p>The second step is downloading the Genymotion Android emulator using your newly created sneaky email for the registration. Using an address is a requirement, as the emulator will later have to Genymotion to pull Android images, and it uses that email as your identity. Picking a provider that operates the way Hushmail used to do would be fine, you only need this email to sign up, and if it evaporates a month later that’s perfect.</p>
<p>Genymotion:<br/>


<img src="https://gir.pub/deepdotweb/imgs/2015/03/5BeOdaa1.png">

<p>When you install Genymotion it’s going to phone home. You can wrap it in Tor, but that’s a bit of a challenge unless you’re a networking guru, and you can’t afford to slip. You should be running a VPN all the time, and especially while doing this.</p>
<p>You can use VPNBook without providing registration but we wonder who they work for that they can afford to do that for free. PrivateTunnel has a first 100 meg free but that goes quickly. The best deal out there is Cryptostorm’s system. They use anonymous tokens rather than username/password, you can buy with Bitcoin, and their Cryptofree (http://cryptofree.me) offering is as safe as the paid service, but it’s capped at 256k.</p>
<p>Once you’ve got Genymotion running you’re going to wait a bit as it downloads a file of around 200 meg in size. The Genymotion system offers many types of Droids, Samsung Galaxy S4 with Android 4.3 is a good choice. Then you will have to install the Google tools package in order to have Gmail and Play Store.</p>
<p>A search for “Google Apps CyanogenMod” will lead to various offerings, the file name you are looking for that goes with 4.3 is gapps-jb-20130813-signed.zip. Get this file from the Android Google Apps collection (https://www.goo.im/gapps/), drag it on top of your running virtual Android, and drop it. Follow your nose through the install process, and don’t worry about the Google Plus crashes, that package is broken on an ongoing basis, just dismiss the alert when it happens.</p>
<p>installing Google Apps for Android:<br/>


<img src="https://gir.pub/deepdotweb/imgs/2015/03/Sv5JDES1.png">

<p>When you first start the system you’ll have a chance to either add or make a new Gmail account. Create a new one, it’s going to be your login to the Play Store, but don’t ever use it for anything else.</p>
<p>home screen /w gmail &amp; playstore:<br/>


<img src="https://gir.pub/deepdotweb/imgs/2015/03/7Zoz3wB1.png">

<p>gmail screen:<br/>


<img src="https://gir.pub/deepdotweb/imgs/2015/03/KdSPHvm1.png">

<p>Once you have the Google Apps installed, start the Play Store, log into it using the Gmail you just created, and install Google Authenticator. Now you’ve got the ability to do two factor auth and you didn’t have to give up a working email address, a real IP address, or an SMS number. Google Authenticator doesn’t need network access, so you can edit the Droid’s config in VirtualBox and disable network access. That *should* make the key to your online treasury fairly secure.</p>
<p>install playstore:<br/>


<img src="https://gir.pub/deepdotweb/imgs/2015/03/8KZ1TtP1.png">

<p>authenticator ready to use:<br/>


<img src="https://gir.pub/deepdotweb/imgs/2015/03/HamxowD1.png">

<p>There are a variety of questions a person trying to do this for the first time might ask. Here are some of the more common ones:</p>
<p>Q: Why did I download this Whonix stuff, it’s huge, and all it did was get me a throwaway email?</p>
<p>A: You darknet market guys need to level up on Tor, Whonix is a good system, and some of you are on your way to being security journeymen. See if you can create another Genymotion virtual Droid and get it to work using the Whonix Gateway as its path to the internet. Genytion wants an HTTP proxy, but Whonix only provides SOCKS5, so you’ll need to install and configure Polipo on the Gateway. Completing this requires command line skills.</p>
<p>Genymotion &amp; polipo proxy:<br/>


<img src="https://gir.pub/deepdotweb/imgs/2015/03/nmWYBw31.png">

<p>Q: I can’t get Tor or OpenVPN or other apps that use cryptography to run on the virtual Droid. Why?</p>
<p>A: Cryptography for Android expects to have access to ARM processor, but you’re running an emulation on an AMD or Intel architecture chip. There are some gamer oriented packages for Genymotion that supposedly fix the missing ARM instructions, we’ve tried a few, and never got them to behave for cryptographic apps. Even if you could do this, the host OS is the right place to have your VPN.</p>
<p>Q: Why didn’t we use TAILS to get the first email? Is there something wrong with it?</p>
<p>A: TAILS is great, as you can see we have the latest, we recommend it highly, and use it all the time, but you should use the right tool for the job. The Whonix dual gateway/workstation setup is even more resistant to de-anonymizing attacks than TAILS, it just needs more resources to accomplish that. Any machine that can run Genymotion will have enough ram and the right processor to run Whonix.</p>

Updated: 2015-08-24

