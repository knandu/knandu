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

I write about systems engineering through experiments, failures, performance investigations, and the decisions that emerge from them. Selected pieces:

* **[Does an Active/Active Compute Plane Need an Active/Active Control Plane?](https://www.linkedin.com/pulse/does-activeactive-compute-plane-need-control-nandagopal-kirubanandan-gkijc/)**  
  *Using a reduced, executable experiment to separate control-plane topology from the need to exclude stale management authority.*
* **[From 300K to 1M+ IOPS: The Declining Cost of Investigation](https://www.linkedin.com/pulse/from-300k-1m-iops-declining-cost-investigation-kirubanandan-biosc/)**  
  *How the cost of investigating performance shapes which engineering opportunities get pursued.*
* **[I Thought I Had a Model Problem. It Turned Out to Be a Latency Problem](https://www.linkedin.com/pulse/i-thought-had-model-problem-turned-out-latency-kirubanandan-ah7nc/)**  
  *Separating interactive typing from background text review made a local AI design simpler.*
* **[The Device Worked. The Workload Didn't.](https://www.linkedin.com/pulse/device-worked-workload-didnt-nandagopal-kirubanandan-rm37f/)**  
  *Why successful device enumeration is only the beginning of validating a hardware-acceleration workload.*
* **[Engineering Judgment Is More Than Being Right](https://www.linkedin.com/pulse/engineering-judgment-more-than-being-right-nandagopal-kirubanandan-xllmc/)**  
  *Lessons from prioritizing performance improvements, sustaining scale, and making room for other engineering work.*
* **[Look for Evidence of Experimentation, Not Polish](https://www.linkedin.com/pulse/look-evidence-experimentation-polish-nandagopal-kirubanandan-ou9oc/)**  
  *Why tested assumptions and visible learning reveal more about a proposal than a polished presentation alone.*

**More writing:** [kirubanandan.me](https://kirubanandan.me)

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
