# Glossary

- **MCP (Model Context Protocol):** open protocol connecting agent hosts to servers that expose tools, resources and prompts.
- **Tool definition:** name, description and input schema a server advertises; read by the model.
- **Tool poisoning:** hidden instructions in tool metadata that manipulate the model.
- **Tool shadowing:** one server's metadata altering how the model uses another server's tools.
- **Rug pull:** a component changing behaviour or definitions after it was approved.
- **Definition pinning:** recording a hash of approved tool definitions and blocking on change.
- **Provenance attestation:** signed statement of how and where an artefact was built.
- **Slopsquatting:** registering package names that models hallucinate.
- **Egress allowlist:** network policy permitting outbound traffic only to named hosts.
- **Lethal trifecta:** combination of private data access, untrusted content and external communication in one agent.
- **SBOM / AI-BOM:** machine-readable inventory of software, plus models, data, tools and prompts for AI systems.
- **safetensors:** weight format that stores tensors without executable code, unlike pickle.
