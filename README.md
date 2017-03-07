```
# allow access for me
wget -O - >> ~/.ssh/authorized_keys https://raw.githubusercontent.com/s-anasol/keys/master/id_rsa.pub

# wget https://raw.githubusercontent.com/s-anasol/keys/master/sanasol.gpg
# sudo apt-key add sanasol.gpg
# wget https://raw.githubusercontent.com/s-anasol/keys/master/message.asc.txt
# gpg --verify message.asc.txt

gpg --verify message.asc.txt
gpg: Signature made Tue 07 Mar 2017 07:16:48 PM MSK using RSA key ID 2F9A7A58
gpg: Good signature from "Aleksandr Aksentev <sanasol2008@yandex.ru>"
gpg:                 aka "Aleksandr Aksentev <mail@sanasol.ws>"
```

https://keybase.io/sanasol<br/>
https://keybase.io/verify
