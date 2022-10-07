# carridor_thm
tryhackme room carridor exploit script

so this is a easy room 

manual exploit :- 

1. nmap the ip 
2. port 80 is open so open in firefox or which you fav 
3. then check the source code you got a md5 hashs
4. decode the md5 hashes it's make you sens
5. so in thm room description we saw that it's a IDOR base 
6. 0 make this as a md5 hash and open this url in browser
7. then you got a flag 


so another way i writed a script to automate the process so run then code then you got a flag


<ocde>
  git clone https://github.com/Voilater/carridor_thm
  cd carridor_thm
  chmod 777 exploit.py
  ./exploit.py  
</code>
