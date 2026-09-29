<div align="center">

# sysretq0

```
  ____ _   _ ___ _ __ ___| |_ __ _ / _ \ 
 / ___| | | / __| '__/ _ \ __/ _` | | | |
 \___ \ |_| \__ \ | |  __/ || (_| | |_| |
 |___/\__, |___/_|  \___|\__\__, |\___/ 
      |___/                    |_|       
```

### `ring0 ⇄ ring3` • Systems Programming • Linux Kernel Internals • LSM & Memory Management

[![GPG Signed](https://img.shields.io/badge/GPG-Ed25519_Signed-238636?style=flat-square&logo=gnupg&logoColor=white)](https://github.com/sysretq0)
[![GitHub](https://img.shields.io/badge/GitHub-sysretq0-181717?style=flat-square&logo=github)](https://github.com/sysretq0)

<p align="center">
  <i>Low-level engineer building custom kernel infrastructure, Linux Security Modules (LSM), rootless userspace daemons, and Android GKI systems.</i>
</p>

---

</div>

## 🛰️ About Me

```c
struct developer sysretq0 = {
    .focus       = "Linux Kernel Internals, GKI, LSM & Userspace Daemons",
    .languages   = { "Rust", "C", "C++", "Shell", "Python", "Kotlin" },
    .architecture= { "AArch64", "x86_64" },
    .interests   = { "Memory Management", "Kernel Security", "eBPF", "APatch/KernelSU" },
    .status      = "Returning to user mode (sysretq)"
};
```

- 🛡️ **Kernel & Security:** Developing data-driven LSMs for Android/GKI (`android-module-gate`, `android-partition-guard`).
- ⚡ **Systems Programming:** Building lightweight, event-driven userspace memory managers (`mini-lmk`) in Rust.
- 🔧 **Kernel Tooling & GKI:** Automating builds for Android Common Kernels (5.10 - 6.18) with KernelSU-Next, NoMount, and Kconfig fragments.
- 🔐 **Cryptographic Verification:** All commits and releases are cryptographically signed with GPG.

---

## 🛠️ Tech Stack & Tooling

<div align="center">

### Languages
![Rust](https://img.shields.io/badge/Rust-black?style=for-the-badge&logo=rust&logoColor=E5732F)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Shell](https://img.shields.io/badge/Shell_Scripting-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

### Systems & Architecture
![Linux](https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Android](https://img.shields.io/badge/Android_Internals-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![ARM64](https://img.shields.io/badge/ARM64-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![x86_64](https://img.shields.io/badge/x86__64-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GnuPG](https://img.shields.io/badge/GnuPG-005A9C?style=for-the-badge&logo=gnupg&logoColor=white)

</div>

---

## 🚀 Featured Projects

| Project | Description | Primary Stack |
| :--- | :--- | :--- |
| [**android-kernel-builder**](https://github.com/sysretq0/android-kernel-builder) | Build GKI kernels (5.10–6.18) with KernelSU-Next, NoMount, Partition Guard + portable Kconfig fragments & AnyKernel3 zips. | `Shell` `Makefile` `CI/CD` |
| [**mini-lmk**](https://github.com/sysretq0/mini-lmk) | Rootless, event-driven userspace memory manager for Android 7.0+ (API 24+) reacting dynamically to memory pressure. | `Rust` `Android` `Memory` |
| [**android-module-gate**](https://github.com/sysretq0/android-module-gate) | Tiny LSM: audit and gate kernel module loads with TOFU allowlists and EPERM enforcement. | `C` `Linux Security Modules` |
| [**android-partition-guard**](https://github.com/sysretq0/android-partition-guard) | Data-driven LSM guard protecting per-device sensitive partitions (NVRAM/persist/EFS) on GKI kernels. | `C` `LSM` `GKI` |

---

## 📊 GitHub Analytics

<div align="center">
  <a href="https://github.com/sysretq0">
    <img src="https://github-stats-extended.vercel.app/api?username=sysretq0&show_icons=true&theme=tokyonight&count_private=true" alt="sysretq0's GitHub Stats" />
  </a>
  <a href="https://github.com/sysretq0">
    <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=sysretq0&layout=compact&theme=tokyonight&exclude_repo=android-kernel-common" alt="Top Languages" />
  </a>
</div>

<br/>

<div align="center">
  <a href="https://github.com/sysretq0">
    <img src="https://streak-stats.demolab.com/?user=sysretq0&theme=tokyonight" alt="GitHub Streak" />
  </a>
</div>

---

## 🔐 Cryptographic Verification

All authentic commits and tags are signed using my Ed25519 GPG key:

```text
pub   ed25519 2026-09-11 [SC] [expires: 2028-09-10]
      97DE 60E3 277B 381B FECA  EE58 628B C9E3 2379 DF41
uid   sysretq0 <324514544+sysretq0@users.noreply.github.com>
sub   cv25519 2026-09-11 [E] [expires: 2028-09-10]
```

---

<div align="center">
  <sub><code>sysretq</code>: execution transitioned back to userspace ring 3 with code 0.</sub>
</div>
