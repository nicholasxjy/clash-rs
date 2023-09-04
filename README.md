# clash-rs
Just a toy for fun, don't use please :+|

TODOs
- [ ] inbounds
    - [x] http
    - [x] socks5
    - [x] mix port
    - [ ] tproxy
    - [x] authentication
- [x] proxy rules
    - [x] groups
        - [x] relay
        - [x] select
        - [x] urltest
        - [x] loadbalance
        - [x] fallback
    - [x] proxies
        - [x] ss
        - [x] socks5
            - [ ] with TLS
        - [x] vmess
            - [x] ws
            - [x] aead and non-aead
        - [ ] trojan
        - [ ] ...
        - [ ] transports
            - [ ] grpc
            - [ ] tls
            - [ ] http
- [x] providers
    - [x] file
    - [x] remote
- [ ] rules
    - [x] domain_keyword
    - [x] domain_suffix
    - [x] geoip
    - [x] ipcidr
    - [x] port
    - [ ] process
    - [ ] ruleset
- [ ] DNS
    - [x] clients
        - [x] DoH
        - [x] DoT
        - [x] UDP/TCP
        - [x] dhcp
    - [ ] server
        - [ ] fake ip persistence
    - [ ] HTTP query
- [ ] API
    - [x] proxies
    - [x] configs
    - [x] logs (TODO: log format)
    - [x] providers
    - [x] rules
    - [ ] connections
    - [ ] dns
- [x] linux support(untested)
- [ ] fwmark and bind interface impl
- [ ] profile store
- [ ] what else?
