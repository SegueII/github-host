# github-host
Available IP addresses for GitHub

## Add hosts

Edit `hosts` (macOS)

```bash
sudo vim /etc/hosts
```

Add these content

```bash
192.30.255.112  github.com
192.30.253.112  github.com
140.82.114.4    github.com
192.30.255.112  www.github.com
140.82.113.3    www.github.com
192.30.255.113  www.github.com

185.199.110.154 github.githubassets.com
185.199.111.154 github.githubassets.com
185.199.108.154 github.githubassets.com

151.101.185.194 github.global.ssl.fastly.net
151.101.13.194  github.global.ssl.fastly.net
199.232.5.194   github.global.ssl.fastly.net

199.232.28.133 raw.githubusercontent.com
199.232.68.133 raw.githubusercontent.com
199.232.28.133 gist.githubusercontent.com
199.232.28.133 cloud.githubusercontent.com
199.232.28.133 camo.githubusercontent.com
199.232.28.133 avatars0.githubusercontent.com
199.232.28.133 avatars1.githubusercontent.com
199.232.28.133 avatars2.githubusercontent.com
199.232.28.133 avatars3.githubusercontent.com
199.232.28.133 avatars4.githubusercontent.com
199.232.28.133 avatars5.githubusercontent.com
199.232.28.133 avatars6.githubusercontent.com
199.232.28.133 avatars7.githubusercontent.com
199.232.28.133 avatars8.githubusercontent.com
199.232.28.133 user-images.githubusercontent.com

52.217.37.46    s3.amazonaws.com
52.216.106.45   s3.amazonaws.com
52.216.16.235   s3.amazonaws.com
52.216.147.13   s3.amazonaws.com

52.216.138.171  github-production-release-asset-2e65be.s3.amazonaws.com
52.216.171.35   github-production-release-asset-2e65be.s3.amazonaws.com
52.217.1.140    github-production-release-asset-2e65be.s3.amazonaws.com

185.199.108.153 documentcloud.github.com

185.199.108.153 help.github.com

140.82.113.9    nodeload.github.com
140.82.114.9    nodeload.github.com
192.30.253.120  nodeload.github.com
192.30.253.121  nodeload.github.com
207.97.227.252  nodeload.github.com

192.30.253.118  gist.github.com

185.199.111.153 assets-cdn.github.com
185.199.108.153 assets-cdn.github.com
185.199.109.153 assets-cdn.github.com
185.199.110.153 assets-cdn.github.com

151.101.108.133 raw.github.com
199.232.4.133   raw.github.com

192.30.253.168  training.github.com

140.82.113.6    api.github.com
```

Refresh `DNS`

```bash
dscacheutil -flushcache
```

---

## Find available IP address

- **IP Lookup:** <https://www.ipaddress.com/ip-lookup>
- **DNS Search:** <http://tool.chinaz.com/dns/>
