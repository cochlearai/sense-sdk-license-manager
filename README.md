# sense-sdk-license-manager
This file is how to install and remove Sense SDK license manager. The version is aksusbd-9.12.1 for linux OS.

## How to install
```bash
sudo ./dinst
```

## How to uninstall
Before uninstalling, you should check whether other applications use this service. It may effect other applications behavior.
The service can find process named **hasplmd**.

- check license manager process
```bash
ps -aux | grep hasplmd
```

- uninstallation
```bash
sudo ./dunst
```