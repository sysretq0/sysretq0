### sysretq0

Systems programming & Linux kernel internals (`ring0 ⇄ ring3`).

Hyper-optimized, event-driven userspace daemons and custom kernel infrastructure — built for low-overhead systems work, not placebo tweaks.

- **Process eviction & reclamation** ([`mini-lmk`](https://github.com/sysretq0/mini-lmk)): Low-overhead, composable userspace OOM handling and process eviction.
- **Zero-allocation task introspection** ([`fgres`](https://github.com/sysretq0/fgres)): Event-driven foreground resolution via `inotify` and `/proc/<pid>/task` traversal.
- **Low-overhead performance telemetry** (`taskfps`): Event-driven frame-rate monitoring and display metrics.
- **Data-driven LSMs**: Kernel module gating ([`android-module-gate`](https://github.com/sysretq0/android-module-gate)) and GKI partition guards ([`android-partition-guard`](https://github.com/sysretq0/android-partition-guard)).

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=sysretq0&show_icons=true&theme=github_dark&hide_border=true" alt="sysretq0's GitHub Stats" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=sysretq0&layout=compact&theme=github_dark&exclude_repo=android-kernel-common&hide_border=true" alt="Top Languages" />
</p>

---

<p align="center">
  <sub>All commits are signed with GPG: <code>97DE 60E3 277B 381B FECA EE58 628B C9E3 2379 DF41</code></sub>
</p>
