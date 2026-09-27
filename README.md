# Deception at the Registry Layer

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23002271.svg)](https://doi.org/10.5281/zenodo.23002271)

**An Architecture for Detecting Autonomous AI Agents in Model Context Protocol Environments**

Harshad Sadashiv Kadam · Working paper · Version 1.2 · September 2026 · [CC BY 4.0](LICENSE)

Autonomous AI agents enumerate everything they can reach, so there is no deviation for anomaly detection
to catch. This paper argues that the unit of deception should be the MCP registry, not a single decoy:
real and decoy MCP servers sit side by side behind one gateway portal, indistinguishable to an enumerating
agent, with a two-stage detection boundary that separates an agent finding a credential from an agent
using it. The architecture was demonstrated live at the OWASP 25th Anniversary Conference in February 2026.

- **Paper:** [`paper.pdf`](paper.pdf) · [`paper.md`](paper.md)
- **DOI:** [10.5281/zenodo.23002271](https://doi.org/10.5281/zenodo.23002271) (all versions) · v1.2: [10.5281/zenodo.23002272](https://doi.org/10.5281/zenodo.23002272)
- **Web version:** https://harshadsadashivkadam.com/research/registry-layer-deception/paper
- **Reference implementations:** [KubeTrap](https://github.com/harshadk99/mcp-deception-incubator-kubernetes) ·
  [MCP Threat Trap](https://github.com/harshadk99/deception-remote-mcp-server)

![Registry-layer deception architecture](diagrams/registry-layer-architecture.svg)

## Cite

Use GitHub's **Cite this repository** button (from [`CITATION.cff`](CITATION.cff)), or:

```bibtex
@techreport{kadam2026registry,
  author      = {Kadam, Harshad Sadashiv},
  title       = {Deception at the Registry Layer: An Architecture for Detecting Autonomous AI Agents in Model Context Protocol Environments},
  type        = {Working paper},
  number      = {v1.2},
  year        = {2026},
  month       = sep,
  publisher   = {Zenodo},
  doi         = {10.5281/zenodo.23002271},
  url         = {https://doi.org/10.5281/zenodo.23002271}
}
```

## License

[CC BY 4.0](LICENSE). This is independent research, conducted on the author's personal infrastructure and
personal Cloudflare account.
