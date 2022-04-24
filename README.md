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

**Summary:** Briefly in your own words, what does dionaea do?

<img src="dionaea-honeypot.gif">

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?

*Be sure to upload session.json directly to this GitHub repo/branch in order to get full credit.*


