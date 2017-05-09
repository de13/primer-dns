# primer-dns
Rancher Primer Lab Dnsmasq 

# Usage
dnsmasq requires NET_ADMIN capabilities to run correctly.
Use docker run -d --restart=unless-stopped -p 53:53/tcp -p 53:53/udp --cap-add=NET_ADMIN de13/primer-dns
