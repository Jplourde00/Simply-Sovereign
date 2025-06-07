# Security Policy

We take transparency seriously. Every node we deliver is based on verifiable open-source software.

## 🔐 No Backdoors Policy

- We never include closed-source software or tracking scripts
- We don’t modify Bitcoin Knots or the operating system beyond official installation instructions
- SSH is enabled for **your** access, not ours
- There are no phone-home features, updaters, or telemetry

## 🔎 How to Verify Your Node

If you received a flashed SD card or full node:

1. Mount the card or SSD on a computer
2. Verify installed packages: `dpkg --get-selections`
3. Inspect running services: `systemctl list-unit-files`
4. Compare binaries using `sha256sum` and official releases

You are encouraged to inspect and rebuild the node yourself.

## 📬 Reporting Issues

If you find a security issue or have concerns, please [open an issue](https://github.com/Jplourde00/Simply-Sovereign/issues) or contact us via email:  
`simplysovereign@protonmail.com`

We’re happy to work with you to fix any problems transparently.

---

Built by Bitcoiners, for Bitcoiners.
