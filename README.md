# **SYNCLAB**

**SYNCLAB — tools, scripts, and research materials for synchronous action scores & distributed performance**

SYNCLAB is a **meta-repository** collecting code, patches, and experiments aimed at supporting **synchronous action scores**, **distributed performance systems**, and **artistic research workflows**. It unifies tools developed across projects, enabling reproducible and extensible practice-based research in networked artistic performance.

---

## 🚀 **Why SYNCLAB?**

Modern artistic performance, especially in domains like **distributed music, dance, and action scores**, often relies on:

* Temporal alignment across machines, performers, and sensors.
* Experimental interaction affordances (e.g., patching, transformations, network sync).
* Reusable tools that bridge research concepts with live practice.

SYNCLAB exists to:

* Aggregate tools, servers, and interfaces used in SYNCLAB-related research.
* Provide a shared foundation for **synchronous performance systems**.
* Support **distributed performance experiments** with clear workflows and documentation.

---

## 📦 **Contents & Structure**

At a glance — what you’ll find in this repo:

```
SYNCLAB/
├── FILES/               ← Core definitions & scripts
├── TIMEKEEP/            ← Temporal coordination tools
├── TransForms/          ← Transform frameworks for action scores
├── polyServer/          ← Server utilities for networked performance
├── polytempoWeb/        ← Browser interfaces & clients
├── tools/               ← Misc scripts and helpers
├── .gitmodules          ← Submodule pointers to linked repos
└── README.md            ← This file
```

Each subfolder is itself a (sub)project, often with its own internal structure, builds, or dependencies.

---

## 🧠 **Key Concepts**

### 🔹 **Synchronous Action Scores**

Action scores are procedural descriptions guiding real-time artistic actions. SYNCLAB’s focus is on *synchronous* scores — where performers coordinate in time across digital and physical boundaries.

### 🔹 **Distributed Performance**

Experiments where performers, systems, and environments interact over networks (e.g., Wi-Fi/LAN), requiring coordinated timing, messaging, and visual/audio feedback.

### 🔹 **Research + Practice**

This repo bridges artistic research (working prototypes, experiments, papers) with tools that can be reused, extended, or adapted.

---

## 🎯 **How to Use This Repo**

### Clone (with submodules)

```bash
git clone --recursive https://github.com/AdrianArtacho/SYNCLAB.git
```

If you’ve already cloned without submodules:

```bash
git submodule init
git submodule update
```

### Navigate

Each directory includes its own README and usage notes — start with those that match your needs:

* `TIMEKEEP/` for timing & sync tools
* `polyServer/` for server infrastructure
* `tools/` for utility scripts used across experiments

### Workflows

Depending on your project or experiment, you might use:

* Live-coding interfaces
* Browser clients (in `polytempoWeb/`)
* Networked messaging servers
* Time synchronization scripts
* Stand-alone performance patches

Refer to each subdirectory’s own docs for details.

---

## 🤝 **Contributing**

This repo is a living lab. Contributions are welcome!

✔ Add or improve tools used in performance workflows
✔ Write or extend documentation for clarity
✔ Share experiments & results that depend on these tools
✔ Open issues to track ideas, bugs, or project planning

**Guidelines**

1. Fork the repo
2. Work in a feature branch
3. Open a PR with context & motivation
4. Link related issues for visibility

---

## 📚 **Related Work & Context**

SYNCLAB supports research inquiries around:

* Temporal coordination in distributed performance
* Networked action scores
* Practice-based artistic research methods

It serves as a **toolbox** for experimental and exploratory systems — both for prototyping and for reproducible research dissemination.

---

## 🧪 **License**

This repository and its submodules are made available under terms defined in their respective folders — please check individual components for license details.

---

## 📬 **Contact**

Maintained by [**Adrián Artacho**](https://www.artacho.at/research/), artist/researcher focused on **action scores, distributed performance, and artistic research experiments**.
For questions, insights, or collaborations, use GitHub discussions or open an issue.
[1]: ["README Best Practices"](https://www.tilburgsciencehub.com/topics/collaborate-share/share-your-work/content-creation/readme-best-practices)
