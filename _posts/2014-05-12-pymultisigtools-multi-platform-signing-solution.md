---
title: "Pymultisigtools: Multi-Platform Signing Solution"
---

Posted by: DeepDotWeb

<span>May 12, 2014</span>

<a href="https://gir.pub/deepdotweb/2014/05/12/pymultisigtools-multi-platform-signing-solution/#respond">Leave a comment</a></span>
</p>
<div class="usertext-body may-blank-within">
<div class="md">
<p>In interesting development by <a class="author may-blank id-t2_e8ae2" href="http://www.reddit.com/user/owockEznan">owockEznan</a> one of the talented developers that made the <a href="https://gir.pub/deepdotweb/2013/12/30/full-guide-how-to-access-i2p-sites-use-themarketplace-i2p/">TMP plugin:</a></p>
<p>Original discussion <a href="http://www.reddit.com/r/DarkNetMarkets/comments/25caoq/introducing_pymultisigtools/">here</a>.</p>
<p><span style="text-decoration: underline;"><strong>Quote</strong></span>:</p>
<p>For those who want to sign transactions, but don&#8217;t have bitcoin-core or the TMP Electrum plugin, I have a new, multi-platform signing solution. Right now it&#8217;s a very rough first draft, but it is capable of signing tx that are well formed, so I figured I should released it now, and deal with the nice stuff I&#8217;d like to have later.</p>
<p><a href="https://github.com/Zah6ooheew/pymultisigtools">https://github.com/Zah6ooheew/pymultisigtools</a></p>
<p>The initial release is very basic, capable of signing transactions only. It can take the json normally given to the TMP electrum plugin, it will prompt for the private key (this can be in any form pybitcointools supports) and will output the raw hex of the signed transaction. It will also ensure that the signatures are in correct order and enough are found for the transaction to be considered complete. Otherwise it will simply show you the half-signed transaction (if you supplied a valid signature but the other sig wasn&#8217;t supplied or invalid in some way). It can&#8217;t push to the blockchain, copy-paste into a site like <a href="http://eligius.st/%7Ewizkid057/newstats/pushtxn.php">http://eligius.st/~wizkid057/newstats/pushtxn.php</a> to actually submit it to the network.</p>
<p>Please submit any bug reports on the github site so I can track them! Or tell me if it works for you here. If you don&#8217;t use the windows binary, you have to install pybitcointools from <a href="https://github.com/vbuterin/pybitcointools">https://github.com/vbuterin/pybitcointools</a> or put the &#8216;bitcoin&#8217; directory from that into the working folder. Note that there are no installation scripts for the program if you&#8217;re not using windows. Windows users can download only <a href="https://github.com/Zah6ooheew/pymultisigtools/blob/master/pymultisig-win32install.exe">https://github.com/Zah6ooheew/pymultisigtools/blob/master/pymultisig-win32install.exe</a> and run the installer. It <em>should</em> work.</p>
<p>&#8212;&#8212;&#8212;-</p>
<p>Noted to myself: Worth Following.</p>
<p>&nbsp;</p>
</div>
</div>

Updated: 2014-05-12
    
