# Awesome-Systems-Networking-High-Performance-Rust
# Awesome-Systems-Networking-High-Performance-Rust

# Top Systems Networking & High-Performance Rust Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on High-Performance Rust Networking, Mesh VPNs, Zero-Trust Tunnels, Packet Inspection & Async Runtimes*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted networking platforms** and **open-source Rust/systems projects** for **Systems Networking & High-Performance Rust**. These tools power low-latency packet processing, deep packet inspection (DPI), encrypted WireGuard/overlay mesh networks, zero-trust edge proxies, and high-throughput network servers.

**Examples** include domcyrus/rustnet, Sniffnet, Bandwhich, Trippy, Tokio, Quinn, BoringTun, Pingora, Rama, Headscale, NetBird, Nebula, Innernet, Firezone, Tailscale, ZeroTier, Cloudflare Magic Transit, Fastly, Twingate, Perimeter 81, Cato Networks, and NordLayer.

**Open-source emphasis**: This list heavily expands on active open-source Rust network monitors, eBPF/packet capture utilities, user-space WireGuard implementations, high-performance proxies, and self-hosted mesh VPN control planes — ideal for systems engineers, network architects, and Rust developers building fast, memory-safe infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Cloudflare Magic Transit & WARP](https://cloudflare.com)**  
  Global Anycast network security, DDoS mitigation, and zero-trust client routing service backed by Cloudflare's Rust-powered edge stack (Pingora/Oxy).

- **[Fastly](https://fastly.com)**  
  High-performance edge cloud and CDN platform built for real-time traffic routing, DDoS protection, and WebAssembly compute at the network edge.

- **[Tailscale](https://tailscale.com)**  
  Zero-config mesh VPN built on WireGuard that creates secure peer-to-peer overlay networks across devices, containers, and cloud VPCs.

- **[ZeroTier](https://zerotier.com)**  
  Software-defined networking (SDN) and global Ethernet virtualization platform connecting distributed systems over encrypted peer-to-peer tunnels.

- **[Netmaker](https://netmaker.io)**  
  Fast WireGuard-based virtual networking and mesh automation platform for connecting multi-cloud servers, Kubernetes clusters, and edge devices.

- **[Twingate](https://twingate.com)**  
  Cloud-managed Zero Trust Network Access (ZTNA) platform replacing legacy VPNs with identity-aware, split-tunnel private resource routing.

- **[Perimeter 81 (Check Point Harmony SASE)](https://perimeter81.com)**  
  Cloud-native Secure Access Service Edge (SASE) and Zero Trust networking platform with global gateways and Software-Defined Perimeter controls.

- **[Cato Networks](https://catonetworks.com)**  
  Single-vendor SASE cloud platform converging SD-WAN, global private backbone routing, and network security into a unified service.

- **[NordLayer](https://nordlayer.com)**  
  Cloud-based network access security and business VPN solution offering dedicated gateways, site-to-site connectivity, and ZTNA controls.


## Open-Source GitHub Projects

- **[RustNet (domcyrus/rustnet)](https://github.com/domcyrus/rustnet)**  
  Cross-platform terminal network monitor written in Rust offering real-time TCP, UDP, and QUIC connection tracking, deep packet inspection (DPI), eBPF process attribution, and sandboxed execution.

- **[Sniffnet](https://github.com)**  
  Cross-platform, open-source network monitoring application written in Rust that provides intuitive real-time traffic analytics, protocol identification, and GeoIP visualizations.

- **[Bandwhich](https://github.com)**  
  Terminal bandwidth utilization tool written in Rust that sniffs network packets to display live throughput broken down by process, connection, and remote IP/hostname.

- **[Trippy](https://github.com)**  
  Modern network diagnostic tool written in Rust combining `traceroute` and `ping` functionality into a rich interactive terminal UI with ASN and GeoIP lookups.

- **[Pingora](https://github.com)**  
  Cloudflare's battle-tested, ultra-fast async Rust framework for building programmable, memory-safe HTTP/1, HTTP/2, and TLS network proxies at massive scale.

- **[BoringTun](https://github.com)**  
  Userspace implementation of the WireGuard protocol written in Rust, designed for high-speed, cross-platform encrypted tunneling without kernel module dependencies.

- **[Quinn](https://github.com)**  
  Async-friendly, pure-Rust implementation of the IETF QUIC transport protocol powering low-latency multiplexed network applications.

- **[Tokio](https://github.com)**  
  Foundational asynchronous runtime for Rust providing high-performance event-driven networking, TCP/UDP sockets, timers, and multi-threaded work-stealing schedulers.

- **[Nebula](https://github.com)**  
  Scalable, open-source overlay networking tool created at Slack featuring mutual cryptographic certificate authentication, NAT hole-punching, and firewall rules.

- **[Headscale](https://github.com)**  
  Open-source, self-hosted implementation of the Tailscale control server enabling fully sovereign mesh WireGuard networks on your own infrastructure.

- **[NetBird](https://github.com)**  
  Open-source zero-trust peer-to-peer overlay network combining WireGuard encryption with WebRTC ICE NAT traversal, SSO, and self-hosted management.

- **[Innernet](https://github.com)**  
  Private network system written in Rust that uses WireGuard and CIDR-based access control lists to build self-hosted overlay networks.

- **[Firezone](https://github.com)**  
  Open-source zero-trust access platform and WireGuard-based tunnel written largely in Rust for granular policy-driven routing to private infrastructure.

- **[Rama](https://github.com)**  
  Modular, service-oriented Rust network framework for building custom proxies, TLS/HTTP/SOCKS5 servers, and packet/stream transformation pipelines.

- **[Aya](https://github.com)**  
  Pure-Rust eBPF library enabling developers to write, load, and observe high-performance Linux kernel networking programs (XDP, TC, socket filters) without C toolchains.

### Additional Strong Open-Source Options

- **[pnet (libpnet)](https://github.com)** — Cross-platform, low-level packet manipulation and raw socket networking library in Rust.
- **[smoltcp](https://github.com)** — Standalone, event-driven TCP/IP stack written in Rust designed for bare-metal, embedded, and userspace networking.
- **[defguard](https://github.com)** — Open-source enterprise WireGuard VPN written in Rust featuring hardware security key 2FA and zero-trust controls.
- **[SoftEther VPN](https://github.com)** & **[WireGuard](https://wireguard.com)** — Foundational open-source high-throughput VPN protocols and kernel/userspace tunneling implementations.
- **[Vector](https://github.com)** — High-performance observability data pipeline written in Rust for collecting, transforming, and routing network logs and metrics.
- **[Ockam](https://github.com)** — Open-source Rust toolkit for end-to-end encrypted, mutually authenticated messaging across distributed networks.
- **[rustscan](https://github.com)** — Modern, ultra-fast asynchronous port scanner written in Rust designed to pipe results into `nmap`.

**Frameworks for building custom systems**: Combine **Tokio** + **Quinn** or **Pingora** for high-throughput Rust network services, pair **Aya (eBPF)** with **RustNet** for kernel-to-terminal packet observability, and deploy **Headscale** or **NetBird** for self-hosted zero-trust mesh networking.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Deep packet inspection (`rustnet`, `sniffnet`, `bandwhich`) and eBPF tools require elevated privileges (`CAP_NET_RAW`, `CAP_BPF`, `sudo`, or Npcap) and should only be run on networks you are authorized to monitor.
- Self-hosted overlay and mesh VPN control planes require proper TLS, key rotation, and firewall policies when exposed to the public internet.

---

**Made for systems programmers, network engineers, Rustaceans, and infrastructure architects.**  
Let's make high-performance networking safer, faster, and open to everyone.
