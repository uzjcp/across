## Across the Great Wall we can reach every corner in the world

## wireguard.sh

- Description: This is a shell script for configure and start WireGuard VPN server.
- Intro: https://teddysun.com/554.html

## bbr.sh

- Description: Auto install latest kernel for TCP BBR
- Intro: https://teddysun.com/489.html
- 使用root用户登录，运行以下命令：

wget --no-check-certificate -O /opt/bbr.sh https://github.com/teddysun/across/raw/master/bbr.sh
chmod 755 /opt/bbr.sh
/opt/bbr.sh
安装完成后，脚本会提示需要重启 VPS，输入 y 并回车后重启。

## kms.sh

- Description: Auto install KMS Server
- Intro: https://teddysun.com/530.html
- **KMS Server Docker Image**: https://hub.docker.com/r/teddysun/kms

## bench.sh

- Description: Auto test I/O & upload & download speed script
- Intro: https://teddysun.com/444.html
- 使用方法：
命令1：

wget -qO- bench.sh | bash
或者

curl -Lso- bench.sh | bash
命令2：

wget -qO- 86.re/bench.sh | bash
或者

curl -so- 86.re/bench.sh | bash
备注：
bench.sh 既是脚本名，同时又是域名。所以不要怀疑我写错了或者你看错了。

## backup.sh

- You must modify the config before run it
- Backup MySQL or MariaDB datebases, files and directories
- Backup file is encrypted with AES256-cbc with SHA1 message-digest (Depends on `openssl` command) (option)
- Auto transfer backup file to Google Drive (Depends on [`rclone`](https://teddysun.com/469.html) command) (option)
- Auto transfer backup file to FTP server (Depends on `ftp` command) (option)
- Auto delete remote file from Google Drive or FTP server (option)
- Intro: https://teddysun.com/469.html

## ftp_upload.sh

- You must modify the config before run it
- Upload file(s) to FTP server
- Intro: https://teddysun.com/484.html

## unixbench.sh

- Description: Auto install unixbench and test script
- Intro: https://teddysun.com/245.html

## l2tp.sh(Deprecated, DO NOT USE)

## pptp.sh(Deprecated, DO NOT USE)

Copyright (C) 2013-2021 Teddysun <i@teddysun.com>
