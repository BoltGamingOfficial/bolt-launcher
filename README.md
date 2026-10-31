# Bolt Launcher

**A free, non-commercial Minecraft launcher hobby project for Java Edition and Bedrock Edition.**

I'm building Bolt Launcher because I want one place to manage both Minecraft editions. I also want mod installation to be less of a hassle: find something inside the launcher, check that it fits the selected instance, and install it there without manually moving files around.

[Project website](https://boltgamingofficial.github.io/bolt-launcher/) · [GitHub Issues](https://github.com/BoltGamingOfficial/bolt-launcher/issues) · [Privacy notice](https://boltgamingofficial.github.io/bolt-launcher/privacy.html) · [API use and creator rights](https://boltgamingofficial.github.io/bolt-launcher/api-use.html)

> **Status:** Early development. There is no public release download yet. Features below describe the project direction and are not a promise that they are already available.

## Why I'm building it

I wanted a single launcher experience for Java and Bedrock instead of treating them as completely separate setups. I also want players to be able to discover mods and install them into the right instance in a few clicks.

## What I'm aiming for

- **Java and Bedrock:** bring both editions into one launcher experience.
- **Instance management:** keep game versions and separate setups organised.
- **In-launcher mod discovery:** search provider catalogues and see content that matches the selected Minecraft version and loader.
- **Install to Instance:** install a permitted download into the selected instance without asking the player to move files manually.
- **Creator attribution:** show where content comes from, link to original project pages, and respect provider and author distribution settings.
- **Lightweight:** built in Rust, with a focus on keeping background overhead low.
- **No ads or paid features planned:** Bolt Launcher is a hobby project, not a business.

## CurseForge API status

A CurseForge third-party API application was submitted on 31 October 2026. It has **not** been approved yet, and no CurseForge API key has been issued to the project.

The intended flow is for a player to browse CurseForge from inside Bolt Launcher and request installation into a selected Minecraft instance. Bolt will not operate its own mod-hosting service, mirror or re-upload CurseForge files, or bypass author distribution settings. Any integration will only be enabled if Overwolf approves this native-launcher use case and the implementation follows the current API terms.

See [API use and creator rights](api-use.html) for the intended flow and the questions awaiting provider clarification.

## Development status

This repository currently contains the public project website and project information, not a downloadable launcher release. The desktop application and its features are still being developed.

## Repository

The project uses **one branch: main**. The website source is in the repository root, with a GitHub Actions workflow prepared for GitHub Pages.

## Contact

- Bugs and feature requests: [GitHub Issues](https://github.com/BoltGamingOfficial/bolt-launcher/issues)
- Source and project updates: [GitHub repository](https://github.com/BoltGamingOfficial/bolt-launcher)

Please don't post passwords, Microsoft tokens, API keys, or other private information in public issues.

## Third-party names

Minecraft is a trademark of Microsoft. CurseForge is a product of Overwolf. Modrinth is a separate third-party platform. Bolt Launcher is an independent, unofficial hobby project and is not affiliated with, endorsed by, or sponsored by Microsoft, Mojang, Overwolf, CurseForge, or Modrinth.
