# AZ-500 Exam Decision Reference

> Compressed decision table covering the entire exam. Use 1 day before the test.

| Scenario | Pick | Why |
|---|---|---|
| CA + workload identities | Apply CA to SPs (P2) | Same engine |
| JIT subscription owner | PIM Azure resource roles | Activate w/ MFA |
| KV authorization | Azure RBAC over access policies | Role-based |
| Lock PaaS to VNet | Private Endpoint + disable public | PE > SE |
| Inspect outbound internet | Azure Firewall + UDR | Egress filter |
| Web L7 protection | WAF on AppGw/Front Door | OWASP rules |
| RDP w/o public IP | Azure Bastion | Browser HTTPS |
| Container scan | Defender for Containers + ACR | Image + runtime |
| Storage immutability | WORM container policy | Compliance |
| SQL TDE w/ own key | TDE + CMK in KV | BYOK |
| Highest-risk findings | DfC Attack Paths | Multi-hop |
| Baseline posture | MCSB initiative | Free in DfC |

---

[Master Index](00-MASTER-INDEX.md)
