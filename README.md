# test rust via EVCR Kernel in jupytor notebook of ubuntu

-- ubuntu version

```bash
hostnamectl
Static hostname: trapapa-ThinkPad-T430
Icon name: computer-laptop
Chassis: laptop
Machine ID: xxx
Boot ID: xxx
Operating System: Ubuntu 22.04.2 LTS
Kernel: Linux 5.19.0-50-generic
Architecture: x86-64
Hardware Vendor: Lenovo
Hardware Model: ThinkPad T430

inxi
CPU: dual core Intel Core i5-3320M (-MT MCP-)
speed/min/max: 1197/1200/3300 MHz Kernel: 5.19.0-50-generic x86_64 Up: 1h 24m
Mem: 10675.7/15671.8 MiB (68.1%) Storage: 596.18 GiB (17.8% used) Procs: 339
Shell: Bash inxi: 3.3.13
```

## check rust is installed (31.07.2023 on ubuntu)

```rustup check
output:
stable-x86_64-unknown-linux-gnu - Up to date : 1.71.0 (8ede3aae2 2023-07-12)
nightly-x86_64-unknown-linux-gnu - Update available : 1.73.0-nightly (0e8e857b1 2023-07-16) -> 1.73.0-nightly (32303b219 2023-07-29)
rustup - Up to date : 1.26.0
```

## [setup see SETUP.md](./SETUP.md)

EOF
