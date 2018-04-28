# system-config
Related to setup and configuration of my workstations and laptops

This is mentioned and referenced in my [macOS 10.13 High Sierra Mostly-Automated Setup](https://gist.github.com/kevinelliott/39c453d305e40c8f157452aee87fa9d8) Gist where I detail out how I automate the fresh install of macOS and my whole development environment with ease.



```
pecl install imagick
pecl install curl
pecl install ssh2
```


```
Host {name}
  HostName {hostname}
  PreferredAuthentications publickey
  User {username}
  IdentityFile ~/.ssh/id_rsa_{xxx}
```