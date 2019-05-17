# OSCP-training-stuff
https://gr0sabi.github.io/security/oscp-insights-best-practices-resources/#final-thoughts

0x06 — Resources

#All in one References
http://pwnwiki.io/#!index.md
https://jivoi.github.io/2015/07/01/pentest-tips-and-tricks/

#Great Reviews
http://www.abatchy.com/2017/03/how-to-prepare-for-pwkoscp-noob.html
https://www.securitysift.com/offsec-pwb-oscp/

#Enumeration Cheatsheet
https://highon.coffee/blog/nmap-cheat-sheet/
https://highon.coffee/blog/penetration-testing-tools-cheat-sheet/
http://www.0daysecurity.com/penetration-testing/enumeration.html

#Privilege Escalation Cheatsheet
https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/
https://github.com/rebootuser/LinEnum
https://www.securitysift.com/download/linuxprivchecker.py
https://github.com/PenturaLabs/Linux_Exploit_Suggester
https://pentest.blog/windows-privilege-escalation-methods-for-pentesters/
https://www.youtube.com/watch?v=kMG8IsCohHA
http://www.fuzzysecurity.com/tutorials/16.html
https://toshellandback.com/2015/11/24/ms-priv-esc/
https://github.com/51x/WHP
https://isc.sans.edu/diary/Windows+Command-Line+Kung+Fu+with+WMIC/1229

#Reverse Shell Cheatsheet
https://www.phillips321.co.uk/2012/02/05/reverse-shell-cheat-sheet/
https://highon.coffee/blog/reverse-shell-cheat-sheet/
http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet

#Get TTY shell
https://blog.ropnop.com/upgrading-simple-shells-to-fully-interactive-ttys/
https://netsec.ws/?p=337

#Buffer Overflow
https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/
http://netsec.ws/?p=180

#Msfvenom Cheatsheet
http://security-geek.in/2016/09/07/msfvenom-cheat-sheet/

#Porting Metasploit Exploits
https://netsec.ws/?p=262

#Port forwarding & Pivoting
https://artkond.com/2017/03/23/pivoting-guide/
http://atropineal.com/2016/11/18/pivoting-with-ssh-and-proxychains/
http://netsec.ws/?p=278

#Client-Side Attacks
https://www.offensive-security.com/metasploit-unleashed/client-side-exploits/

#Practice Points
https://www.hackthebox.eu/
https://www.vulnhub.com/
https://exploit-exercises.com/
https://shellterlabs.com/en/


When accessing the system it was either ran as system or if it wasn't I then went through the G0tm1lk guide or the fuzzy guide. G01m1lk it seemed I always found a file with the wrong permissions (like /etc/passwd) or I'd find a SUID bit set for pkexec, or a /usr/local/ file in there which I'd never seen before and that always ended up being the flaw. If that wasn't one of them I'd look at ps aux and check for programs running higher PID numbers that didn't have [ ] around them and look for things I never saw on the other boxes, check their version then check searchsploit for it.



For Windows it was a system exploit, or a flaw I found from accesschk.exe, or it just put me in as root access.
