# Level 0 ➡️ Level 1
## command
```sh
cat readme
```

> password: `NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL`

&nbsp;
# Level 1 ➡️ Level 2
## command
```sh
cat ./-
```

> password: `rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi`

&nbsp;
# Level 2 ➡️ Level 3
## command
```sh
cat "spaces in this filename"
```

> password: `aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG`

&nbsp;
# Level 3 ➡️ Level 4
## command
```sh
cd inhere
ls -al
cat .hidden
```

> password: `2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe`

&nbsp;
# Level 4 ➡️ Level 5
## command
```sh
cd inhere
ls -al
file ./*
cat ./-file07
```

> password: `lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR`

&nbsp;
# Level 5 ➡️ Level 6
## command
```sh
find -type f -size 1033c ! -executable -exec file {} + | grep "ASCII text" | cut -d ":" -f 1 | xargs cat
```

> password: `P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU`

&nbsp;
# Level 6 ➡️ Level 7
## command
```sh
find / -type f -user bandit7 -group bandit6 -size 33c 2> /dev/null 
```

> password: `z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S`

&nbsp;
# Level 7 ➡️ Level 8
## command
```sh
cat data.txt | grep 'millionth'
```

> password: `TESKZC0XvTetK0S9xNwm25STk5iWrBvP`

&nbsp;
# Level 8 ➡️ Level 9
## command
```sh
cat data.txt | sort | uniq -u
```

> password: `EN632PlfYiZbn3PhVK3XOGSlNInNE00t`

&nbsp;
# Level 9 ➡️ Level 10
## command
```sh
strings data.txt | ===
```

> password: `G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s`

&nbsp;
# Level 10 ➡️ Level 11
## command
```sh
base64 -d data.txt
```

> password: `6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM`

&nbsp;
# Level 11 ➡️ Level 12
## command
```sh
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```

> password: `JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv`

&nbsp;
# Level 12 ➡️ Level 13
## command
```sh
cd /tmp
mktemp -d
cd /tmp/tmp.NulV2TS5M3
cp ~/data.txt .
mv data.tx hex_data
cat hex_data | head
xxd -r hex_date comp_data
cat comp_data | head
mv comp_data comp_data.gz
gzip -d comp_data.gz
xxd comp_data
mv comp_data comp_data.bz2
bzip2 -d comp_data.bz2
xxd comp_data
mv comp_data comp_data.gz
gzip -d comp_data.gz
xxd comp_data | head
mv comp_data comp_data.tar
tar -xf comp_data.tar
ls
tar -xf data5.bin
xxd data6.bin
bzip2 -d data6.bin
ls
tar -xf data6.bin.out
ls
xxd data8.bin
mv data8.bin data8.gz
gzip -d data8.gz
ls
cat data8
```

> password: `wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw`

&nbsp;
# Level 13 ➡️ Level 14
## command
```sh
scp -P 2220 bandit13@bandit.labs.overthewire.org:sshkey.private .

chmod 700 sshkey.private

ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220
```

> password: `fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq`

&nbsp;
# Level 14 ➡️ Level 15
## command
```sh
cat /etc/bandit_pass/bandit14
```

> password: `jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt`

&nbsp;
# Level 15 ➡️ Level 16
## command
```sh
openssl s_client localhost:30001 -quiet < /etc/bandit_pass/bandit15
```

> password: `JQttfApK4SeyHwDlI9SXGR50qclOAil1`

&nbsp;
# Level 16 ➡️ Level 17
## command
```sh
nmap -sV localhost -p 31000-32000
cat /etc/bandit_pass/bandit16
    JQttfApK4SeyHwDlI9SXGR50qclOAil1

openssl s_client localhost:31790

ssh -i sshkey.private bandit17@bandit.labs.overthewire.org -p 2220
```

## sshkey.private

&nbsp;
# Level 17 ➡️ Level 18
## command
```sh
di>#ff password : old pa rd :s.ne
 ``

> password: `hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg`

&nbsp;
# Level 18 ➡️ Level 19
## command
```sh
ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme
```

> password: `awhqfNnAbc1naukrpqDYcF95h7HoMTrC`

&nbsp;
# Level 19 ➡️ Level 20
## command
```sh
ls -al
./bandit20-do cat /etc/bandit_pass/bandit20
```

> password: `VxCazJaVykI6W36BkBU0mJTCM8rR95XT`

&nbsp;
# Level 20 ➡️ Level 21
## command
```sh
./suconnect 1234
```

> password: `NvEJF7oVjkddltPSrdKEFOllh9V1IBcq`

&nbsp;
# Level 21 ➡️ Level 22
## command
```sh
ls -al /etc/cron.d
cat /usr/bin/cronjob_bandit22.sh
cat /etc/bandit_pass/bandit22
cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
```

> password: `WdDozAdTM2z9DiFEQ2mGlwngMfj4EZff`

&nbsp;
# Level 22 ➡️ Level 23
## command
```sh
ls -al /etc/cron.d
cat /etc/cron.d/cronjob_bandit23
cat /usr/bin/cronjob_bandit23.sh
echo I am user bandit23 | md5sum | cut -d ' ' -f 1
cat /tmp/8ca319486bfbbc3663ea0fbe81326349
```

> password: `QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G`

&nbsp;
# Level 23 ➡️ Level 24
## command
```sh
```
> password : 