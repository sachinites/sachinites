<div align="center">

# Hi, I'm Abhishek 👋

### Network Systems Engineer · C/C++ · Routing & Switching · High-Performance Datapaths

**Building networking systems from the packet up.**

[![Website](https://img.shields.io/badge/Website-CSEPracticals-0ea5e9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.csepracticals.com/)
[![GitHub](https://img.shields.io/badge/GitHub-sachinites-181717?style=for-the-badge&logo=github)](https://github.com/sachinites)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/abhishekiit)

</div>

---

## 👨‍💻 About Me

I'm a software engineer focused on **network systems and infrastructure software**, with **14+ years of experience in networking**. My work spans routing protocols, control-plane development, system programming, and packet-processing architecture.

I enjoy understanding how networking systems work internally—and implementing those ideas in code. My interests range from protocol state machines and routing information bases to packet forwarding, memory management, and high-performance user-space datapaths.

- 🧭 **Professional focus:** Network control plane, routing protocols, and systems software
- 🧱 **Engineering foundation:** C, Linux, data structures, concurrency, and system programming
- 🌐 **Networking interests:** BGP, EVPN, multicast, IPv4/IPv6, routing and switching
- ⚡ **Performance interests:** DPDK, packet processing, lockless data structures, and datapath design
- 🧪 **Learning by building:** I create implementations and labs to make complex systems tangible
- 🎓 **Teaching:** I create technical courses and practical learning resources for engineers

---

## 🚀 Featured Project: `tcpip_stack`

<div align="center">

### A networking stack built from the ground up

**My flagship hands-on systems project**

</div>

The [`tcpip_stack`](https://github.com/sachinites) project is my long-running effort to explore and implement networking functionality through code. It brings together protocol implementation, control-plane concepts, packet processing, and systems engineering in a practical codebase.

> **The goal:** learn networking deeply by implementing it—not only by configuring devices or reading protocol specifications.

### What I'm building and exploring

| Area | Project work / concepts |
|---|---|
| **Layer 2** | Ethernet and switching concepts; EVPN implementation work |
| **EVPN control plane** | Route Type 2 (MAC/IP and MAC-only), Route Type 3 (IMET), and related route processing |
| **Layer 3** | Routing architecture, route lookup, and forwarding integration |
| **Routing data structures** | Flat routing tables, trie/multibit trie ideas, and longest-prefix match |
| **BGP / EVPN** | Route exchange, route attributes, MAC mobility, and control-plane integration |
| **Data plane** | Packet forwarding and user-space datapath experiments |
| **DPDK** | PMD-based packet I/O, queues, mempools, rings, and high-performance packet processing |
| **Testing** | Focused unit tests, protocol scenarios, and repeatable labs |

### Why this project matters

- **Protocol internals:** turn specifications and design concepts into working implementations.
- **Control plane meets data plane:** explore how routes and protocol state influence packet forwarding.
- **Systems-level engineering:** work with memory, queues, concurrency, interfaces, and performance constraints.
- **Practical learning:** use the project as a foundation for experiments, demonstrations, and course material.

### Project direction

The broader vision is to develop a modular networking stack that can serve as a learning platform for:

- Implementing routing and switching functionality
- Understanding EVPN and BGP through code
- Experimenting with forwarding architectures
- Exploring DPDK-powered datapaths
- Building reproducible labs and educational content

➡️ **Explore my repositories:** [github.com/sachinites](https://github.com/sachinites)

---

## 🧩 Other Engineering Projects & Areas

The following projects represent complementary explorations around the networking stack. Some are standalone experiments; others are integrations or components of the broader work.

### 1. EVPN implementation

Hands-on EVPN work covering route processing and forwarding implications.

- EVPN Route Type 2: MAC-only and MAC/IP advertisement concepts
- EVPN Route Type 3: Inclusive Multicast Ethernet Tag (IMET)
- MAC mobility and sequence-number behavior
- ARP suppression and MAC/IP reachability
- Route import/export and control-plane integration

### 2. DPDK-powered user-space datapath

Experiments with high-performance packet I/O and forwarding outside the conventional kernel networking path.

- DPDK poll-mode driver (PMD) interfaces
- RX/TX queues and packet-buffer lifecycle
- Mbufs, mempools, and rings
- Huge pages and memory considerations
- User-space forwarding architecture
- Exploring socket/TUN/TAP integration paths

### 3. GoBGP ↔ C integration

A wrapper/integration experiment exposing GoBGP functionality through a C-facing API.

- C ABI around GoBGP gRPC functionality
- IPv4 unicast route operations
- EVPN Route Type 2 import/export experiments
- Multi-instance GoBGP testing and lab integration

### 4. Routing-table and data-structure experiments

Exploring the structures behind efficient route lookup and packet forwarding.

- Flat routing-table implementation
- Longest-prefix match
- Trie and multibit-trie approaches
- Memory layout and lookup trade-offs
- Unit testing and correctness validation

### 5. Packet inspection and filtering

A packet-sniffer / packet-processing project exploring visibility and control over traffic.

- Interface-based packet capture
- Packet filtering and ACL concepts
- PCAP output
- Packet injection experiments
- CLI-driven workflows
- Recording packet metadata for analysis

### 6. Systems programming experiments

Smaller implementations and learning projects around core Linux/C concepts:

- Threads and synchronization
- Atomic operations and compare-and-swap
- Lockless producer-consumer patterns
- Shared memory and memory mapping
- POSIX timers, semaphores, and file descriptors
- Socket programming and network utilities

---

## 🧰 Technology & Skills

<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![DPDK](https://img.shields.io/badge/DPDK-High_Performance-007ACC?style=flat-square)
![Networking](https://img.shields.io/badge/Networking-Routing_%26_Switching-0EA5E9?style=flat-square)

</div>

| Domain | Topics |
|---|---|
| **Languages** | C, C++, Go (integration work) |
| **Systems** | Linux, POSIX APIs, memory management, concurrency |
| **Networking** | Ethernet, IPv4/IPv6, BGP, EVPN, multicast, routing and switching |
| **Data structures** | Hash tables, tries, routing tables, queues, rings |
| **Datapath** | DPDK, PMDs, packet buffers, RX/TX processing |
| **Tools & labs** | Git, GNS3, virtual network labs, packet capture, debugging |

---

## 💼 Career Journey

My career has been centered on **networking software engineering**, evolving from protocol and network-system development toward broader systems and datapath engineering.

```text
Networking foundations
        │
        ▼
Network protocol & systems development
        │
        ▼
Routing / switching / control-plane engineering
        │
        ▼
EVPN, multicast, BGP & network infrastructure
        │
        ▼
Staff-level engineering · cross-domain system integration
        │
        ▼
Expanding into high-performance datapaths & DPDK
```

### Professional experience

- **Cisco** — Networking software engineering experience
- **Calix** — Network systems development, with focus on multicast and control-plane behavior

*This is a high-level career summary, not a complete employment chronology. Add exact titles, dates, and earlier roles if you want a fully detailed timeline.*

### Current engineering direction

I believe strong networking engineers benefit from understanding both sides of a network system:

- **Control plane:** protocols, route computation, state machines, signaling, and convergence
- **Data plane:** packet parsing, forwarding, memory, queues, and performance

That is why I continue to explore DPDK and user-space packet processing alongside protocol development.

---

## 🎓 My Udemy Journey

Teaching is an important part of my engineering journey. I create technical courses that help learners move beyond theory and understand systems through practical implementation.

<div align="center">

### 24+ networking & systems courses

**From protocol concepts to hands-on engineering**

</div>

Over time, I have built a catalog of technical courses on Udemy and learning resources through my own platform. My teaching focuses on practical explanations, implementation-oriented learning, and helping students understand what happens inside networking systems.

### What I aim to teach

- Networking fundamentals and protocol behavior
- Routing and switching concepts
- System programming in C
- Building networking functionality through implementation
- Control-plane and data-plane architecture
- DPDK and high-performance packet processing
- Practical labs that connect theory with engineering

### Creator & educator

- 🎥 **Udemy instructor:** [View my instructor profile](https://www.udemy.com/user/sachin-2/)
- 🌐 **Learning platform:** [CSEPracticals](https://www.csepracticals.com/)
- 🧑‍🏫 **Teaching philosophy:** explain the concept, build it, test it, and understand its trade-offs

> My engineering projects and teaching reinforce each other: building systems gives me practical material to teach, and teaching encourages me to make complex ideas clearer.

---

## 📚 Learning Philosophy

I value engineering approaches that emphasize:

1. **Implementation over superficial familiarity** — understand a system by building meaningful parts of it.
2. **End-to-end thinking** — connect protocols, APIs, data structures, and packet forwarding.
3. **Correctness before optimization** — establish behavior with tests, then measure and improve.
4. **Readable engineering** — design interfaces and code that others can understand and extend.
5. **Continuous learning** — keep expanding into adjacent domains without abandoning core expertise.

---

## 📈 GitHub Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=sachinites&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sachinites&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=sachinites&theme=tokyonight&hide_border=true)

</div>

<!-- Optional contribution snake:
After configuring the GitHub Actions workflow, uncomment this:
![Contribution Snake](https://raw.githubusercontent.com/sachinites/sachinites/output/github-contribution-grid-snake.svg)
-->

---

## 🤝 Let's Connect

I'm interested in connecting with engineers and learners working on:

- Network operating systems and routing platforms
- BGP, EVPN, multicast, and control-plane development
- DPDK, high-performance networking, and packet-processing systems
- C/Linux systems programming
- Practical technical education

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-sachinites-181717?style=for-the-badge&logo=github)](https://github.com/sachinites)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/abhishekiit)
[![CSEPracticals](https://img.shields.io/badge/CSEPracticals-Learn-0ea5e9?style=for-the-badge)](https://www.csepracticals.com/)

### Thanks for visiting! ⭐

*Build systems. Understand packets. Share knowledge.*

</div>
