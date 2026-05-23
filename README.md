# Dominik Bullo

Software Engineer — Energy Infrastructure  
Stockholm, Sweden · [bullo.sk](https://bullo.sk) · [LinkedIn](https://linkedin.com/in/bullodominik)

---

Building SCADA platforms, energy management systems, and trading pipelines for Nordic power markets. Currently at [Ingrid](https://ingridcapacity.com) controlling BESS, wind, and hydro assets across FCR and mFRR ancillary markets.

---

### Machine Setup

**[dominikbullo/nix-config](https://github.com/dominikbullo/nix-config)** — Declarative configuration for all my machines (MacBook + home server). One command to reproduce the full environment — packages, dotfiles, secrets, and system settings — on any host.

```bash
nix run .#build-switch
```

**[dominikbullo/ai](https://github.com/dominikbullo/ai)** — Claude Code agents and skills for engineering work in energy infrastructure. Includes domain-specific agents for IEC 61850, Nordic ancillary markets, and asset dispatch optimisation.

```bash
# Agents
git clone https://github.com/dominikbullo/ai ~/ai && ~/ai/scripts/link-agents.sh

# Skills
npx skills@latest add dominikbullo/ai --global --all
```
