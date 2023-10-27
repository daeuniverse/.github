## Welcome to daeuniverse 👋🏻

[dae](https://github.com/daeuniverse/dae) is an open-source, Linux high-performance transparent proxy solution, fueled by the revolutionary Kernel technology [eBPF](https://ebpf.io/).

dae has also been recognized as an emerging application in the [eBPF project lanscape](https://ebpf.io/applications/). Learn more about eBPF at [ebpf.io](https://ebpf.io/what-is-ebpf/)

### dae

<img src="https://github.com/daeuniverse/dae/blob/main/logo.png" border="0" width="25%">

<p align="left">
    <img src="https://github.com/daeuniverse/dae/actions/workflows/build.yml/badge.svg" alt="Build"/>
    <img src="https://custom-icon-badges.herokuapp.com/github/license/daeuniverse/dae?logo=law&color=orange" alt="License"/>
    <img src="https://custom-icon-badges.herokuapp.com/github/stars/daeuniverse/dae?logo=star&color=red" alt="star">
    <img src="https://custom-icon-badges.herokuapp.com/github/v/release/daeuniverse/dae?logo=rocket" alt="version">
    <img src="https://custom-icon-badges.herokuapp.com/github/issues-pr-closed/daeuniverse/dae?color=purple&logo=git-pull-request&logoColor=white"/>
    <img src="https://custom-icon-badges.herokuapp.com/github/last-commit/daeuniverse/dae?logo=history&logoColor=white" alt="lastcommit"/>
</p>

**_dae_**, means goose, is a high-performance transparent proxy solution.

To enhance traffic split performance as much as possible, dae employs the transparent proxy and traffic split suite within the Linux kernel using eBPF. As a result, dae can enable direct traffic to bypass the proxy application's forwarding, facilitating genuine direct traffic passage. Through this remarkable feat, there is minimal performance loss and negligible additional resource consumption for direct traffic.

## Features

- [x] Implement `Real Direct` traffic split (need ipforward on) to achieve [high performance](https://docs.google.com/spreadsheets/d/1UaWU6nNho7edBNjNqC8dfGXLlW0-cm84MM7sH6Gp7UE/edit?usp=sharing).
- [x] Support to split traffic by process name in local host.
- [x] Support to split traffic by MAC address in LAN.
- [x] Support to split traffic with invert match rules.
- [x] Support to automatically switch nodes according to policy. That is to say, support to automatically test independent TCP/UDP/IPv4/IPv6 latencies, and then use the best nodes for corresponding traffic according to user-defined policy.
- [x] Support advanced DNS resolution process.
- [x] Support full-cone NAT for shadowsocks, trojan(-go) and socks5 (no test).
- [x] Support various trending proxy protocols, seen in [proxy-protocols.md](https://github.com/daeuniverse/dae/blob/main/docs/en/proxy-protocols.md).

## Getting Started

Please refer to [Quick Start Guide](https://github.com/daeuniverse/dae/blob/main/docs/en/README.md) to start using `dae` right away!

## How it works

![](https://github.com/daeuniverse/dae/raw/main/docs/netstack-path.webp)

See [How it works](https://github.com/daeuniverse/dae/blob/main/docs/en/how-it-works.md).

### Community

Dae is an open-source project that anyone in the community can use, improve, and enjoy. Many people have already contributed to the Dae project and [you can too](https://github.com/daeuniverse/dae/blob/main/docs/en/development/contribute.md). We'd love you to join us! Here's a few ways to find out what's happening and get involved:

Join the [Daeuniverse International discussion channel on Telegram](https://t.me/v2raya)

Join the [Daeuniverse CN discussion channel on Telegram](https://t.me/daeuniverse)

You’ve already found us on Github!

### Side projects

- [@juicity/juicity](https://github.com/juicity/juicity)
