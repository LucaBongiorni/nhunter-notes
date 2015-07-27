
**Set up**
Nexus 5 originally on M. Using 'hammerhead' on Lollipop.

---

*Radare2*

* Added r2 on Nethunter (Nexus 5, on Lollipop).  
* Use git clone instead of apt-get
* Try out the UI layout r2 -A -c=H /bin/ls then http://locahost:9090 (via @maijin212)

---

* No OpenVPN on Lollipop. Do policy-based routing. Source.

---

* Add exloitdb/sploitsearch via git not apt-get. Can't recall if already on Nethunter.

---

*List of tools ( http://tools.kali.org/tools-listing) already available but not mentioned in menu*

Information Gathering
* nmap
* sslstrip 

Vulnerability analysis
* sqlmap

Wireless attacks
* aircrack-ng
* asleap
* giskmet
* kismet (some issues, do -h to see options)
* mdk3
* pixiewps
* reaver

Maintaining access
* dbd

Sniffing and Spoofing
* sslsplit (message 'no proxyspec specified' so do -h to see options)
* wireshark (tries to run but has gtk-warning **: cannot open display: so do -h to see options)
