# Data import tool for Firefly 3

Just a simple data import tool for Firefly 3 to cover my needs.

### **Requirements**

* Python version 3
* Firefly 3 instance running
* Python tool dependencies

```
pip install -r requirements.txt
```

### **Setup**

1. **Firefly Personal Access Token**

Generate a personal access token on Firefly admin interface and save it in .token file.


2. **Server configuration**

Edit the config.ini file and change the server settings (host, protocol, port).

### **Usage**

Copy your data xlsx files into data directory.
Then, navigate to data-import directory in the terminal and run the command

```
python ca-import.py
```