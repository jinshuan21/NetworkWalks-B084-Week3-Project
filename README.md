# NetworkWalks-B084-Week3-Project
Network Walks Internship Week 3 Assignment: Password Cracking with John the Ripper and Network Walks Tools

This repository is documentation of my attempt at the Week 3 laboratory work as presented by NetworkWalks for the batch B084 Cybersecurity internship. In this project, I cracked the password of two locked PDF files using two different methods.

All steps described in the lab were instead carried out by me on Kali Linux, including downloading and installing Johnny.

For Project Module 1, I used John the Ripper and its Johnny GUI. I extracted the password hash from the PDF using an online hash extractor tool, saved it into a text file, then loaded it into Johnny and started the attack to recover the password.

For Project Module 2, I used the Networkwalks Hash Calculator and Password Cracker, two free online tools that run entirely in the browser. I uploaded the locked PDF to the Hash Calculator to get its hash, then pasted that hash into the Password Cracker to recover the password.

In both cases, I used the recovered password to successfully open the locked PDF files, confirming the attacks worked. No exploitation was performed beyond password recovery.

All activities were carried out only on the file provided for this lab exercise and on systems I own, and everything here is for education and research purposes only.
