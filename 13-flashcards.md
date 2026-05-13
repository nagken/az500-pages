# Flashcards - AZ-500

> Click any card to reveal the answer. Use the Domain pager bottom-right to switch between exam areas.

<section class="fc-section" data-fc-title="Manage Identity and Access">
<h2>1 - Manage Identity and Access</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">CA + Workload identities P2 lets you do what?</div><div class="fc-a">Apply Conditional Access conditions (location, risk) to service principals.</div></div>

<div class="flashcard"><div class="fc-q">Azure RBAC scope hierarchy?</div><div class="fc-a">Management group -> Subscription -> Resource group -> Resource.</div></div>

<div class="flashcard"><div class="fc-q">Best fit for daemon to KV?</div><div class="fc-a">Managed identity + Key Vault Secrets User role.</div></div>

<div class="flashcard"><div class="fc-q">PIM for Azure resources difference vs Entra roles?</div><div class="fc-a">Same engine - eligible vs active assignment, MFA + justification + approval on activation.</div></div>

<div class="flashcard"><div class="fc-q">Best CA policy to deploy first?</div><div class="fc-a">Block legacy authentication.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Secure Networking">
<h2>2 - Secure Networking</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Private Endpoint vs Service Endpoint?</div><div class="fc-a">PE = private IP in your VNet (PaaS appears local). SE = public IP whitelisted to your subnet (still public network).</div></div>

<div class="flashcard"><div class="fc-q">Azure Firewall Premium adds what?</div><div class="fc-a">TLS inspection, IDPS, URL filtering, web categories.</div></div>

<div class="flashcard"><div class="fc-q">Where do you put WAF: App Gateway or Front Door?</div><div class="fc-a">AppGw for regional; Front Door for global multi-region.</div></div>

<div class="flashcard"><div class="fc-q">How do you RDP to a VM without public IP?</div><div class="fc-a">Azure Bastion (browser RDP/SSH over HTTPS).</div></div>

<div class="flashcard"><div class="fc-q">JIT VM access requires what?</div><div class="fc-a">Defender for Servers Plan 2.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Secure Compute, Storage, and Databases">
<h2>3 - Secure Compute, Storage, and Databases</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Soft delete + purge protection on KV?</div><div class="fc-a">Soft delete = recoverable for retention period. Purge protection = cannot be permanently deleted before retention expires.</div></div>

<div class="flashcard"><div class="fc-q">Always Encrypted vs TDE?</div><div class="fc-a">TDE = data at rest server-side. Always Encrypted = client-side; SQL never sees plaintext.</div></div>

<div class="flashcard"><div class="fc-q">Best authorization model for KV?</div><div class="fc-a">Azure RBAC (preferred over legacy access policies).</div></div>

<div class="flashcard"><div class="fc-q">Where do you scan container images?</div><div class="fc-a">ACR via Defender for Containers + at runtime in AKS/ACI.</div></div>

<div class="flashcard"><div class="fc-q">Encryption at host adds what over disk encryption?</div><div class="fc-a">Encrypts data on the hypervisor host (covers temp disk + cache).</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Manage Security Operations">
<h2>4 - Manage Security Operations</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">MCSB?</div><div class="fc-a">Microsoft Cloud Security Benchmark - Microsoft's prescriptive baseline mapped to NIST/CIS/PCI/etc.</div></div>

<div class="flashcard"><div class="fc-q">Foundational CSPM vs Defender CSPM?</div><div class="fc-a">Foundational = free, Secure Score, recs. Defender CSPM = paid, attack paths, agentless scan, sensitive data discovery.</div></div>

<div class="flashcard"><div class="fc-q">Defender for Storage protects how?</div><div class="fc-a">Malware scan on upload + suspicious access activity alerts.</div></div>

<div class="flashcard"><div class="fc-q">Sentinel cost driver?</div><div class="fc-a">Ingestion + retention. Use commitment tiers + Basic/Auxiliary logs.</div></div>

<div class="flashcard"><div class="fc-q">Defender plans you must know?</div><div class="fc-a">Servers, Storage, SQL, Containers, App Service, Key Vault, Resource Manager, DNS, APIs, AI.</div></div>

</div>
</section>

---

[Master Index](00-MASTER-INDEX.md)
