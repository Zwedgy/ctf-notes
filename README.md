# ctf-notes
Notes of CTF challenges
A lot of them are random
<h1>Linux and privesc</h1>

When having a limited shell you can try these following methods:
1) Check if NetCat is installed
2) Try to get a shell using Python, PHP or an other language
3) If SSH is installed try to add your key to <code>authorized_keys</code>

If you know an username, try to grep files containing it.
<code>grep -Ril "username" / 2> /dev/null</code>

Sometimes you can find information to guess the password or even the password in plaintext

Run [LinEmum.sh](https://github.com/rebootuser/LinEnum) and [PsPy](https://github.com/DominicBreuker/pspy)

<h1> Stego </h1>
Run strings on it. The -n is for length:

<code>strings -n 7</code>

Extract files with Binwalk:

<code>binwalk -Me image.jpg</code>
