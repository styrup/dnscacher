# Caching DNS server
For at fjerne dns port i Ubunut 20.04
sudo nano /etc/systemd/resolved.conf
DNS=DNS server (IP)
DNSStubListener=no
sudo ln -sf /run/systemd/resolve/resolv.conf /etc/resolv.conf
reboot
