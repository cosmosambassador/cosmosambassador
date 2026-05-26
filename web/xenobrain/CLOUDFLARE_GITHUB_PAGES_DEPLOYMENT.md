# Xenobrain.org — Cloudflare / GitHub Deployment Plan

**Status:** Active Web Deployment Note  
**Domain:** xenobrain.org  
**Registrar / DNS:** Cloudflare  
**Repository:** cosmosambassador/cosmosambassador  
**System Date:** May 26, 2026  
**Source Authority:** TJ / Theresa Janette Morris  
**Operational Routing:** TJ → Jet Services → AISI.services  
**Purpose:** Connect the Cloudflare-purchased domain `xenobrain.org` to the GitHub-hosted `cosmosambassador` public web/repository system.

---

## Correction Notice

The correct domain spelling is:

```text
xenobrain.org
```

Do not use `xenobtain.org` for this deployment record unless TJ later confirms that as a separate domain.

---

## Core Intention

`xenobrain.org` is held at Cloudflare and should be routed into the `github.com/cosmosambassador` ecosystem as a public web / ontology / publishing / AI-services deployment node.

Xenobrain.org is the knowledge-map and intelligence-sorting layer for public knowledge, symbolic ontology, AI-assisted research, UFO/UAP cultural memory, publishing records, authors, consultants, oracles, ACO Club, UFO Association, and UAP Associates.

---

## Recommended Deployment Model

Use **Cloudflare Pages connected to GitHub**.

Recommended repository:

```text
cosmosambassador/cosmosambassador
```

Recommended branch:

```text
main
```

Recommended site folder:

```text
web/xenobrain/
```

---

## Domain Routing Goal

Primary target:

```text
https://xenobrain.org
```

Optional redirect / alias:

```text
https://www.xenobrain.org
```

Recommended public rule:

- Use apex domain `xenobrain.org` as the main address.
- Redirect `www.xenobrain.org` to `xenobrain.org`, unless a separate `www` landing page is intentionally needed.

---

## Cloudflare Dashboard Steps

1. Open Cloudflare dashboard.
2. Go to **Workers & Pages**.
3. Choose **Create application**.
4. Select **Pages**.
5. Select **Connect to Git**.
6. Connect GitHub and select:

```text
cosmosambassador/cosmosambassador
```

7. Set production branch:

```text
main
```

8. Set the project/output folder according to the static-site tool selected for the repository. For a simple static deployment, use the Xenobrain folder as the source directory:

```text
web/xenobrain/
```

9. Set custom domain:

```text
xenobrain.org
```

10. Add `www.xenobrain.org` as a redirect or alias if desired.

---

## Suggested Homepage Copy

# Xenobrain.org

**Map the signal. Organize the knowledge. Preserve the record.**

Xenobrain.org is a TJ Morris / Cosmos Ambassador AI / AISI.services knowledge-map for ontology, AI-assisted research, UFO/UAP cultural memory, public-source organization, authors, consultants, oracles, and creator-intelligence publishing workflows.

This site connects the Cloudflare domain layer with the GitHub `cosmosambassador` repository system for public documentation, publishing, research notes, and structured web deployment.

---

## Ecosystem Placement

| Layer | Role |
|---|---|
| Cloudflare | Domain, DNS, Pages deployment, security edge |
| GitHub | Repository, source files, version control, public documentation |
| Xenobrain | Knowledge-map, ontology, intelligence sorting, public-facing index |
| Cosmos Ambassador | Public identity and symbolic-intelligence brand layer |
| ACO Club | Community, authors, consultants, oracles, contributors |
| UFO Association | Legacy UFO archive and experiencer-history lane |
| UAP Associates | Modern UAP language and consultant lane |
| AISI.services | Practical AI / web / domain / publishing services layer |
| Jet Services | Operational routing layer |
| TJ | Human source authority |

---

## Public Boundary

Xenobrain.org should be framed as a public web, research, publishing, ontology, archive, community, consultant, oracle, and AI-services domain.

It should not claim official government, military, intelligence, law-enforcement, academic, or corporate authority unless separate documentation exists.

UFO/UAP material should be categorized as documented public record, witness/experiencer account, historical media archive, symbolic canon, speculative interpretation, or public-source commentary.

---

## Standing Rule

**Cloudflare holds the domain.  
GitHub holds the source.  
Xenobrain organizes the map.  
Cosmos Ambassador holds the public identity.  
AISI.services delivers the web-services layer.  
Jet Services routes the operations.  
TJ remains the human source authority.**
