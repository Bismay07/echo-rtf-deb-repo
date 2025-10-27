<p align="center">
  <img src="https://raw.githubusercontent.com/Bismay07/echo-rtf-deb-repo/main/GithubRepoBanner.png" alt="RTF Banner" width="90%" />
</p>


# 🕵️ RTF — Retrieve The Flag™ Challenge System

**RTF (Retrieve The Flag)** is a hands-on cybersecurity challenge framework — similar in spirit to Capture The Flag (CTF), but built from the ground up to be:

- 🔁 Reproducible
- 💻 Offline and self-hosted
- 🧠 Concept-focused
- 📦 Delivered as `.deb` packages via APT

> 🧬 **RTF is an original concept and trademark of Bismay** — a modular learning and hacking simulation system for serious cybersecurity learners.

---

## 📦 What Is This Repo?

This repository serves as an **APT-style `.deb` package feed**. That means students can install challenges just like any other Linux software:

```bash
echo "deb [trusted=yes] https://bismay07.github.io/echo-rtf-deb-repo/ ./" | sudo tee /etc/apt/sources.list.d/rtf.list
sudo apt update
sudo apt install echo-rtf-1-hidden-flag
```

