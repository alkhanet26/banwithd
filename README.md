# banwithd
Install banwithd untuk Router

Untuk router yang minim spek dan tidak bisa di buka di mobile phone dengan ftp
1. Copy dan Paste command dibawah ini
   ```
   wget --no-check-certificate "https://raw.githubusercontent.com/alkhanet26/banwithd/main/luci-app-bandwidthd_1-1_all.ipk" -O /tmp/luci-app-bandwidthd_1-1_all.ipk && cd /tmp && opkg update && opkg install --force-depends *.ipk
   ```
2. Tunggu sampai selesai
3. reboot router

# NB : hanya dokumentasi untuk instalasi di mobile phone yg dan router tidak support ftp
