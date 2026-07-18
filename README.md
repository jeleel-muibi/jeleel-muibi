I work on governed infrastructure operations across hybrid environments: source of truth, controlled execution, disaster recovery evidence, networking, Kubernetes platforms, and public engineering documentation.

I create and maintain [HybridOps](https://hybridops.tech), a public hybrid infrastructure platform for operating on-premises and cloud systems through explicit intent, validation, run records, recovery controls, and reusable infrastructure modules.

The focus is on making infrastructure easier to inspect, reproduce, recover, and hand over.

## Current Work

- Creator and maintainer of [HybridOps Core](https://github.com/hybridops-tech/hybridops-core)
- Publisher of infrastructure components through [Terraform Registry](https://registry.terraform.io/modules/hybridops-tech/sdn/proxmox) and [Ansible Galaxy](https://galaxy.ansible.com/ui/namespaces/hybridops/)
- NetBox Ansible collection co-author via maintainer-reviewed upstream PRs
- Upstream contributor to `ansible-collections/community.proxmox` and `geerlingguy/ansible-role-docker`
- Author of public technical writing on disaster recovery governance, platform engineering, source-of-truth automation, and infrastructure operating models

## HybridOps Entry Points

- [Platform overview](https://hybridops.tech/why)
- [Documentation](https://docs.hybridops.tech)
- [Capability map](https://docs.hybridops.tech/evidence_map)
- [Reference scenarios](https://docs.hybridops.tech/reference-scenarios/)
- [Platform modules](https://docs.hybridops.tech/platform/modules/)
- [Blueprint registry](https://docs.hybridops.tech/platform/blueprints/)

## Engineering Focus

- Governed infrastructure execution
- Source-of-truth operations
- Hybrid infrastructure architecture
- Disaster recovery decision control
- Network and platform automation
- Kubernetes and GitOps delivery
- Evidence-producing run records
- Technical documentation and learning systems

## Public Engineering Outputs

- [hybridops-core](https://github.com/hybridops-tech/hybridops-core): orchestration layer, runtime evidence model, modules, blueprints, and platform contracts
- [terraform-proxmox-sdn](https://github.com/hybridops-tech/terraform-proxmox-sdn): Terraform module for Proxmox SDN networking
- [hybridops-workloads](https://github.com/hybridops-tech/hybridops-workloads): workload definitions and deployment patterns
- [hybridops-terraform-gitmods](https://github.com/hybridops-tech/hybridops-terraform-gitmods): Terraform module registry and dependency management
- Ansible Galaxy collections: `hybridops.common`, `hybridops.app`, `hybridops.network`, and `hybridops.helper`
- [netbox-community/ansible_modules](https://github.com/netbox-community/ansible_modules): [PR #1547](https://github.com/netbox-community/ansible_modules/pull/1547) and [PR #1546](https://github.com/netbox-community/ansible_modules/pull/1546)
- [ansible-collections/community.proxmox](https://github.com/ansible-collections/community.proxmox): Proxmox KVM documentation improvement
- [geerlingguy/ansible-role-docker](https://github.com/geerlingguy/ansible-role-docker): Docker APT repository override support for mirrors, caches, and restricted-network deployments
- [HybridOps Blog](https://hybridops.tech/blog)
- [HybridOps technical papers](https://hybridops.tech/papers): long-form work on reproducible practical environments, infrastructure governance, and recovery operations
- [HackerNoon](https://hackernoon.com/u/jeleel_muibi)
- [DZone](https://dzone.com/users/5524956/hybridops.html)

## Why This Work Exists

As infrastructure becomes easier to generate, the harder problem is operating it responsibly. HybridOps is built around that problem: clear intent, controlled execution, recovery evidence, and documentation that allows another engineer to understand the system.

Origin note: [GoatOps incident report](https://hybridops.tech/goatops/)
