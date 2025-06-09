# Simply Sovereign

**Pre-configured Bitcoin nodes for everyday sovereignty.**  
Helping Bitcoiners run their own full node with ease — no spyware, no backdoors, just freedom.

---

## 🔐 What This Is

Simply Sovereign helps non-technical Bitcoiners start their own node.  
We provide pre-flashed, ready-to-use SD cards and plug-and-play kits for Raspberry Pi using **open source Bitcoin Knots**.

You can trust it — because it's all open source, and we show every step.

---

## 🛠️ How It's Built

No funny business. Here's what we do:
1. [Download Umbrel OS from the official site](https://umbrel.com)
2. Flash it with [Balena Etcher](https://etcher.io) (or `dd`)
3. Install [Bitcoin Knots](https://bitcoinknots.org/) using official builds
4. Set up the SSD for blockchain data
5. Enable SSH for remote control
6. No custom code. No auto-updaters. No firewall changes.

We *do not*:
- Include any private software
- Phone home to any server
- Inject tracking or backdoors

You are encouraged to inspect everything yourself.

---

## 🔍 Verifying the Build

Want to verify the SD card you bought from us?

1. Mount it on your computer
2. Check installed software (`dpkg --get-selections`)
3. Inspect startup services (`systemctl list-unit-files`)
4. Run `sha256sum` on binaries and compare with official releases
5. Ask us for a signed build log!

---

## 💻 Run It Yourself

You don’t need us. Here's a [self-install guide](#) (coming soon) if you want to build it yourself.

---

## 🤝 Trust and Transparency

This project is fully open source. We will **never** add closed-source code or spyware.

Want to be extra sure? Fork this repo and build it yourself!

---

## 📜 License

[MIT License](LICENSE)

---

## ⚠️ Disclaimer

This software is provided **as-is**, with no warranty.  
You are responsible for verifying the integrity of anything you run.

