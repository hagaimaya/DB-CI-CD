# DB-CI-CD

Runner Installations:

install the following on the runner:
https://docs.microsoft.com/en-us/sql/tools/sqlpackage/sqlpackage-download?view=sql-server-ver16#linux-net-core

```bash
cd ~
mkdir sqlpackage
sudo apt install unzip
cd /tmp
wget https://download.microsoft.com/download/f/0/9/f091c731-45be-48fa-ae84-bc28388e3ef8/sqlpackag
e-linux-x64-en-16.0.6161.0.zip
unzip /tmp/sqlpackage-linux-x64-en-16.0.6161.0.zip -d ~/sqlpackage 
echo "export PATH=\"\$PATH:$HOME/sqlpackage\"" >> ~/.bashrc
chmod a+x ~/sqlpackage/sqlpackage
source ~/.bashrc
```
