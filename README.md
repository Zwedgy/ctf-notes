# ctf-notes
Notes of CTF challenges

<h1>Linux and privesc</h1>

When having a limited shell you can try these following things:
1) Check if NetCat is installed
2) Try to get a shell using Python, PHP or othet languages
3) If SSH is installed try to add your key to authorized_keys

If you know an username, try to grep files containing it. 
<code>grep -Ril "username" / 2> /dev/null</code>
Sometimes you can find information to guess the password or even plaintext

