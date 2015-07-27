
*Initial Notes*
After spending months watching over the Kali Nethunter updates, I finally bought a Nexus 5.  The phone was originally on the Android M but the existing Nethunter versions for Nexus 5 support KitKat and Lollipop. I opted for the Lollipop one.  

I personally can only make observations from my Nexus 5 phone which I bought specifically for Kali Nethunter.  Obviously there are limitations between Nexus 5 and the newer versions as well as the tablet versions.

Once installed and once you are on Nethunter you will notice that there are already tools, services and options available. The following below were via the terminal option. 

I have some other things I want to try out as well, may write it here.

**Links**
Kali Linux Nethunter Downloads page https://www.offensive-security.com/kali-linux-nethunter-download/

---

**Radare2**
* Use git clone (https://github.com/radare/radare2) instead of apt-get
* Try out the UI layout r2 -A -c=H /bin/ls then http://locahost:9090 (via @maijin212)

---

**Exploit Database/Searchsploit**
* Add exloitdb/sploitsearch via git clone (https://github.com/offensive-security/exploit-database) not apt-get.

---

**List of tools not mentioned in Nethunter menu**
Based from http://tools.kali.org/tools-listing - there are also a few more but took them out due to a few issues usually to do with the display.

Information Gathering
* nmap
* sslstrip 

Vulnerability analysis
* sqlmap

Wireless attacks
* aircrack-ng
* asleap
* giskmet
* mdk3
* pixiewps
* reaver

Maintaining access
* dbd
