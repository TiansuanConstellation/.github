<div align="center">

<img src="http://www.tiansuan.org.cn/pic/logo.png" alt="Tiansuan Constellation logo" width="15%">

# Tiansuan Constellation · 天算星座

### An open-source constellation of real satellites, built for research

**Where research code doesn't just run in CI — it runs in orbit.**

[About Us](#-about-us) · [Roadmap](#%EF%B8%8F-roadmap) · [The Fleet](#-the-fleet) · [Open-Source Projects](#-open-source-projects) · [Get Involved](#-get-involved) · [Contact](#-contact)

[Website](http://www.tiansuan.org.cn/index.html) · [中文官网](http://www.tiansuan.org.cn/Chinese/index.html) · [Experiment Platform](https://github.com/TiansuanConstellation/TiansuanExperimentPlatform) · [Our Repositories](#-open-source-projects)

</div>

---

## 🪐 About Us
> **Bring your research to orbit — we'll handle the rocket.** 🛰️

**Tiansuan Constellation** (天算星座 — literally *"celestial computing"*) is an open-source testbed of low-Earth-orbit satellites for computing and networking research. It was initiated in 2021 by Prof. **Shangguang Wang**'s team at the State Key Laboratory of Networking and Switching Technology, **Beijing University of Posts and Telecommunications (BUPT)**, and is jointly built with partners across industry, academia, and research.

Putting an experiment into orbit has always demanded a launch budget, a hardware program, and a healthy tolerance for risk — which is why most research ideas never leave the ground. Tiansuan exists to change that. The constellation pairs in-orbit satellites with ground stations, a cloud supercomputing center, and an open service platform, so that the **global research community can deploy, test, and measure real systems on real satellites — openly, and at low cost.**

Beyond the satellites themselves, the team founded **[OPENSAT — Open Source Satellite Community](https://github.com/Satellite-OSS)**, an open community that gathers satellite-related open resources — software, papers, datasets, and industry standards and specifications — from Tiansuan and from the wider community.

**At a glance:** 5 satellites in orbit · 7 world-first systems verified on orbit · 33 alliance members across China and Europe · 20+ peer-reviewed publications (2021–2025)

---
## 🗺️ Roadmap

| Phase | Scale | Status |
| --- | --- | --- |
| **Phase I** | 6 LEO satellites (2 main · 2 auxiliary · 2 edge) + ground stations, TT&C center, cloud supercomputing center, open service platform | ✅ In service — 5 of 6 satellites on orbit |
| **Phase II** | 24 satellites |  In planning |
| **Phase III** | 300 satellites |  Long-term vision |

**Where we are heading next:**

- Batch-deploying payloads verified on pilot satellites across the growing fleet
- Cloud-native satellites with inter-satellite links, plus cloud-native ground stations
- An autonomous, controllable, software–hardware co-designed open-source satellite platform

Once completed, the constellation will stand as a global base for satellite-network innovation — one of the forces shaping the coming era of interstellar exploration.

---

## 🚀 The Fleet

Phase I of the constellation comprises **6 LEO satellites** — 2 main, 2 auxiliary, and 2 edge satellites — supported by ground stations, a TT&C center, a cloud supercomputing center, and an open service platform. **Five are flying today.**

| Satellite | Launched | Role in the constellation | What it carries / proves |
| --- | --- | --- | --- |
| **Tiansuan-1 · "Baoyun" (宝酝号)** | Dec 7, 2021 | Pilot satellite: intelligent service & computing platform | On-orbit 5G soft base station + lightweight core network, 6G cognitive service architecture, KubeEdge + Sedna edge-AI stack, spaceborne UPF, DOIP protocol, and the first satellite-borne Data-Internet test node. Built with China Mobile Research Institute, Peking University, and Huawei Cloud |
| **Tiansuan-2 · "Chuangxing Leishen" (创星雷神号)** | Feb 27, 2022 (record 22-satellite rideshare) | Pilot satellite: satellite–ground integrated network services | KubeEdge-based remote-sensing inference, lightweight 5G core network v2, QUIC on orbit, and an adaptive service-provisioning framework for satellite edge computing. Built with Beijing University of Technology |
| **Tiansuan-3 · "Wangqizhou" (望齐州号)** | Dec 14, 2022 — launch failure | Edge satellite | Payload lost during launch; its role will be taken over by satellites in later phases |
| **BUPT-1 (北邮一号)** | Jan 15, 2023 | First main satellite: core node of the open-source in-orbit testbed | Cloud-native satellite running distributed on-orbit AI inference, 5G core network v4, and eBPF-based lightweight network elements; hosted Tsinghua's IoTDB, Peking University's Data-Internet node #3, Beihang's lightweight containers, and the Ascend Atlas 200 AI acceleration module |
| **BUPT-2 (北邮二号)** | May 17, 2025 | High-compute core node | A self-developed high-performance server flying as the computing payload — a major step up in on-orbit compute for "process-then-downlink" satellite autonomy. Runs on-orbit container updates, WASM measurements, semantic image communication, model compression and incremental learning, and single-event-upset characterization. Hosted ZTE's spaceborne core-network service trials |
| **BUPT-3 (北邮三号)** | May 17, 2025 | Inter-satellite interconnection node | High-bandwidth laser inter-satellite links, breaking the bandwidth, latency, and security bottlenecks of conventional microwave links — the foundation of a space-based information highway |

## 🧰 Open-Source Projects

The constellation's work also lives in **[OPENSAT — Open Source Satellite Community](https://github.com/Satellite-OSS)**, an open satellite community founded by the Tiansuan Constellation team. OPENSAT shares satellite-related open resources — software, papers, datasets, and industry standards and specifications — from the Tiansuan team and from the wider community, giving anyone a single place to find, reuse, and contribute to them.

The following is a selection of the constellation's open-source projects:

| Project | What it is |
| --- | --- |
| **[TiansuanExperimentPlatform](https://github.com/TiansuanConstellation/TiansuanExperimentPlatform)** | 🚀 The heart of the constellation: apply to run your experiment on our real satellites — open to the global academic community, low-cost and easy to access |
| **[RROS](https://github.com/TiansuanConstellation/RROS)** | 🦀 A dual-kernel OS for satellites — Rust RTOS + Linux — for scenarios needing both real-time and general-purpose abilities; the first Rust OS to run in orbit |
| **[MobiCom24-SatelliteCOTS](https://github.com/TiansuanConstellation/MobiCom24-SatelliteCOTS)** | Artifact of *Deciphering the Enigma of Satellite Computing with COTS Devices* (ACM MobiCom '24) |
| **[SatLink-Artifact](https://github.com/TiansuanConstellation/SatLink-Artifact)** | Measurement and analysis of LEO satellite data transmission: performance and reliability |
| **[ATC25-RHONE-DATA](https://github.com/TiansuanConstellation/ATC25-RHONE-DATA)** | Emulating space computing networks with RHONE (USENIX ATC '25) |
| **[awesome-satellite-data](https://github.com/TiansuanConstellation/awesome-satellite-data)** | A curated collection of satellite data for scientific research |

---

## ✨ Get Involved

**The constellation is open — and it needs you.**

🚀 **Run your experiment in orbit.**
The [Tiansuan Experiment Platform](https://github.com/TiansuanConstellation/TiansuanExperimentPlatform) lets researchers worldwide propose experiments, submit their code, and have our team deploy it on real satellites — then return your results and data. No launch vehicle required. Start with the [User Agreement](https://github.com/TiansuanConstellation/TiansuanExperimentPlatform/blob/main/TERMS.md).

💻 **Contribute code.**
We build in the open: satellite OS kernels ([RROS](https://github.com/TiansuanConstellation/RROS)) and satellite open-source community ([OPENSAT](https://github.com/Satellite-OSS)). All code is public, and contributions are welcome.


📊 **Use our data and artifacts.**
Measurement datasets ([SatLink](https://github.com/TiansuanConstellation/SatLink-Artifact)), emulation tools ([RHONE](https://github.com/TiansuanConstellation/ATC25-RHONE-DATA)), and paper artifacts are all public. Use them, extend them, and cite the papers — that's what they're for.

---

## 📬 Contact

- 🌐 Website: <http://www.tiansuan.org.cn> ([English](http://www.tiansuan.org.cn/index.html) · [中文](http://www.tiansuan.org.cn/Chinese/index.html))
- 🧪 Experiment platform: [platform repository](https://github.com/TiansuanConstellation/TiansuanExperimentPlatform)
- 📧 General: `buptts@163.com` · Alliance applications: `liyuanzhe@bupt.edu.cn`
- 🛰️ Maintained by the Star Network and Intelligent Computing Laboratory, BUPT

---

<sub>Founded at BUPT · Co-built with Spacety and the Tiansuan Alliance</sub>