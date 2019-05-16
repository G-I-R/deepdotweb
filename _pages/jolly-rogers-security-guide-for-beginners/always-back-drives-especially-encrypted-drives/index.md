---
layout: single
title: "WHY YOU SHOULD ALWAYS BACK UP YOUR DRIVES, ESPECIALLY ENCRYPTED DRIVEs"
sidebar:
  - title: "Jolly Rogers Security Guide"
    nav: "jolly"
  - title: "DeepDotWeb"
    nav: "pages"
  - title: "Security Tutorials"
    nav: "security"
  - title: "Blog Archive"
    nav: "blognav"
permalink: "jolly-rogers-security-guide-for-beginners/always-back-drives-especially-encrypted-drives/"
redirect_from: "jolly-rogers-security-guide-for-beginners/always-back-drives-especially-encrypted-drives"
---



<p>This is an embarrassing story of something that happened to me in the past few days, and it was a lesson well learned, for some of the things I have lost are not recoverable. &#8211; Jolly Roger</p>
<p>Do you have your Bitcoin wallets saved on a flash drive? What would happen if you lost your flash drive? Do you have a backup? What would happen if your files became corrupted and were not able to be recovered, could you live with that? Do you have certain things that would absolutely cause a huge problem if you lost them? Then you better start backing up your drives regularly, better yet, <strong>do it daily!</strong></p>
<p>I am the type of person who usually backs up his files regularly, but unfortunately do to the large amount of strange events occuring online lately with Utopia being brought down, BMR forums being seized, Silk Road being robbed and so forth, I had not backed up my files in about 2 weeks. I had all of my most recent files, including a few new Bitcoin wallets with balances on them on my main portable drive, and on top of it, this drive was encrypted.</p>
<p>Then, without warning, I suddenly received an error that the file system was corrupted and my disk could not be read. No matter, if you have an unencrypted drive, you can simply run a data recovery program such as <strong>testdisk</strong>. Open up your terminal and type the following. Make sure you started Tails with a login at the boot up when it asks you.</p>
<p><strong>sudo apt-get install testdisk</strong></p>
<p>Using this program (follow documentation online) you can likely recover most of your files because it ignores file system headers and other types of file organization required to identify the way the files are stored. There are many other programs as well. The problem in my case, was that all my files were encrypted. This means, that in order to decrypt the files, I needed a key file that is stored on the drive to unlock my files. If this key file gets damaged, then even if you have the password for your files, you will not be recovering your files.</p>
<p>The key is unique to that particular instance when you encrypted the drive. Meaning that even if I tried to recreate the key file with the same password, the result would be a different key file. This means essentially that my data is unrecoverable, because my key file was somehow corrupted. Technology is delicate, data is stored in the form of magnetic frequencies and there is no guarantee that files will not become corrupted one day for seemingly no reason. Here are some things that could ruin your data.</p>
<p>Flood, hurricane, power surge, fire, moisture damage, accidentally stepping on your drive, a family member (usually a child) breaks it, you lose it, spill water on it, over heats, and so forth.</p>
<p>All of these could result in your data or drive getting damaged and losing all of your data. This is why you need a minimum of 2 backups. Not 1, but 2. And have one of your backups preferrably stored outside of your home. If you work, store one at work, or in your car, or somewhere you can access regularly, and try to back up your data as often as possible. If your house burns down and you kept all your backups at home, then you lose everything. If you kept a copy at work, then you can recover it. The more backups the better, as long as they are encrpypted. Any time you create a new wallet and transfer Bitcoin into it, back it up. Any time you set up a new account or a new email with a unique password (which should be every time), back it up. You need to be backing up everything.</p>
<p>Luckily for myself my main wallet was recoverable with the majority of my coins, but I did lose some coins, which can never be recovered, trust me, I tried. Getting extra USB drives or SD cards are very cheap and inexpensive, so you owe it to yourself to spend a few extra dollars to have multiple backups just in case you wind up in my situation where you had not backed up your drive in a couple of weeks and end up losing data that could cost you a lot more than what it would have costed to have a few extra drives laying around as back ups.</p>

Updated: 2014-02-22

