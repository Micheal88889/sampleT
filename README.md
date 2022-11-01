pre-setting







  ```html
  apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
  ```



  ```html
  apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && sleep 2 && reboot
  ```
 
## INSTALLATION SCRIPT

  ```html
  sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/Micheal88889/sampleT/main/setup2.sh && chmod +x setup2.sh && sed -i -e 's/\r$//' setup2.sh && screen -S setup2 ./setup2.sh
  ```
 
 ## Preseting
 ```html
  sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/Micheal88889/new-preset/main/setup2.sh && chmod +x setup2.sh && sed -i -e 's/\r$//' setup2.sh && screen -S setup2 ./setup2.sh
  ```
  
comingsoonFreeAutoscripts
