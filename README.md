<p align="center">
  <picture>
    <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/sacreman/sacreman/main/assets/header-mobile.svg" />
    <img src="https://raw.githubusercontent.com/sacreman/sacreman/main/assets/header.svg" alt="Steven Acreman — Platform engineering for applied AI" width="100%" />
  </picture>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/stevenacreman/">LinkedIn</a> ·
  <a href="https://github.com/sacreman/thaipoai">Current project</a> ·
  <a href="https://github.com/Kubedex">Kubernetes tooling</a>
</p>

I build cloud infrastructure and developer tooling with **Kubernetes, Terraform, Helm, Go and Python**. My current focus is AI/ML platforms: reproducible training, useful evaluation and dependable serving.

## Building now: ThaiPoAI

[**ThaiPoAI**](https://github.com/sacreman/thaipoai) explores self-hosted English–Thai translation: can a model we fine-tune replace a hosted translation service without losing meaning?

- **Built:** synthetic-data training experiments, a [feasibility report](https://github.com/sacreman/thaipoai/blob/main/docs/steps/01-feasibility.md), and a Go evaluation harness.
- **Next:** translation-quality and context evaluation, then a reproducible training pipeline and controlled Kubernetes rollouts.

This is work in progress; the training experiments establish feasibility, not production translation quality.

## Platform engineering & open source

The **Kubedex** projects pinned below cover Kubernetes controllers, cloud provisioning benchmarks, Terraform-driven deployments and Helm chart testing. They are historical work from **2018–2019**, with dependencies and instructions from that period.

Selected merged contributions to Akash Network:

- [Persistent storage support for the Akash node chart](https://github.com/akash-network/helm-charts/pull/24)
- [Rook/Ceph production configuration and end-to-end test fixes](https://github.com/akash-network/helm-charts/pull/64)

