# Alias-for-kali-linux

The alias's will provide ease for doing stuff in  kali linux suck as: starting a vpn via a alias; python webserver; an alias that pulls your tun0 ip address.


`alias vpnip='ifconfig tun0 | grep -i netmask | cut -d " " -f10'
alias killvpn='killall -9 openvpn'
alias thmvpn='/dirctory/of/vpn/file'
alias htbvpn='/dirctory/of/vpn/file'
alias websrv='python3 -m http.server 3333'`

To add you have to `nano .bashrc` and put it under the alias's at the bottom of the file and save the file and restart your VM and done.
