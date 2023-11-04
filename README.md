# Bomb-Proof Password Wordlist
A tiny but effective wordlist for cracking the Navy SEAL "bomb proof" password scheme

I recently saw tacticalrifleman's video over on the Clock App (https://www.tiktok.com/@tacticalrifleman/video/7290736419474132257) and realised that this super cool password generation scheme (as shown) can be cracked with a wordlist of exactly nine entries.

This is a keyboard walk and it’s NOT secure. Firstly, password cracking wordlists already contain common keyboard walks. Second, this method guarantees super low entropy: if someone knows (or guesses) the keyboard walk scheme, they can brute force someone else’s password by hand!

It’s worse than that too: the video examples all use the lowest row of the keyboard (M, N, B) which implies that this keyboard walk scheme always starts with Z - period which can only generate a maximum of NINE unique passwords! (It would be ten but the ? sequence ends in a backspace so it’s probably not used.)

This password generation method is only safe against humans typing in passwords manually (as long as they don’t know the walk sequence!) and true brute force password cracking where every possible character is iterated through. This video seems to imply that the SEALs are sharing passwords so everyone on the team either already knows each other’s password or can guess it with a minute’s worth of work.

The only scenario where this could ever be considered “secure enough” is when you’re resetting someone’s password and you need to communicate that new password to someone over an insecure channel AND that person will be logging in and resetting their password IMMEDIATELY.

It took me less than a minute to manually type every password generated by this scheme! This isn’t “bomb-proof” -- it’s not even “firecracker proof”.




See "bppw.txt" for a file with just the passwords. Enjoy!

zaq1zse4ZAQ!ZSE$

xsw2xdr5XSW@XDR%

cde3cft6CDE#CFT^

vfr4vgy7VFR$VGY&

bgt5bhu8BGT%BHU*

nhy6nji9NHY^NJI(

mju7mko0MJU&MKO)

,ki8,lp-<KI*<LP_

.lo9.;[=>LO(>:{+
