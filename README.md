*INSTALL& CONFIGURE 🕷️SPIDERFOOT 4.0.0 ON KALI LINUX
🔗www.spiderfoot.net
https://github.com/smicallef/spiderfoot
https://www.youtube.com/watch?v=k7j_BerpkHE
🕷️ What is SpiderFoot
An automated OSINT tool that scans hundreds of data sources (domains, emails, usernames, IPs) and shows results in a web interface.
✅ Method 1 (Recommended): Install from Kali repo
Kali already includes SpiderFoot, so this is the easiest:
sudo apt update sudo apt install spiderfoot
▶️ Run it:
spiderfoot -l 127.0.0.1:5001
Then open your browser:
http://127.0.0.1:5001
🔧 Method 2: Install latest version from GitHub
Use this if you want the newest features.
Install dependencies
sudo apt updatesudo apt install git python3 python3-pip python3-venv -y
Clone repo
git clone https://github.com/smicallef/spiderfoot.gitcd spiderfoot
Create virtual environment (important)
python3 -m venv venvsource venv/bin/activate
Install requirements
pip install -r requirements.txt
Run SpiderFoot
python3 sf.py -l 127.0.0.1:5001
🌐 Access the interface
‼️Open browser → through Firefox icon in Kali Linux
6. http://127.0.0.1:5001
