# Architectures - AZ-500

> Reference architectures you should be able to draw on a whiteboard for the exam.

## Hub-and-spoke with Azure Firewall + WAF

```mermaid
flowchart LR
    Internet --> FD[Front Door + WAF]
    FD --> AGW[App Gateway + WAF]
    AGW --> App[Spoke app subnet]
    App --> PE[Private Endpoint]
    Egress[Spoke egress] --> AFW[Azure Firewall]
    AFW --> Internet
```

## DfC + Sentinel layered

```mermaid
flowchart TD
    Az[Azure resources] --> DfC[Defender for Cloud]
    AWS[AWS / GCP] --> DfC
    DfC --> Sent[Sentinel workspace]
    XDR[Defender XDR] --> Sent
    Pol[Azure Policy + MCSB] --> DfC
    Sent --> SOC[SOC analyst]
```


---

[Master Index](00-MASTER-INDEX.md)
