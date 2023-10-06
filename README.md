

### Installation
Install the app on the server
```sh
user@domain:~# git clone https://github.com/rodrise1337/bruter.git
user@domain:~# cd ./bruter/
user@domain:~# gcc ./*.c -o telnet-bruter -pthread -std=c99 -fcommon
user@domain:~# zmap -p 23 | ./telnet-bruter <threads>
```

