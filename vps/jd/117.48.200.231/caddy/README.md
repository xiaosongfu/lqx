## caddy

#### 安装

```
[root@JD ~]# curl https://getcaddy.com | bash -s personal
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  7380  100  7380    0     0   5518      0  0:00:01  0:00:01 --:--:--  5519
Downloading Caddy for linux/amd64 (personal license)...
Download verification OK
Extracting...
Putting caddy in /usr/local/bin (may require password)
Caddy 0.11.0 (non-commercial use only)
Successfully installed
[root@JD github-trending]#
```

#### 启动命令

```
nohup caddy -conf /root/files/github.com/lqx/vps/jd/117.48.200.231/caddy/Caddyfile &
```