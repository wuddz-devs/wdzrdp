<h1 align="center">WDZRDP</h1>

## Description
 - WDZRDP Is A LightWeight, Memory-Efficient & Ultra Fast Performing Cli Windows Remote Desktop Service Bruteforce App.
 - Scan Using Password Or Ntlm Hash (32 characters)
 - Scan An Entire Network (e.g 1.1.1.0/24)
 - Check If Credential(s) Are valid (e.g "server:port@domain\\username;password")
 - Scan Using "user;password" | "user;ntlm_hash" combo(s) (e.g "admin;admin123", "dev;ab2d4912fc7132fb7165d79cffbc5db5")
 - Password Generator (e.g all perms, all upper & lower, all no repeat chars)
 - Save Network Cidr Lists For All Or Specified Datacenter Or Country (2 letter international country code)
 - 5x Or More Faster Than Anything I've Seen Out Here
 - No Viruses, Can Be Run Using Guest Or Admin Account On Any Windows OS.
 - Encrypt/Decrypt Hits With A Password (Can Only Be Decrypted With This Program).
 - Clean/Delete All Input Files (Total Stealth)
 - Scan With 1000 Threads On A Pc/Server (Specs: 2 cores; 4 logical processors; 4 gb Memory)  Without Breaking A Sweat Pun Intended 🔥.
 - Light As A Feather At 16.4 MB You Can't Find That Anywhere.
 - Made By A Pentester For Pentesting &Or Network Administrator Purposes.
 - Hit Me Up & Let Me Know, Serious Inquiries Only.

## Prerequisites
 - Can Be Distributed As An Executable For Windows/Linux Or As A Package To Install With Python On The System.

### Datacenters
```
all
akamai
alibaba
amazon
aws_cloudfront
aws_ec2
aws_s3
bigo
bing
cloudflare
digitalocean
facebook
fastly
github
google
google_cloud
linode
microsoft
netflix
openai
oracle
telegram
twitter
zenlayer
zoom
```


### Usage
Scan Servers In 's.txt' For Valid User 'admin' & Password 'admin@123' Using 1000 threads
```
rdp.exe -s s.txt -u admin -p admin@123 -t 1000
```
Scan Servers In 's.txt' For Valid User 'admin' & NTLM_Hash '0bae622ab68138248c66d66882818dfd'
```
rdp.exe -s s.txt -u u.txt -hs 0bae622ab68138248c66d66882818dfd
```
Scan Servers In 's.txt' For Valid 'User;Password' Combos In 'combo.txt' & Type Password To Encrypt Valid Creds.
```
rdp.exe -s s.txt -up combo.txt -e
```
Scan Servers In 's.txt' For Valid 'User;NTLM_Hash' Combos In 'combo.txt' With Connection Timeout 5 Seconds
```
rdp.exe -s s.txt -up combo.txt -uh -to 5
```
Scan Servers In Network 1.1.1.0/24 For Valid User 'user1' & Generated Password(s), Save Passwords To 'pwd.txt'
```
rdp.exe -nw 1.1.1.0/24 -u user1 -ps user -pt nrc -pe @123 -po pwd.txt
```
Save All CIDR Networks For USA In us.txt
```
rdp.exe -nc US -no us.txt
```
Save All CIDR Networks For microsoft Datacenter In ms.txt
```
rdp.exe -nc microsoft -no ms.txt
```
Save All CIDR Networks For All Datacenters In datacenters.txt
```
rdp.exe -nc all -no datacenters.txt
```
Scan Servers In 's.txt' For Users In 'u.txt' & Passwords In 'p.txt' & Stealthily Delete All 3 Input Files.
```
rdp.exe -s s.txt -u u.txt -p p.txt -clean
```
While Scanning Press Ctrl+C ("...Closing Running Tasks Hang On..." Will Print In Console) To Gracefully Clean Up Threads And Close App.

## Illustration Video:
https://mega.nz/file/FTERmaKC#8h5jO_ThFhLZ9JoWgC347an2OfoxJDJZNvnSZojd32Y

## Contact Info:
 - Email:     wuddz_devs@protonmail.com
 - Github:    https://github.com/wuddz-devs
 - Telegram:  https://t.me/wuddz_devs
 - Youtube:   https://youtube.com/@wuddz-devs
 - Reddit:    https://reddit.com/user/wuddz-devs

### Buy Me A Coffee!!
![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/eth.png)
 - ERC20:    0xbF4d5309Bc633d95B6a8fe60E6AF490F11ed2Dd1

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/btc.png)
 - BTC:      bc1qa7ssx0e4l6lytqawrnceu6hf5990x4r2uwuead

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/ltc.png)
 - LTC:      LdbcFiQVUMTfc9eJdc5Gw2nZgyo6WjKCj7

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/doge.png)
 - DOGE:     DFwLwtcam7n2JreSpq1r2rtkA48Vos5Hgm

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/tron.png)
 - TRON:     TY6e3dWGpqyn2wUgnA5q63c88PJzfDmQAD

#### Enjoy my awesome creativity!!
#### Peace & Love Always!!
