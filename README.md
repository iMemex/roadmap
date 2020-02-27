# iMemex Roadmap v0.0.1

## Table of Contents

- [iMemex Mission Statement](#imemex-mission-statement)
- [2020 Priority](#2020-priority)
- [Epics](#epics)
  - [♻️ Distributed Web](#%EF%B8%8F-distributed-web-d2-e2-i4)
  - [👩🏽‍💻 Personal Web](#-personal-web-d3-e4-i2)
  - [👟 Sneaker Web](#-sneaker-web-d3-e2-i4)
  - [🚀 Interplanetary Web - Mars 2024](#-interplanetary-web---mars-2024-d3-e3-i4)
  - [🌐 WebOS](#-webos-d5-e2-i3)

---

## iMemex Mission Statement

:whale:  `make the web more personal`  :shipit:

---

## 2020 Priority

***TBD***

---

## Epics


### ♻️ Distributed Web (D2 E2 I4)

> Info and apps function equally well in local area networks and offline. The Web is a partitionable fabric, like the internet.

The web and mobile -- the most important application platforms on the planet -- are capable of working entirely in sub-networks. The norm for networked apps is to use the available data and connections, to sync asynchronously, and to leverage local connectivity protocols. The main apps for every top use case work equally well in offline or local network settings. It means IPFS and apps on top work excellently on desktops, the browser, and mobile. Users can use webapps like email, chat, forums, social networks, collaboration tools, games, and so on without having to be connected to the global internet. Oh, and getting files from one computer to another right next to it finally becomes an easy thing to do (airdrop level of easy).

### 👩🏽‍💻 Personal Web (D3 E4 I2)

> Personal Data and programs are under user control.

The memex becomes reality. The web becomes a drastically more personal thing. Users' data and exploration is under the users' control -- similar to how a "personal computer" is under the user's control, and "the cloud" is not. Users decide which apps and other people get access to their data. Explorations can be recorded for the user in memex fashion. The user gets to keep copies of all the data they have observed through the web. A self-archiving personal record forms, which the user can always go back to, explore, and use -- whether or not those applications are still in development by their authors.

### 👟 Sneaker Web (D3 E2 I4)

> The web functions over disconnected sneaker networks, spreading information, app data, apps, and more.

The web is capable of working fully distributed, and can even hop across disconnected components of the internet. Apps and their data can flow across high latency, intermittent, asynchronous links across them. People in disconnected networks get the same applications, the same quality of experience, and the same ability to distribute their contributions as anybody in the strongest connected component ("the backbone of the internet"). The Web is totally resistant to large scale partitions. Information can flow so easily across disconnected components that there is no use in trying to block or control information at the borders.

### 🚀 Interplanetary Web - Mars 2024. (D3 E3 I4)

> **Mars**. Let's live the interplanetary dream!**

SpaceX plans to land on mars in 2022, and send humans in 2024. By then, IPFS should be the default/best choice for SpaceX networking. The first humans on mars should use IPFS to run the top 10 networked apps. That means truly excellent and well-known IPFS apps addressing the top 10 networked use cases must exist. For that to happen, the entire system needs to be rock solid, audited, performant, powerful, easy-to-use, well known, and so on. It means IPFS must work on a range of platforms (desktop, servers, web, mobile), and to work with both special purpose local area networks, and across interplanetary distances. If we achieve this, while solving for general use and general users (not specifically for the Mars use case, then IPFS will be in tremendous standing.

### 🗃 Interplanetary DevOps (D4 E2 I2)

> Versioning, packaging, distribution, and loading of Programs, Containers, OSes, VMs, defaults to IPFS.

IPFS is great for versioning, deduping, packaging, distributing assets, through a variety of mediums. IPFS can revolutionize computing infrastructure systems. It has the potential to become the default way for datacenter and server infrastructure users to set up their infrastructure. This can happen at several different layers. (a) In the simplest sense, IPFS can help distribute programs to servers, by sitting within the OS, and plugging in as the downloading mechanism (replace wget, rsync, etc.).  (b) IPFS can also distribute containers -- it can sit alongside docker, kubernetes, and similar systems to help version, dedup, and distribute containerized services. (c) IPFS can also distribute OSes themselves, by plugging in at the OS package manager level, and by distributing OS installation media. (d) IPFS can also version, dedup, and distribute VMs, first by sitting alongside host OSes and hypervisors moving around VM snapshots, and then by modeling VMs themselves on top of IPFS/IPLD. --- To get there, we will need to solve many of the same problems as package managers, and more. We will need the IPLD importers to model and version the media super-effectively.

### 🌐 WebOS (D5 E2 I3)

> The Web Platform and the OS'es merge.

The rift between the web and the OS is finally healed. The OS and local programs and WebApps merge. They are not just indistinguishable, they are _the same thing_. "Installing" becomes pinning applications to the local computer. "Saving" things locally is also just pinning. The browser and the OS are no longer distinguishable. The entire OS data itself is modelled on top of IPLD, and the internal FileSystem is IPFS (or something on top, like unixfs). The OS and programs can manipulate IPLD data structures natively. The entire state of the OS itself can be represented and stored as IPLD. The OS can be frozen or snapshotted, and then resumed. A computer boots from the same OS hash, drastically reducing attack surface.
