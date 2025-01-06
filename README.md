# Armitage-Kali-2023.4-solved
Error: **Unable to locate package armitage**
Armitage is a front-end GUI of Metasploit. It is good for new learners of Cybersecurity & Ethical Hacking.
It is a common issue that while we try to install armitage on Kali Linux then we get the error "Unable to locate package armitage". So, in order to solve this issue, we have to follow below steps:

**Step1.** Open /etc/apt/sources.list in any text editor (like mousepad) as a root user & add the following lines to the list:

deb http://http.kali.org/kali kali main non-free contrib

deb-src http://http.kali.org/kali kali main non-free contrib


**Step2.** Save the file. Open the terminal & run below commands:

sudo apt-get update

sudo apt-get install armitage

sudo service postgresql start

sudo msfdb init

armitage

Y

Now armitage has been installed & is ready to be used.
Feel free to contact me if you face any issues waqasulkarim@gmail.com
