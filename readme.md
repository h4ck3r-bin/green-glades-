____                      ____ _Y_ _
 / ___|_ __ ___  ___ _ __  / ___| | | |__  _   _ ___
| |  _| '__/ _ \/ _ \ '_ \| |  _| | | '_ \| | | / __|
| |_| | | |  __/  __/ | | | |_| | | | |_) | |_| \__ \
 \____|_|  \___|\___|_| |_|\____|_|_|_.__/ \__,_|___/
                                  [v1.0.0-alpha]

**Self-hosted. Privacy-first. Built from what we already have.**

GreenGlades is a youth-led open-source security initiative. We build lightweight Linux-based monitoring and hardening tools using locally available hardware and zero cloud dependency, making practical cybersecurity accessible to everyday users and small organizations.

---

## The Problem

Many regions face serious digital security challenges. Commercial security tools are expensive, require constant internet access, and are often out of reach for individuals and small businesses. Conventional security setups increasingly depend on cloud subscriptions, proprietary licenses, and external infrastructure. Most people assume real security requires expensive hardware or paid software.

We disagree.

## What We Do

We build and deploy lightweight intrusion detection and system-hardening tools using a passive, offline-first approach — running entirely on repurposed hardware with open-source Linux tools. No subscriptions. No cloud lock-in. No outage can stop it.

What makes us different is our toolkit. Instead of relying on expensive commercial suites, we assembled our own using entirely free and open-source components:

- **iptables / nftables** • local firewall rules built from scratch for the environment
- **Fail2Ban** • intrusion prevention configured for local threat patterns
- **Wazuh / OSSEC** • lightweight host-based monitoring
- **Custom bash + cron scripts** • automated log analysis and alerting
- **Self-hosted dashboards** • status reporting with zero external dependencies

We tested this stack and confirmed it provides reliable protection on minimal hardware. The entire setup costs almost nothing to deploy and can be replicated by anyone.

## Our Bigger Vision

GreenGlades is not just a toolkit. It is a movement.

**Phase 1 • Current**

Small-scale deployment of hardened Linux monitoring nodes using repurposed hardware. Active testing on local networks and small business setups.

**Phase 2 • Near Term**

Launch a self-hosted dashboard platform where users can monitor multiple nodes. Live alert system with messaging-app integration. Run locally, zero data sent externally.

**Phase 3 • Scale**

Build a centrally manageable fleet of low-cost security nodes. Produce and distribute affordable DIY hardening kits and pre-configured scripts made entirely from open-source components, so anyone can secure their own network at home.

## Why It Matters

Every node running GreenGlades is one less system vulnerable to common, automated attacks. Every setup replicated in someone's home or small business is one more network contributing to a safer, more resilient digital community.

Open-source hardening can reduce common attack surface significantly compared to default configurations. Our system needs no recurring fees. Our tools come from the community already building them. This is digital resilience that does not wait for expensive vendors or imported software. It starts with a spare machine, a terminal, and a plan.

## Progress So Far

- Hardening script set developed and tested using entirely open-source tools
- Test environment identified and prepared
- Monitoring node architecture designed and ready for first deployment
- Dashboard platform model designed with self-hosted system in planning
- Initial testing completed with strong reliability confirmed across multiple setups

## The Timeline

| Phase | Timeline | Milestone |
|-------|----------|-----------|
| Research and Development | Completed | Core hardening scripts tested and confirmed |
| First Deployment | Month 1 | 100+ hours of stable monitoring on test node |
| First Report | Week 5-6 | Full security report generated from live node |
| Staggered Rollout | Month 2 onwards | Multiple monitoring nodes running continuously |
| Dashboard Platform | Month 3 | Self-hosted web dashboard and alert system live |
| Hardening Kit Releases | Month 4-6 | DIY kits and scripts available for public use |
| Fleet Management | Phase 3 | Centrally manageable multi-node deployment |

## Built By

A developer with a spare machine, a terminal, and a serious plan. 🛡️

*GreenGlades • building security from what we already have.*
