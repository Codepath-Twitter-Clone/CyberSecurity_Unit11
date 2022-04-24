# Honeypot Assignment

**Time spent:** **2** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. 


### MHN-Admin Deployment (Required)

**Summary:** Use GCP SDK. Windows PowerShell Commands shown in the text editor in gif.
mhm-admin application installation:
```
cd /opt/
sudo git clone https://github.com/pwnlandia/mhn.git
cd mhn/
sudo sed -i 's/Flask-SQLAlchemy==2.3.2/Flask-SQLAlchemy==2.5.1/g' server/requirements.txt
sudo ./install.sh
```
<img src="https://github.com/Codepath-Twitter-Clone/CyberSecurity_Unit11/blob/main/unit11_1.gif">

### Dionaea Honeypot Deployment (Required)

**Summary:** dionaea intention is to trap malware exploiting vulnerabilities exposed by services offered to a network, finally gaining a copy of the malware.
Deploy dionaea in cloud node.
```
wget "http://34.75.149.158/api/script/?text=true&script_id=2" -O deploy.sh && sudo bash deploy.sh http://34.75.149.158 JrOA7h74
```

<img src="https://github.com/Codepath-Twitter-Clone/CyberSecurity_Unit11/blob/main/unit11_2.gif">

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses?
```
| ms-sql-info: 
|   35.243.241.174:1433: 
|     Version: 
|       name: Microsoft SQL Server 2000 SP1+
|       number: 8.00.528.00
|       Product: Microsoft SQL Server 2000
|       Service pack level: SP1
|       Post-SP patches applied: true
|_    TCP port: 1433
```
What information does the exported JSON file record?
The results of attack samples, including but not limited to DB scan, OS scan, traceroute, NAS info and etc.


