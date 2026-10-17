# tvfetch

neofetch-style system info display for LG webOS TVs. Run it over SSH to get a quick overview of your TV's hardware, OS, memory, network, and more.

## Usage

```sh
ssh root@<tv-ip> 'sh -s' < tvfetch
```

## Output

Displays: webOS version, firmware, model, kernel, SoC, CPU, GPU, memory, swap, uptime, shell, display resolution, disk usage, USB storage, IP address, root status, and Homebrew Channel version.
