```
# allow access for me
wget -O - >> ~/.ssh/authorized_keys https://raw.githubusercontent.com/poiuty/keys/master/id_rsa.pub

# wget https://raw.githubusercontent.com/poiuty/keys/master/poiuty.gpg
# sudo apt-key add poiuty.gpg
# wget https://raw.githubusercontent.com/poiuty/keys/master/message.asc.txt
# gpg --verify message.asc.txt

gpg --verify message.asc.txt
gpg: Signature made Tue 24 Jan 2017 01:38:04 AM MSK using RSA key ID 0FCAD97E
gpg: Good signature from "poiuty <poiuty@lepus.su>"
```

https://keybase.io/poiuty<br/>
https://keybase.io/verify
