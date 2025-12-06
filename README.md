This file is for Raspberry Pi that runs Ubuntu Server to be configured to an XMRig machine

### This installed or configured

- Swappiness (Swap when RAM usage hits 90%)

- Log2Ram

- XMRig ([coin]:[address] haven't setted)

- Cockpit

### DO NOT just disconnect the monitor after dropping the script. There're some purple screens to deal with.

### Instruction:

#### First,

```shell
wget https://raw.githubusercontent.com/theArnoll/rpi-xmrig-setup/main/setup_miner.sh
```

or the short link version:

```shell
wget https://pse.is/rpi-xmrig-setup
```

#### Then,

```shell
chmod +x rpi-xmrig-setup
./rpi-xmrig-setup
```

#### After that,

Input your password

Make your choice in some purple screens

After displaying your IP address, you're free to go!

### Accessing you Pi

We installed `cockpit` in our Pi, so you can go to `http://[your_raspberry_pi_ip]:9090` to go to cockpit, see what's going on in your Pi and see the status, and run commands almost like you're using PuTTY in the Terminal of the page
