<p align="center">
  <img src="logo.svg" width="96" height="96" alt="GlpiNg">
</p>

<h1 align="center">GlpiNg</h1>

<p align="center">
  Gestion de parc informatique compatible GLPI-Agent, en .NET / Blazor Server.<br>
  <i>IT asset management compatible with GLPI-Agent, in .NET / Blazor Server.</i>
</p>

---

## 🇫🇷 Présentation

GlpiNg est une réimplémentation d'un serveur de gestion de parc informatique compatible avec le
protocole **GLPI-Agent**. De vrais agents (contact, inventaire, déploiement) dialoguent avec son
endpoint `/inventory`, et une interface Blazor Server administre le parc en reprenant la
navigation de GLPI : Parc, Assistance, Gestion, Outils, Administration, Configuration.

- Inventaire alimenté par les agents, sur 15 types d'actifs
- Déploiement de paquets, découverte réseau SNMP et Wake-on-LAN
- Tickets, problèmes, changements et niveaux de service
- Base de connaissances, contrats, budgets, licences
- Import depuis une base GLPI MySQL existante
- API REST compatibles GLPI, plugins personnels
- SQL Server, MySQL ou PostgreSQL

## 🇬🇧 Overview

GlpiNg is a reimplementation of an IT asset management server compatible with the
**GLPI-Agent** protocol. Real agents (contact, inventory, deploy) talk to its `/inventory`
endpoint, and a Blazor Server UI manages the asset park with GLPI's navigation: Assets,
Assistance, Management, Tools, Administration, Setup.

- Agent-fed inventory across 15 asset types
- Package deployment, SNMP network discovery and Wake-on-LAN
- Tickets, problems, changes and service levels
- Knowledge base, contracts, budgets, licenses
- Import from an existing GLPI MySQL database
- GLPI-compatible REST APIs, custom plugins
- SQL Server, MySQL or PostgreSQL

## Dépôts / Repositories

| Dépôt / Repository | |
|---|---|
| [GlpiNg](https://github.com/GlpiNg-fr/GlpiNg) | Application (hôte Blazor, CLI) — *application (Blazor host, CLI)* |
| [GlpiNg.Plugins.Sdk](https://github.com/GlpiNg-fr/GlpiNg.Plugins.Sdk) | SDK de plugins — *plugin SDK* · [documentation](https://glping-fr.github.io/GlpiNg.Plugins.Sdk/) |
| [GlpiNg.Modules.Abstractions](https://github.com/GlpiNg-fr/GlpiNg.Modules.Abstractions) | Contrats partagés — *shared contracts* |
| [GlpiNg.Modules.Inventory](https://github.com/GlpiNg-fr/GlpiNg.Modules.Inventory) | Parc — *assets* |
| [GlpiNg.Modules.Deployment](https://github.com/GlpiNg-fr/GlpiNg.Modules.Deployment) | Déploiement et réseau — *deployment and network* |
| [GlpiNg.Modules.Assistance](https://github.com/GlpiNg-fr/GlpiNg.Modules.Assistance) | Tickets, problèmes, changements — *tickets, problems, changes* |
| [GlpiNg.Modules.Management](https://github.com/GlpiNg-fr/GlpiNg.Modules.Management) | Gestion — *management* |
| [GlpiNg.Modules.KnowledgeBase](https://github.com/GlpiNg-fr/GlpiNg.Modules.KnowledgeBase) | Base de connaissances — *knowledge base* |
| [GlpiNg.Modules.Cron](https://github.com/GlpiNg-fr/GlpiNg.Modules.Cron) | Actions automatiques — *automatic actions* |
| [GlpiNg.Modules.Scheduler](https://github.com/GlpiNg-fr/GlpiNg.Modules.Scheduler) | Planification des tâches — *task scheduling* |

Les modules sont des sous-modules de `GlpiNg` — *modules are submodules of `GlpiNg`*:

```bash
git clone --recurse-submodules https://github.com/GlpiNg-fr/GlpiNg.git
```

Licence / License: [AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0)

---

<sub>GlpiNg est un projet indépendant, ni affilié à, ni approuvé, soutenu ou sponsorisé par
Teclib' ou le projet GLPI. « GLPI » et « GLPI-Agent » sont des marques de leurs propriétaires
respectifs. — <i>GlpiNg is an independent project, not affiliated with, endorsed, supported or
sponsored by Teclib' or the GLPI project. "GLPI" and "GLPI-Agent" are trademarks of their
respective owners.</i></sub>
