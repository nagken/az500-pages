# AZ-500 - Microsoft Azure Security Engineer Associate - Visual Study Guide

> Concept-only study aid. No exam questions reproduced. Source PDF (if any) stays local + gitignored.

**Skills outline:** https://learn.microsoft.com/en-us/credentials/certifications/exams/az-500/

## Master mind map

```mermaid
mindmap
  root((AZ-500))
    Manage Identity and Access
      Manage Microsoft Entra ID identities users, groups, devices, AUs, e...
      Manage Entra authentication MFA, passwordless, CA, Identity Protection
      Manage Entra authorization RBAC, custom roles, PIM, Workload Identi...
      Manage application access registrations, MIs, OAuth, App Proxy, con...
    Secure Networking
      Plan and implement security for virtual networks NSGs, ASGs, route ...
      Plan and implement security for private access to Azure resources P...
      Plan and implement security for public access Azure Firewall, WAF o...
      Configure Azure Bastion, just-in-time VM access Defender for Server...
    Secure Compute, Storage, and Databases
      Plan and implement advanced security for compute VM disk encryption...
      Plan and implement security for storage firewall, PE, immutable, en...
      Plan and implement security for Azure SQL Database / Managed Instan...
      Plan and implement security for Key Vault RBAC vs access policy, so...
    Manage Security Operations
      Plan, implement, and manage governance with Azure Policy + Microsof...
      Manage security posture with Defender for Cloud Secure Score, recom...
      Configure and manage threat protection Defender plans for Servers, ...
      Configure and manage Microsoft Sentinel workspace, connectors, anal...
```

## Domain map

```mermaid
flowchart LR
    Master["AZ-500 Master Index"]
    D01["Manage Identity and Access"]
    Master --> D01
    D02["Secure Networking"]
    Master --> D02
    D03["Secure Compute Storage and Databases"]
    Master --> D03
    D04["Manage Security Operations"]
    Master --> D04
```

## Domain weights

```mermaid
pie showData
    title AZ-500 domain weights
    "Manage Identity and Access" : 27
    "Secure Networking" : 22
    "Secure Compute Storage and Databases" : 23
    "Manage Security Operations" : 28
```

> Click a slice / legend label to jump to that chapter.

## Recommended study order

```mermaid
gantt
    title Suggested study plan
    dateFormat X
    axisFormat Day %d
    section Plan
    Manage Identity and Access :t1, 0, 2d
    Secure Networking :t2, after t1, 2d
    Secure Compute Storage and Databases :t3, after t2, 2d
    Manage Security Operations :t4, after t3, 2d
```

---

**Next:** open [01-identity-access.md](01-identity-access.md)

<!-- TODO: fill remaining sections via Copilot chat. Target structure mirrors c:\az305\study-guide\00-MASTER-INDEX.md. -->
