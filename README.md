# dingo
A DNS client (stub resolver) implemented in Go for the [Google
DNS-over-HTTPS](https://developers.google.com/speed/public-dns/docs/dns-over-https).
It effectively encrypts all your DNS traffic. It also supports
[OpenResolve](https://www.openresolve.com/) by OpenDNS.

### April 18, 2018
As of today, the original `dingo` does not support Cloudflare's 1.1.1.1 DNS over HTTPS servers.  
I figured I would extend `dingo` to support it, and started work. But found out that [this](https://github.com/m13253/dns-over-https), exists. Currently, looking into its code base.
