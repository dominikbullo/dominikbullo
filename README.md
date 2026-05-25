# Dominik Bullo

Software Engineer — Energy Infrastructure  
Stockholm, Sweden · [bullo.sk](https://bullo.sk) · [LinkedIn](https://linkedin.com/in/bullodominik)

---

### Machine Setup

Declarative configuration for all my machines. One command to reproduce the full environment — packages, dotfiles, secrets, and system settings on any host.

```bash
nix run .#build-switch
```

**[dominikbullo/ai](https://github.com/dominikbullo/ai)** — Agents and skills for engineering used daily. Includes energy domain-specific knowledge. 

```bash
# Agents
git clone https://github.com/dominikbullo/ai ~/ai && ~/ai/scripts/link-agents.sh

# Skills
npx skills@latest add dominikbullo/ai --global --all
```
