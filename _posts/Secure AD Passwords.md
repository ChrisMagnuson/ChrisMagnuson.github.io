+++
title = "Secure passwords for all accounts in Active Directory"
date = 2018-11-07
+++

Prequisites:

https://www.youtube.com/watch?v=0SkdP36wiAU&t=89s

Some points from this:



Passphrases are not necessarily good passwords
123456781234567812345678
monkeymonkeymonkeymonkey
To mitigate this you generate the passphrase for the user:
outride adust jaundice vassal
shiksa durable object encode
toffee doughty anaconda gifted
https://www.fourmilab.ch/javascrypt/pass_phrase.html
To use much of the passphrases this thing generates I would need a bigger vocabulary
 
Thoughts:
The goal is improvement (though solving the problem forever would be nice)
baseballbaseballbaseball is better than baseball
As bad passphrases become more common place they will end up in the haveibeenpwned database and then won't be usable in our environment
If we never change passwords then we may still have known bad passphrases used by some accounts
We are not relying on passwords or passphrases to keep us safe, MFA is the only way to feel a modicum of security, anything without MFA isn't secure

* Awareness of Active Directory Fine Grained password policies features

If you don't know what you can do with Active Directory fine grained password policies google that first and then come back.

Once you have looked at the state of the art with fin grained password policies you will find there are a number of things that are essential for having secure passwords:

* Ensuring the password isn't a password that has already 