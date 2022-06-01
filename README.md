# What does systemd provide?

- An init system
- System services
- logind
- A tool to manage system services and the system state (`systemctl`)
- A tool to generate zram images (`zram-generator`)
- A tool to enroll luks keys to TPM (`systemd-cryptenroll`)
- Temporary directories for programs (`systemd-tmpfiles`)
- Networking support (`systemd-networkd`)
- DNS resolving (`systemd-resolvd`)
- NTP sync (`timedatectl`)
- Bootloader (`systemd-boot`, `bootctl`)
- Out-of-memory daemon (`systemd-oomd`)
- Journal daemon (`journald`, `journalctl`)
- Boot time analyzer (`systemd-analyze`)
- Containers (`systemd-nspawn`)
- ***And many more***
