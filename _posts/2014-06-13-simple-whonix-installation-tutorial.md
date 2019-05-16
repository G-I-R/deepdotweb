---
title: "Simple Whonix Installation Tutorial"
---

Posted by: Chris </span>
<span>June 13, 2014</span>

<p>Whonix is an operating system focused on anonymity, privacy and security. It&#8217;s based on the Tor anonymity network and security by isolation. DNS leaks are impossible, and not even malware with root privileges can find out the user&#8217;s real IP. This makes it a safer way to access the Deep Web opposed to just using Tor on your current operating system. It is especially discouraged to be using Tor with a Windows operating system because of the direct access that the NSA has to Microsoft’s systems and the information that Microsoft is willing to hand over to them.</p>
<p>(Read more about the <a href="http://www.theguardian.com/world/2013/jul/11/microsoft-nsa-collaboration-user-data" target="_blank">NSA and Microsoft</a>)</p>
<img src="/imgs/2014/06/whonix.png" />

<p>(Diagram above showing how Whonix Works.)</p>
<p>Before using Whonix, it is helpful to understand how exactly it works. Whonix is made up of two parts. There is one that solely runs Tor and acts as a gateway, aptly called Whonix-Gateway. The second part which the user actually uses is called the Whonix-Workstation. It is on a completely isolated network that only allows connections through Tor. Both of these parts are run in their own virtual machines on your computer and this keeps what you docontained within Whonix.</p>
<p>To start you will first want to download <a href="https://www.virtualbox.org/wiki/Downloads" target="_blank">VirtualBox</a>. This will allow you to create the virtual machines for running Whonix on your computer. Then download both <a href="https://www.whonix.org/wiki/Download#Download_Whonix" target="_blank">Whonix-Gateway and Workstation</a>. There are a couple download options and you can choose which one you think is best. It is also suggested that you verify the images using the Signing Key if you understand how to do so. If not, you may want to learn how with the guide on PGP encryption.</p>
<p>After installing VirtualBox, open up the program and just follow a few simple steps:</p>
<ol>
<li>Click File &gt; Import Appliance…</li>
<li>Click “Choose” and select the downloaded Whonix-Gateway.ova file.</li>
<li>Click next and then “Import” without changing any of the settings.</li>
<li>Wait for the progress bar to complete the import.</li>
<li>Repeat those steps for the Whonix-Workstation.ova file.</li>
<li>Now start both the Whonix-Gateway and Whonix-Workstation.</li>
</ol>
<p>For your first use you will have to go through a quick setup process and then wait for Whonix to search for and install any necessary updates. Keep in mind you will need to keep Whonix-Gateway running but you don’t actually use it for anything besides updating. You will conduct all your activities within the Whonix-Workstation virtual machine window.</p>
<p>Now you can use Whonix to browse in a safer and more secure way, all without having to make drastic changes to your computer.</p>
<p><strong>This article is added in our <a href="security-tutorials/" target="_blank">security tutorials</a> section.</strong></p>
</div>

Updated: 2014-06-13
    
