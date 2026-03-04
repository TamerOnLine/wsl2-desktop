## Quick Start

Install WSL and Ubuntu quickly:

``` powershell
wsl --install
```

Update the Ubuntu system:

``` bash
sudo apt update && sudo apt upgrade -y
```

Enable systemd support:

``` bash
sudo nano /etc/wsl.conf
```

Add the following configuration:

``` ini
[boot]
systemd=true
```

Restart WSL to apply the changes:

``` powershell
wsl --shutdown
```
