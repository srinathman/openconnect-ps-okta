# openconnect-ps-okta #

This script is based on https://github.com/zdave/openconnect-gp-okta but adapted to connect to Pulse Connect Secure SSLVPN.
You will need sudo/privileged access for openconnect.

Ex: sudo ./openconnect-ps-okta --username [username] [vpn_gateway]


### Known issues: ###


### Openconnect related issues: ###

- I'm using `--protocol=nc` since `--protocol=pulse` doesn't work for me.
- "ESP detected dead peer" error occurs often, which forces you to stop and reconnect. 


