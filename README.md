# Nandagopal (Nandu) Kirubanandan

**Principal Software Engineer**  
*AI Inference Infrastructure | Distributed Systems | Resource Management | High Availability | Enterprise AI Platforms*  

📍 **Base:** Dallas–Fort Worth Metro Area  
🔗 **LinkedIn:** [linkedin.com/in/knandu](https://www.linkedin.com/in/knandu/)  
🌐 **Website:** [kirubanandan.me](https://kirubanandan.me/)  

---

## Executive Overview

I am a Principal Software Engineer specializing in low-level systems engineering, distributed infrastructure, and accelerated compute platforms. My experience spans high-availability clustering, storage engine internals, software-defined infrastructure, datacenter automation, and enterprise AI inference systems.

My primary focus is turning complex, heterogeneous GPU/CPU compute environments into manageable, low-latency, resilient inference platforms. I work on problems involving resource allocation, distributed control loops, failure domains, hardware qualification, and operational lifecycle management for production workloads.

---

## Technical Focus & Systems Expertise

* **AI & Accelerated Computing:** Local and self-hosted model inference, inference performance and resource economics, heterogeneous CPU/GPU placement, context/KV-cache optimization, model serving, and agent/tool orchestration.
* **Distributed & Core Systems:** High-availability clustering, failover mechanisms, distributed state & reconciliation, storage virtualization (Storage Spaces Direct, NVMe, NTFS), kernel-level diagnostic drivers.
* **Platform & Orchestration:** Software-defined infrastructure, datacenter-scale VM/bare-metal orchestration, hardware qualification, performance regression isolation.

---

## Selected Systems Writing & Technical Insights

I regularly publish technical teardowns and case studies focusing on engineering constraints, systems trade-offs, performance debugging, and operational simplicity:

* **[I Thought I Had a Model Problem. It Turned Out to Be a Latency Problem](https://www.linkedin.com/pulse/i-thought-had-model-problem-turned-out-latency-kirubanandan-ah7nc)**  
  *Analyzing local ONNX WASM execution constraints, CPU thread boundaries, and interactive candidate generation for on-device natural language interfaces.*
* **[The Device Worked. The Workload Didn't.](https://www.linkedin.com/pulse/device-worked-workload-didnt-nandagopal-kirubanandan-rm37f)**  
  *Cross-layer systems debugging involving Hyper-V Discrete Device Assignment, PCIe Atomic Operations, and guest VM enumeration failures.*
* **[Chasing the Wrong Target](https://www.linkedin.com/pulse/chasing-wrong-target-nandagopal-kirubanandan-2z36c)**  
  *Lessons on metric selection, architectural constraints, and organizational alignment from large-scale storage virtualization.*
* **[When Expertise Stops Being the Bottleneck](https://www.linkedin.com/pulse/when-expertise-stops-being-bottleneck-nandagopal-kirubanandan-clvlc)**  
  *Accelerating specialized systems engineering workflows and complex infrastructure debugging through structured AI tools.*

---

## Featured Repositories & Evidence Artifacts

* **[`capability-under-constraints`](https://github.com/knandu/capability-under-constraints)**  
  *Engineering notebook on extracting useful AI capability under constrained hardware, context, and tooling. Measurements span model placement, context economics, agent overhead, bounded workflows, and explicit stopping decisions.*
* **[`control-plane-experiment`](https://github.com/knandu/control-plane-experiment)**  
  *Architecture experiment exploring authority, observation, durable intent, fencing, reconciliation, failure, and recovery in a small distributed control plane.*
* **[`tamil-transliterator`](https://github.com/knandu/tamil-transliterator)**  
  *Browser-native Tamil transliteration using IndicXlit and ONNX Runtime Web/WASM, with local inference and explicit editing ownership.*
* **[`hyper-v-lab`](https://github.com/knandu/hyper-v-lab)**  
  *Reproducible Windows Server/Hyper-V substrate for systems experiments, including AD/DNS and multi-node failover clustering.*
* **[`kvm-lab`](https://github.com/knandu/kvm-lab)**  
  *Reproducible Linux/KVM substrate with disposable Ubuntu guests, isolated networking, and validated lifecycle operations.*

---

*Note: This repository serves as a curated portfolio index. Reference implementations, architecture experiments, engineering notebooks, and reproducible lab substrates are hosted in the dedicated public repositories above.*
