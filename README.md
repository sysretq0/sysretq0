### sysretq0

Systems programming & Linux kernel internals (`ring0 ⇄ ring3`).

#### Userspace Engineering
- **Process eviction & reclamation** ([`mini-lmk`](https://github.com/sysretq0/mini-lmk)): Low-overhead, composable userspace OOM handling and process eviction.
- **Zero-allocation task introspection** ([`fgres`](https://github.com/sysretq0/fgres)): Event-driven foreground resolution via `inotify` and `/proc/<pid>/task` traversal.
- **Low-overhead performance telemetry** (`taskfps`): Event-driven frame-rate monitoring and display metrics.

#### Kernel & Security
- **Data-driven LSMs**: Kernel module gating ([`android-module-gate`](https://github.com/sysretq0/android-module-gate)) & per-device partition protection on GKI ([`android-partition-guard`](https://github.com/sysretq0/android-partition-guard)).
- **GKI Infrastructure**: Automated common kernel builds (5.10–6.18) with KernelSU-Next, NoMount & AnyKernel3 ([`android-kernel-builder`](https://github.com/sysretq0/android-kernel-builder)).

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=sysretq0&show_icons=true&theme=github_dark&hide_border=true" alt="sysretq0's GitHub Stats" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=sysretq0&layout=compact&theme=github_dark&exclude_repo=android-kernel-common&hide_border=true" alt="Top Languages" />
</p>

---

<p align="center">
  <sub>All commits are signed with GPG: <code>97DE 60E3 277B 381B FECA EE58 628B C9E3 2379 DF41</code></sub>
</p>
