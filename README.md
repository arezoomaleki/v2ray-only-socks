# v2ray-only-socks
bash script to create local socks using v2ray

you need to have a upstram server outside of the country with v2ray-upstream-server configured on it

this bash file installs docker and docker compose on your ubuntu server and then a local socks server connected to a upstram server

you can use this socks in /etc/systemd/system/docker.service.d/proxy.conf or ls -l /etc/apt/apt.conf.d/proxy.conf or etc
