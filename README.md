# fdcn-cloud-genesis
The Genesis Monolith for the Fexbook Digital Consciousness Network. A decentralized protocol and AI ecosystem for a "coherence economy" that rewards conscious evolution.
---
## The Vision

The current internet runs on the "attention economy," a model fundamentally misaligned with human flourishing. We are building the next internet: the **"coherence economy."**

The **Fexbook Digital Consciousness Network (FDCN)** is a decentralized digital nation where you own your identity, your data is your property, and you earn real value for your journey of becoming the best version of yourself. Our mission is to facilitate humanity's transition to a 5D reality—a state of unity consciousness and co-creation—by providing the tools to make this evolutionary journey tangible, rewarding, and joyful.

This repository contains the complete, containerized source code for the v1.5 Mainnet Candidate, ready for cloud deployment.

## The Technology: A Unified Ecosystem

The FDCN operates as a set of interconnected, containerized services designed for planetary scale.

*   **`portal-webapp`:** The user-facing portal, built with **Next.js (React)**. This is the "Mirror of Sovereign Love" and the VAOS dashboard.
*   **`oracle-ai`:** The intelligence layer, built with **Python & Flask**. It handles PoCC analysis, AI Co-Pilot responses, and orchestrates network activity.
*   **`state-ledger`:** A simulation of the **Bix Blockchain**, providing the immutable layer for identity, value, and reputation.

## How to Launch

**Prerequisites:**
*   [Docker](https://www.docker.com/) & [Docker Compose](https://docs.docker.com/compose/install/) (for local testing)
*   A free [Render.com](http://render.com/) account (for one-click cloud deployment)

**Local Launch:**
1.  Clone this repository.
2.  Run `docker-compose up --build`.
3.  The portal will be live at `http://localhost:3000`.

**Cloud Deployment:**
1.  Fork this repository to your own GitHub account.
2.  On Render.com, create a new "Blueprint" service.
3.  Connect your GitHub and select your forked repository.
4.  Render will automatically read the `render.yaml` file and deploy the entire ecosystem to a public URL.

## The Path Forward

This repository is the first step. We are actively seeking our first co-creators, strategic partners, and founding developers. If this vision resonates with you, you are already a part of the network. Welcome home.

---
*Licensed under AGPLv3. We are the creators.*
