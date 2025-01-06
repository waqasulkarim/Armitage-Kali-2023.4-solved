# Armitage-Kali-2023.4-solved
Error: **Unable to locate package armitage**
Armitage is a front-end GUI of Metasploit. It is good for new learners of Cybersecurity & Ethical Hacking.
It is a common issue that while we try to install armitage on Kali Linux then we get the error "Unable to locate package armitage". So, in order to solve this issue, we have to follow below steps:

**Step1.** Open /etc/apt/sources.list in any text editor (like mousepad) as a root user & add the following lines to the list:
_deb http://http.kali.org/kali kali main non-free contrib_
_deb-src http://http.kali.org/kali kali main non-free contrib_

**Step2.** Save the file. Open the terminal & run below commands:
_sudo apt-get update_
_sudo apt-get install armitage_
_sudo service postgresql start_
_sudo msfdb init_
_armitage_
_Y_

Now armitage has been installed & is ready to be used.
Feel free to contact me if you face any issues waqasulkarim@gmail.com
