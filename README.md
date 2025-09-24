# F5-SSL.Provider-Automation
F5 BIG-IP automation to extract the PreMasterSecret key through BASH Scripting
You need to run the provided script on the BIG-IP device to extract the PMS from the packet capture
# Prerequisites
  - You should enable TCPDUMP SSLPROVIDER in the TMSH
  - Take the capture with "**--f5 ssl**"
# How to run the script 
You'll need to copy the script provided in the Extract_PMS repository into the BIG-IP device under /var/tmp directory.
