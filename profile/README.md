<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="PodUtils — small, static tools for hosts that say no." src="./assets/banner-light.svg" width="100%">
</picture>

<br>

<p align="center">
  Locked-down CI runners, HPC nodes, sandboxes, and networks where the only way out is HTTPS.<br>
  <b>PodUtils</b> is a family of small Rust tools that still work there, one static binary at a time.
</p>

<br>

### &nbsp;Tools

| Tool | What it does | Status |
|:--|:--|:--|
| **[pod](https://github.com/PodUtils/pod)** | One installer for every PodUtils tool: install, pin, verify, update, roll back | `soon` |
| **podcat** | Pipe bytes between sockets, tunnels and processes, like netcat and socat | `soon` |
| **[podci](https://github.com/PodUtils/podci)** | Run CI/CD actions on pods | `soon` |
| **podfs** | File system tools for restricted hosts and sandboxes | `soon` |
| **podinfo** | Fetch and probe a host: what it is, and what it lets you do | `soon` |
| **[podinit](https://github.com/PodUtils/podinit)** | Turn a fresh Linux server into a locked-down fleet node in one command | `soon` |
| **[podkey](https://github.com/PodUtils/podkey)** | An in-memory secret agent with a time window, like ssh-agent for any secret | `soon` |
| **[podlog](https://github.com/PodUtils/podlog)** | Ship logs and metrics from a node over HTTPS, with buffering and redaction | `soon` |
| **podmesh** | Mesh networking between hosts behind NAT and strict firewalls | `soon` |
| **[podnet](https://github.com/PodUtils/podnet)** | Tunnels, WARP and per-process proxying in one binary | `beta` |
| **[podnode](https://github.com/PodUtils/podnode)** | The one agent of a fleet server: enrol, supervise, self-update, no open port | `soon` |
| **[podrelay-worker](https://github.com/PodUtils/podrelay-worker)** | The podssh relay as a Cloudflare Worker with Durable Objects | `soon` |
| **[podrepl](https://github.com/PodUtils/podrepl)** | Continuous SQLite replication between nodes and to object storage | `soon` |
| **[podrunner](https://github.com/PodUtils/podrunner)** | Ephemeral CI runners on your own servers, one fresh unit per job | `soon` |
| **podshell** | A resilient remote terminal, a mosh alternative for strict networks | `soon` |
| **[podsnap](https://github.com/PodUtils/podsnap)** | Encrypted, append-only backups with signed manifests and verify | `soon` |
| **[podssh](https://github.com/PodUtils/podssh)** | SSH from machines whose only way out is HTTPS, through a WebSocket relay | `beta` |
| **[podutils](https://github.com/PodUtils/podutils)** | The PodUtils umbrella: install and manage the whole family | `soon` |
| **[podvm](https://github.com/PodUtils/podvm)** | Container runtime for rootful-but-restricted sandboxes, CI executors and HPC nodes | `beta` |
| **[podwatch](https://github.com/PodUtils/podwatch)** | Outside prober and heartbeat that alerts once and closes on recovery | `soon` |

<sub>Shared libraries for all of them live in <a href="https://github.com/PodUtils/podcrates"><b>podcrates</b></a>.</sub>

<br>

### &nbsp;What they share

- **One static binary.** No installer, no runtime, no shared libraries. Copy it and run it.
- **No root, no daemon.** Built for hosts where you get a shell and little else.
- **Made for hostile networks.** Proxies, HTTPS-only egress and blocked UDP are the normal case, not the edge case.
- **Free to use.** Everything is under [0BSD](https://opensource.org/license/0bsd).

<br>

<p align="center">
  <sub>Made with care, for the machines that make it hard.</sub>
</p>
