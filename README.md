# grafana_installer
For Redhat based Operating systems only Ex: Redhat, RHEL, CentOS, Rocky, Fedora.
This script will download the Grafana GPG key, adds the repo to Yum and triggers the installation.

#### Installation Instructions
'''
cd /tmp
wget https://github.com/dl-romero/grafana_installer/archive/refs/heads/main.zip
unzip grafana_installer-main.zip
cd grafana_installer-main
sudo chmod 777 install_grafana.sh
sudo ./install_grafana.sh
'''
