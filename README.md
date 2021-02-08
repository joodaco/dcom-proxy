# mixp-docs
Add a sysctl file in /etc/sysctl.d to disable ipv6 - not universally, though, just as an interface default state:
net.ipv6.conf.default.disable_ipv6=1
<br/>
curl -SL -o px-install.sh https://github.com/bocproxy/dcom-proxy/releases/download/1.0/px-install-arm64.sh
<br/>
UPDATE 1.2: curl -SL -o update.sh https://github.com/bocproxy/dcom-proxy/releases/download/1.0/px-update.sh && bash update.sh
<br/>
UPDATE 1.5: curl -SL -o update.sh https://github.com/bocproxy/dcom-proxy/releases/download/1.0/px-update-15.sh && bash update.sh
<br/>
UPDATE port 8888: curl -SL -o update-prt.sh https://github.com/bocproxy/dcom-proxy/releases/download/1.0/px-update-port.sh && bash update-prt.sh
